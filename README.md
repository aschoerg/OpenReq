# OpenReq
This repository contains information regarding the H2020 Project OpenReq and its components.
The  project is funded by the European Union Horizon 2020 Research and Innovation programme under grant agreement No 732463.

Our aim is to provide better requirements engineering to organisations. These are some of the problems that the OpenReq project is targeting:

- How to handle a large number of requirements from customers asking for features to a product?
- How to notice and manage duplicate bug reports?
- Could we develop better tools to deal with bugs and requirements?
- How to notice relationships between requirements?
- How is it possible to produce a single recommendation to a group of people with conflicting views?

We are looking for improvements in the areas of requirements identification, classification and decision-making support. These improvements can be achieved through improved processes, methods and tools.

The goal of OpenReq is to build an intelligent recommendation and decision system for community-driven requirements engineering. The system shall recommend, prioritise, and visualise requirements.

The OpenReq project gathers together both academic and industrial partners looking for the best ways to ease organisations requirements engineering. The project evaluates its innovations in a series of trials provided by the project industrial partners in the field of telecom, transportation, and cross-platform open source software.


# Teams

- [HITeC e.V.](https://hitec-hamburg.de) is the technology transfer centre of the Department of Informatics at the University of Hamburg. Since 1997, HITEC provides professional services to the department and to public and commercial organizations. In particular, it conducts R&D cooperation with companies, presents, customizes, and disseminates the research results of the university.

- [Graz Technical University](http://ase.ist.tugraz.at/ASE/) is represented by the Applied Software Engineering group at the Institute for Software Technology (IST). Our areas of expertise are recommender systems, model-based diagnosis and repair, configuration of complex products and services, and group decision making.

- [ENG Ingegneria Informatica](https://www.eng.it/) is the largest Software and Information Technology services group in Italy. The Group mission is to design, develop and deliver innovative information systems and solutions for medium to large scale clients, involves over 1.000 clients in Europe and worldwide, with increasing overseas market activities.

- [Universidad Politecnica de Catalunya](https://gessi.upc.edu/en) is represented by the GESSI research group (Department of Service and Information System Engineering) which is one of the newest UPC departments. Its members conduct research in many fields of software, service and data engineering. In relation with the project, we mention requirements engineering, risk management, and software quality.

- [vogella GmbH](http://vogella.com/) is a German company based in Hamburg which provides services ranging from technology development, production and developer support, training and mentoring in the area of Eclipse and Android.
Within our open source activities, our employees are actively involved in the Eclipse IDE Project.

- [Siemens AG Österreich](https://www.siemens.com/at/de/home.html) is a global powerhouse focusing on the areas of electrification, automation, and digitalization. One of the world’s largest producers of energy-efficient, resource-saving technologies, Siemens is a leading supplier of systems for power generation and transmission as well as medical diagnosis.

- [University of Helsinki](https://www.helsinki.fi/en/researchgroups/empirical-software-engineering) is represented by the Empirical Software Engineering Helsinki (ESEH, prof. Männistö) research group. The group addresses software engineering research problems and challenges with industrial relevance, including product requirements and software architecture, software intensive services and (software) product variability in particular from the perspectives of requirements engineering.

- [The Qt Company](http://qt.io/) is responsible for all Qt activities including product development, commercial and open source licensing together with the Qt project under the open governance model. Together with our licensing, support and services capabilities, we operate with the mission to work closely with developers to ensure that their Qt projects are deployed on time, within budget and with a competitive advantage.

- [WindTre Italia S.p.a.](http://www.windtre.it/) is part of the CK group Hutchison Holdings Limited (CK Hutchison). WindTre is leader in the development of new generation mobile technologies, having relationships with GSMA and main standardization bodies like 3GPP and IETF.

# Components

| ID                                                                                                                                    | Name                                                    | Description                                                                            | Lead team |                  Project deliverable                   |
| ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- | -------------------------------------------------------------------------------------- | :-------: | :----------------------------------------------------: |
| [analytics-backend](https://github.com/OpenReqEU/analytics-backend)                                                                   | Analytics Backend                                       | Description needed                                                                     |    ENG    | [D2.2 - Requirements Intelligence Engine Version 1]()  |
| [prs-improving-requirements-quality-features](https://github.com/OpenReqEU/prs-improving-requirements-quality-features)               | Improving Requirements Quality Features                 | For every Requirement candidate, this Microservice enhance the requirement text, display a set of quality metrics and requirement structure.                                                                     |    ENG    |        [D3.2 - Recommender Engine Version 1]()         |
| [update-manager](https://github.com/OpenReqEU/update-manager)                                                                         | Update Manager                                          | Description needed                                                                     |    ENG    |  [D2.2 Requirements Intelligence Engine Version 1]()   |
| [prs-improving-requirements-quality](https://github.com/OpenReqEU/prs-improving-requirements-quality)                                 | Requirements Quality Improvement                        | Description needed                                                                     |   HITeC   |        [D3.2 - Recommender Engine Version 1]()         |
| [gds-edemocracy](https://github.com/OpenReqEU/gds-edemocracy)                                                                         | Liquid Democracy for requirements engineering tasks     | WIP                                                                                    |   HITeC   |        [D3.2 - Recommender Engine Version 1]()         |
| [ri-analytics-classification-google-play-review](https://github.com/OpenReqEU/ri-analytics-classification-google-play-review)         | Classification of Google Play reviews                   | WP2 - a microservice that classifies a list of app reviews as a bug report, feature request, or other                                                                     |   HITeC   | [D2.2 - Requirements Intelligence Engine Version 1]()  |
| [ri-analytics-classification-twitter](https://github.com/OpenReqEU/ri-analytics-classification-twitter)                               | Tweets Classification                                   | WP2 - a microservice to classify tweets into problem report, inquiry, or irrelevant.                                                                     |   HITeC   | [D2.2 - Requirements Intelligence Engine Version 1]()  |
| [ri-analytics-rationale-miner](https://github.com/OpenReqEU/ri-analytics-rationale-miner)                                             | Rationale Miner                                         | WP2 - Pro/contra stances and rationale analytics                                                                     |   HITeC   |        [D3.2 - Recommender Engine Version 1]()         |
| [ri-collection-explicit-feedback-google-play-page](https://github.com/OpenReqEU/ri-collection-explicit-feedback-google-play-page)     | Google Play page miner                                  | WP2 - This microservice returns a json, containing the information available on an app page from the Google Play store for a given package name.                                                                     |   HITeC   | [D2.2 - Requirements Intelligence Engine Version 1]()  |
| [ri-collection-explicit-feedback-google-play-review](https://github.com/OpenReqEU/ri-collection-explicit-feedback-google-play-review) | Google Play review miner                                | WP2 - This microservice returns a json, containing a list of app reviews from the Google Play store for a given package name.                                                                     |   HITeC   | [D2.2 - Requirements Intelligence Engine Version 1]()  |
| [ri-collection-explicit-feedback-twitter](https://github.com/OpenReqEU/ri-collection-explicit-feedback-twitter)                       | Tweets miner                                            | WP2 - This microservice returns a json, containing a list of tweets that addresses a given account.                                                                     |   HITeC   | [D2.2 - Requirements Intelligence Engine Version 1]()  |
| [ri-logging](https://github.com/OpenReqEU/ri-logging)                                                                                 | UI interactions collector                               | WP2 - This microservice provides an endpoint for logging of frontend user interactions and retrieving frontend and backend (logged separately) logs.                                                                    |   HITeC   |        [D3.2 - Recommender Engine Version 1]()         |
| [ri-orchestration-app](https://github.com/OpenReqEU/ri-orchestration-app)                                                             | Google Play orchestrator                                | WP2 - this microservice coordinates all microservice related to app store data. It initiates the crawling process, the observation (configure apps to be crawled on a regular basis), calls the microservice to process and classify the apps, and sends these to the storage layer.                                                                     |   HITeC   | [D2.2 - Requirements Intelligence Engine Version 1]()  |
| [ri-orchestration-twitter](https://github.com/OpenReqEU/ri-orchestration-twitter)                                                     | Twitter orchestrator                                    | WP2 - this microservice coordinates all microservice related to data from Twitter. It initiates the crawling process, the observation, calls the microservice to process and classify the apps, and sends these to the storage layer.                                                                     |   HITeC   |        [D3.2 - Recommender Engine Version 1]()         |
| [ri-storage-app](https://github.com/OpenReqEU/ri-storage-app)                                                                         | Google Play storage                                     | WP2 - Data storage service for app pages and reviews.                                                                     |   HITeC   | [D2.2 - Requirements Intelligence Engine Version 1]()  |
| [ri-storage-twitter](https://github.com/OpenReqEU/ri-storage-twitter)                                                                 | Twitter storage                                         | WP2 - This micro service provides APIs to store and retrieve information related to twitter. |   HITeC   | [D2.2 - Requirements Intelligence Engine Version 1]()  |
| [ri-visualization](https://github.com/OpenReqEU/ri-visualization)                                                                     | Feedback visualization                                  |WP2 - this repository covers the frontend code for the WP2 visualization                                                                     |   HITeC   | [D2.3 -  Requirements Intelligence Engine Version 2]() |
| [qthulhu](https://github.com/OpenReqEU/qthulhu)                                                                                       | Requirements dependencies visualization                 | Visualizes the link network of issues in Qt's Jira                                                                   |    Qt     |  [D5.2 - Requirements Dependency Engine Version 1]()   |
| [qthulhu-jira-plugin](https://github.com/OpenReqEU/qthulhu-jira-plugin)                                                               | A Jira Plugin for requirements dependency visualization | Displays a link that redirect the user to the OpenReq Issue Link Map (the web application)                                                                    |    Qt     |  [D5.2 - Requirements Dependency Engine Version 1]()   |
| [consistency-check](https://github.com/OpenReqEU/consistency-check)                                                                   | Requirements consistency checker                        | Description needed                                                                     |  TUGraz   |  [D5.2 - Requirements Dependency Engine Version 1]()   |
| [dependency-detection](https://github.com/OpenReqEU/dependency-detection)                                                             | Requirements detection                                  | Description needed                                                                     |  TUGraz   |  [D5.2 - Requirements Dependency Engine Version 1]()   |
| [issue-prioritizer](https://github.com/OpenReqEU/issue-prioritizer)                                                                   | Issue prioritizer                                       | Description needed                                                                     |  TUGraz   |                          []()                          |
| [openreq-live](https://github.com/OpenReqEU/openreq-live)                                                                             | OpenReq Live web application                            | Description needed                                                                     |  TUGraz   |  [D5.2 - Requirements Dependency Engine Version 1]()   |
| [similar-related-requirements-recommender](https://github.com/OpenReqEU/similar-related-requirements-recommender)                     | Related requirements recommender                        | Description needed                                                                     |  TUGraz   |  [D5.2 - Requirements Dependency Engine Version 1]()   |
| [twitter-extraction](https://github.com/OpenReqEU/twitter-extraction)                                                                 | Twitter Extraction                                      | Description needed                                                                     |  TUGraz   |                          []()                          |
| [keljucaas](https://github.com/OpenReqEU/keljucaas)                                                                                   | KeljuCaaS 				                        | Inference engine service                                                                     |    UH     |  [D5.2 - Requirements Dependency Engine Version 1]()   |
| [mallikas](https://github.com/OpenReqEU/mallikas)                                                                                     | Mallikas                                       | A database caching service for Milla                                                                     |    UH     |  [D5.2 - Requirements Dependency Engine Version 1]()   |
| [milla](https://github.com/OpenReqEU/milla)                                                                                           | Milla                                      | An orchestrator service between Qt Jira and OpenReq infrastructure                                                                     |    UH     |  [D5.2 - Requirements Dependency Engine Version 1]()   |
| [mulperi](https://github.com/OpenReqEU/mulperi)                                                                                       | Mulperi                                      | A broker service between OpenReq infrastructure and KeljuCaaS                                                                     |    UH     |  [D5.2 - Requirements Dependency Engine Version 1]()   |
| [conformance-to-templates](https://github.com/OpenReqEU/conformance-to-templates)                                                     | Conformance to requirements template checker            | Description needed                                                                     |    UPC    |        [D3.2 - Recommender Engine Version 1]()         |
| [cross-reference-detection](https://github.com/OpenReqEU/cross-reference-detection)                                                   | Cross reference detection                               | Description needed                                                                     |    UPC    |                          []()                          |
| [dependency-detection](https://github.com/OpenReqEU/dependency-detection)                                                             | Requirements dependency detection                       | Description needed                                                                     |    UPC    |                          []()                          |
| [requirement-patterns](https://github.com/OpenReqEU/requirement-patterns)                                                             | Requirements Patterns storage                           | This services is used to store a catalogue of requirement patterns                     |    UPC    |  [D5.3 - OpenReq Ontologies and Patterns Catalogue]()  |
| [requirements-classifier](https://github.com/OpenReqEU/requirements-classifier)                                                       | Requirements classifier                                 | Description needed                                                                     |    UPC    |                          []()                          |
| [similarity-detection](https://github.com/OpenReqEU/similarity-detection)                                                             | Requirements similarity detection                       | Description needed                                                                     |    UPC    |                          []()                          |
| [eclipse-plugin](https://github.com/OpenReqEU/eclipse-plugin)                                                                         | OpenReq Eclipse plugin                                  | Description needed                                                                     |  vogella  |                          []()                          |
| [eclipse-plugin-server](https://github.com/OpenReqEU/eclipse-plugin-server)                                                           | OpenReq Eclipse plugin server                           | Description needed                                                                     |  vogella  |                          []()                          |

# Contributing
See the OpenReq Contribution Guidelines [here](https://github.com/OpenReqEU/OpenReq/blob/master/CONTRIBUTING.md).

# Contacts
 For problems regarding the services, please open an issue in the service repository.
 You can contact us at [info@openreq.eu](mailto:info@openreq.eu)
