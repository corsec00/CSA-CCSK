## M1 - Cloud Architecture

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

#CCSK Simulator

01 - A cloud deployment of two or more unique clouds is known as:
A: A Hybrid Cloud

04 - What are the primary security responsibilities of the cloud provider in the management infrastructure?
A: Building and properly configuring a secure network infrastructure

05 - If there are gaps in network logging data, what can you do?
A: You can instrument the technology stack with your own logging.

07 - Who is responsible for the security of the physical infrastructure and virtualization platform?
A: The cloud provider

08 - What factors should you understand about the data specifically due to legal, regulatory, and jurisdictional factors?
A: The physical location of the data and how it is accessed

09 - Which cloud-based service model enables companies to provide client-based access for partners to databases or applications?
A: Software-as-a-service (SaaS)

10 - what are the main considerations for key management
A: Performance, accessibility, latency, and security 

11 - six phases of data security lifecycle
A: Creation , Storing , activity ,made accessible, long-term storage , destroyed 
A: Create, Store, Use, Share, Archive, Destroy

15 - what is the most important resason for know where the cloud service provider will host the data?
A: To allow compliance with local laws regarding data privacy and safeguarding

18 - when deploying security as a service in a highly regulated industry or enviorenment, what should both parties agree on in advance and include in the sla?
A: The metrics defining the service level required to achieve regulatory objectives.

19 - In volume storage, what methods is often used to support resilience and security?
A: data dispersion

20 - What is it called when a customer's information and/or processes are compromised by the actions of another customer in a multi-tenancy environment?
A: isolation failure
A(L): Information leakage

21 - For cloud consumers to be able to properly configure and manage their network security, what must cloud providers do?
D. provide api access (?)
A: explose securiyt controls

22 - What is resource pooling?
A: The provider's computing resources are pooled to serve multiple consumer

25 - Which governance domain focuses on proper and adequate incident detection, response, notification, and remediation?
A: incident response, notification and remediation

27 - What type of information is contained in the Cloud Security Alliance's Cloud Control Matrix?
A: a number of requirements to be implemented based upon numerous standards and regulatory requirements

28 - which SDP component terminates network traffic and enforces communication policies?
A: Gateway

29 - When considering business continuity and disaster recovery with a cloud provider, which layer of the logical stack includes code and message queues?
A: Applistructure (SecGuiV4, P.74)

30 - which type of application security testing tests running applications and includes tests such as web vulnerability testing and fuzzing?
A: Dynamic Application Security Testing (DAST)

32 - which proeminent recommended standard to enable federation of identity in cloud enviorenment include:
A: SAML

33 - How should an SDLC be modified to address application security in a Cloud Computing environment?
A(L): integrate development enviorenments
A: Updated threat and trust models

34 - What is a potential concern of using security-as-a-service(Secaas)?
A: Lack of visibility

35 - which security advantage considers that anything that goes into production is created by the ci/cd pipeline on approved code and configuration templates?
A: Standarization

36 - Isolation failure refers to:
A: Failure of mechanisms separating storage, memory, routing between diferent tenants

38 - What is a challenge of application security in a cloud enviorenment?
A: Limited detailed visibility

40 - The Software Defined Perimeter (SDP) includes which components?
A(L): Controller, Initiating Hosts, and Accepting Hosts
A: Client, Controller (for Auth and Autho), Gateway

41 - In a cloud environment, how can you best determine data/information security risks and potential controls?
A(L): understand the cloud storage architecture in use

43 - which component is a key part of software container systems? (the execution enviorenment, An orchestration and scheduling controller, repository for the container images or code to execute)
A: the execution enviorenment

46 - what makes the metastructure layer of cloud computing so different from traditional computing?
A: It includes the management plane components which are network enabled and remotly accessible

47 - the scope applicability column in the CCM indicates the applicability of the cloud security control to which of the following elements?
A: mappings to well know standards and frameworkss

48 - which computing model contains the protocols and mechanisms providing the interface between the infrastructure and other layers?
A: metastructure layer

