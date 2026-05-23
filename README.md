# Bentley Systems

Profile of [Bentley Systems](https://www.bentley.com) (NASDAQ: BSY) — infrastructure engineering software and the [iTwin Platform](https://developer.bentley.com) digital twin APIs — for the API Evangelist network.

Bentley publishes a serious public developer platform: 31 REST APIs across 8 functional groups (Administration, Digital Twin Management, Project Scheduling, Reality Modeling, Reality Capture, Reporting & Insights, Synchronization, Validation, Visualization, Workflow Automation) plus 84 GitHub repositories under [github.com/iTwin](https://github.com/iTwin) including the iTwin.js TypeScript SDK, Unreal Engine plugin, mobile SDKs for iOS and Android, the iTwinUI design system, and an additional `bentleysystems` org carrying MicroStation/STAAD Python SDKs and an OpenSTAAD MCP server.

## Scale

- $1.3 billion annual revenue
- 5,500 colleagues across 42 countries
- 42,000 accounts in 189 countries
- NASDAQ: BSY

## Developer Platform Highlights

- **Base URL:** `https://api.bentley.com`
- **Authorization:** Bentley IMS OAuth2 (`https://ims.bentley.com/connect/authorize`)
- **Status page:** [status.bentley.com](https://status.bentley.com) monitors 60+ components across iTwin Platform, iTwin Products, identity, and core services
- **Pricing model:** Credit-based subscriptions (Community free / Standard $199 / Premium $499 / Enterprise custom) with overage at $1.20 per credit. Service consumption metered (1 credit per 2 GB iModel ingress, 1 credit per visualization-hour, 1 credit per 250,000 reporting rows, etc.)

## APIs (31)

| API | Group | Operations | Spec |
|---|---|---:|---|
| Access Control | Administration | 39 | [openapi/itwin-access-control-openapi.yml](openapi/itwin-access-control-openapi.yml) |
| iTwins | Administration | 29 | [openapi/itwin-itwins-openapi.yml](openapi/itwin-itwins-openapi.yml) |
| Users | Administration | 6 | [openapi/itwin-users-openapi.yml](openapi/itwin-users-openapi.yml) |
| iModels | Digital Twin Management | 51 | [openapi/itwin-imodels-openapi.yml](openapi/itwin-imodels-openapi.yml) |
| Storage | Digital Twin Management | 27 | [openapi/itwin-storage-openapi.yml](openapi/itwin-storage-openapi.yml) |
| Webhooks | Workflow Automation | 6 | [openapi/itwin-webhooks-openapi.yml](openapi/itwin-webhooks-openapi.yml) |
| Synchronization | Synchronization | 42 | [openapi/itwin-synchronization-openapi.yml](openapi/itwin-synchronization-openapi.yml) |
| Reality Management | Reality Capture | 12 | [openapi/itwin-reality-management-openapi.yml](openapi/itwin-reality-management-openapi.yml) |
| Reality Modeling (ContextCapture) | Reality Modeling | 11 | [openapi/itwin-reality-modeling-openapi.yml](openapi/itwin-reality-modeling-openapi.yml) |
| Reality Analysis | Reality Capture | 19 | [openapi/itwin-reality-analysis-openapi.yml](openapi/itwin-reality-analysis-openapi.yml) |
| Reality Conversion | Reality Capture | 7 | [openapi/itwin-reality-conversion-openapi.yml](openapi/itwin-reality-conversion-openapi.yml) |
| Schedules | Project Scheduling | 128 | [openapi/itwin-schedules-openapi.yml](openapi/itwin-schedules-openapi.yml) |
| Insights (Reporting) | Reporting & Insights | 62 | [openapi/itwin-insights-openapi.yml](openapi/itwin-insights-openapi.yml) |
| Carbon Calculation | Reporting & Insights | 15 | [openapi/itwin-carbon-calculation-openapi.yml](openapi/itwin-carbon-calculation-openapi.yml) |
| Clash Detection | Validation | 20 | [openapi/itwin-clash-detection-openapi.yml](openapi/itwin-clash-detection-openapi.yml) |
| Changed Elements | Validation | 4 | [openapi/itwin-changed-elements-openapi.yml](openapi/itwin-changed-elements-openapi.yml) |
| Issues | Project Delivery | 29 | [openapi/itwin-issues-openapi.yml](openapi/itwin-issues-openapi.yml) |
| Forms | Project Delivery | 29 | [openapi/itwin-forms-openapi.yml](openapi/itwin-forms-openapi.yml) |
| Library | Digital Twin Management | 60 | [openapi/itwin-library-openapi.yml](openapi/itwin-library-openapi.yml) |
| Saved Views | Visualization | 22 | [openapi/itwin-saved-views-openapi.yml](openapi/itwin-saved-views-openapi.yml) |
| Scenes | Visualization | 19 | [openapi/itwin-scenes-openapi.yml](openapi/itwin-scenes-openapi.yml) |
| Named Groups | Digital Twin Management | 6 | [openapi/itwin-named-groups-openapi.yml](openapi/itwin-named-groups-openapi.yml) |
| Grouping and Mapping | Reporting & Insights | 24 | [openapi/itwin-grouping-mapping-openapi.yml](openapi/itwin-grouping-mapping-openapi.yml) |
| Transformations | Digital Twin Management | 22 | [openapi/itwin-transformations-openapi.yml](openapi/itwin-transformations-openapi.yml) |
| Export | Visualization | 9 | [openapi/itwin-export-openapi.yml](openapi/itwin-export-openapi.yml) |
| Mesh Export | Visualization | 5 | [openapi/itwin-mesh-export-openapi.yml](openapi/itwin-mesh-export-openapi.yml) |
| Sensor Data | Digital Twin Management | 6 | [openapi/itwin-sensor-data-openapi.yml](openapi/itwin-sensor-data-openapi.yml) |
| Cesium Curated Content | Visualization | 3 | [openapi/itwin-cesium-curated-content-openapi.yml](openapi/itwin-cesium-curated-content-openapi.yml) |
| Geospatial Features | Digital Twin Management | 3 | [openapi/itwin-geospatial-features-openapi.yml](openapi/itwin-geospatial-features-openapi.yml) |
| Enterprise Data Federation (EDFS) | Data Management | 24 | [openapi/itwin-edfs-openapi.yml](openapi/itwin-edfs-openapi.yml) |
| P&ID to iTwin | Digital Twin Management | 14 | [openapi/itwin-pnid-openapi.yml](openapi/itwin-pnid-openapi.yml) |

Total operations across the 31 surfaces: **750+** (counted from the developer portal sitemap).

## Artifacts

- **31** OpenAPI 3.1 specifications under `openapi/`
- **16** Naftiko capabilities under `capabilities/` covering access control, iTwins, iModels (lifecycle / changesets / named versions), storage, webhooks, synchronization, reality management, schedules (tasks + resources), insights, issues, and clash detection
- **8** JSON Schemas under `json-schema/` for iTwin, iModel, Changeset, NamedVersion, RealityData, ScheduleTask, Issue, WebhookSubscription
- **5** JSON Structures under `json-structure/`
- **1** JSON-LD context at `json-ld/bentley-systems-context.jsonld` mapping iTwin entities to schema.org / Dublin Core / WGS84
- **13** request/response examples under `examples/`
- **1** Spectral ruleset at `rules/bentley-systems-rules.yml` enforcing api.bentley.com base URL, OAuth2 security, PascalCase operationIds, UUID-typed path parameters, Title Case summaries, and externalDocs requirements
- **1** vocabulary at `vocabulary/bentley-systems-vocabulary.yml` (iTwin, iModel, Changeset, Named Version, BIS Schema, Reality Data, ContextCapture, ProjectWise, SYNCHRO, MicroStation, OpenRoads/OpenBridge/OpenBuildings, AssetWise, Saved View, Clash Detection, Issue, Mapping, EC3 Integration, Synchronization Connection, Connector, Credit, Bentley IMS, 4D Construction Schedule, Digital Twin)
- **1** API Commons Plans manifest at `plans/bentley-systems-plans-pricing.yml` (Community / Standard / Premium / Enterprise + service-credit rates)
- **1** API Commons Rate Limits manifest at `rate-limits/bentley-systems-rate-limits.yml`
- **1** FinOps Framework manifest at `finops/bentley-systems-finops.yml` (FOCUS 1.3 aligned) covering credit consumption meters, allocation strategies, and optimization recommendations

## GitHub Surface

| Org | Notable Repos |
|---|---|
| [iTwin](https://github.com/iTwin) (84 repos) | `itwinjs-core`, `iTwinUI`, `viewer`, `viewer-components-react`, `admin-components-react`, `appui`, `presentation`, `imodel-native`, `imodels-clients`, `bis-schemas`, `mobile-sdk-ios`, `mobile-sdk-android`, `mobile-samples`, `itwin-unreal-plugin`, `reality-capture`, `imodel-transformer`, `stratakit` |
| [bentleysystems](https://github.com/bentleysystems) (11 repos) | `MicroStationPython`, `openstaadpy`, `openstaad-mcp` (MCP Server for AI Agents to drive STAAD.Pro), `ES-API-Samples` |

## Notable Findings

- Real, modern public developer platform with consistent surface design across 31 APIs
- Schedules API (128 operations) and Library API (60) are the two largest surfaces — both reflect Bentley's deep heritage in construction scheduling (SYNCHRO) and reusable BIM component libraries
- AI-forward extensions are first class: Reality Analysis (AI on point clouds), P&ID-to-iTwin (AI extraction from process diagrams), Carbon Calculation (EC3-backed sustainability reporting), and an OpenSTAAD MCP server enabling AI agents to drive structural analysis
- Cesium acquisition shows up in the platform with a dedicated Cesium Curated Content API and Unreal/CesiumJS-targeted Mesh Export API

## Notable Absences

- No public, downloadable OpenAPI specs published from the developer portal (the "OpenAPI v3 (JSON)" link on each API page renders client-side and is not crawlable). Specs in this repo are reconstructed skeletons from the sitemap and operation pages.
- No public RSS or Atom feed for changelog / release notes; changelog content is per-API and surfaced through the community area only
- Per-API rate limits are not published — runtime throttling is delivered via 429 + Retry-After headers
- No public AsyncAPI for webhooks even though Webhooks v2 has a dedicated API

## Files at Repo Root

- [apis.yml](apis.yml) — the master APIs.yml index for this provider
- [README.md](README.md) — this file
