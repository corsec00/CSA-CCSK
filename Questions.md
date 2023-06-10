### M1 - Cloud Architecture

### M1U2 -  Introduction & Cloud Architecture
Q: Which technology is gererally require to build a resource pools?
A: Virtualization

Q: What is the key difference between traditional virtualization and cloud?
A: Orchestration

Q: Which of the following is *not* a key potential benefit of cloud computing?
A: Compliance
Resiliency
Agility

Q: What benefit(s) was Amazon attempting to realize when they create their internal cloud computing program? 
A: Faster time to deploy developer resources | Better match real-time capacity to fluctuating demand

Q: Resource Pools permanentely assign resource to the user
A: False

Q: Cloud computingsupports scalling up of required resources, but not scaling down
A: False

Q: Which of the following appear in both NIST and ISO/IEC cloud computing definitions?
A: (all)

### M1U3 - Cloud Essential Characteristics

Q: Click and drag the correct NIST model element to appropriate category level
A: (Essential) Broad Network Access | (Service) PaaS | (Depolyment) Private

Q: Services Scaling ou and scale in in quickly are an example of which essensial caharacteristic of cloud
A: Rapid Elasticity

Q: Click and Drag the essential characteristics to the box below
A: Broad Network access | Measured Service | On-Demand self-Service | Rapid elasticity | R Pooling

Q: Which of the following is not an emergency property of resource pooling?
A: Broad network access

### M1U4 - Cloud Service Models

Q: Which service model would a cloud database be considered?
A: Platform as a Service

Q: Software as a Service is always build on top of Platform as a Service which is always build on Infrastructure as a Servce
A: FALSE

Q: Which of the following is most likely to be considered IaaS?
A: A Virtual Machine

Q: In IaaS, Individual virtual machines use which kind of storage?
A: Virtual volumes from a storage pool

Q: Platform as a Service abstracts application platform and platform components for underlying resources, and can be build on top os IaaS.
A: TRUE

Q: Which of the following is not required to be considered SaaS?
A: Customer management of the underlying resources

Q: Drag the labels to indicate which of the SaaS components are build on IaaS
A: The Web Server Auto Scale Group | Application Server Auto Scale Group  

### M1U5 - Cloud Deployment Models

Q: If an organization uses a community cloud deployment model, some portion of the physical infrastructure of the physical infrastructure must be on-premises with one of the comunity members.
A: FALSE

Q: if an organization employs the technique of cloud bursting, which cloud deployment model are they utilizing?
A: Hybrid

Q: Which element of the logical model describes the cloud management plane?
A: Metastructure

Q: Click and drag the accessible and Comsumed by itens on the left to complete the column
A: Untrusted | Trusted | Trusted & Untrusted

### M1U6 - Shared Responsibilities

Q: In which service model does the cloud consumer have the least amount of control over security?
A: Software as a Service

Q: In which cloud service model is the cloud consumer responsible for ensuring that hypervisor is not vulnerable to attack
A: None of the above

Q: When should you define the security controls when building a cloud deployment?
A: After identify control gaps

Q: Click and drag the itens to the correct category
A: Consumer: (Host/Server Security) | (Network, IAM, and Metastructure Configuration Security) | (Data and Application Security)
Provider: (Physical Infrastructure) | (Virtualizat ion/Abstraction) | (Applicat ion and PaaS Services)

## M2 Infrastructure Security for Cloud

### M2U2 - Intro to Infrastructure Security for Cloud Computing

Q: Cloud infrastructure security does not include the virtualization components
A: FALSE

Q: Which the folowing resources pools is not associate with IaaS?
A: Middleware

Q: Click on the component that the cloud consumer is primarily responsible for securing
A: Management & Orchestration --> VM

Q: Which of the following are typically in the underlying infrastructure of a cloud?
A: All options

Q: Why is hardening infrastructure components so important?
A: Cloud are sometimes based on common components that may contain vulnerabilities


### M2U3 - Software Defined Networks

Q: which of the following physical networks is used for internet to instance traffic?
A: Service

Q: Why should cloud providers use multiple underlying physical networks 
A: better isolation | better performance

Q: Which virtual network technology is best suited for cloud?
A: SDN

Q: Virtual Networks:
A: May include inherent security capabilities

Q: Which is a defining characteristic of Software defined Networks
A: Decouples the control plane from the underlying physical network

Q: Which SDN Security capability oftem replaces the need for a physical or virtual appliance?
A: Security Groups

