# Architecture Principles

This document describes the principles that underpin our architecture activities.

TOGAF defines architecture principles as follows:

> Principles are general rules and guidelines, intended to be enduring and seldom amended, that inform and support the way in which an organization sets about fulfilling its mission.
In their turn, principles may be just one element in a structured set of ideas that collectively define and guide the organization, from values through to actions and results.

There are two existing sets of principles that are available, authored by the Scottish public sector that should be duly considered as a part of establishing our architecture principles:

- The principles documented in the [High Level Operating Framework](http://www.gov.scot/Topics/Economy/digital/digitalservices/HLOF) (HLOF);
- The principles elaborated from the [Digital First Service Standard](https://github.com/scottishgovernment/arch-standards/tree/master/organisational-standards/digital-first/principles/done) (D1SS).


## High Level Operating Framework

| ID | Name | Statement
| -  | -    | -
| OFP-CC1 | Digital Standards | The design of applications and services (information and transactions) will be user focused and with a presumption of alignment with the technical standards and design principles of mygov.scot
| OFP-CC2 | Multi-Channel | The design of new applications and services shall not restrict service consumers from accessing the new functionality from currently known or defined access devices.
| OFP-CC3 | Verification and easy sign-in for citizen access | Public Sector organisations will use the national myaccount service to verify the identity of citizen access to digital public services as a default. Where this is not currently possible, organisations will ensure that any procured or developed authentication system complies with standards-based federation.
| OFP-PO1 | Data Management – Open Data | The Scottish public sector produces huge amounts of data. However, there is relatively little open publishing of that data. By making non-personal information more accessible and encouraging its publication and reuse, opportunities exist to maximise its economic and social value.
| OFP-PO2 | Data Management – Data Sharing | The Scottish public sector produces huge amounts of data. However, there is relatively little sharing of that data. Opportunities exist to benefit from and/or improve services via better use of the data, whilst complying with privacy requirements.
| OFP-SW1 | ICT work force Capability | To increase the capability of ICT professionals at all levels in the public sector to support digital public service delivery.
| OFP-SW1.2 | ICT Work force Capability – Enterprise Architecture Skills | To increase the capability of the public sector in the discipline of Enterprise Architecture to support principle OFP-CV4
| OFP-CV1 | Reuse, Before Buy, Before Build | The design of ICT solutions/services must seek to maximise reuse of existing services across the Scottish Public Sector. If existing services do not meet the business requirements and cannot be extended cost-effectively, then a supplier will be sought to provide that product or service and make it available for re-use across the sector. If there are no existing services to reuse or suitable COTS packages that can be obtained cost-effectively, then bespoke solutions that strictly conform to the architecture principles will be considered.
| OFP-CV2 | Collaboration | Collaboration is now the default choice in the design and delivery of services and in the procurement and deployment of ICT services to support this.
| OFP-CV4 | Use of Open Standards in Software | Wherever possible organisations should seek to procure new or upgraded ICT services based on Open Standards.
| OFP-CV5 | Use of Open Source software | Wherever possible, and subject to compliance with the principles of fair and open procurement, organisations should seek to procure new or upgraded ICT services based on Open Source software.
| OFP-CV6 | Single Approach to Identity & Access management for public sector employees | Access to ICT systems for public sector employees should follow the same principles as access for citizens to digital public services and should take into account modern Internet technology authentication approaches as well as nationally developed services/capabilities which may be available in the near future via SWAN.
| OFP-CV7 | Enterprise Architecture Approach to ICT Planning | An Enterprise Architecture approach to ICT planning will be adopted by all Scottish Public Sector organisations.
| OFP-CV8 | Service Oriented Approach (SOA) to Design of ICT Solutions | Wherever possible, design of any new or upgraded ICT solutions should use the principles of Service Orientation.


## Digital First Service Standard

| ID | Name | Statement
| -  | -    | -
|  1 | User Centered | Understand user needs. Research to develop a deep knowledge of who the service users are and what that means for the design of the service.
|  2 | Continuous Feedback | Put a plan in place for ongoing user research and usability testing to continuously seek feedback and input from users to improve the service.
|  3 | Cross-functional Team | Put in place a sustainable multidisciplinary team that can design, build and operate the service, led by a suitably skilled senior manager with decision-making responsibility.
|  4 | Continuous Improvement | Build the service incrementally, releasing early and often, using the iterative and user-centred methods set out in the GDS service manual.
|  5 | Sustainability | Build a service that can be iterated and improved on a frequent basis and make sure that you have the capability, resources and technical flexibility to do so.
|  6 | Technology Appraisal | Evaluate what technology, tools and systems will be used to build, host, operate and measure the service, and how to procure them.
|  7 | Information Governance | Evaluate what user data and information the digital service will be providing or storing, and address the security level, legal responsibilities, privacy issues and risks associated with the service (consulting with experts where appropriate).
|  8 | Open Source | Make all new source code open and reusable, and publish it under appropriate licences (or provide a convincing explanation as to why this cannot be done for specific subsets of the source code).
|  9 | Open Standards | Use open standards and common government platforms where available.
| 10 |  Operational Acceptance | Regularly test the end-to-end service in an environment identical to that of the live version, including on all common browsers and devices, and using dummy accounts and a representative sample of users.
| 11 | Business Continuity | Define, document and regularly test a plan to handle disasters and other incidents that may cause the digital service to be taken temporarily offline.
| 12 | Usable and Accessible | Create a service that is usable, accessible and intuitive enough that users succeed first time.
| 13 | Consistent User Experience | Build a service consistent with the user experience of the rest of mygov.scot including using the design patterns and style guide.
| 14 | Channel Shift | Identify and, wherever possible, remove impediments that prevent citizens from using the digital service, clearly establishing it as the primary channel. Plan to provide appropriate assisted digital support if necessary.
| 15 | Data Driven | Use tools for analysis that collect performance data. Use this data to analyse the success of the service and to translate this into features and tasks for the next phase of development.
| 16 | Performance Management | Identify performance indicators for the service, including the 4 mandatory key performance indicators (KPIs) defined in the GDS service manual. Establish a benchmark for each metric and make a plan to enable improvements.
| 17 | Transparent | Publish performance data on the Digital First Performance Platform.
| 18 | Open Data | Make all non-personal, non-commercially sensitive data from the service available for re-use by others under an appropriate licence.
| 19 | Green ICT | Deliver a digital service whose impact on the environment, over its whole lifecycle, is understood. Plan to reduce the environmental impact of the service over time.
| 20 | Data Hosting and Data Centres | Adopt cloud computing or virtualisation as the preferred approaches to the delivery of data hosting for the service.
| 21 | Sponsor Acceptance | Test the service from beginning to end with the minister responsible for it.


## Consideration

There is some overlap between the HLOF principles and the D1SS principles. This may seem confusing at first, however, it can be explained because the two sets of principles are designed to cover different scopes:

- The principles of the HLOF are designed to inform and support the *architectural activities of a whole organisation*;
- The principles of the D1SS are designed to inform and support *a project or programme delivering a specific digital public service*.

For simplicity we will record the principles that relate to each other below, providing any necessary comments.

| HLOF | D1SS | Comments
| -    | -    | -
| OFP-CC1 | n/a | The D1SS is the primary standard for citizen-facing public services delivered via [mygov.scot](https://www.mygov.scot).
| OFP-CC2 |  14 | If we are to be successful in delivering a substantive shift in usage of of public services from traditional channels to digital channels then the services we build must be available on the widest possible range of devices, operating systems and browsers.
| OFP-PO1 |  18 | Direct match. |
| OFP-SW1 |   5 | Direct match. |
| OFP-CV1 |   6 | A robust but efficient method of identify, analysing and appraising different technology options is crucial to making informed decisions when sourcing either a whole or parts of a solution.
| OFP-CV2 | 2,3 | Collaboration is not just about working effectively within a division or directorate but also about disregarding organisational boundaries to construct high-performing, cross-functional teams of subject matter experts as well as engaging with the citizens who consume our services and acting on the feedback they provide.
| OFP-CV4 |   9 | Direct match. |
| OFP-CV5 |   8 | Direct match. |


## Our Approach

**By default we will follow the architecture principles documented in the HLOF and the D1SS for our architecure practice.**

Where necessary we will deviate from the above principles but the decision to do so will be recorded on the project's architecture decision log, along with a clear explanation of why this decision was necessary.


## References

- [TOGAF on Architecure Principles](http://pubs.opengroup.org/architecture/togaf9-doc/arch/chap23.html).
