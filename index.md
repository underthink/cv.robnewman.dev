# Rob Newman

<div class="header-links">

[E-Mail](mailto:cv@robnewman.dev) &middot; [GitHub](https://github.com/underthink)
&middot; [LinkedIn](https://linkedin.com/in/rob-newman-b65299b5) &middot; [CV](http://cv.robnewman.io/)

</div>



I'm a lead/senior developer with 12 years experience writing and designing reliable, scalable applications.
I've written code that correctly handles tens of thousands of operations per second, provided technical 
leadership and mentorship for agile teams, and worked with other development teams, product teams, and customers
to make sure the right thing gets built. I have a passion for learning, for solving interesting problems, and 
for getting the details right.

## Skills

* Experience writing backends and frontends using **Java 5/6/8/11** _(12 years)_, **Python 2/3** _(10 years)_,
  **Javascript** _(10 years)_, **Rust** and **Go**. Familiarity with many libraries and frameworks in those 
  languages, including:
  * **Spring Boost**, **Dropwizard**, **Netty**, **OSGi** and **Wicket** in Java
  * **Flask**, **Sanic**, **SQLalchemy** and **Requests** in Python
  * **vue.js**, **React** and **jQuery** in Javascript
* Knowledge of RDBMS and SQL (**MySQL**, **PostgreSQL**, **SQLite**), graph databases 
  (**Sesame/RDF4J**, **Stardog**), indexes (**Elasticsearch**, **Lucene**), big-data 
  stores (**HBase**, **Hadoop**) and messaging/streaming systems (**Kafka**, **ActiveMQ**)
* Deployment, operation and management of services on **Kubernetes**, **AWS** (using **Terraform**),
  **OpenStack** and **bare-metal servers** (**Linux** using **Ansible**)
* Familiarity with build tools such as **Gradle**, **Maven**, **Buildah**, **setuptools** and **GitLab CI/CD**

## Commercial Experience

### EXFO/Ontology Partners: Nova Context

Nova Context is a platform that allows networks and operators to visualize their network topology, using large RDF graph databases to model free-form data.

#### 2017 - Present: Senior Developer &amp; Lead Architect

* Acted as local architectural lead, working the with wider EXFO architecture community. In this role, I:
  * Shared interesting development approaches and technologies used by my teams with the other members of the architectural group
  * Worked with representatives of other business units to develop a set of recommendations for transitioning to a cloud-native development and deployment approach
  * Developed and led portions of Kubernetes workshops, introducing concepts like tracing and distributed logging
  * Ensured local team were aware of wider EXFO architectural strategy and direction, advising and helping with implementation as necessary
* Developed frontend and backend features, and fixed regressions, with the core big-data graph platform. These included:
  * Worked with the product team and internal customers to gather requirements for and develop new features.
  * Re-wrote platform indexing capabilities to injest terabytes of raw data produced by dozens of threads more quickly and with fewer failures
  * Led evaluation of candidates for a replacement graph datastore. Developed PoC code to benchmark and prove the viability of possible stores.
  * Led efforts to deploy the platform and dependencies using OCI containers.
* Developed internal tooling and applications to help with CI and release automation.

\pagebreak

### Elsevier/Mendeley

Mendeley is a researcher-focused citation-management and social networking platform, deployed as 
a large, continually-tested set of microservices on AWS.

#### 2016 - 2017: Technical Lead for the Access &amp; Onboarding Team

* Led backend work to migrate users from a legacy internal Mendeley database to a new company-wide OpenID Connect-based authentication platform
  * Worked with product owners, front end developers and other development teams across Elsevier to design a secure migration process
  * Developed backend code to securely and correctly migrate accounts between systems 
  * Ensured critical identity and authorization changes were correctly rolled out to the ~100 other microservices that make up Mendeley's backend
  * Designed well-defined, stable REST APIs to allow integration with the new security services.
* Developed infrastructure and tooling to improve Mendeley's AWS-based continuous deployment environment and process
* Developed backend features to ease sign-up, better integrate systems, and increase security
* Acted as the technical point-of-contact for the team
  * Provided advice and guidance to other teams in Mendeley and Elsevier relating to authentication and security implementations.
  * Worked with the support team to trace issues with user accounts
* Mentored and advised junior developers on the team

### OpenMarket

OpenMarket is a mobile messaging aggregator, allowing enterprises to deliver messages to users in hundreds of countries. The messaging platform is one of the company's core services, responsible for routing and delivering tens of thousands of messages per second in a reliable, auditable way.

#### 2007 - 2016: Developer/Technical Lead for the EMEA/APAC Messaging Platform

* Designed next-generation SMS routing and delivery platform
  * The new platform designed to be horizontally-scalable, fault-tolerant across datacentres, and aware of data locality issues. Able to handle up to hundreds of thousands of transactions per second.
  * Worked with other teams in UK and Seattle to refine the design and develop replacement public-facing RESTful and binary APIs.
  * Created a deployment plan to allow the new platform to temporarily operate in sync with the old one, avoiding a risky 'big bang' deployment.
* Core platform development, including:
  * Re-wrote core connectivity code to use NIO/selector-based networking code, allowing for greatly increased scale
  * Developed resilient, high-performance integrations with third-party suppliers, using tools like Wireshark to analyse protocols
  * Developed systems to generate accurate, queryable billing data from immutable event data in near real-time
* Acted as a mentor to less senior team members
* Involved in recruiting new developers - this included CV review, interviewing candidates, and selecting the candidate to hire

## Education

* **University of Warwick (2003-2007):** Graduated with a 2:1 Masters degree in Computer Science
* **Wisbech Grammar School (1996-2003):** 3 A-Levels, 1 AS Level