Q: The most effective way from an attacker to compromise a security group is to compromise the host/virtual machine and them modify the rules
A: False

### M2U4 - Cloud Network Security

Q: Which of the following is most effective security barrier to contain blast radius?
A: cloud account/project/subscription

Q: How does a virtual network affect network visibility?
A: Virtual machines on the same physical host don't use the physical network

Q: Place the following networks security tools in the preferred order in most cloud deployments from 1 (most preferred) to 4:
A: Inherent cloud controls (1) | Host Security Agents (2) | Virtual Appliance (3) |Physical appliance (4)

Q: What is the purpose of a bastion network/transit VPC?
A: to better support multiple virtual networks and accounts in hybrid scenarios

Q: Which of the following is primary a responsability of the cloud provider?
A: Securing the underlying virtualization technology

Q: Of the following, which is the most important use case for the Software Defined Permieter?
A: To improve and secure remote access

### M2U5 - Security Compute Workloads

Q: Which of the following are cloud workloads?
A: Virtual Machines | Finctions Serveless | Containers

Q: Click on the pipeline component that executed security tests and build images
A: Continuous Integration Server

Q: Which of the following *most* impacts traditional workload security controls when applied to cloud deployments?
A: High volatility/rates of change

Q: How can immutable workloads improve security?
A: They eliminate error-prone manual management

Q: Select the cloud workload security option that can most improve overall security and reduce attack surface:
A: Use immutable as much as possible

Q: Which of the following is primarily a cloud consumer workload security responsability?
A: Monitoring and logging

### M2U6 - Management Plane Security

Q: Why is management plane security is so critical?
A: Compromise of the management plane potentially compromises all cloud assets

Q: Select the best option for authenticating to a cloud API:
A: HTTP request signing

Q: Click and drag the management plane security steps to te correct order
A: Secure Root Account | Manage non-root users| Enable monitoring/Auditing

Q: Multifactor authentication is the single most important management plane security control
A: TRUE

Q: Identify one drawback to managing users in the management plane:
A: High variability between cloud providers

Q: What is the role of a service administrator?
A: To administer a limited set of cloud services

Q: Select the best option for management plane monitoring, when it is available:
A: Inherent cloud audit, since it captures the most activity

### M2U7 BC DR

Q: What is the single most important rule for cloud BC/DR?
A: Architect for failure

Q: Which is not a key aspect of cloud BC/DR?
A: Hypervisor resiliency

Q: Click on the logical model layer that is most difficult to enable for DR accross Cloud Providers
A: Metastructure

Q: Select a technique to manage continuity withing the cloud provider
A: Cross location/Region Design

## M3 - Managing Cloud Security and Risk

### M3U2 - Governence

Q: Select the governance tool that is most affected by the transaction to cloud computing
A: Compliance reporting

Q: Does the shared responsabilities model define the contract or the contract defines the shared responsabilities model?
A: The contract defines the shared responsability model

Q: In terms of cloud computing and security... what is the primary governance role of a contract?
A: regulatory requirements

Q: Select the layer where you evaluate your providers in the diagram
A: Supplier Assessment

### M3U3 - Managing Cloud Security Risk

Q: What is the responsabilitry of Information risk manahement?
A: Align ris management to the tolerance of the data owner

Q: Your risk assessment effort should be equal for all information assets
A: False

Q: In which service model does the cloud consumer have to rely most on what is in the contract and documented to enforce and manage security?
A: SaaS

Q: Under which conditions is managing risk similar for public and private cloud?
A: When your private cloud is 3rt party hosted and managed

Q: Which do you need to rely more on the manage risks when using public cloud computing?
A: Contracts and SLAs

Q: What is critical when evaluating a cloud service within your risk management program?
A: Accounting for the context of the information assets involved

Q: How can you manage risk if you can't negotiate a contract with the cloud provider?
A: Use compensating controls and your own risk mitigations mechanisms

### M3U4 - Compliance

Q: Audits are only used to meed government regulatory requirements
A: False

Q: Cloud changes compliance. Selec the statement that is incorrect
A: The cloud provider is ultimately responsible for their customer compliance

Q: Which is *not* a source of compliance obligations?
A: Internal audits

Q: Compliance inheritance means that an application built on top of a cloud provider's service that is compliant with a regulation/standard is always guaranteed to be compliance
A: False

### M3U5 - Legal Considerations for Cloud

