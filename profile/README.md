
# Welcome to Confidential Computing API Group

Collaboration at [slack](https://cc-api.slack.com/archives/C0708HZ9087)

## 1 Goal

The CC (Confidential Computing) API Group is a community of people interested in
how innovation can accelerate the adoption of confidential computing technology
in cloud environments.
It serves as a central gathering place for specs, documentation, and ideas.

## 2 CC Trusted API

### 2.1 Overview

1. `CC Trusted API` is designed to access trust measurements **across different TEEs**
like Intel TDX, AMD SEV etc

![](/profile/TEEs.png)

2. `SDK & services` are designed to collect trust measurements across
**different frameworks** like confidential VM,
[confidential cluster](https://github.com/edgelesssys/constellation), [confidential container](https://github.com/confidential-containers) etc

![](/profile/ccnp_deployment.png)

_NOTE: Please refer to https://www.redhat.com/en/blog/confidential-computing-use-cases._

1. `Cloud measurement` will be saved into TEE's report/quote as follow examples:

![](/profile/cloud_measurements.png)

## 2.2 SDKs

| SDK | Repository |
| --- | ---------- |
| Virtual Machine | [cc-trusted-vmsdk](https://github.com/cc-api/cc-trusted-vmsdk) |
| Cloud Native | [confidential cloud native primitive (CCNP)](https://github.com/cc-api/confidential-cloud-native-primitives) |

## 2.3 Tools

| Tool | Description |
| ---- | ----------- |
| [CC Measure](https://github.com/cc-api/cc-measure) | Dump and debug the measurement (TCG event log). (_Replace original [pytdxmeasure](https://pypi.org/project/pytdxmeasure/)_) |
| [CVM Image Rewriter](https://github.com/cc-api/cvm-image-rewriter) | Create and customize the confidential VM's qcow2 image including IMA policy, initrd, device permission etc.|
| [CC Cloud Automation](https://github.com/cc-api/cc-cloud-automation) | Automation framework & tools which supporting diverse confidential cloud flavors like confidential VM/cluster/container/FaaS etc.|

# 3. Solutions

| Solution | Description |
| -------- | ----------- |
| [Full Disk Encryption](https://github.com/cc-api/full-disk-encryption) | Full disk encryption via remote attestation in CC environment without manual key provision |
| [Confidential Cloud Native AI Pipeline](https://github.com/intel/cloud-native-ai-pipeline/blob/main/docs/How_to_Protect_AI_Models_in_Cloud_Native_Environments.md) | Protect the AI model via E2E measurement and attestation, refer [here](https://github.com/cc-api/cloud-native-ai-pipeline/blob/main/docs/How_to_Protect_AI_Models_in_Cloud_Native_Environments.md) |
| [Confidential Cluster](https://github.com/cc-api/confidential-cluster) | Help E2E trust measurement for existing confidential cluster |

# 4. Community

| Date | Community | Description |
| ---- | --------- | ----------- |
| 2024/05/07 | CCC Attestation SIG | Q&A Update ([Video](https://www.youtube.com/watch?v=qoAOXZpdz38), Slide) |
| 2024/05/01 | Linux Foundation OneSummit | [Zero Trust Architecture for AI Workload on Edge](https://onesummit2024.sched.com/event/1YUs1/zero-trust-architecture-for-ai-workload-on-edge-wenhui-zhang-bytedance-ken-lu-intel?iframe=no)
| 2024/04/23 | CCC Attestation SIG | Initial discussion ([Video](https://www.youtube.com/watch?v=63Qgr695xSg), [Slide](https://github.com/CCC-Attestation/meetings/blob/main/materials/KenLu_CC_API.pdf)) |
| 2023/11/16 | CCC TAG | Initial proposal ([Video](https://www.youtube.com/watch?v=Ia2uhSelFnM&list=PLmfkUJc39uMjaB_I1dYW72I44kr9QzG_B&index=11), [Slide](https://github.com/confidential-computing/governance/blob/main/TAC/Meetings/2023/2023-11-16/CCC%20TAC-2023-11-16-CCAPI-CCC-Proposal-TechTalk.pptx.pdf))
| 2022/09/12 | Linux Plumbers Conference | [Secure Bootloader for Confidential Computing](https://lpc.events/event/16/contributions/1260/attachments/932/1950/Secure%20bootloader%20for%20Confidential%20Computing%20-%20LPC.pdf) |

# 5. Papers

| Date | Description |
| ---- | ----------- |
| 2024/03/20 |[Configure and Attest Confidential Virtual Machines in Kubernetes with KubeVirt and Intel® Trust Domain Extensions](https://www.intel.com/content/www/us/en/developer/articles/technical/configure-confidential-vms-kubevirt-intel-trustdom.html?wapkw=Configure%20and%20Attest%20Confidential%20Virtual%20Machines%20in%20Kubernetes%20with) |
| 2024/01/12 | [Full Disk Encryption with Intel® Trust Domain and Intel® Trust Authority](https://www.intel.com/content/www/us/en/developer/articles/technical/disk-encryption-intel-trust-domain-trust-authority.html) |
| 2023/11/10 | [Runtime Integrity Measurement and Attestation in a Trust Domain](https://www.intel.com/content/www/us/en/developer/articles/community/runtime-integrity-measure-and-attest-trust-domain.html) |