49 - a defining set of rules composed of claims and attributes os the entities in a transaction, which is used to determine their level of access to cloud based resource is called what?
A: Entilement Matrix

50 - What is true of Software Defined Network firewalls?
A: They are not limited based on physical topology

51 - Which cloud storage technology would include a content delivery network (CDN), files stored in SaaS, and caching?
A: Application

54 - which concept provides the abstraction needed for resource pools?
A: Virtualization

55 - which common component of big data is focused on the mechanism used to ingest large volumes of data, oftem of a streaming nature
A: Distributed data collection

14 - CCSK: what is more secure and cost effective approach to data security and encryption
A: C. apply a risk based approach

37 - What is the audit related implications of the outsourced cloud services?
A(L): Organizations need to be prepared to share the burden of blame with their outsourced partners

39 - When attempting to contain, erradicate, and recover from a cloud based incident, what is the first step you should do?
A: Put the device in stand by mode
A(L): Terminate all super user/administrative access

### NEW PACK 

In the cloud provider and consumer relationship, which entity manages the virtual or abstracted infrastructure?
A(L): Only the cloud consumer

Who is responsible for the proper rights management and configuration of exposed controls in the management plane?
A(L): The cloud consumer

Cloud provider contract enforceability should be carefully considered in light of
A(L): Foreign and out of state jurisdictions

Which security concept includes the policy, process, and internal controls comprising how an organization is run – including the structures and policies of the leadership and other mechanisms for management?
A(L): Governance

In which layer is the management plane?
A(L): Metastructure layer

Why, in the event that an enterprise seeks a new provider for Security as a Service, must they concern themselves with the problems of translating and transporting existing data and log files in a forensically sound manner?
A(L): Providers often have proprietary standards for logging and reporting

Which phase of the incident response lifecycle includes creating and validating alerts?
A(L): Detection & Analysis

Which technique uses the management plane to detect various activities, such as file uploads or configuration changes?
A(L): Event-driven security

If a provider’s infrastructure is not in scope, who is responsible for building compliant applications and services?
A(L): The customer is responsible for compliant applications and services

Which of the following is NOT a method of object storage encryption?
A(L): Enterprise digital rights management

In which deployment model do cloud customers have a reduced ability to govern operations because the cloud provider is responsible for the management and governance of the infrastructure?
A: Public Cloud

What is the main data source for detection and analysis of an incident?
A(L): Logs

What are the components of an encryption system?
A(L): Data, encryption engine, and key management

What makes single cloud assets less resilient compared with a traditional infrastructure?
A(L): Greater fragility of virtualized resources

Which components typically comprise Infrastructure-as-a-Service (IaaS) providers?
A: Hardware, APIs, and Core Connectivity & Delivery

Which action is part of the containment phase of the incident response lifecycle?
A(L): Making considerations for data loss versus service availability

What is true of how the management plane is to be secured in the cloud?
A(L): The cloud provider is responsible for securing the management plane and exposing the required security features, while the cloud consumer is responsible for configuring access to the management plane

Which of the following statements best describes the potential advantages of security as a service?
A(L): The advantages may include flexible offering of services, greater security domain knowledge and efficiency of SecaaS providers

Which of the following statements best defines the "authentication" component of identity, entitlement, and access management (IdEA).
A(L): Establishing/asserting the identity to the application

What can be implemented to help with account granularity and limit blast radius with IaaS an PaaS?
A: Establishing multiple accounts

Which statement best describes the options for PaaS encryption?
A(L): PaaS is very diverse and may include client/application, database, and proxy encryption as well as other options

Which tool is the primary tool between the cloud provider and consumer that extends governance into business partners and providers?
A: Contracts

Which of the following cloud deployment models represents a composition of two or more clouds that remain unique identities but are bound together by standardized or proprietary technology that enables data and application portability?
A(L): Hybrid Cloud 

Which statement best describes a data (information) dispersion fragmentation scheme?
A: A file is split into fragments; all of the fragments are sent to multiple physical storage repositories.

