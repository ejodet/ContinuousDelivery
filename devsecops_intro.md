---

Copyright:
 years: 2021
lastupdated: "2021-06-25"

keywords: IBM Cloud DevOps, DevSecOps

subcollection: ContinuousDelivery

---

{:shortdesc: .shortdesc}
{:external: target="_blank" .external}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:note: .note}
{:important: .important}
{:download: .download}


# DevSecOps with {{site.data.keyword.contdelivery_short}}
{: #devsecops_intro}

[DevSecOps](https://www.ibm.com/cloud/learn/devsecops){: external} is an evolution of Agile and DevOps, integrating secure development best practices as early as possible in the software delivery lifecycle (also known as "shift left"), preventing security problems from reaching production systems and failing corporate audits.
{:shortdesc}

DevSecOps requires automating security and compliance controls as part of continuous integration and continuous delivery processes, and collecting evidence of these controls to demonstrate to auditors that every change in history meets the necessary controls. 

Aligned with the requirements of the Financial Services industry, {{site.data.keyword.contdelivery_short}} provides a reference implementation of [NIST Configuration Management](https://csrc.nist.gov/Projects/risk-management/sp800-53-controls/release-search#!/controls?version=5.1&family=CM){: external} controls as a service that you can configure in a few clicks by using templates.

DevSecOps uses {{site.data.keyword.contdelivery_short}} ({{site.data.keyword.gitrepos}}, Tekton Pipelines, {{site.data.keyword.DRA_short}}, Code Risk Analyzer, and Eclipse Orion {{site.data.keyword.webide}}), and Secrets Manager and Key Protect, Cloud Object Storage, and Container Registry. It can also be used with more tools such as external Git providers and artifact stores. DevSecOps supports hybrid deployments, in particular by using private pipeline workers, and can be interfaced with other deployment tools such as Satellite Config and ArgoCD.

## Background
{: #cd-devsecops-background}

Agile and DevOps provide for automation and greater development velocity, software quality, and consistency and reliability in the delivery processes while removing the potential for human error. DevSecOps integrates a set of security and compliance controls into the DevOps processes. This allows organizations to deliver rapidly and often while maintaining a strong security posture and continuous state of audit-readiness.

Like Agile and DevOps, DevSecOps introduces a culture change and removes the traditional barriers between Developers, Operations, and Security and Compliance officers. Development teams take greater ownership of security rather than relying on external teams to evaluate their software for security, often late in the development cycle when discovered vulnerabilities are much more disruptive and expensive to remediate. The old model of having a siloed security team simply does not scale and will not meet the needs of a development project in a cloud-native DevOps domain. With DevSecOps, a security team's purpose evolves to more of a supportive, advising, and governance role.

With DevSecOps, developers can continue to deliver updates frequently with a minimal amount of friction. Integration of automated security scans and controls into the DevOps pipelines provides confidence with evidence to the change management process, and allows for automated approvals of new deployments to production when all secure criteria are met and specific checks pass. Introducing security and compliance early into the development and deployment process reduces costs and risk by catching problems early, before the software reaches a production environment. This is often referred to as "shift-left".  Moreover, while secure best practices should be a part of training in every organization, it's often the case that developers may lack deep expertise at the security level. Applying DevSecOps and shift-left to the delivery lifecycle reduces the risk of naively releasing known vulnerabilities into production.

There are significant benefits to an organization when a standard set of processes can be used for Continuous Integration and Continuous Delivery by multiple disparate teams developing heterogeneous offerings and components. These benefits include consistency and economies of scales. When a single set of prescriptive, reference pipelines that are instrumented for compliance can be used for all components across an organization, developers are able to spend less time developing automation solutions and rather can focus more on feature development. The development leaders and security officers can be confident that the necessary controls are in place to ensure secure, compliant software and provide evidence that can be used in an audit. Security audits within an organization can be streamlined and are easier when a standard implementation is used, as opposed to each component or offering team implementing compliance their own way.

Learn more about [DevSecOps](https://www.ibm.com/cloud/learn/devsecops){: external}.

For more information about the {{site.data.keyword.contdelivery_short}} DevSecOps reference architecture, see [DevSecOps architecture](/docs/ContinuousDelivery?topic=ContinuousDelivery-cd-devsecops-arch).

Get started and [deploy a secure app with DevSecOps best practices](/docs/ContinuousDelivery?topic=ContinuousDelivery-tutorial-cd-devsecops).
