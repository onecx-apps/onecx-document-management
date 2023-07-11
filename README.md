# OneCX Document Management 
onecx-document-management-ui  ![onecx-document-management-ui](https://github.com/onecx-apps/onecx-document-management-ui/actions/workflows/build.yml/badge.svg)  
onecx-document-management-bff ![onecx-document-management-bff](https://github.com/onecx-apps/onecx-document-management-bff/actions/workflows/build.yml/badge.svg)  
onecx-document-management-svc ![onecx-document-management-svc](https://github.com/onecx-apps/onecx-document-management-svc/actions/workflows/build.yml/badge.svg)

## Licence
This software is licensed under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0). You may obtain a copy of the license in the corresponding LICENSE file or visit the [Apache website](https://www.apache.org/licenses/LICENSE-2.0) for more information.

## Contributing
We welcome contributions from the community. If you would like to contribute to the development of OneCX Document Management Software, please follow our [contribution guidelines (tbd)]().

## What is Document Management
Document management refers to the systematic process of capturing, organizing, storing, and retrieving documents within an organization. It involves the efficient handling of digital documents, ensuring secure access, version control, collaboration based on TM-Forum standard [TMF 667](https://github.com/tmforum-apis/TMF667_Document).

With OneCX Document Management Software, you can streamline your document management workflows, reduce manual efforts, and enhance productivity. Whether it's managing contracts, invoices, legal documents, or any other form of digital content, OneCX Document Management provides a centralized and user-friendly solution for effectively managing your documents.

## Key Features
* Document Storage and Retrieval: Store and retrieve documents securely and efficiently.
* Metadata Management: Add and manage metadata to enhance document categorization and search capabilities.
* Access Control: Define access permissions and roles to control document visibility and editing rights.
* Search and Filters: Quickly locate documents using advanced search and filtering options.
* Version Control: Keep track of document versions and manage changes effectively.
* Collaboration: Enable collaboration by allowing multiple users to access and work on documents simultaneously.
* Integration Capabilities: Seamlessly integrate with other systems and tools for enhanced productivity.

## Flexibility and Integration
OneCX Document Management Software is designed with a modular and extensible architecture, allowing you to customize and integrate it with other components of the OneCX ecosystem. Think of it like building with Lego blocks – you can easily plug in additional modules and extend the functionality according to your specific needs.

Whether you want to integrate OneCX Document Management Software with existing enterprise systems, third-party tools, or other components of the OneCX suite, the software provides flexible APIs and integration points to enable seamless connectivity. This flexibility empowers you to create a tailored document management solution that perfectly fits your organization's requirements.

With OneCX's modular approach, you can leverage the power of the software while integrating it with various systems and workflows, enhancing productivity and optimizing your document management processes.

## Issue tracking
All OneCX Document Management issues are tracked and maintained here [issue tracking tool][].

## Overview
OneCX Document Management Software is a comprehensive solution for managing documents in a user-friendly and efficient manner. It is a solution that consists of three main components: a backend service, a user interface, and a backend-for-frontend (BFF) layer.

The three components of OneCX Document Management Software are as follows:
1. __Document Management UI__  
The user interface component is based on Angular, a popular JavaScript framework for building dynamic web applications. It offers a user-friendly and intuitive interface for interacting with the document management system. Users can perform actions such as uploading documents, searching, linking them with others or attaching files to it, etc..
3. __Document Management BFF__  
The BFF layer acts as an intermediary between the frontend user interface and the backend service. It handles tasks such as data aggregation, transformation, and composition to provide an optimized API for the UI. The BFF layer is designed to enhance performance and simplify the integration of the frontend with the backend service.
5. __Document Management Backend__  
This component provides the core functionality for document management. It handles tasks such as document storage, retrieval, metadata management, and access control. The backend is built cloud native using Quarkus. 

__Interfaces are based on the TM-Forum standard [TMF 667](https://github.com/tmforum-apis/TMF667_Document).__

## Getting Started
To get started with OneCX Document Management Software, please refer to the following installation and setup instructions specific to each component:
* [OneCX Document Management SVC (Backend) - Getting Started](https://github.com/onecx-apps/onecx-document-management-svc)
* [OneCX Document Management UI (User Interface) - Getting Started](https://github.com/onecx-apps/onecx-document-management-ui)
* [OneCX Document Management BFF (Backend for Frontend) - Getting Started](https://github.com/onecx-apps/onecx-document-management-bff)

For detailed usage instructions and API documentation, please refer to the respective documentation files for each component.

## Roadmap
tbd

[issue tracking tool]: https://xyz.com