Q: Cloud Security Alliance Security Guidance provides
A: Information you should discuss with your attorneys

Q: Australian Privacy Act of 1998 can apply to Australian customers, even if the cloud service provider is based elsewhere
A: True

Q: What is the purpose of data localization law?
A: To require that data about the country's citzens be stored in the contry

Q: Which of the following is correct?
A: GDPR prohibits the transfer of personal data outside the EU or EEA to a contry that does not offer a similar privacy rights

Q: The Federal Covernment in the USA does not directly address issues of data privacy, but instead leave it up to the states to create laws that address privacy concerns
A: FALSE

Q: If a business is locate outside EU it does not have to comply with the privacy laws of the European Union
A: FALSE

Q: In the Uninted States, only entities that collect or process financial data or health data must comply with privacy or security laws
A: FALSE

Q: Which of the following is a Standard?
A: PCI DSS

Q: When selecting a cloud provider, is a provider won't negotiate a contract
A: Read the contract carefully, and consult with your advisors to evaluate the terms and understand the potential risks

Q: Cloud consumers ar ultimately responsible for understanding the legal implicationsof using a particular cloud provider and service
A: TRUE

Q: A contract with a cloud provider can fulfill all of the following, except one
A: Prevent a breach of security

Q: if you own the data, it is still possible for your CSP to own the metadata
A: TRUE

### M3U6 - Audit

Q: Why do cloud providers typically limit their customers ability to directly assess and inspect their facilities and services?
A: On-site inspections can be a security risk, and remote assessments are hard to distinguish from real attacks

Q: Audit scopes for any given standard, like an SSAE16 are always consistent
A: FALSE

Q: Select all the following sources that are considered artifacts of compliance
A: Change Management details | Log Files | System configuration details | Activity reports 

Q: Should you review or access the audits of a cloud provider more or less frequently than traditional outsourcers?
A: More

### M3U7 - CSA Tools

Q: Which CSA tool maps cloud security control specifications to architectural relevance?
A: Cloud Control Matrix

Q: You are a cloud provider and struggling to respond to a large amount of highly variable customer RFP requests for security controls documentation. Which CSA document could you instead complete and send to cuspomers?
A: Consensus Assessment Initiative Questionary

Q: Where can cloud providers publish their CAIQ and other security/compliance documents to help cloud prospects and customers assess the provider's security posture?
A: The Security, Trust and Assurance Registry (STAR)

Q: Which CSA tool allows you to queickly search a providers assessment for controls that map to regulations you care about and see the responses to those controls
A: STARWhatch

Q: The CSA Cloud Control Matrix v3.0.1 maps control specifications to FedRAMP High Impact Level
A: FALSE

Q: The CSA Cloud Control Matrix x3.0.1 contains how many control specifications?
A: 133

## M4 - Data Security For Cloud

### M4U2 - Cloud Data Storage & Data Moving to the Cloud

Q: All cloud data is eventually stored on a physical device, like a hard drive
A: TRUE

Q: Which of the following cloud data storage types can be described as 'a database for files'
A: Object storage

Q: Why do we use data dispersion in cloud computing?
A: To improve resiliency in case of an individual drive failure

Q: Which security tool can help detect sensitive data migration to the cloud
A: Data Loss Prevention (DLP)

Q: Which of the available CASB modes is most cloud-native but often not supported by smaller, specially SaaS, providers?
A: API

### M4U3 - Securing Data in the Cloud

Q: How does cloud complicate access controls as compared to traditional data storage?
A: Cloud storage may offer more options, sucha as sharing privileges or access to the data''s metadata

Q: In a cloud computing environment, what is always your most significant security control?
A: Access controls

Q: In the entitlement matrix below, click on the boxees to allow the service administrator to describe and modify volumes but not access logs or object storage:
A: Volume Describe and Volume Modify options

Q: In the entitlement matrix below, select which entitlement allows user to view metadata
A: Volume Describe 

### M4U4 - Encryption for IaaS

Q: Click on the layer on the stack where encryption is best for protecting discrete data throughout the layers, but may be more complex and is less effective for bulk data
A: Application

Q: Select the 3 components of an encryption system
A: Key, Encryption Engine, Data

Q: In 'externally managed' encryption, which is the key component that should be kept externally to improve security?
A: Key Management

Q: Instance managed encryption is
A: An example of what not to do 

Q: Which of the following options encrypts data before you transfer it to object storage?
A: Client side encryption

### M4U5 - Encryption for Paas & SaaS

