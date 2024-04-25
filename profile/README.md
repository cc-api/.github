
# Welcome to Confidential Computing API Group

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

- Virtual Machine: [cc-trusted-vmsdk](https://github.com/cc-api/cc-trusted-vmsdk)
- Cloud Native: [confidential cloud native primitive (CCNP)](https://github.com/cc-api/confidential-cloud-native-primitives)

## 2.3 Tools

- [CC Measure](https://github.com/cc-api/cc-measure): Dump and debug the measurement (TCG event log). (_Replace original [pytdxmeasure](https://pypi.org/project/pytdxmeasure/)_)

# 3. Solutions

- [Full Disk Encryption](https://github.com/cc-api/full-disk-encryption)
- [Confidential Cloud Native AI Pipeline](https://github.com/intel/cloud-native-ai-pipeline/blob/main/docs/How_to_Protect_AI_Models_in_Cloud_Native_Environments.md)
