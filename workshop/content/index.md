---
Sort: 1
Title: OpenShift Dedicated Workshop
NextPage: exercises/1-prereqs
ExitSign: Setup Environment
---

## Introduction to the workshop

### What is OpenShift Dedicated?

OpenShift Dedicated (OSD) is an OpenShift cluster provided as a managed cloud service, configuredfor high availability (HA), and dedicated to a single customer (single-tenant). OpenShift Dedicated is managed by Red Hat Operations, providing increased security and years ofoperational experience working with OpenShift in both development and production. OpenShift Dedicated also comes with award-winning 24x7 Red Hat Premium Support.

You can learn more at: https://www.openshift.com/dedicated

### Choosing between OSD 3.11 and OSD 4.1
Today OpenShift Dedicated clusters are available in both 3.11 or 4.1 versions.  Below is a summary table to help you assess which might be the correct fit. We are working to achieve feature parity across both versions, but until that happens there are some differences.

| Requirement                        | 3.11 | 4.1          |
|------------------------------------|------|--------------|
| Private Clusters                   | Yes  | No (roadmap) |
| Logging Stack on Infra Nodes       | Yes  | No           |
| Operator Support                   | No   | Yes          |
| BYOC                               | Yes  | No (roadmap) |
| Consumption-based billing          | Yes  | No (roadmap) |
| Red Hat Managed Integration (RHMI) | Yes  | No (roadmap) |

### What will we do in this workshop?
In this lab, you’ll go through a set of tasks that will help you understand some of the concepts of deploying and securing container based applications on top of OpenShift Dedicated 3.11.

Some of the things you’ll be going through:

- Deploy a node.js based app via S2I and Kubernetes Deployment objects
- Set up an continuous delivery pipeline to automatically push changes to the source code
- Explore logging in OSD
- Experience self healing of applications
- Explore configuration management through configmaps, secrets and environment variables
- Use persistent storage to share data across pod restarts
- Explore networking within Kubernetes and applications
- Familiarization with OpenShift and Kubernetes functionality

**TODO:ADD HPA SECTION????**

You’ll be doing the majority of the labs using the OpenShift CLI, but you can also accomplish them using the OpenShift Dedicated web console.
