# CLOUD NATIVE TOOLS TEAM - OPEN SOURCE PROJECTS

This document is maintained by the **Cloud Native Tools Team** team. It serves as a guide to help internal teams and stakeholders find projects relevant to our space. Use it to assess which projects to adopt, contribute to, or monitor—depending on your goals (e.g., prototyping, production use, long-term investment).

## Support Expectations

Projects listed here are open source and are **not covered by any enterprise support agreement** unless explicitly stated. If you require help:
- Check open issues in the project’s repo.
- Join project communication channels (Slack, mailing lists, etc.).

If the project is consumed through a managed service or vendor-supported product, refer to that product’s support policy.

---

## Project List

| Project Area                         | Project & Artifacts                                                                                                                                                           | Goal / Description                                                                                                         | Maturity & API Version                                       | Upstream Communication                                                                                                  | Notes / Usage Guidance                                                                                                   |
| ------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------ |
| {{ Area Name }}                      | [{{ Project Name }}]({{ project_url }}) <br> ([Releases]({{ releases_url }})) <br> [Tests]({{ test_url }})                              | {{ One-liner purpose statement }}                                                   | {{ Maturity level }} <br> API: {{ api_version }}            | {{ Slack channel / mailing list / GitHub issues }}                                                                      | {{ Usage notes, platform integration, internal guidance }}                                                               |
| Deployment                    | [Draft](https://github.com/Azure/draft) <br> [Releases](https://github.com/Azure/draft/releases) <br> [Tests](https://github.com/Azure/draft/actions/workflows/unit-tests.yml)                              | Make Deploying to Kubernetes Easy - Autogeneration of templates                                               |           |                                                                    |                                                             |

<!-- Copy the row template above for each project and fill in the values -->

---

## Maturity Model

When evaluating a project, consider:

- **Project State**: 
  - CNCF projects follow the [CNCF maturity model](https://github.com/cncf/toc/blob/master/process/graduation_criteria.adoc).
  - Projects under {{ orgs }} may follow a custom internal maturity model ([link] if applicable).
- **API Version**: API maturity follows [Kubernetes versioning](https://kubernetes.io/docs/concepts/overview/kubernetes-api/#api-versioning) unless otherwise noted.

Typical states include:
- `sandbox` / `alpha`: Early development, rapid change.
- `incubating` / `beta`: Functionally complete, stability improving.
- `graduated` / `stable`: Actively maintained and widely adopted.

---

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