Q: Select all *potential* options for encryption data in PaaS, if they are supported by the platform
A: Application-level (in your own code) | Provider-Integrated | Database

Q: Click on the location that would provide the most secure place to keep encryption keys:
A: Encryption Server

Q: When using provider managed encryption you are always sharing the same key with other tenants
A: Fasle

Q: Proxy-Encryption requires you to break any existing secure connection to your cloud provider
A: True

### M4U6 - Encryption Key Manegement

Q: Which is the most inherently secure key manegement option, but it may not be viable or even needed depending on your project requirements an platform/provider support?
A: HSM/Appliance

Q: To be considered Bring Your Own Key (BYOK) the provider must not be able to ever see or manage your keys
A: False

Q: Which key management option should you select if you are dealing with high sensitive data that you don't whant your provider to potentially access under any circunstances?
A: HSM/Hybrid

Q: Which option aloows you to use an existing build for keys management without replicating everything in the cloud?
A: Hybrid

### M4U7 - Other Data Security Options

Q: in the diagram below, what area shows the greatest reduction in attack surface
A: Network attack paths

Q: For cloud, where is DLP often best integrated?
A: CASB

Q: What is the primary goal of data masking?
A: Generate test data that still resembles production data

Q: Logs os some events in a cloud environment may not be available to you depending on your choice of cloud provider
A: True.

### M4U8 - The Data Security Lifecycle

Q: How should the data lifecycle be used?
A: as a lightweight tool to better understand data flow and potential vs desired data usage

Q: Place the lifecycle phases in order
A: Create, Store, Use, Share, Archive, Destroy

Q: Why do we map location and access
A: to understand where data flows, in what phases and how it might be accessed (eg devices)

Q: What is the primary objective of mapping functions, actors and locations?
A: To determine what is possible vs what should be allowed

Q: What do we use to reduce what is possible to what should be allowed within the context of the lifecycle?
A: Security controls

## M5 - Securing Cloud Applications, Users and Related Technologies

### M5U2 - Secure Software Development Life Cycle

Q: When moving to cloud, what now becomes within the scope of appication security unlike traditional infrastructure?
A: Management Plane

Q: Click and drag the phases of the lifecycle to the correct order
A: Training, Define, Design, Develop, Test

Q: STRIDE is a common threat modeling framework. Which of the four categories does a cloud provider typically take more responsability to manage?
A: Denial of Service

Q: What is one example of a control that can reduce the potential of Spoofing?
A: Authentication.

### M5U3 - SSDLC Testing & Assessment

Q: Specific testing techniques are tightly aligned and should be performed during their designed phase in the secure software development process
A: FALSE

Q: Which kind of test should be added to static analysis for cloud deployments?
A: Scanning for stored cloud credentials


Q: Which kind of testing will most likely require permission from your cloud provider before performing?
A: Vulnerability assessment

Q: Which vulnerability analysis option will always comply with the terms of service of the cloud provider, but may require paying close attention to network architecture?
A: Host-Based

### M5U4 - DevOps

Q: While there are many definitions of DevOps, one technology/process is typically considered to be central to any devops program. Which tecnology is that?
A: Continuous Integration

Q: Click and drag the version control repository and the continuous integration server to the correct location
A: Version Control Repository | Continuous Integration Server

Q: Identify the core security benefit of immutable
A: Therte are no manual changes, so everything is consistent and administrative access can be disabled

Q: Which of the following are security benefits of DevOps?
A: Greater Standarization | Automated Testing | Improved Security Operations | Improved Auditing.

### M5U5 - Secure Operations

Q: Which of the following is not a new concern of secure operations for applications in the cloud?
A: SAST

Q: Which of the following is an inherence architectural security advanced of cloud?
A: Segregation

Q: How can Serveless improve security?
A: Some attack surface is the responsability of the cloud provider in the shared responsability model

Q: Many of the new architecture options for cloud offer security benefits over what is possible in traditional infrastructure
A: TRUE

### M5U6 - Identity & Access Management Definitions

Q: What could an email address be considered?
A: Identity

Q: What is the technical definition of authentications?
A: The process of confirming an Identity

Q: What is the defining characteristics of federated identity?
A: It inserts an identity acreoss different systems or organizations

Q: Which of the following is a discrete type that will have an identity? Examples include users and organizations.
A: Entity

### M5U7 - IAM Standards

