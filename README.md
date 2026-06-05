# Bentley Systems (bentley-systems)

Bentley Systems (NASDAQ: BSY) is an infrastructure engineering software company providing comprehensive applications and cloud services for the design, construction, and operations of infrastructure across roads, bridges, rail, water, energy, and the built environment. Bentley exposes its developer platform through iTwin — a digital twin platform with 30+ REST APIs covering iModel data management, reality capture, project scheduling, reporting, visualization, clash detection, and webhooks. The company reports $1.3 billion in annual revenue, ~5,500 colleagues across 42 countries, and serves 42,000 accounts in 189 countries.

**APIs.json:** [https://github.com/api-evangelist/bentley-systems](https://github.com/api-evangelist/bentley-systems)

## Tags

- Infrastructure Engineering
- Digital Twin
- BIM
- CAD
- Reality Capture
- Construction
- Asset Management
- Geospatial
- iTwin
- iModel

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### iTwin Access Control API

Manage user permissions, roles, group memberships, owner members, share invitations, and job-based access for iTwin projects. Provides role-based access control across the iTwin Platform with 39 operations covering invitations, group/user membership, share links, and permission discovery.

- **Human URL:** [https://developer.bentley.com/apis/access-control-v2/](https://developer.bentley.com/apis/access-control-v2/)
- **Base URL:** `https://api.bentley.com/accesscontrol`

#### Tags

- Access Control
- Identity
- Permissions
- Roles
- Groups
- Members
- Invitations
- Administration

#### Properties

- [Documentation](https://developer.bentley.com/apis/access-control-v2/)
- [API Reference](https://developer.bentley.com/apis/access-control-v2/operations/)
- [OpenAPI](openapi/itwin-access-control-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-access-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-access-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwins API

Create, manage, and query iTwin containers — the top-level organizational unit that holds iModels, reality data, schedules, and project context. The iTwins API administers projects, organizations, repositories, and hierarchy across the iTwin Platform.

- **Human URL:** [https://developer.bentley.com/apis/itwins/](https://developer.bentley.com/apis/itwins/)
- **Base URL:** `https://api.bentley.com/itwins`

#### Tags

- iTwins
- Projects
- Organizations
- Administration
- Hierarchy
- Repositories

#### Properties

- [Documentation](https://developer.bentley.com/apis/itwins/)
- [API Reference](https://developer.bentley.com/apis/itwins/operations/)
- [OpenAPI](openapi/itwin-itwins-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-itwins.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-itwins.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Users API

Read user account profile information for users authorized to the iTwin Platform. Provides identity lookup and profile data used by other iTwin services.

- **Human URL:** [https://developer.bentley.com/apis/users/](https://developer.bentley.com/apis/users/)
- **Base URL:** `https://api.bentley.com/users`

#### Tags

- Users
- Identity
- Profiles
- Administration

#### Properties

- [Documentation](https://developer.bentley.com/apis/users/)
- [API Reference](https://developer.bentley.com/apis/users/operations/)
- [OpenAPI](openapi/itwin-users-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-users.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-users.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin iModels API

Create, clone, fork, query, and manage iModels — Bentley's specialized information containers for the lifecycle of infrastructure assets. Covers changesets, named versions, locks, briefcases, users, baselines, thumbnails, and changesets-extended-data across 51 operations.

- **Human URL:** [https://developer.bentley.com/apis/imodels-v2/](https://developer.bentley.com/apis/imodels-v2/)
- **Base URL:** `https://api.bentley.com/imodels`

#### Tags

- iModels
- Changesets
- Named Versions
- Briefcases
- Locks
- Versioning
- Digital Twin
- Data Management

#### Properties

- [Documentation](https://developer.bentley.com/apis/imodels-v2/)
- [API Reference](https://developer.bentley.com/apis/imodels-v2/operations/)
- [OpenAPI](openapi/itwin-imodels-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-imodels.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-imodels.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Storage API

Store and retrieve files inside iTwin containers — folders, files, file versions, and trashed items. Supports upload, copy, lock, and content download operations across 27 endpoints.

- **Human URL:** [https://developer.bentley.com/apis/storage/](https://developer.bentley.com/apis/storage/)
- **Base URL:** `https://api.bentley.com/storage`

#### Tags

- Storage
- Files
- Folders
- Uploads
- Versions
- Content

#### Properties

- [Documentation](https://developer.bentley.com/apis/storage/)
- [API Reference](https://developer.bentley.com/apis/storage/operations/)
- [OpenAPI](openapi/itwin-storage-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-storage.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-storage.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Webhooks API

Subscribe to iTwin Platform events. Create, list, update, and delete webhook subscriptions to receive callbacks when iModels, iTwins, reality data, synchronization jobs, and other resources change state.

- **Human URL:** [https://developer.bentley.com/apis/webhooks-v2/](https://developer.bentley.com/apis/webhooks-v2/)
- **Base URL:** `https://api.bentley.com/webhooks`

#### Tags

- Webhooks
- Events
- Subscriptions
- Notifications
- EventDriven

#### Properties

- [Documentation](https://developer.bentley.com/apis/webhooks-v2/)
- [API Reference](https://developer.bentley.com/apis/webhooks-v2/operations/)
- [OpenAPI](openapi/itwin-webhooks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Synchronization API

Synchronize native design files (DGN, DWG, IFC, SHP, RVT, and more) from Azure Blob Storage, iTwin Storage, or ProjectWise into iModels. Manages connections, source files, runs, and synchronization configurations across 42 operations.

- **Human URL:** [https://developer.bentley.com/apis/synchronization/](https://developer.bentley.com/apis/synchronization/)
- **Base URL:** `https://api.bentley.com/synchronization`

#### Tags

- Synchronization
- Connections
- Connectors
- Source Files
- DGN
- IFC
- Project Delivery

#### Properties

- [Documentation](https://developer.bentley.com/apis/synchronization/)
- [API Reference](https://developer.bentley.com/apis/synchronization/operations/)
- [OpenAPI](openapi/itwin-synchronization-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-synchronization.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-synchronization.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Reality Management API

Organize and manage reality data — photos, point clouds, meshes, 3D Tiles, and orthophotos. Provides metadata management and access control for reality capture deliverables across the iTwin Platform.

- **Human URL:** [https://developer.bentley.com/apis/reality-management/](https://developer.bentley.com/apis/reality-management/)
- **Base URL:** `https://api.bentley.com/reality-management`

#### Tags

- Reality Capture
- Reality Data
- Point Clouds
- Meshes
- 3D Tiles
- Photogrammetry

#### Properties

- [Documentation](https://developer.bentley.com/apis/reality-management/)
- [API Reference](https://developer.bentley.com/apis/reality-management/operations/)
- [OpenAPI](openapi/itwin-reality-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-reality-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-reality-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Reality Modeling API (ContextCapture)

Submit reality modeling jobs that process photos and laser scans into 3D meshes, point clouds, and 3D Tiles using Bentley's ContextCapture engine. Covers workspaces, settings, and job management.

- **Human URL:** [https://developer.bentley.com/apis/contextcapture/](https://developer.bentley.com/apis/contextcapture/)
- **Base URL:** `https://api.bentley.com/contextcapture`

#### Tags

- Reality Modeling
- ContextCapture
- Photogrammetry
- 3D Reconstruction
- Jobs

#### Properties

- [Documentation](https://developer.bentley.com/apis/contextcapture/)
- [API Reference](https://developer.bentley.com/apis/contextcapture/operations/)
- [OpenAPI](openapi/itwin-reality-modeling-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-reality-modeling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-reality-modeling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Reality Analysis API

Run AI-powered analyses against reality data — object detection, segmentation, lines/polygon extraction, change detection — across 19 operations spanning jobs, output results, and detectors.

- **Human URL:** [https://developer.bentley.com/apis/reality-analysis/](https://developer.bentley.com/apis/reality-analysis/)
- **Base URL:** `https://api.bentley.com/realitydataanalysis`

#### Tags

- Reality Analysis
- AI
- Machine Learning
- Object Detection
- Change Detection
- Reality Capture

#### Properties

- [Documentation](https://developer.bentley.com/apis/reality-analysis/)
- [API Reference](https://developer.bentley.com/apis/reality-analysis/operations/)
- [OpenAPI](openapi/itwin-reality-analysis-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-reality-analysis.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-reality-analysis.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Reality Conversion API

Convert reality data formats between point cloud, mesh, and 3D Tile representations. Submit conversion jobs and retrieve outputs.

- **Human URL:** [https://developer.bentley.com/apis/realityconversion/](https://developer.bentley.com/apis/realityconversion/)
- **Base URL:** `https://api.bentley.com/realityconversion`

#### Tags

- Reality Conversion
- Format Conversion
- Point Clouds
- Meshes
- 3D Tiles

#### Properties

- [Documentation](https://developer.bentley.com/apis/realityconversion/)
- [API Reference](https://developer.bentley.com/apis/realityconversion/operations/)
- [OpenAPI](openapi/itwin-reality-conversion-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-reality-conversion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-reality-conversion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Schedules API

Plan and manage 4D construction schedules. The largest iTwin API surface — 128 operations — covering tasks, resources, calendars, baselines, animations, work breakdown structures, and progress tracking for SYNCHRO-grade project management.

- **Human URL:** [https://developer.bentley.com/apis/schedules/](https://developer.bentley.com/apis/schedules/)
- **Base URL:** `https://api.bentley.com/schedules`

#### Tags

- Schedules
- Scheduling
- Tasks
- Resources
- 4D Construction
- SYNCHRO
- Project Management
- Gantt

#### Properties

- [Documentation](https://developer.bentley.com/apis/schedules/)
- [API Reference](https://developer.bentley.com/apis/schedules/operations/)
- [OpenAPI](openapi/itwin-schedules-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-schedules.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-schedules.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Insights API (Reporting)

Build custom reports and dashboards on top of iModel data. Define mappings, groups, properties, and ODATA endpoints to extract structured data for Power BI, Tableau, and custom analytics. 62 operations span reports, mappings, extractions, calculated properties, and ODATA.

- **Human URL:** [https://developer.bentley.com/apis/insights/](https://developer.bentley.com/apis/insights/)
- **Base URL:** `https://api.bentley.com/insights`

#### Tags

- Insights
- Reporting
- Dashboards
- ODATA
- Analytics
- Business Intelligence
- Mappings

#### Properties

- [Documentation](https://developer.bentley.com/apis/insights/)
- [API Reference](https://developer.bentley.com/apis/insights/operations/)
- [OpenAPI](openapi/itwin-insights-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-insights.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-insights.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Carbon Calculation API

Compute embodied carbon footprint across infrastructure projects using EC3 (Embodied Carbon in Construction Calculator) integrations and iModel quantity takeoffs. 15 operations covering carbon templates, materials, and EPD lookups.

- **Human URL:** [https://developer.bentley.com/apis/carbon-calculation/](https://developer.bentley.com/apis/carbon-calculation/)
- **Base URL:** `https://api.bentley.com/carboncalculation`

#### Tags

- Carbon
- Sustainability
- EC3
- Embodied Carbon
- ESG
- Quantity Takeoff

#### Properties

- [Documentation](https://developer.bentley.com/apis/carbon-calculation/)
- [API Reference](https://developer.bentley.com/apis/carbon-calculation/operations/)
- [OpenAPI](openapi/itwin-carbon-calculation-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-carbon-calculation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-carbon-calculation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Clash Detection API

Detect geometry clashes between 3D elements in iModels. Define clash tests, suppression rules, and retrieve clash run results across 20 operations.

- **Human URL:** [https://developer.bentley.com/apis/clash-detection-v2/](https://developer.bentley.com/apis/clash-detection-v2/)
- **Base URL:** `https://api.bentley.com/clashdetection`

#### Tags

- Clash Detection
- Validation
- Quality Assurance
- BIM Coordination

#### Properties

- [Documentation](https://developer.bentley.com/apis/clash-detection-v2/)
- [API Reference](https://developer.bentley.com/apis/clash-detection-v2/operations/)
- [OpenAPI](openapi/itwin-clash-detection-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-clash-detection.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-clash-detection.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Changed Elements API

Track and query design changes between iModel versions. Enables visual diff workflows and change reporting across project iterations.

- **Human URL:** [https://developer.bentley.com/apis/changed-elements-v2/](https://developer.bentley.com/apis/changed-elements-v2/)
- **Base URL:** `https://api.bentley.com/changedelements`

#### Tags

- Changed Elements
- Change Tracking
- Versioning
- BIM Coordination

#### Properties

- [Documentation](https://developer.bentley.com/apis/changed-elements-v2/)
- [API Reference](https://developer.bentley.com/apis/changed-elements-v2/operations/)
- [OpenAPI](openapi/itwin-changed-elements-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-changed-elements.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-changed-elements.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Issues API

Manage issues raised against project deliverables — observations, defects, RFIs, punch list items. Supports attachments, comments, audit trail, and workflow transitions across 29 operations.

- **Human URL:** [https://developer.bentley.com/apis/issues-v1/](https://developer.bentley.com/apis/issues-v1/)
- **Base URL:** `https://api.bentley.com/issues`

#### Tags

- Issues
- Issue Tracking
- Punchlist
- RFI
- Collaboration
- Project Delivery

#### Properties

- [Documentation](https://developer.bentley.com/apis/issues-v1/)
- [API Reference](https://developer.bentley.com/apis/issues-v1/operations/)
- [OpenAPI](openapi/itwin-issues-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-issues.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-issues.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Forms API

Define and submit forms — field-data capture templates used for inspections, checklists, and project-data collection. 29 operations covering form definitions, instances, and attachments.

- **Human URL:** [https://developer.bentley.com/apis/forms-v2/](https://developer.bentley.com/apis/forms-v2/)
- **Base URL:** `https://api.bentley.com/forms`

#### Tags

- Forms
- Data Collection
- Inspections
- Checklists
- Field Capture

#### Properties

- [Documentation](https://developer.bentley.com/apis/forms-v2/)
- [API Reference](https://developer.bentley.com/apis/forms-v2/operations/)
- [OpenAPI](openapi/itwin-forms-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-forms.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-forms.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Library API

Manage reusable component libraries — catalogs, components, parameters, and component instances. 60 operations span catalog management, search, ingest, and component definition.

- **Human URL:** [https://developer.bentley.com/apis/library/](https://developer.bentley.com/apis/library/)
- **Base URL:** `https://api.bentley.com/library`

#### Tags

- Library
- Catalog
- Components
- Reusable Assets
- Parameters

#### Properties

- [Documentation](https://developer.bentley.com/apis/library/)
- [API Reference](https://developer.bentley.com/apis/library/operations/)
- [OpenAPI](openapi/itwin-library-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-library.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-library.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Saved Views API

Persist and share saved iModel viewer states — camera positions, display styles, category visibility, model selections, and viewport overrides. 22 operations covering groups, tags, images, and extensions.

- **Human URL:** [https://developer.bentley.com/apis/savedviews/](https://developer.bentley.com/apis/savedviews/)
- **Base URL:** `https://api.bentley.com/savedviews`

#### Tags

- Saved Views
- Visualization
- Camera
- Display Styles
- Collaboration

#### Properties

- [Documentation](https://developer.bentley.com/apis/savedviews/)
- [API Reference](https://developer.bentley.com/apis/savedviews/operations/)
- [OpenAPI](openapi/itwin-saved-views-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-saved-views.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-saved-views.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Scenes API

Configure 3D scenes that compose iModels, reality data, OpenStreetMap, terrain, and overlays into a single viewer experience. 19 operations covering scenes, layers, and scene extensions.

- **Human URL:** [https://developer.bentley.com/apis/scenes/](https://developer.bentley.com/apis/scenes/)
- **Base URL:** `https://api.bentley.com/scenes`

#### Tags

- Scenes
- Visualization
- 3D
- Composition
- Layers

#### Properties

- [Documentation](https://developer.bentley.com/apis/scenes/)
- [API Reference](https://developer.bentley.com/apis/scenes/operations/)
- [OpenAPI](openapi/itwin-scenes-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-scenes.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-scenes.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Named Groups API

Create and manage logical groupings of iTwin elements by query, selection, or hierarchy. Used by reporting, validation, and visualization workflows.

- **Human URL:** [https://developer.bentley.com/apis/named-groups/](https://developer.bentley.com/apis/named-groups/)
- **Base URL:** `https://api.bentley.com/namedgroups`

#### Tags

- Named Groups
- Element Grouping
- Queries
- Selections

#### Properties

- [Documentation](https://developer.bentley.com/apis/named-groups/)
- [API Reference](https://developer.bentley.com/apis/named-groups/operations/)
- [OpenAPI](openapi/itwin-named-groups-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-named-groups.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-named-groups.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Grouping and Mapping API

Map iModel elements to logical groups and property mappings used in reporting and analysis workflows. Bridges the geometric element world to the tabular reporting world. 24 operations.

- **Human URL:** [https://developer.bentley.com/apis/grouping-and-mapping/](https://developer.bentley.com/apis/grouping-and-mapping/)
- **Base URL:** `https://api.bentley.com/grouping-and-mapping`

#### Tags

- Grouping
- Mapping
- Property Mapping
- Reporting
- Calculated Properties

#### Properties

- [Documentation](https://developer.bentley.com/apis/grouping-and-mapping/)
- [API Reference](https://developer.bentley.com/apis/grouping-and-mapping/operations/)
- [OpenAPI](openapi/itwin-grouping-mapping-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-grouping-mapping.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-grouping-mapping.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Transformations API

Submit and manage transformation jobs that derive new iModels from existing ones — element filtering, schema migration, and data shaping. 22 operations covering transformations and runs.

- **Human URL:** [https://developer.bentley.com/apis/transformations/](https://developer.bentley.com/apis/transformations/)
- **Base URL:** `https://api.bentley.com/transformations`

#### Tags

- Transformations
- Data Transformation
- iModel Filtering
- Schema Migration
- Jobs

#### Properties

- [Documentation](https://developer.bentley.com/apis/transformations/)
- [API Reference](https://developer.bentley.com/apis/transformations/operations/)
- [OpenAPI](openapi/itwin-transformations-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-transformations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-transformations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Export API

Export iModel data to web-friendly formats including 3D Tiles, glTF, and tileset bundles. Supports browser-ready visualization pipelines.

- **Human URL:** [https://developer.bentley.com/apis/export/](https://developer.bentley.com/apis/export/)
- **Base URL:** `https://api.bentley.com/imodels-export`

#### Tags

- Export
- 3D Tiles
- glTF
- Web Visualization
- Mesh Export

#### Properties

- [Documentation](https://developer.bentley.com/apis/export/)
- [API Reference](https://developer.bentley.com/apis/export/operations/)
- [OpenAPI](openapi/itwin-export-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-export.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-export.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Mesh Export API

Export 3D mesh geometry from iModels for use in CesiumJS, Three.js, Unity, and Unreal Engine visualizations.

- **Human URL:** [https://developer.bentley.com/apis/mesh-export/](https://developer.bentley.com/apis/mesh-export/)
- **Base URL:** `https://api.bentley.com/mesh-export`

#### Tags

- Mesh Export
- Geometry
- 3D Tiles
- glTF
- Cesium
- Web Visualization

#### Properties

- [Documentation](https://developer.bentley.com/apis/mesh-export/)
- [API Reference](https://developer.bentley.com/apis/mesh-export/operations/)
- [OpenAPI](openapi/itwin-mesh-export-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-mesh-export.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-mesh-export.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Visualization API

Server-side visualization service for rendering iTwins in web browsers without client compute. Supports interactive viewers and image generation.

- **Human URL:** [https://developer.bentley.com/apis/visualization/](https://developer.bentley.com/apis/visualization/)
- **Base URL:** `https://api.bentley.com/visualization`

#### Tags

- Visualization
- Rendering
- Web Visualization
- Streaming

#### Properties

- [Documentation](https://developer.bentley.com/apis/visualization/)
- [Postman Collection](collections/itwin-access-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-access-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-carbon-calculation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-carbon-calculation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-cesium-curated-content.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-cesium-curated-content.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-changed-elements.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-changed-elements.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-clash-detection.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-clash-detection.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-edfs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-edfs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-export.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-export.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-forms.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-forms.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-geospatial-features.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-geospatial-features.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-grouping-mapping.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-grouping-mapping.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-imodels.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-imodels.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-insights.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-insights.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-issues.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-issues.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-itwins.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-itwins.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-library.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-library.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-mesh-export.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-mesh-export.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-named-groups.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-named-groups.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-pnid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-pnid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-reality-analysis.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-reality-analysis.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-reality-conversion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-reality-conversion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-reality-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-reality-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-reality-modeling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-reality-modeling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-saved-views.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-saved-views.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-scenes.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-scenes.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-schedules.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-schedules.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-sensor-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-sensor-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-storage.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-storage.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-synchronization.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-synchronization.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-transformations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-transformations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-users.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-users.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/itwin-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Sensor Data API

Ingest, store, and query IoT sensor telemetry associated with iTwin assets. Provides device, sensor, observation, and time-series endpoints.

- **Human URL:** [https://developer.bentley.com/apis/sensor-data/](https://developer.bentley.com/apis/sensor-data/)
- **Base URL:** `https://api.bentley.com/sensor-data`

#### Tags

- Sensor Data
- IoT
- Time Series
- Telemetry
- Devices
- Observations

#### Properties

- [Documentation](https://developer.bentley.com/apis/sensor-data/)
- [API Reference](https://developer.bentley.com/apis/sensor-data/operations/)
- [OpenAPI](openapi/itwin-sensor-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-sensor-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-sensor-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Cesium Curated Content API

Access Cesium's curated geospatial content — Cesium World Terrain, Bing Maps imagery, OpenStreetMap buildings — for streaming into iTwin viewers.

- **Human URL:** [https://developer.bentley.com/apis/cesium-curated-content/](https://developer.bentley.com/apis/cesium-curated-content/)
- **Base URL:** `https://api.bentley.com/curated-content`

#### Tags

- Cesium
- Curated Content
- Geospatial
- Imagery
- Terrain
- Streaming

#### Properties

- [Documentation](https://developer.bentley.com/apis/cesium-curated-content/)
- [API Reference](https://developer.bentley.com/apis/cesium-curated-content/operations/)
- [OpenAPI](openapi/itwin-cesium-curated-content-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-cesium-curated-content.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-cesium-curated-content.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin Geospatial Features API

Manage geospatial feature collections — GeoJSON-style points, lines, polygons — associated with iTwins. Supports overlay layers in viewers.

- **Human URL:** [https://developer.bentley.com/apis/geospatial-features/](https://developer.bentley.com/apis/geospatial-features/)
- **Base URL:** `https://api.bentley.com/geospatial-features`

#### Tags

- Geospatial
- Features
- GeoJSON
- GIS
- Overlays

#### Properties

- [Documentation](https://developer.bentley.com/apis/geospatial-features/)
- [API Reference](https://developer.bentley.com/apis/geospatial-features/operations/)
- [OpenAPI](openapi/itwin-geospatial-features-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-geospatial-features.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-geospatial-features.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enterprise Data Federation Service (EDFS) API

Federate access to data held in Bentley and third-party repositories — ProjectWise, SharePoint, and external systems — so that iTwin applications can query unified asset metadata. 24 operations across data sources, schemas, queries, and federation policies.

- **Human URL:** [https://developer.bentley.com/apis/edfs/](https://developer.bentley.com/apis/edfs/)
- **Base URL:** `https://api.bentley.com/edfs`

#### Tags

- EDFS
- Data Federation
- ProjectWise
- Enterprise Data
- Federated Queries

#### Properties

- [Documentation](https://developer.bentley.com/apis/edfs/)
- [API Reference](https://developer.bentley.com/apis/edfs/operations/)
- [OpenAPI](openapi/itwin-edfs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-edfs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-edfs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### iTwin P&ID to iTwin API

Convert Process & Instrumentation Diagrams (P&IDs) into iTwin-compatible intelligent data — symbols, lines, and connectivity — using AI extraction. 14 operations covering jobs, outputs, and training.

- **Human URL:** [https://developer.bentley.com/apis/pnid-to-itwin-v2/](https://developer.bentley.com/apis/pnid-to-itwin-v2/)
- **Base URL:** `https://api.bentley.com/pnid`

#### Tags

- PnID
- Process Diagrams
- Plant Engineering
- AI Extraction
- Symbols

#### Properties

- [Documentation](https://developer.bentley.com/apis/pnid-to-itwin-v2/)
- [API Reference](https://developer.bentley.com/apis/pnid-to-itwin-v2/operations/)
- [OpenAPI](openapi/itwin-pnid-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/itwin-pnid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/itwin-pnid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Developer Portal](https://developer.bentley.com)
- [Portal](https://developer.bentley.com)
- [Documentation](https://developer.bentley.com/apis/)
- [API Reference](https://developer.bentley.com/apis/)
- [Getting Started](https://developer.bentley.com/tutorials/quickstart-web-and-service-apps/)
- [Quickstart](https://developer.bentley.com/tutorials/quickstart-web-and-service-apps/)
- [Tutorials](https://developer.bentley.com/tutorials/)
- [Authentication](https://developer.bentley.com/apis/overview/authorization/)
- [Sign Up](https://www.bentley.com/forms/register/)
- [Pricing](https://developer.bentley.com/pricing/)
- [Plans](plans/bentley-systems-plans-pricing.yml)
- [Rate Limits](rate-limits/bentley-systems-rate-limits.yml)
- [Fin Ops](finops/bentley-systems-finops.yml)
- [Status Page](https://status.bentley.com)
- [Changelog](https://developer.bentley.com/community/)
- [Compliance](https://www.bentley.com/legal/data-privacy/)
- [Terms of Service](https://developer.bentley.com/legal/)
- [Privacy Policy](https://www.bentley.com/legal/privacy-policy/)
- [GitHub Organization](https://github.com/iTwin)
- [GitHub Organization](https://github.com/bentleysystems)
- [SDK](https://github.com/iTwin/itwinjs-core)
- [SDK](https://github.com/iTwin/iTwinUI)
- [SDK](https://github.com/iTwin/imodels-clients)
- [SDK](https://github.com/iTwin/mobile-sdk-ios)
- [SDK](https://github.com/iTwin/mobile-sdk-android)
- [SDK](https://github.com/iTwin/viewer)
- [SDK](https://github.com/iTwin/itwin-unreal-plugin)
- [SDK](https://github.com/iTwin/presentation)
- [SDK](https://github.com/iTwin/appui)
- [SDK](https://github.com/bentleysystems/MicroStationPython)
- [SDK](https://github.com/bentleysystems/openstaadpy)
- [SDK](https://github.com/bentleysystems/openstaad-mcp)
- [Sandbox](https://developer.bentley.com/tutorials/web-application-quick-start/)
- [Console](https://developer.bentley.com/my-apps/)
- [LinkedIn](https://www.linkedin.com/company/bentley-systems)
- [YouTube](https://www.youtube.com/user/BentleySystems)
- [X (Twitter)](https://twitter.com/BentleySystems)
- [Blog](https://blog.bentley.com)
- [Support](https://www.bentley.com/support/)
- [Community](https://developer.bentley.com/community/)
- [Vocabulary Of Terms](vocabulary/bentley-systems-vocabulary.yml)
- [JSON-LD](json-ld/bentley-systems-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [L L Ms Txt](https://bentley.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
