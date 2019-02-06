---
title: "Fusion: Align design guides with policy."
description: How do you align design guides with policy?
author: BrianBlanchard
ms.date: 01/04/2019
---
<!---
I've established policies. How to help developers adopt these policies?
Draft an architecture design guide.

[Aspirational statement] If you're using Azure, you can use one of ours as a starting point. The choose one of the following 6 as a starting point and mold it to fit your policies.
--->

<!-- markdownlint-disable MD026 -->

# How do you align design guides with policy?

After you've [defined cloud policies](define-policy.md) based on your [identified risks](understanding-business-risk.md), you'll need to generate actionable guidance that aligns with these policies for your IT staff and developers to refer to. Drafting a cloud architecture design guide allows you to specify specific structural, technological, and process choices based on the policy statements you generated for each of the five governance disciplines.

A cloud governance design guide should establish the architecture choices and design patterns for each of the core infrastructure components of cloud deployments that best meet your policy requirements. Alongside these you should provide a high-level explanation of the technology, tools, and processes that will support each of these design decisions.

Although your risk analysis and policy statements may, to some degree, be cloud platform agnostic, your design guide should provide platform-specific implementation details that your IT and dev. Focus on the architecture, tools, and features of your chosen platform when making design decision and providing guidance.

While cloud design guides should take into account some of the technical details associated with each infrastructure component, they are not meant to be extensive technical documents or specifications. Make sure your guides address all of your policy statements and clearly state design decisions in a format easy for staff to understand and reference.

<!-- markdownlint-enable MD033 -->

## Sample cloud design guides

If you're planning to use the Azure platform for your cloud adoption, the Fusion guidance provides several [sample design guides](../journeys/overview.md) covering a range of common adoption scenarios. In addition to the design guide itself, each sample gives the use case, business risks, tolerance requirements, and policy statements that went into creating the example design guide. These examples represent a synthesis of real-world customer experience of the cloud adoption process in Azure.

While every cloud adoption has unique goals, priorities, and challenges, these samples should provide a good template for converting your policy into guidance. Pick the closest scenario to your situation as a starting point, and mold it to fit your specific policy needs.

| Design guide scenario                                                       | Description                                                                   |
|-----------------------------------------------------------------------------|-------------------------------------------------------------------------------|
| [Future-Proof](../journeys/future-proof/design-guide.md) | Early stage adoption may not warrant and investment in governance. However, this guide will establish a few best practices and policies to future-proof adoption and ensure that proper governance can be added later. |
| [Protected Data](../journeys/production-workload/design-guide.md) | Some solutions are dependent upon protected data, like customer information or business secrets. The business risks associated with hosting protected data in the cloud can often be mitigated with proper disciplines. |
| [Enterprise MVP](../journeys/enterprise-mvp/design-guide.md) | Migrating the first few workloads in an enterprise comes with a few common business risks. The Enterprise MVP design guide provides a scalable starting point to move quickly, but grow into larger governance needs with cloud adoption. |
| [Enterprise @ Scale](../journeys/enterprise-scale/design-guide.md) | As additional solutions are deployed to the cloud, business risks grow. When enterprises reach scale across cloud deployments, governance requirements scale. This design guide builds on Enterprise MVP to meet these more complex needs. |
| [Enterprise Guardrails](../journeys/enterprise-guardrails/design-guide.md) | Multiple teams deploying to multiple clouds will naturally create policy violations. In complex environments, with thousands of applications and hundreds of thousands of VMs, automated policy enforcement is required. |
| [Multi-Cloud Governance](../journeys/multi-cloud/design-guide.md) | Industry analysts are predicting that multi-cloud solutions are an inevitable future. This design guide establishes current approaches to prepare for a multi-cloud landscape. |

## Next steps

With design guidance in place, establish [policy adherence processes](processes.md) to ensure policy compliance.

> [!div class="nextstepaction"]
> [Policy adherence processes](processes.md)