# CVAT (cvat)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