Which common component of big data is focused on the mechanisms used to ingest large volumes of data, often of a streaming nature?
A: Distributed data collection 

When configuring SDN firewalls, after adding all assets, what is typically the first configuration you must address?
A(L): Opening connections

At a minimum, how often should incident response testing occur?
A(L): Annually and whenever a significant change occurs

In the case of Infrastructure as a Service (IaaS) or Platform as a Service (PaaS) the responsibility to effectively manage the security of the application running in the cloud primarily belongs to who?
A(L): The cloud consumer's administrators

What are the encryption options available for SaaS consumers?
A(L): Provider-managed and (sometimes) proxy encryption

You have a business relationship with a cloud provider for all sales management functionality. Through the APIs and SDKs, you have customized the interface and some functionality, but the back end service is done through the cloud provider. In this relationship, which service is completed by the cloud provider?
A(L): Platform-as-a-service (PaaS)

What is a benefit of application security in a cloud environment?
Isolated environments

A key element of the "Destroy" phase of the Data Security Lifecycle is:
A(L): Crypto-Shredding

To what extent does the CSA Guidance document suffice for legal advice in setting up relationships with cloud service providers?
A(L): The CSA Guidance document provides an overview of selected issues and it is not a substitute for obtaining legal advice. 

What are the three valid options for protecting data as it moves to and within the cloud?
A: Client/Application Encryption, Link/Network Encryption, Proxy-Based Encryption 

How can you reduce the blast radius if an attacker compromises one system?
A(L): Configure applications on distinct virtual networks only connecting where needed

What are major factors to building and managing a secure management plane?
A(L): Perimeter security; customer authentication; internal authentication and credential passing; authorization and entitlements; and logging, monitoring, and alerting

Which of the following items is one of the major regulatory compliance problems associated with cloud environments?
A(L): The distributed nature of cloud storage may result in regulated information being sent across geographical boundaries

Which SDP component is used for authentication and authorization?
A(L): Controller

What are the three main aspects for data security controls?
A: Controlling, protecting, and enforcing

Which facet is focused on protecting the management plane components, such as web and API servers, from attacks?
A(L): Perimeter security

Which type of application security testing should incorporate checks on API calls to the cloud service?
A: Static Application Security Testing (SAST)

When associating the functions to an actor, what is used to restrict a list of possible actions dowr to allowed actions?
A(L): Controls

Why do blind spots occur in a virtualized environment, where network-based security controls may not be able to monitor certain types of traffic?
A(L): Virtual machines may communicate with each other over a virtual network all on the same host rather than a physical network between servers
A(L): None of the above

The level of attention and scrutiny paid to enterprise risk assessments should be directly related to what?
A(L): The value of the information at risk

What is a core tenant of risk management?
A: You can manage, transfer, accept, or avoid risks.

Which deployment model is commonly used to describe a non-cloud data center bridged directly to a cloud provider?
A: Hybrid Cloud

For cloud consumers to be able to properly configure and manage their network security, what must cloud providers do?
A: Expose security controls

What is a method used to decouple the network control plane from the data plane?
A: Software Defined Networking (SDN)

Which concept is defined as the unique expression of an entity within a given namespace?
A(L): Identity

How can you monitor and filter data in a virtual network when traffic might not cross the physical network? (Both)
•	Route traffic to a virtual appliance on the same virtual network
•	Route traffic to a virtual network monitoring or filtering tool on the same hardware

What best describes the tradeoff of Infrastructure as a Service as compared to other cloud service models?
A(L): Greater initial costs and greater security features

Which part of the incident response process is greatly complicated by the resource pooling and rapid elasticity of cloud infrastructure?
A(L): Forensics

What are the NIST defined essential characteristics of cloud computing?
A(L): Broad network access, rapid elasticity, measured service, on-demand self-service, and resource pooling

What is true of cloud built-in firewalls?
A: They typically offer fewer features that newer physical firewalls (SecGuiV4, P.96)

What factor(s), if any, allows for more efficient and effective containment and recovery in a cloud environment than in a non-cloud environment.
A(L): Virtualization technologies, and the elasticity inherent in cloud computing platforms