Q: What is the biggest difference between IAM in Cloud and in traditional environments?
A: IAM Must span at least two organizational boundaries

Q: Which IAM standard is best suited for enterprises federating with cloud providers?
A: SAML

Q: Which of the following is one of the 3 most common identity standards in cloud environments?
A: OATH

Q: In the OpenID exchange below, click on the element that represents the enterprise's directory server?
A: Identity Provider

### M5U8 - IAM in Practice

Q: In a hub spoke model, which technology mediates between directory server/identity providers and the service providers/relying parties?
A: Federated Identity Brokers

Q: Which of the following IAM Security incident is mnore likely in cloud versus traditional infrastructure and requires a dedicated incident response focus?
A: Account takeover

Q: Multifactor Authentication is absolutely mandatory for cloud computing due to the higher potential for recomte account takeover
A: TRUE

Q: Checking to see if a user authenticated with MFA from a corporate IP address to authorize an action is an example of what?
A: Attribute based access controls

Q: What is an entitlement matrix used for?
A: To document authorizations

## M6 - Cloud Security Operations

### M6U2 - Selecting a Cloud Provider

Q: Why are elasticity and infrasstructure templating critical IaaS security capabilities?
A: They enable immutable deploynments

Q: Which of the following protocols should a SaaS provider support to help extend an enterprise existing user management security controls and is considered a critical security capability?
A: SAML

Q: Whay are reviewable audits important when evaluating a cloud providerr?
A: They provide third party validation when you cannot audit a provider yourself

Q: Frequent audits and assessments are important when looking at a cloud provider due to how rapidly they evolve their service
A: TRUE

### M6U3 - Incident Response

Q: If an attacker compromises one of your virtual machine, and then uses it to attack other clients on the same cloud platform, what is the cloud provider's likely action?
A: The CSP will first protect the rest of their broader clients, which may mean disrupting your deployment

Q: Click and drag the incident response phases in the proper orther
A: Preparation | Detection and Analysis | Containment, erradication, recovery | Post-Mortem

Q: In which phase would you build a cloud "Jump Kit" of tools and code to speed a response?
A: Preparation

Q: In which phase would you snapshot a virtual machine for forensic?
A: Detection and Analysis

Q: Which of the following most helps you quickly build parallel infrastructure, so that you can rapidly restore operations while still having the compromised enviroinment for analysis?
A: IaS templates

Q: In a postmortem what would be your highest priority to review and remediate if it was a blocker in your incident response?
A: Communications with the cloud provider

### M6U4 - SECaaS Fundamentals

Q: Security as a Service is only used to secure cloud services
A: FALSE

Q: Select all of the following characteristics that are required for something to be considered Security as a Service
A: It is a security product or service delivered as a cloud Service | It meets the NIST essential characteristics

Q: Which of the following is one of the more unique potential benefits of a Security as a Service
A: Intelligence Sharing

Q: Why are regulation differences a potential concern of using Security as a Service?
A: The Cloud Consumer may have regulatory obligations the SECaaS Provider can't meet

Q: Using SECaaS removes accountability for the client, but only for the particular security control the service addresses
A: FALSE

### M6U5 - SECaaS Categories & Recomendations

Q: What characteristics would make a Federated Identity Broker be considered SECaaS a traditional tool?
A: It is hosted in the cloud, elastic and you pay per use
It brokeres authentication to cloud services
It supports multiple cloud providers AND on premise directories
It supports SAML

Q: What is the potential advanced of a web security gateway SECaaS over an on-premisse tool?
A: You can protect mobile users without requiring a VPN to the corporate network

Q: What is the required to redirect traffic to a cloud WAF?
A: DNS Change

Q: Can a cloud-based key management service be integrated with on-premisse encryption?
A: YES

### M6U6 - Domain 14 Considerations

Q: What is the following is not considered a related technology?
A: Security as a Service

Q: Big Data is oftem defined as "high volume, high velocity and high variety". What does high velocity means?
A: The data changes constantly/rapidly

Q: What should you consider relaying extensively on the isolations capabilities of cloud to defend a big data deployment?
A: Big Data Platforms tend to have low inherent security

Q: While not directly related to the clcoud, which IoT Principle is critical for long-term security?
A: The ability to patch/update the 'things' (devices)
Data Encryption

Q: Which of the following issues on a mobile device can acctually create security risks for the cloud deployment?
A: Embedded/static/store credentials

Q: Serveless, used properly, can offer more security benefits than risks
A: TRUE










