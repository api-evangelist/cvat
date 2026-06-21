# CVAT (cvat)

CVAT (Computer Vision Annotation Tool) is an open-source platform for annotating images, video, and 3D point clouds for vision AI. The CVAT REST API exposes projects, tasks, jobs, annotations, labels, organizations, memberships, and cloud storage integrations, available both self-hosted (MIT-licensed) and as the hosted CVAT Online service at app.cvat.ai.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cvat/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cvat/refs/heads/main/apis.yml)

## Tags

- Computer Vision
- Data Annotation
- Labeling
- Datasets
- Open Source

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### CVAT Projects API

Create, list, retrieve, update, and delete annotation projects, the top-level container that groups tasks and shares a label set, plus dataset import and export operations.

- **Human URL:** [https://app.cvat.ai/api/docs/](https://app.cvat.ai/api/docs/)
- **Base URL:** `https://app.cvat.ai/api`

#### Tags

- Projects
- Datasets

#### Properties

- [Documentation](https://docs.cvat.ai/docs/api_sdk/api/)
- [API Reference](https://app.cvat.ai/api/docs/)
- [OpenAPI](openapi/cvat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cvat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cvat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/cvat-ai/cvat)

### CVAT Tasks API

Manage annotation tasks - create tasks, upload media data, retrieve metadata, import and export annotations and datasets, and run background data processing within a project.

- **Human URL:** [https://app.cvat.ai/api/docs/](https://app.cvat.ai/api/docs/)
- **Base URL:** `https://app.cvat.ai/api`

#### Tags

- Tasks
- Data

#### Properties

- [Documentation](https://docs.cvat.ai/docs/api_sdk/sdk/reference/apis/tasks-api/)
- [API Reference](https://app.cvat.ai/api/docs/)
- [OpenAPI](openapi/cvat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cvat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cvat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/cvat-ai/cvat)

### CVAT Jobs API

Work with jobs, the assignable annotation units that subdivide a task - list, retrieve, update stage and state, manage assignees, and import or export job-level annotations.

- **Human URL:** [https://app.cvat.ai/api/docs/](https://app.cvat.ai/api/docs/)
- **Base URL:** `https://app.cvat.ai/api`

#### Tags

- Jobs
- Annotation Units

#### Properties

- [Documentation](https://docs.cvat.ai/docs/api_sdk/sdk/reference/apis/jobs-api/)
- [API Reference](https://app.cvat.ai/api/docs/)
- [OpenAPI](openapi/cvat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cvat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cvat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/cvat-ai/cvat)

### CVAT Annotations API

Read, replace, and remove annotation data (shapes, tracks, and tags) on tasks and jobs, and trigger background import and export of annotations in supported dataset formats.

- **Human URL:** [https://app.cvat.ai/api/docs/](https://app.cvat.ai/api/docs/)
- **Base URL:** `https://app.cvat.ai/api`

#### Tags

- Annotations
- Labeling

#### Properties

- [Documentation](https://docs.cvat.ai/docs/api_sdk/api/)
- [API Reference](https://app.cvat.ai/api/docs/)
- [OpenAPI](openapi/cvat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cvat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cvat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/cvat-ai/cvat)

### CVAT Labels API

List, retrieve, update, and delete labels and their attributes and sublabels, defining the annotation taxonomy shared by projects, tasks, and jobs.

- **Human URL:** [https://app.cvat.ai/api/docs/](https://app.cvat.ai/api/docs/)
- **Base URL:** `https://app.cvat.ai/api`

#### Tags

- Labels
- Taxonomy

#### Properties

- [Documentation](https://docs.cvat.ai/docs/api_sdk/api/)
- [API Reference](https://app.cvat.ai/api/docs/)
- [OpenAPI](openapi/cvat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cvat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cvat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/cvat-ai/cvat)

### CVAT Organizations and Memberships API

Manage organizations and their memberships - create and configure organizations, invite and manage members, assign roles, and scope projects, tasks, and storage to an organization context.

- **Human URL:** [https://app.cvat.ai/api/docs/](https://app.cvat.ai/api/docs/)
- **Base URL:** `https://app.cvat.ai/api`

#### Tags

- Organizations
- Memberships

#### Properties

- [Documentation](https://docs.cvat.ai/docs/api_sdk/api/)
- [API Reference](https://app.cvat.ai/api/docs/)
- [OpenAPI](openapi/cvat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cvat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cvat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/cvat-ai/cvat)

### CVAT Cloud Storages API

Register and manage connections to external object storage (AWS S3, Azure Blob, Google Cloud Storage) used as data sources for tasks, including listing bucket content and previews.

- **Human URL:** [https://app.cvat.ai/api/docs/](https://app.cvat.ai/api/docs/)
- **Base URL:** `https://app.cvat.ai/api`

#### Tags

- Cloud Storage
- Integrations

#### Properties

- [Documentation](https://docs.cvat.ai/docs/api_sdk/api/)
- [API Reference](https://app.cvat.ai/api/docs/)
- [OpenAPI](openapi/cvat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cvat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cvat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/cvat-ai/cvat)

## Common Properties

- [GitHub Organization](https://github.com/cvat-ai)
- [LinkedIn](https://www.linkedin.com/company/cvat-ai)
- [Website](https://www.cvat.ai)
- [Documentation](https://docs.cvat.ai)
- [Plans](plans/cvat-plans-pricing.yml)
- [Rate Limits](rate-limits/cvat-rate-limits.yml)
- [Fin Ops](finops/cvat-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
