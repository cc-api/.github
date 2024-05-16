
# Welcome to Confidential Computing API Group

The CC (Confidential Computing) API Group is a community to accelerate the adoption of confidential computing technology in cloud environments. It serves as a central gathering place for specs, code, documentation, and ideas.

Welcome to contribute efforts for a common goal of confidential computing technology adoption!


Goals:
    
- Define unified and vendor agnostic APIs for cloud workloads measurement gathering running on diverse TEE vendors. APIs being defined and implemented are about evidence gathering, which can be found in the [spec](https://docs.google.com/document/d/1nO0y3GgnUKGBG7VEwGfzc6ndhArGzWFcULhYEb0-zrg/edit) and [cc-trusted-api](https://github.com/cc-api/cc-trusted-api). Welcome to propose and define more APIs. 
- Provide frameworks to gether [node level evidence](https://github.com/cc-api/cc-trusted-vmsdk) and [container level evidence](https://github.com/cc-api/confidential-cloud-native-primitives)  for workloads. The evidence can be used to complete remote attestation or other verification based on the business needs.
- Provide easy-to-use tools and examples of building trust chain in multiple deloyment flavors of confidential computing environments.

## Getting Started

- [Container Measurement Quick Start](https://github.com/cc-api/confidential-cloud-native-primitives/blob/main/deployment/README.md) - how to prepar a CVM guest image, create a CVM and gather measurement, eventlogs for containers.
- [CC Measure Tool for Node Measurement](https://github.com/cc-api/cc-measure) - CLI tools of gathering measurement, eventlogs and verifying eventlogs for CVM. 
- [CVM Image Rewriter](https://github.com/cc-api/cvm-image-rewriter) - Create and customize the confidential VM's qcow2 image including IMA policy, initrd, device permission etc.
- [CC Cloud Automation](https://github.com/cc-api/cc-cloud-automation) - Automation framework & tools which supporting diverse confidential cloud flavors like confidential VM/cluster/container/FaaS etc.

## More Information

- [CC Trusted API Introduction](https://github.com/cc-api/cc-trusted-api/wiki)
- [Container Measurement Design](https://github.com/cc-api/confidential-cloud-native-primitives/blob/main/docs/container-measurement-design.md)
- [CCNP Architecture](https://cc-api.github.io/confidential-cloud-native-primitives/)
- [Community Activities](https://github.com/cc-api/.github/blob/main/profile/community.md)


## Join the community

- Slack - Join `CC API` [slack channel](https://cc-api.slack.com/archives/C0708HZ9087).
