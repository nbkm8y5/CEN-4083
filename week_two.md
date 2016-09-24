# CEN-4083
Notes for cloud computing course
##Week Two

###Cloud computing

* Definition of Cloud computing

  * Broad network access
  * on-demand self service
  * resource pooling or shared services
  * rapid elasticity
  * measured service

* Cloud Cell

  * Specialist cloud
  * Single Function

    * Data Storage
    * Database Service
    * Web service

* Interoperability

  * Loosely coupled so it can interact with other cloud cells
  * Push / Pull service to provide content on-demand

* Abstraction Levels

  * Service model view in Levels
  * Highest form of abstraction is always at the top
  * Service Stack

####Infrastructure as a Service

* Hardware Infrastructure (servers, storage, etc.) on a utility basis.

####Platform as a Service

* Same as IaaS but includes the operating system and any other core applications of the operating environment to enable you to install and run your software. Pricing generally is on a utility basis.

####Software as a Service

* As per PaaS but includes posted applications that fulfill a function. The function could be a business, social, or personal function. You simply use the application or applications that you need, when you need it, and avoid the cost of installing and maintaining the application and its supporting hardware infrastructure. Pricing is on a per-use basis.

####Information as a Service

* Provides information relevant to as individual or corporation and to their businesses, business processes, or tasks. Pricing is usually on a consumption, per-use bases.

####Business Process as a Service

* Fulfills a business function or replaces a business process in an organization. Typically combines business process outsourcing (BPO) with software as a service (SaaS). Pricing generally on a per-use basis.

###Deployment Models

* Public Cloud

  * Consumption is always via the internet
  * No restrictions
  * Monthly charge for use (if needed)

* Private Cloud

  * Scoped to organizations, business units, or single entity (person)
  * Restrictions to select group/users
  * Delivered via WAN/LAN

* Community Cloud

  * Broader version of a private cloud
  * Supports common interest communities
  * Shared requirements:

    * security
    * data privacy
    * regulatory environment
    * business models


* Hybrid Cloud

    * An encapsulation of two or more cloud deployment models   (private, community, or public)
    * Unique characteristics
      * Mixture of services and content

###Types of Clouds

* Personal Cloud

* Internet of Things

####Personal Cloud

* Defined by its scope. Person or single entity (can be private, public or hybrid)

####Cloud of Things

* Defined by its scope. Inanimate objects, or things.

* Works with “things” and not people.

###Cloud Relationships

* Cloud components share information /services

  * Types of Relationships

    * encapsulation

      * Object contained/wrapped within another Object
    * Types of encapsulation
      * Composition
       * Multiple distinct objects to create an overall object
      * Aggregate
       * Collection of same/similar clouds/cells
    * Composition
      * Multiple distinct objects to create an overall distinct object
      * Each cell can be replicated across other clouds
      * Management Characteristics
       * updates/patches to cloud cell
       * upgrades to the cell’s hardware
       * upgrades to the cell’s OS and core applications that form platform
       * Upgrades to the applications hosted on the cell, and changes in the roadmap that define when upgrades and updates are to occur in future
      * Any change in one cell applies to all other replicas
    * Federation Aggregate
     * Special type of Composition
     * Mash-up of distinct cloud services with third party cells
     * Mashup of distinct cloud services built entirely of third party cells.
     * Transparent to end user.
     * Collection of same/similar clouds/cell
    * Cloud Cell Patterns
     * Distinct cloud services built from distinct cloud cells for distinct functionality
     * Four essential elements:
      * Pattern name - ID that creates a common vocabulary
      * Problem statement - Description of when and what circumstances to apply pattern
      * Solution - Description of elements that make up the pattern, relationships, and interfaces
      * Consequences - Trade offs and impact of using the pattern (in some cases price and value model)
