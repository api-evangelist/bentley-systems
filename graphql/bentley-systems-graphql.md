# Bentley Systems iTwin Platform — GraphQL Schema

## Overview

This conceptual GraphQL schema models the Bentley Systems iTwin Platform developer API surface. Bentley exposes its infrastructure engineering data through 30+ REST APIs at `https://api.bentley.com`. This schema maps those REST resources into a unified GraphQL type system so applications can query project containers, iModels, changesets, elements, schemas, views, issues, access control, and webhooks through a single interface.

The iTwin Platform organizes infrastructure asset data around three core abstractions:

- **iTwin (Project)** — the top-level container holding all data for a project, asset, or portfolio
- **iModel** — a versioned, change-tracked information container for the lifecycle of an infrastructure asset
- **Element** — the atomic unit of BIM data inside an iModel, typed by its BIS (Base Infrastructure Schema) class

## Schema Sources

| REST API | GraphQL Types |
|---|---|
| [iTwins API](https://developer.bentley.com/apis/itwins/) | `Project`, `ProjectDetails`, `ProjectStatus`, `ProjectType` |
| [iModels API v2](https://developer.bentley.com/apis/imodels-v2/) | `iModel`, `iModelDetails`, `iModelChangeset`, `Changeset`, `ChangesetDetails`, `ChangeType`, `Branch`, `BranchDetails`, `BranchTag`, `Tag`, `TagDetails`, `Checkpoint`, `CheckpointDetails`, `ElementBriefcase` |
| [iModel Element APIs](https://developer.bentley.com/apis/imodels-v2/) | `Element`, `ElementDetails`, `ElementType`, `ElementCode`, `ElementLabel`, `ElementUserLabel` |
| [BIS Schema APIs](https://developer.bentley.com/apis/imodels-v2/) | `Schema`, `SchemaDetails`, `Class`, `ClassDetails`, `Property`, `PropertyDetails` |
| [ECSQL Query](https://developer.bentley.com/apis/imodels-v2/) | `Query`, `QueryDetails`, `QueryResults` |
| [Saved Views API](https://developer.bentley.com/apis/savedviews/) | `View`, `ViewDetails`, `ViewType`, `SpatialView`, `DrawingView` |
| [iModel Geometry](https://developer.bentley.com/apis/imodels-v2/) | `Category`, `SubCategory`, `Model`, `ModelDetails`, `ModelType`, `PhysicalModel`, `DrawingModel`, `Sheet`, `SheetDetails` |
| [Presentation Library](https://developer.bentley.com/apis/imodels-v2/) | `Ruleset`, `RulesetDetails`, `Presentation`, `PresentationDetails` |
| [Issues API v1](https://developer.bentley.com/apis/issues-v1/) | `Issue`, `IssueDetails`, `IssueType`, `IssueStatus` |
| [Users API](https://developer.bentley.com/apis/users/) | `User`, `UserDetails` |
| [Access Control API v2](https://developer.bentley.com/apis/access-control-v2/) | `RBAC`, `RBACDetails`, `UserRole` |
| [Auth / App Registration](https://developer.bentley.com/apis/overview/authorization/) | `APIKey`, `Token` |
| [Webhooks API v2](https://developer.bentley.com/apis/webhooks-v2/) | `Webhook` |

## Type Inventory

### Project and iTwin Types
- `Project` — iTwin container with status, type, member list, and linked iModels
- `ProjectDetails` — full iTwin metadata including data center location and hierarchy
- `ProjectStatus` — enum: `ACTIVE`, `INACTIVE`, `TRIAL`, `DELETED`
- `ProjectType` — enum: `PROJECT`, `ASSET`, `PORTFOLIO`, `REPOSITORY`, `ORGANIZATION`, `STANDARD`

### iModel Core Types
- `iModel` — versioned BIM container with changesets, branches, and named versions
- `iModelDetails` — full iModel metadata including extent and container settings
- `iModelChangeset` — changeset record scoped to an iModel (lightweight reference)
- `Changeset` — full changeset including author, parent, size, and change type
- `ChangesetDetails` — extended changeset data including synchronization provenance
- `ChangeType` — enum: `INSERT`, `UPDATE`, `DELETE`

### Branch and Version Types
- `Branch` — named timeline fork within an iModel
- `BranchDetails` — branch metadata and link envelope
- `BranchTag` — tag pinned to a specific changeset on a branch
- `Tag` — named version (milestone marker) on an iModel's main timeline
- `TagDetails` — extended named version data including application attribution

### Checkpoint Types
- `Checkpoint` — materialized snapshot of an iModel at a specific changeset
- `CheckpointDetails` — checkpoint state and container access token for download

### Element Types
- `Element` — atomic BIM object typed by its BIS class; carries code, model, and category associations
- `ElementDetails` — full element data including parent hierarchy, geometry ref, and JSON properties
- `ElementType` — enum covering physical, drawing, spatial, information, document, definition, and link elements
- `ElementCode` — three-part code (spec, scope, value) uniquely identifying an element
- `ElementLabel` — localized display label for an element
- `ElementUserLabel` — user-assigned label override on an element
- `ElementBriefcase` — local copy of an iModel held by a user or application

### Schema and Class Types
- `Schema` — BIS schema containing class definitions; versioned and aliased
- `SchemaDetails` — full schema metadata including references and custom attributes
- `Class` — BIS class definition with base class, type (entity/relationship/mixin), and properties
- `ClassDetails` — extended class metadata including modifier and mixin list
- `Property` — typed property on a BIS class with label, read-only flag, and priority
- `PropertyDetails` — extended property data including min/max constraints and custom attributes

### Query and Results Types
- `Query` — stored ECSQL query definition persisted on an iModel
- `QueryDetails` — full stored query metadata
- `QueryResults` — paginated ECSQL result set with column names and continuation token

### Presentation Types
- `Ruleset` — iTwin Presentation ruleset defining how BIS elements map to UI nodes and content
- `RulesetDetails` — full ruleset with version and supplementation metadata
- `Presentation` — evaluated presentation output: nodes, content, or distinct values
- `PresentationDetails` — descriptor envelope for presentation responses

### Geometry and Model Types
- `Category` — drawing or spatial category grouping elements by type and visibility
- `SubCategory` — appearance subdivision within a category
- `Model` — sub-model partitioning elements within an iModel
- `ModelDetails` — full model metadata with geometry GUID
- `ModelType` — enum: `PHYSICAL_MODEL`, `DRAWING_MODEL`, `SPATIAL_LOCATION_MODEL`, `DEFINITION_MODEL`, `INFORMATION_RECORD_MODEL`, `DOCUMENT_LIST_MODEL`
- `PhysicalModel` — physical sub-model containing real-world elements
- `DrawingModel` — 2D drawing sub-model
- `View` — saved viewer state with camera, display style, and category/model selectors
- `ViewDetails` — full view metadata with JSON properties
- `ViewType` — enum: `SPATIAL_VIEW`, `DRAWING_VIEW`, `SHEET_VIEW`
- `SpatialView` — 3D spatial view with camera, extents, and model selector
- `DrawingView` — 2D drawing view with origin and delta
- `Sheet` — sheet view with scale, dimensions, and drawing attachments
- `SheetDetails` — full sheet metadata

### Issue Types
- `Issue` — project issue (defect, RFI, punchlist item) with status and assignee
- `IssueDetails` — full issue data including attachments, comments, and audit trail
- `IssueType` — enum: `OBSERVATION`, `DEFECT`, `RFI`, `PUNCHLIST`, `COORDINATION`, `DESIGN_REVIEW`
- `IssueStatus` — enum: `OPEN`, `IN_PROGRESS`, `RESOLVED`, `CLOSED`, `VOID`

### Identity and Access Types
- `User` — iTwin Platform user with email and display name
- `UserDetails` — full user profile with organization affiliation
- `UserRole` — enum: `OWNER`, `ADMINISTRATOR`, `PROJECT_ADMINISTRATOR`, `CONTRIBUTOR`, `VIEWER`, `CREATOR`
- `RBAC` — role-based access control envelope for an iTwin, listing roles and members
- `RBACDetails` — individual role definition with permission list
- `APIKey` — application API key with scopes and expiry
- `Token` — OAuth 2.0 bearer token response

### Integration Types
- `Webhook` — event subscription sending callbacks on iTwin Platform state changes

## Authorization

All iTwin Platform APIs require OAuth 2.0 bearer tokens obtained from the Bentley IMS (Identity Management Service). The `Token` type models the token response. Application credentials are registered at `https://developer.bentley.com/my-apps/`.

Supported grant types:
- **Authorization Code + PKCE** — for user-interactive applications
- **Client Credentials** — for service-to-service applications

Required OAuth scopes vary by API (e.g., `itwin-platform`, `imodels:read`, `issues:modify`). The `APIKey` type models the application identity used to obtain tokens.

## Key Relationships

```
Project (iTwin)
  └── iModel (1..n)
        ├── Changeset (ordered log)
        │     └── Checkpoint (materialized snapshot)
        ├── Branch (timeline fork)
        │     └── BranchTag
        ├── Tag / NamedVersion
        ├── Briefcase (client copy)
        ├── Schema → Class → Property
        ├── Model → Element → Category/SubCategory
        ├── View (SpatialView | DrawingView | Sheet)
        ├── Ruleset → Presentation
        └── Query → QueryResults

Project (iTwin)
  ├── Issue (with attachments, comments, audit trail)
  ├── User (member)
  ├── RBAC (roles + permissions)
  └── Webhook (event subscription)
```

## Sample Queries

### Retrieve an iTwin project with its iModels

```graphql
query GetProjectWithIModels($projectId: ID!) {
  project(id: $projectId) {
    id
    displayName
    number
    status
    type
    iModels {
      id
      displayName
      state
      lastModifiedDateTime
    }
  }
}
```

### List changesets for an iModel

```graphql
query ListChangesets($iModelId: ID!, $top: Int) {
  changesets(iModelId: $iModelId, top: $top) {
    id
    displayName
    description
    pushDateTime
    changeType
    fileSize
    author {
      displayName
      email
    }
  }
}
```

### Execute an ECSQL query against an iModel

```graphql
query RunQuery($iModelId: ID!, $changesetId: ID) {
  executeQuery(
    iModelId: $iModelId
    changesetId: $changesetId
    ecsql: "SELECT ECInstanceId, UserLabel, CodeValue FROM bis.Element WHERE ECClassId IS (bis.PhysicalElement) LIMIT 50"
  ) {
    columns
    rows
    rowCount
  }
}
```

### Create an issue on a project

```graphql
mutation CreateIssue($iTwinId: ID!, $subject: String!) {
  createIssue(
    iTwinId: $iTwinId
    displayName: $subject
    type: DEFECT
    status: OPEN
    subject: $subject
  ) {
    id
    displayName
    status
    createdDateTime
  }
}
```

## Links

- Developer Portal: https://developer.bentley.com
- API Reference: https://developer.bentley.com/apis/
- iTwin GitHub: https://github.com/iTwin
- iTwin.js SDK: https://github.com/iTwin/itwinjs-core
- Status Page: https://status.bentley.com
