# Behind the Scenes: Uncovering TLS and Server Certificate Practice of IoT Device Vendors in the Wild


## Description
This repository publicly shares IoT datasets utilized in the research study titled ***Behind the Scenes: Revealing TLS and Server Certificate Practices of IoT Device Vendors in Real-world Scenarios***, which is to be appeared at ACM IMC 2023. 

In accordance with user privacy safeguards, the datasets do not include *device_id* information. Researchers interested in utilizing the datasets for their studies are encouraged to reach out to authors for a complete version.


## Citation
Please kindly provide proper citations to the following publications when utilizing these datasets:
1. ToBeFilled. 
2. Huang, Danny Yuxing, et al. "Iot inspector: Crowdsourcing labeled network traffic from smart home devices at scale." Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies 4.2 (2020): 1-21.


## Datasets
We describe the shared IoT datasets as follows:
- IoTInspectorClientHello: the client-side dataset collected by IoTInspector of 2,014 unique IoT deivces, which includes:
  - Device name
  - Device vendor
  - Client-proposed TLS version
  - Client-proposed ciphersuites
  - Client-proposed extensions    
- ServerHello: the parsed server-side dataset obtained by initiating TLS connections to 1,151 IoT servers, which includes:
  - Server name indication
  - Server TLS version
  - Server ciphersuite
  - Server extensions
  - Server certificate version
  - Server certificate not before
  - Server certificate not after
  - Server certificate validity period
  - Server certificate serial number
  - Server certificate issuer
  - Server certificate subject
  - Server certificate key identifier
  - Server certificate signature algorithm
  - Server certificate SAN
  - crt.sh response of server-presented certificate