Which regulation affects data controllers with business in Japan?
A(L): Act on the Protection of Personal Information

The key concern of data backup and recovery schemes is:
A(L): Data should not be commingled with other customers

If there are gaps in network logging data, what can you do?
**You can instrument the technology stack with your own logging.

Who is responsible for the security of the physical infrastructure and virtualization platform?
A(L): The cloud provider

What factors should you understand about the data specifically due to legal, regulatory, and jurisdictional factors?
A(L): The physical location of the data and how it is accessed

Which attack surfaces, if any, does virtualization technology introduce?
A(L): All of the above

What is defined as the process by which an opposing party may obtain private documents for use in litigation?
A: Discovery

What item below allows disparate directory services and independent security domains to be interconnected?
A: Federation

To understand their compliance alignments and gaps with a cloud provider, what must cloud customers rely on?
A: Third-party attestations

Which of the following is a perceived advantage or disadvantage of managing enterprise risk for cloud deployments?
A: Greater reliance on contracts, audits, and assessments due to lack of visibility or management.

Which data security control is the LEAST likely to be assigned to an IaaS provider?
A: Application logic

How does virtualized storage help avoid data loss if a drive fails?
A: Multiple copies in different locations

What is the newer application development methodology and philosophy focused on automation of application development and deployment?
A: DevOps

What is true of searching data across cloud environments?
A: You might not have the ability or administrative rights to search or access all hosted data.

How does running applications on distinct virtual networks and only connecting networks as needed help?
A: It reduces the blast radius of a compromised system

How can virtual machine communications bypass network security controls?
A: VM communications may use a virtual network on the same hardware host

Which concept is a mapping of an identity, including roles, personas, and attributes, to an authorization?
A: Entitlement

Select the best definition of 'compliance' from the options below.
A(L): The awareness and adherence to obligations, including the assessment and prioritization of corrective actions deemed necessary and appropriate.

Which of the following is NOT a cloud computing characteristic that impacts incidence response?
A: Object-based storage in a private cloud.

A defining set of rules composed of claims and attributes of the entities in a transaction, which is used to determine their level of access to cloud-based resources is called what?
A: An entitlement matrix 

Which layer is the most important for securing because it is considered to be the foundation for secure cloud operations?
A: Infrastructure

Why is a service type of network typically isolated on different hardware?
A: It has distinct functions from other networks

Which governance domain deals with evaluating how cloud computing affects compliance with internal security policies and various legal requirements, such as regulatory and legislative?
A: Compliance and Audit Management1

An important consideration when performing a remote vulnerability test of a cloud-based application is to
A: Obtain provider permission for test 

Cloud services exhibit five essential characteristics that demonstrate their relation to, and differences from, traditional computing approaches. Which one of the five characteristics is described as: a consumer can unilaterally provision computing capabilities such as server time and network storage as needed?
A: On-demand self-service

Which of the following statements are NOT requirements of governance and enterprise risk management in a cloud environment?
A: Negotiate long-term contracts with companies who use well-vetted software application to avoid the transient nature of the cloud environment.

In volume storage, what method is often used to support resiliency and security?
A: data dispersionQuestion

What is true of security as it relates to cloud network infrastructure?
A: You should implement a default deny with cloud firewalls.
Which statement best describes the impact of Cloud Computing on business continuity management?
A: Clients need to do business continuity planning due diligence in case they suddenly need to switch providers. 

What is known as a code execution environment running within an operating system that shares and uses the resources of the operating system?
A: ContainerQuestion 

Which term is used to describe the use of tools to selectively degrade portions of the cloud to continuously test business continuity?
A: Chaos Engineering

What is true of companies considering a cloud computing business relationship?
A: The companies using the cloud providers are the custodians of the data entrusted to them.

When deploying Security as a Service in a highly regulated industry or environment, what should both parties agree on in advance and include in the SLA?
A: The metrics defining the service level required to achieve regulatory objectives.

