
# Welcome to Confidential Computing API Group

## 1 Goal

The CC (Confidential Computing) API Group is a community of people interested in
how innovation can accelerate the adoption of confidential computing technology
in cloud environments.
It serves as a central gathering place for specs, documentation, and ideas.

## 2 APIs and SDKs

### 2.1 CC Trusted API

CC Trusted API is designed to reduce the challenge of:

- collecting trust measurements for **different frameworks** like confidential VM,
[confidential cluster](https://github.com/edgelesssys/constellation), [confidential container](https://github.com/confidential-containers) etc
![](/profile/cloud_frameworks.png)
- accessing trust measurements from the **different TEEs** like Intel TDX, AMD SEV etc
![](/profile/TEEs.png)

Fine mores SDK/Services to calculate measurements:

- Virtual Machine: [cc-trusted-vmsdk](https://github.com/cc-api/cc-trusted-vmsdk)
- Cloud Native: [confidential cloud native primitive (CCNP)](https://github.com/cc-api/confidential-cloud-native-primitives)
