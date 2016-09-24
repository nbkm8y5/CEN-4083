# CEN-4083
Notes for cloud computing course
##Week One
>Cloud computing is a model for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources ( e.g. networks, servers, storage, applications and services) that can be rapidly provisioned and released with minimal management effort or service provider interaction.  This cloud model promotes availability and is composed of five essential characteristics, three service models and four deployment models.

###Virtualization - Technical Perspective

####Application

* Hosted on a single machine

* Cheaper to deliver to end user because cost are shared among the users.

* Users do not need high grade systems to run application

* If data stored on cloud, users can access data from any device(mobile or browser)

####Server

* Uses common physical hardward (networks, storage or computing machines) to host virtual machines

* Physical host machines could have any number of virtual machines running on it

* Virtual machines could be hosted using their own OS, and their own set of applications

* Cost benefits include consolidation of a large number of physical machines onto fewer physical machines that host the virtual machines

* Increased efficiency in less space, maintenance, cooling and electricity costs.

* Elasticity: Pooling a set of virtual machines together when they can join/leave the pool of other virtual machines so that scalability is automated and on-demand.

###Cloud Services

* Definition of a service: “a collection of IT systems, components, and resources that work together to provide value to users.”

* Two parameters used to asses a service:

  * Cost
  * SLA (Service Level Agreement)

* Service Level Agreement (SLA)

  * Contract between service consumer and the service supplier
  * Terms: Service delivery time frame (when), its quality (what) and scope (where and how much).

* Operational Level Agreement (OLA)

  * If consumer is internal to service supplier company, then internal agreement is considered an operational level agreement.

* Service Level Objectives (SLO)

  * Objectives, or metrics user to monitor performance and auditing of the system.
  * Used to measure specific characteristics of SLA.

###Cloud Service models

* Business Architecture

  * Business Process as a Service

* Information Architecture

  * Information as a Service

* Application Architecture

  * Software as a Service

* Technology Architecture

  * Platform as a Service

  * Infrastructure as a Service

###Cloud Deployment models

* Public

  * Advantage: Open to anyone with internet access
  * Disadvantage: Non-regulatory, security, restrictions (Finance/Medical/etc.)

* Private

  * Provides service to a single entity, with any additional services and not shared
  * Expensive when compared to public because costs are not divided

* Community

  * In between public and private.
  * Common interest entities such as banks, corporations, individuals

* Hybrid

  * Conglomerate of the other types of clouds.
  * Bursting, when resource exceed that of a given cloud and needs to extend into other clouds.

###Five Characteristics of Cloud computing

* Broad network access (Where)

  * Consume services from anywhere

* On-demand self-service (When)

  * Consume services when you want

* Resource Pooling and Virtualization (How)

  * Pool the infrastructure, virtual platforms, and applications

* Rapid Elasticity (How)

  * Share pooled resources to enable horizontal scalability

* Measured service (How much)

  * Pay for the service you consume as you consume it

### Cloud Computing Actors

* Service Consumer

  * Uses cloud services, determines which services to use, and reaches agreement with service provider

 * Service Provider

  * Entity that provides cloud services to service consumers
  * Orchestrates configuration and activation of services to consumer
  * Maintains service catalog of services provided including service costs and price.

* Service Creator

  * Creates the service for the service provider
  * Main function is to marshal and optimize the supply of resources

* Service Broker

  * Intermediary between consumer and a number of service providers
  * Plays three distinct roles:
    * Prevents consumer from locked in to a specific provider
    * Aggregates services from various providers and provides a transparent interconnection between multiple providers
    * Orchestrates the services to the consume from a number of providers based on cost, quality and timeliness.