Which cloud storage technology is basically a virtual hard drive for instanced or VMs?
A: Volume storage

Which of the following items is NOT an example of Security as a Service (SecaaS)?
A: Provisioning 

How is encryption managed on multi-tenant storage?
A: The answer could be A, B, or C depending on the provider 

Which statement best describes why it is important to know how data is being accessed?
A: The devices used to access data use a variety of applications or clients and may have different security characteristics.

What is resource pooling?
A: The provider's computing resources are pooled to serve multiple consumers.

Which of the following is NOT normally a method for detecting and preventing data migration into the cloud?
A: Intrusion Prevention System

In which type of environment is it impractical to allow the customer to conduct their own audit, making it important that the data center operators are required to provide auditing for the customers?
A: Multi-tenant environments

What is the best way to ensure that all data has been removed from a public cloud environment including all media such as back-up tapes?
A: Maintaining customer managed key management and revoking or deleting keys from the key management system to prevent the data from being accessed again.
A: Keep the keys stored on the client side so that they are secure and so that the users have the ability to delete their own data.

Which communication methods within a cloud environment must be exposed for partners or consumers to access database information using a web application?
A: Application Programming Interface (API)

Which governance domain focuses on proper and adequate incident detection, response, notification, and remediation?
A: Incident Response, Notification and Remediation

Which opportunity helps reduce common application security issues?
A: Segregation by default

What is the most significant security difference between traditional infrastructure and cloud computing?
A: Management plane

When investigating an incident in an Infrastructure as a Service (IaaS) environment, what can the user investigate on their own?
A: Their own virtual instances in the cloud

If in certain litigations and investigations, the actual cloud application or environment itself is relevant to resolving the dispute in the litigation or investigation, how is the information likely to be obtained?
A: It may require a subpoena of the provider directly 

What are the primary security responsibilities of the cloud provider in compute virtualizations?
A: Enforce isolation and maintain a secure virtualization infrastructure
	
What should every cloud customer set up with its cloud service provider (CSP) that can be utilized in the event of an incident?
A: A communication plan

Audits should be robustly designed to reflect best practice, appropriate resources, and tested protocols and standards. They should also use what type of auditors?
A: Independent auditorsQuestion 

Which of the following statements is true in regards to Data Loss Prevention (DLP)?
A: DLP can provide options for how data found in violation of a policy can be handled. 

For third-party audits or attestations, what is critical for providers to publish and customers to evaluate?
A: Scope of the assessment and the exact included features and services for the assessment

When mapping functions to lifecycle phases, which functions are required to successfully process data?
A: Create and Use

Which of the following is one of the five essential characteristics of cloud computing as defined by NIST?
A: Measured serviceQuestion 

What type of information is contained in the Cloud Security Alliance's Cloud Control Matrix?
A: A number of requirements to be implemented, based upon numerous standards and regulatory requirementsQuestion 

How can key management be leveraged to prevent cloud providers from inappropriately accessing customer data?
A: Segregate keys from the provider hosting dataQuestion

Which statement best describes the Data Security Lifecycle?
A: The Data Security Lifecycle has six stages, can be non-linear, and varies in that some data may never pass through all stages.

Which of the following encryption methods would be utilized when object storage is used as the back-end for an application?
A: Client/application encryption

In the Software-as-a-service relationship, who is responsible for the majority of the security?
A: Cloud ProviderQuestion 

What method can be utilized along with data fragmentation to enhance security?
A: Encryption

Which of the following statements best defines the "authorization" as a component of identity, entitlement, and access management?
A: Enforcing the rules by which access is granted to the resources
How can web security as a service be deployed for a cloud consumer?
A: Both A and C

What of the following is NOT an essential characteristic of cloud computing?
A: Third Party Service

Which type of application security testing tests running applications and includes tests such as web vulnerability testing and fuzzing?
A: Dynamic Application Security Testing (DAST)

In which deployment model should the governance strategy consider the minimum common set of controls comprised of the Cloud Service Provider contract and the organization's internal governance agreements?
A: Hybrid

