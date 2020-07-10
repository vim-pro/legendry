# Software Requirements Specification
## For  vim-pro
Version alpha  
7/7/2020, 7/8/2020  
Prepared by [@z2e3r40o](https://github.com/z2e3r40o)  

Table of Contents
=================
  * [Revision History](#revision-history)
  * [Introduction](#introduction)
    * 1.1 [Purpose](#11-purpose)
    * 1.2 [Document Conventions](#12-document-conventions)
    * 1.3 [Intended Audience and Reading Suggestions](#13-intended-audience-and-reading-suggestions)
    * 1.4 [Product Scope](#14-product-scope)
    * 1.5 [References](#15-references)
  * [Overall Description](#overall-description)
    * 2.1 [Product Perspective](#21-product-perspective)
    * 2.2 [Product Functions](#22-product-functions)
    * 2.3 [User Classes and Characteristics](#23-user-classes-and-characteristics)
    * 2.4 [Operating Environment](#24-operating-environment)
    * 2.5 [Design and Implementation Constraints](#25-design-and-implementation-constraints)
    * 2.6 [User Documentation](#26-user-documentation)
        * 2.6.1 [Online User Documentation](#261-online-user-documentation)
    * 2.7 [Assumptions and Dependencies](#27-assumptions-and-dependencies)
  * [External Interface Requirements](#external-interface-requirements)
    * 3.1 [User Interfaces](#31-user-interfaces)
    * 3.2 [Hardware Interfaces](#32-hardware-interfaces)
    * 3.3 [Software Interfaces](#33-software-interfaces)
    * 3.4 [Communications Interfaces](#34-communications-interfaces)
  * [System Features](#system-features)
    * 4.1 [Settings](#41-settings)
      * 4.1.1 [Navigate to Settings](#411-navigate-to-settings)
      * 4.1.2 [Load Settings](#412-load-settings)
    * 4.2 [Plugins](#42-plugins)
      * 4.2.1 [Manage Plugins](#421-manage-plugins)
  * [Other Nonfunctional Requirements](#other-nonfunctional-requirements)
    * 5.1 [Performance Requirements](#51-performance-requirements)
    * 5.2 [Safety Requirements](#52-safety-requirements)
    * 5.3 [Security Requirements](#53-security-requirements)
    * 5.4 [Software Quality Attributes](#54-software-quality-attributes)
    * 5.5 [Business Rules](#55-business-rules)
  * [Other Requirements](#other-requirements)
* [Appendix A: Glossary](#appendix-a-glossary)
* [Appendix B: Analysis Models](#appendix-b-analysis-models)
* [Appendix C: To Be Determined List](#appendix-c-to-be-determined-list)




## Revision History
| Name | Date    | Reason For Changes  | Version   |
| ---- | ------- | ------------------- | --------- |
| [@z2e3r40o](https://github.com/z2e3r40o) | 7/7/20 | Initial preparation | alpha |
| [@z2e3r40o](https://github.com/z2e3r40o) | 7/8/20 | Online documentation | alpha |
| [@z2e3r40o](https://github.com/z2e3r40o) | 7/8/20 | Settings introduction | alpha |
|      |         |                     |           |
|      |         |                     |           |

## Introduction
### 1.1 Purpose 
> Identify the product whose software requirements are specified in this document, including the revision or release number. Describe the scope of the product that is covered by this SRS, particularly if this SRS describes only part of the system or a single subsystem.

### 1.2 Document Conventions
> Describe any standards or typographical conventions that were followed when writing this SRS, such as fonts or highlighting that have special significance. For example, state whether priorities  for higher-level requirements are assumed to be inherited by detailed requirements, or whether every requirement statement is to have its own priority.
### 1.3 Intended Audience and Reading Suggestions
> Describe the different types of reader that the document is intended for, such as developers, project managers, marketing staff, users, testers, and documentation writers. Describe what the rest of this SRS contains and how it is organized. Suggest a sequence for reading the document, beginning with the overview sections and proceeding through the sections that are most pertinent to each reader type.
### 1.4 Product Scope
> Provide a short description of the software being specified and its purpose, including relevant benefits, objectives, and goals. Relate the software to corporate goals or business strategies. If a separate vision and scope document is available, refer to it rather than duplicating its contents here.
### 1.5 References
> List any other documents or Web addresses to which this SRS refers. These may include user interface style guides, contracts, standards, system requirements specifications, use case documents, or a vision and scope document. Provide enough information so that the reader could access a copy of each reference, including title, author, version number, date, and source or location.

## Overall Description
### 2.1 Product Perspective
> Describe the context and origin of the product being specified in this SRS. For example, state whether this product is a follow-on member of a product family, a replacement for certain existing systems, or a new, self-contained product. If the SRS defines a component of a larger system, relate the requirements of the larger system to the functionality of this software and identify interfaces between the two. A simple diagram that shows the major components of the overall system, subsystem interconnections, and external interfaces can be helpful.
### 2.2 Product Functions
> Summarize the major functions the product must perform or must let the user perform. Details will be provided in Section 3, so only a high level summary (such as a bullet list) is needed here. Organize the functions to make them understandable to any reader of the SRS. A picture of the major groups of related requirements and how they relate, such as a top level data flow diagram or object class diagram, is often effective.
### 2.3 User Classes and Characteristics
> Identify the various user classes that you anticipate will use this product. User classes may be differentiated based on frequency of use, subset of product functions used, technical expertise, security or privilege levels, educational level, or experience. Describe the pertinent characteristics of each user class. Certain requirements may pertain only to certain user classes. Distinguish the most important user classes for this product from those who are less important to satisfy.
### 2.4 Operating Environment
> Describe the environment in which the software will operate, including the hardware platform, operating system and versions, and any other software components or applications with which it must peacefully coexist.
### 2.5 Design and Implementation Constraints
> Describe any items or issues that will limit the options available to the developers. These might include: corporate or regulatory policies; hardware limitations (timing requirements, memory requirements); interfaces to other applications; specific technologies, tools, and databases to be used; parallel operations; language requirements; communications protocols; security considerations; design conventions or programming standards (for example, if the customer’s organization will be responsible for maintaining the delivered software).
### 2.6 User Documentation
> List the user documentation components (such as user manuals, on-line help, and tutorials) that will be delivered along with the software. Identify any known user documentation delivery formats or standards.
#### 2.6.1 Online User Documentation
For general documentation, API reference, tutorials visit https://docs.vim-pro.com.

> The Online User Documentation is written in and accessible at https://gitbook.com.
### 2.7 Assumptions and Dependencies
> List any assumed factors (as opposed to known facts) that could affect the requirements stated in the SRS. These could include third-party or commercial components that you plan to use, issues around the development or operating environment, or constraints. The project could be affected if these assumptions are incorrect, are not shared, or change. Also identify any dependencies the project has on external factors, such as software components that you intend to reuse from another project, unless they are already documented elsewhere (for example, in the vision and scope document or the project plan).
## External Interface Requirements
### 3.1 User Interfaces
> Describe the logical characteristics of each interface between the software product and the users. This may include sample screen images, any GUI standards or product family style guides that are to be followed, screen layout constraints, standard buttons and functions (e.g., help) that will appear on every screen, keyboard shortcuts, error message display standards, and so on. Define the software components for which a user interface is needed. Details of the user interface design should be documented in a separate user interface specification.
### 3.2 Hardware Interfaces
> Describe the logical and physical characteristics of each interface between the software product and the hardware components of the system. This may include the supported device types, the nature of the data and control interactions between the software and the hardware, and communication protocols to be used.
### 3.3 Software Interfaces
> Describe the connections between this product and other specific software components (name and version), including databases, operating systems, tools, libraries, and integrated commercial components. Identify the data items or messages coming into the system and going out and describe the purpose of each. Describe the services needed and the nature of communications. Refer to documents that describe detailed application programming interface protocols. Identify data that will be shared across software components. If the data sharing mechanism must be implemented in a specific way (for example, use of a global data area in a multitasking operating system), specify this as an implementation constraint.
### 3.4 Communications Interfaces
> Describe the requirements associated with any communications functions required by this product, including e-mail, web browser, network server communications protocols, electronic forms, and so on. Define any pertinent message formatting. Identify any communication standards that will be used, such as FTP or HTTP. Specify any communication security or encryption issues, data transfer rates, and synchronization mechanisms.
## System Features
> This template illustrates organizing the functional requirements for the product by system features, the major services provided by the product. You may prefer to organize this section by use case, mode of operation, user class, object class, functional hierarchy, or combinations of these, whatever makes the most logical sense for your product.
### 4.1 Settings

| | |
|----|----|
| Description | All configuration and vimfile management related to `vim-pro` |
| Prefix | `,` |
| Online docs | https://docs.vim-pro.com/user-docs/settings |

<details>
 <summary>Expand</summary>

The settings for `vim-pro` have been organized logically into the following sections:

| settings name | description |
|---------------|-------------|
| General       | Mouse settings |
| Plugins       | Specify plugins, plugin configurations |
| Appearance    | Colors |
| Editing       | Line numbers, tabs, etc. |
| Bindings      | All vim-pro bindings for all modes |

</details>

#### 4.1.1 Navigate to Settings
<details>
 <summary>Expand</summary>
 
| binding | function |
|---------|----------|
| `<leader>,,`  | Open main settings file (`.vimrc`) |
| `<leader>,g` | Open general settings |
| `<leader>,p` | Open plugins settings |
| `<leader>,a` | Open appearance settings |
| `<leader>,e` | Open editing settings |
| `<leader>,b` | Open bindings settings |

 </details>

#### 4.1.2 Load Settings
<details>
 <summary>Expand</summary>
 
| binding | function |
|---------|----------|
| `<leader>,r` | Source main settings file (`.vimrc`) |
| `<leader>,l` | Source current buffer |

</details>

### 4.2 Plugins

| | |
|----|----|
| Description | Plugin management |
| Prefix | `p` |
| Online docs | https://docs.vim-pro.com/user-docs/plugins |

#### 4.2.1 Manage Plugins
<details>
 <summary>Expand</summary>
 
| binding | function |
|---------|----------|
| `<leader>pi`  | Install plugins |
| `<leader>pu` | Install or update plugins |
| `<leader>pc` | Clean out unlisted plugins |
| `<leader>pu` | Upgrade plugin system |
| `<leader>ps` | Check the status of plugins |

</details>

## Other Nonfunctional Requirements
### 5.1 Performance Requirements
> If there are performance requirements for the product under various circumstances, state them here and explain their rationale, to help the developers understand the intent and make suitable design choices. Specify the timing relationships for real time systems. Make such requirements as specific as possible. You may need to state performance requirements for individual functional requirements or features.
### 5.2 Safety Requirements
> Specify those requirements that are concerned with possible loss, damage, or harm that could result from the use of the product. Define any safeguards or actions that must be taken, as well as actions that must be prevented. Refer to any external policies or regulations that state safety issues that affect the product’s design or use. Define any safety certifications that must be satisfied.
### 5.3 Security Requirements
> Specify any requirements regarding security or privacy issues surrounding use of the product or protection of the data used or created by the product. Define any user identity authentication requirements. Refer to any external policies or regulations containing security issues that affect the product. Define any security or privacy certifications that must be satisfied.
### 5.4 Software Quality Attributes
> Specify any additional quality characteristics for the product that will be important to either the customers or the developers. Some to consider are: adaptability, availability, correctness, flexibility, interoperability, maintainability, portability, reliability, reusability, robustness, testability, and usability. Write these to be specific, quantitative, and verifiable when possible. At the least, clarify the relative preferences for various attributes, such as ease of use over ease of learning.
### 5.5 Business Rules
> List any operating principles about the product, such as which individuals or roles can perform which functions under specific circumstances. These are not functional requirements in themselves, but they may imply certain functional requirements to enforce the rules.

## Other Requirements
> Define any other requirements not covered elsewhere in the SRS. This might include database requirements, internationalization requirements, legal requirements, reuse objectives for the project, and so on. Add any new sections that are pertinent to the project.
---
### Appendix A: Glossary
> Define all the terms necessary to properly interpret the SRS, including acronyms and abbreviations. You may wish to build a separate glossary that spans multiple projects or the entire organization, and just include terms specific to a single project in each SRS.
### Appendix B: Analysis Models
> Optionally, include any pertinent analysis models, such as data flow diagrams, class diagrams, state-transition diagrams, or entity-relationship diagrams.
### Appendix C: To Be Determined List
> Collect a numbered list of the TBD (to be determined) references that remain in the SRS so they can be tracked to closure.
