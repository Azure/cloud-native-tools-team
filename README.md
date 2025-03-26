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
| VSCode        | [Kubernetes VScode Tool](https://github.com/vscode-kubernetes-tools/vscode-kubernetes-tools) <br> [Releases](https://github.com/Azure/vscode-aks-tools/releases) <br/> [Market Place Link](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-kubernetes-tools) <br> [Tests](https://github.com/vscode-kubernetes-tools/vscode-kubernetes-tools/actions/workflows/build-dev.yml)                              | The VS Code Kubernetes Extension provides a seamless, innovative way to create, manage, and debug Kubernetes workloads—right from your favorite editor. Our extension bridges the gap with easy-to-use commands, real-time insights, and deep integration with kubectl, Helm, and Azure Kubernetes Service (AKS). Simplify cloud-native development with easy integration for powerful tools, smart workflows, and a streamlined experience—all within VS Code. | [`1.3.20` stable release](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-kubernetes-tools) | [Slack Channel](https://cloud-native.slack.com/archives/C02QTE1NKUL)  | [Introduction](https://github.com/vscode-kubernetes-tools/vscode-kubernetes-tools?tab=readme-ov-file#commands-and-features) |
|       | [AKS VScode Tool](https://github.com/Azure/vscode-aks-tools) <br> [Releases](https://github.com/Azure/vscode-aks-tools/releases) <br/> [Market Place Link](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-aks-tools) <br> [Tests](https://github.com/Azure/vscode-aks-tools/actions/workflows/build.yml)                              | Make AKS Developer Experience/debuggability from VSCode Easy - Seamless AKS Management in VS Code, Simplified Deployment & Configuration and Developer-Friendly Workflows | [`1.6.2` stable release](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-aks-tools) | [Shared Slack Channel](https://cloud-native.slack.com/archives/C02QTE1NKUL)  | [Introduction](https://azure.github.io/vscode-aks-tools/index.html) |
| CLI                    | [Draft](https://github.com/Azure/draft) <br> [Releases](https://github.com/Azure/draft/releases) <br> [Tests](https://github.com/Azure/draft/actions/workflows/unit-tests.yml)                              | Make Deploying to Kubernetes Easy - Autogeneration of templates                                               |           |                                                                    |                                                             |
| GitHub Actions                    | [k8s-deploy](https://github.com/Azure/k8s-deploy) <br> [Releases](https://github.com/Azure/k8s-deploy/releases) <br> [Tests](https://github.com/Azure/k8s-deploy/actions/workflows/run-integration-tests-private.yml)                              | GitHub Action for deploying to Kubernetes clusters |  `v5.0.1`         |                                                                    |                                                             |
|                    | [k8s-set-context](https://github.com/Azure/k8s-set-context) <br> [Releases](https://github.com/Azure/k8s-set-context/releases) <br> [Tests](https://github.com/Azure/k8s-set-context/actions)                              | GitHub Action for setting context and retrieving Kubeconfig before deploying to Kubernetes clusters |  `v4.0.1`         |                                                                    |                                                             |
|                     | [k8s-create-secret](https://github.com/Azure/k8s-create-secret) <br> [Releases](https://github.com/Azure/k8s-create-secret/releases) <br> [Tests](https://github.com/Azure/k8s-create-secret/releases)                              | GitHub Action to create Kubernetes cluster secrets |  `v5.0.1`         |                                                                    |                                                             |
|                    | [setup-helm](https://github.com/Azure/setup-helm) <br> [Releases](https://github.com/Azure/setup-helm/releases) <br> [Tests](https://github.com/Azure/setup-helm/actions)                              | GitHub Action for installing Helm |  `v4.3.0`         |                                                                    |                                                             |
|                  | [setup-kubectl](https://github.com/Azure/setup-kubectl) <br> [Releases](https://github.com/Azure/setup-kubectl/releases) <br> [Tests](https://github.com/Azure/setup-kubectl/actions)                              | GitHub Action for installing Kubectl |  `v4.0.0`         |                                                                    |                                                             |
<!-- Copy the row template above for each project and fill in the values -->

---

## 📺 VS Code & AKS Extensions - Videos & Resources  

| 🎥 Topic | 🔗 Link |
|----------|--------|
| **Azure Friday 1**: Azure Kubernetes Services Tools extension in VS Code | [Watch on YouTube](https://www.youtube.com/watch?v=71lfnHZ0IOg) |
| **Azure Friday 2**: Update on Azure Kubernetes Services Tools extension in VS Code | [Listen on Apple Podcasts](https://podcasts.apple.com/nz/podcast/azure-kubernetes-services-tools-extension-in-vs-code/id739501868?i=1000579561542) |
| **VS Code LiveStream**: 🔴 AKS VS Code Tools Extension | [Watch on YouTube](https://www.youtube.com/watch?v=SMNpowToWaI) |
| **AKS x Draft**: Day Zero with Draft | [Watch on YouTube](https://www.youtube.com/watch?v=K1VYLSm32wg&pp=ygUfIERheSB6ZXJvIHdpdGggRFJBRlQgQUtTIFZzY29kZQ%3D%3D) |
| **Inpektor Gadget x VS Code** | [Watch on YouTube](https://www.youtube.com/watch?v=IK1uTboM138&pp=ygUZSW5zcGVjdG9yIEdhZGdldCB4IFZzY29kZQ%3D%3D) |
| **Open @ MSFT** with Prabha, Tom & Tats - *15th March* | [Watch on YouTube](https://www.youtube.com/watch?v=vS0SXEkLDdQ) |
| **More coming soon - Retina** | [Watch on YouTube](https://www.youtube.com/watch?v=yszYA5iu7B4&pp=ygURcmV0aW5hIGFrcyB2c2NvZGXSBwkJvQCDtaTen9Q%3D) |
| **Automated Deployment from AKS VS Code Extension** | [Watch on YouTube](https://www.youtube.com/watch?v=h3mbOFbZDJI&pp=ygU0IFZzQ29kZSBMaXZlU3RyZWFtOiDwn5S0IEFLUyBWUyBDb2RlIFRvb2xzIEV4dGVuc2lvbg%3D%3D) |
| **GitHub Copilot integration with Code** | [Watch on YouTube](https://www.youtube.com/watch?v=O4yBKzXKwhk&t=324s&pp=ygUVR0ggQ29waWxvdCBha3MgdnNjb2Rl0gcJCb0Ag7Wk3p_U) |

## 📝 Blogs / Write-ups  

| 📰 Title | 🔗 Link |
|----------|--------|
| **🛠️ Release It with Changelog** | [Read on Medium](https://medium.com/@tatsat.mishra/%EF%B8%8F-%EF%B8%8F-release-it-with-changelog-fb1d7224bd5d) |
| **VS Code AKS Tools Documentation** | [Read on Azure GitHub](https://azure.github.io/vscode-aks-tools/index.html) |
| **Open @ Microsoft – Bridge to Kubernetes** | [Read on Microsoft Tech Community](https://techcommunity.microsoft.com/t5/azure-infrastructure-blog/open-at-microsoft-bridge-to-kubernetes/ba-p/3853691) |
| **Unlocking DevOps Magic – Azure Kubernetes Service** | [Read on Microsoft Tech Community](https://techcommunity.microsoft.com/t5/educator-developer-blog/unlocking-devops-magic-dive-into-the-azure-kubernetes-service/ba-p/3944622) |
| **VS Code AKS Extensions Guide** | [Read on VS Code Docs](https://code.visualstudio.com/docs/azure/aksextensions) |


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