What is known as the interface used to connect with the metastructure and configure the cloud environment?
A: Management plane

What does it mean if the system or environment is built automatically from a template?
A: Changes made in production are overwritten by the next code or template change.

Which type of application security testing involves manual activity that is not necessarily integrated into automated testing?
A: Code ReviewQuestion 

Which meta-phase does the Cloud Security Alliance use to focus on the security and testing activities when moving code from an isolated development environment to production?
A: Secure DeploymentQuestion

Highly regulated industries such as finance and health care should consider the impact of cloud providers operating in diverse geographic locations and ______________.
A: Legal jurisdictions

The key concern of data location is:
A: Data is stored only in geographic locations permitted by regulations

Which architecture for hybrid cloud connectivity allows you to connect multiple, different cloud networks to a data center using a single hybrid connection?
A: Bastion

What are the barriers to developing full confidence in security as a service (SecaaS)?
A: Compliance, multi-tenancy, and vendor lock-in

Of the choices below which option allows for the most interoperability in security authentication in a cloud environment?
A: SAML

Which of the following is NOT a common storage option with Infrastructure as a Service?
A: Big Data as a Service

Select the statement below which best describes the relationship between identities and attributes
A: An identity is a distinct and unique object within a particular namespace. Attributes are properties which belong to an identity. Each identity can have multiple attributes.

Which cloud security model type provides generalized templates for helping implement cloud security?
A: Reference architecturesQuestion 

What is true of a workload?
A: It is a unit of processing that consumes memoryQuestion 

What are the primary security responsibilities of the cloud provider in the management infrastructure?
A: Building and properly configuring a secure network infrastructureQuestion 

What is a potential concern of using Security-as-a-Service (SecaaS)?
A: Lack of visibility

How should an SDLC be modified to address application security in a Cloud Computing environment?
A: Updated threat and trust models


### CCM 

CCM: What is the role of the Scope Applicability column in the CCM?
A(L): It maps the existing industry standards to the controls in the domains

06 - CCM: In the CCM tool, a ____________ is a measure that modifies risk and includes any process, policy, device, practice or any other actions which modify risk.
A: Control Specification

CCM: In the Identity & Access Management (IAM) domain, what does the number ‘04’ in IAM-04 signify?
A: It is the 4th control in the IAM domain

CCM: What security requirements does the Identity and Access Management domain in the CCM address?
A(L): The requirement to ensure appropriate access to resources and to enable the right individuals to access the right resources at the right times for the right reasons.

CCM: A hypothetical company called "lnfrastructure4Sure" provides Infrastructure as a Service (IaaS) to its clients. A customer wants to review Infrastructure4Sure's hypervisor security implementation measures. Which of the following measures should Infrastructure4Sure implement?
A(L): Choose a hypervisor with a smaller footprint for a reduced attack surface.

CCM: A hypothetical company called "Security4Sure" provides a cloud based service to share confidential documents. The confidential documents are stored in their servers and are encrypted. How will Security4Sure ensure the protection of client data within their data center?
A(L): Encrypt the data at rest and put in place appropriate measures for management of encryption keys

CCM: A hypothetical start-up company called "IT4Sure" provides a cloud based IT management solution. They are growing rapidly and have some security measures in place but the employees are still using their personal mobile devices for storing and communicating company confidential information. So they decide to provide the employees with company mobile devices and implement a Mobile Device Management policy. Two months later, a customer wants to review IT4Sure's mobile device security practices. Which of the following basic protection measures should the client look for in the company's Mobile Device Management policy?
A(L): All of the above

CCM: The following list of controls belong to which domain of the CCM? GRM 06 " Policy GRM 07" Policy Enforcement GRM 08 " Policy Impact on Risk Assessments GRM 09 " Policy Reviews GRM 10" Risk Assessments GRM 11 " Risk Management Framework
A(L): Governance and Risk Management

CCM: A hypothetical company called: 'Health4Sure' is located in the United States and provides cloud based services for tracking patient health. The company is compliant with HIPAA/HITECH Act among other industry standards. Health4Sure decides to assess the overall security of their cloud service against the CCM toolkit so that they will be able to present this document to potential clients. Which of the following approach would be most suitable to assess the overall security posture of Health4Sure's cloud service?
A(L): The CCM domains are not mapped to HIPAA/HITECH Act. Therefore Health4Sure should assess the security posture of their cloud service against each and every control in the CCM. This approach will allow a thorough assessment of the security posture.

CCM: In the CCM tool, 'Encryption and Key Management' is an example of which of the following?
A(L): Domain (for CMM < 4)

CCM: Which of the following statement about CSA's CCM and Security Guidance is False?
A(L): CSA's CCM tells you WHAT to do, the Guidance tells you HOW to do it

CCM: The Cloud Service Delivery Model Applicability column in the CCM indicates the applicability of the cloud security control to which of the following elements?
A(L): SaaS, PaaS or IaaS

CCM: A hypothetical start-up company called "ABC" provides a cloud based IT management solution. They are growing rapidly and therefore need to put controls in place in order to manage any changes in their production environment. Which of the following Change Control & Configuration Management production environment specific control should they implement in this scenario?
A: Policies and procedures shall be established for managing the risks associated with applying changes to business-critical or customer (tenant)-impacting (physical and virtual) applications and system-system interface (API) designs and configurations, infrastructure network and systems components.

CCM: A company wants to use the IaaS offering of some CSP. Which of the following options for using CCM is NOT suitable for the company as a cloud customer?
A: Submit the CCM on behalf of the CSP to CSA Security, Trust & Assurance Registry (STAR), a free, publicly accessible registry that documents the security controls provided by CSPs

CCM: The Architectural Relevance column in the CCM indicates the applicability of the cloud security control to which of the following elements?
A: Physical, Network, Compute, Storage, Application or Data


### ENISA
02 - ENISA: Which is not one of the five key legal issues common across all scenarios:
A: Globalization

03 - ENISA: An example high risk role for malicious insiders within a Cloud Provider includes
A: Auditors

44 - ENISA: an underlying vulnerability related to Loss of Governance is:
A(L): C. Unclear asset owership

12 - ENISA: Which of the following is among the vulnerabilities contributing to a high risk ranking for Network Management?
A: System or O/S vulnerabilities

ENISA: To mitigate credential compromise or theft, cloud provider can implement:
A(L): Anomaly detection capabilities

ENISA: As it relates to public cloud computing, in the European Data Protection law, the customer is considered to be the
A(L): Data controller

ENISA: In Infrastructure as a Service (IaaS), who is responsible for guest systems monitoring?
A(L): Customer

ENISA: Because it is practically impossible to process data in encrypted form, customers should have the following expectation of cloud providers:
A: Provider should always manage customer encryption keys with hardware security module (HSM) storage

ENISA: A key area of controls for cloud provider network architecture is
A(L): Distributed Denial of Service mitigation

ENISA: Which is a potential security benefit of cloud computing?
A: More efficient and timely system updates

ENISA: Licensing Risks refer to:
A: A traditional software licensing scheme may lead to high costs or lack of compliance in cloud systems

ENISA: 'VM hopping' is:
A: Using a compromised VM to exploit a hypervisor, used to take control of other VMs.

ENISA: Lock-in is ranked as a high risk in ENISA research, a key underlying vulnerability causing lock in is:
A: Lack of completeness and transparency in terms of use

ENISA: A reason for risk concerns of a cloud provider being acquired is:
A: Non-binding agreements put at risk


### True or False

16 - APIs and web services require extensive hardening and must assume attacks from authenticated and unauthenticated adversaries
A: True

26 - Cloud applications can use virtual networks and other structures, for hyper-segregated environments
A: True

42 - Sending data to a providers storage over an API is likely as much more reliable and secure than setting up your own SFTP server on a VM in the same provider
A: True (pg 122)

45 - without virtualization, there's no cloud
A: True

52 - Virtual appliances can become bottlenecks because they cannot fail open and must intercept all traffic
A: True

53 - To increase network isolation; you should use SDN capabilities for multiple networks and cloud accounts or segments
A: True

56 - Use elastic servers when possible and move workloads to new instances.
A: True

13 - computer virtualization abstracts the running of code, not including the operation system, from the underlying hardware
A: False (include OS)

24 - Your SLA with your cloud provider ensures continuity for all services.
A: False

The hub and spoke architecture uses internal identity providers or sources connected directly to cloud providers.
A: False (Guide, 12.1.2, pg 136)

Cloud storage will most often utilize the same types of data storage used in traditional data storage technologies.
A(L): False (11.1.2)

While the cloud consumer is responsible for implementing the security controls, the cloud provider implements the security of the workload.
A(L): True

Immutable workloads make it faster to roll out updated versions because applications must be designed to handle individual nodes going down.
A(L): True

Installing security software designed for physical servers onto a virtualized server can result in severe degradation in performance.
A(L): True

To increase network isolation, you should use SDN capabilities for multiple networks and cloud accounts or segments.
A(L): True

Identified issues, risks, and recommended remediations are included when determining compliance.
A(L): True

When the application components communicate directly with the cloud service, the management plane and metastructure might fall within the application security scope.
A(L): True

Absent other evidence, such as tampering or hacking, documents should not be considered more or less admissible or credible because they were created or stored in the cloud.
A(L): True

While a virtual machine is a full abstraction of an operating system, a container is a constrained place to run segregated processes while still using the kernel and other OS capabilities.
A(L): True

Generally speaking, in the United States, a party is obligated to take reasonable steps to prevent the destruction or modification of data in its possession that it reasonably should know, is relevant to an anticipated litigation or government investigation.
A(L): True

All cloud services utilize virtualization technologies.
A(L): True

Big data includes high volume, high variety, and high velocity.
A(L): True

APIs and web services require extensive hardening and must assume attacks from authenticated and unauthenticated adversaries.
A(L): True

Cloud applications can use virtual networks and other structures, for hyper-segregated environments.
A(L): True

Your cloud and on-premises infrastructures should always use the same network address ranges.
A(L): False

REST APIs are the standard for web-based services because they run over HTTPS and work well across diverse environments.
A(L): True

Use elastic servers when possible and move workloads to new instances.
A(L): False

Network logs from cloud providers are typically flow records, not full packet captures.
A(L): True

Dynamic Application Security Testing (DAST) might be limited or require pre-testing permission from the provider.
A: True

Your SLA with your cloud provider ensures continuity for all services.
A(L): False

A security failure at the root network of a cloud provider will not compromise the security of all customers because of multitenancy configuration.
A: False

The containment phase of the incident response lifecycle requires taking systems offline.
A: True

When designing an encryption system, you should start with a threat model.
A: True

Vulnerability assessments cannot be easily integrated into CI/CD pipelines because of provider restrictions.
A: False

If the management plane has been breached, you should confirm the templates/configurations for your infrastructure or applications have not also been compromised.
A: True

Containers are highly portable code execution environments.
A: True

When configured properly, logs can track every code, infrastructure, and configuration change and connect it back to the submitter and approver, including the test results.
A: True

Without virtualization, there is no cloud.
A: True

All assets require the same continuity in the cloud.
A: False

Any given processor and memory will nearly always be running multiple workloads, often from different tenants.
A(L): True

Even with immutable infrastructures, the production environment, should be actively monitored for changes and deviations from approved baselines.
A(L): True

31 - Cloud Control Matrix (CCM) is a completely independent cloud assessment toolkit that does not map any existing standards
A(L): False

### Unaswered

23 - in general, the majority of laws and regulations regarding data in network or cloud environment are designed to be what?
A(L): Designed to ensure data privacy, security, and complianceand to protect the confidentiality, integrity, and availability of data, as well as to establish guidelines for data handling, storage, transfer, and disclosure. They often address issues such as data protection, data breach notification, consent requirements, cross-border data transfers, industry-specific regulations, and compliance 


