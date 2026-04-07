# Ian Cahoon

icahoon@gmail.com  
https://github.com/icahoon/  
https://www.linkedin.com/in/icahoon/

Senior software engineer with extensive experience designing, developing, and
deploying software for cloud based applications. Enjoy collaborating with
other engineers, designers, and stakeholders, as well as contributing to the
continuous improvement and optimization of the product and the software
development process. Always eager to learn new skills and tools, and to share
my knowledge and insights with others.


## Skills

#### Cloud Computing
- **GCP** | Cloud Functions, Cloud Storage, SQL, GKE, PubSub, Artifact Registry  
- **AWS** | EC2, ECR, S3, RDS, SQS, IAM  

#### Databases
- PostgreSQL, MySQL, CockroachDB, SQLite

#### Languages
- Go, Bash, Python, C++, C, Ruby, JSON, YAML, Puppet, Ansible

#### Messaging APIs
- REST, gRPC, Protobuf

#### Observability
- New Relic, DataDog, InfluxDB, Prometheus, OpenTelemetry, Zipkin, Jaeger

#### Operating Systems
- RedHat, CentOS, Fedora, Debian, Ubuntu, Mac OS X

#### Process Methodologies
- Agile, Kanban, DevOps

#### Software and Tools
- Redis, Docker, Kubernetes, ArgoCD, Cloudflare, HAProxy, Git, GitHub, GitHub Actions, CircleCI, Jira, Rally, Pivotal Tracker, Jenkins, VMware, OpenStack, KitchenCI


## Experience

### Paramount+, New York, NY (remote position)
**Senior Software Engineer**  
3 years (August 2022 - August 2025)

Worked on the Video Streaming Ingestion Pipeline team, which formed the
foundation for the global content delivery of Paramount, Showtime and CBS
content to streaming services such as Paramount+, Youtube, Apple, Amazon, and
Roku.

#### Key Highlights

- Rewrote the central video package ingestion backend, Harverster, using Go. It
  was formerly written in PHP and deployed as a monolith on a single compute
  engine instance using the LAMP stack. This was converted to a Go microservice
  running on Kubernetes. The Go microservice provided a RESTful API leveraged
  by upstream content providers. The backend interfaced with a number of
  internal systems via REST APIs, used MySQL for transaction recording, and
  delivered the content to the Comcast Video Platform (formerly known as MPX),
  the media asset management (MAM) system used by Paramount+.  This
  implementation allowed Harvester to grow with the increase in upstream media
  providers. Additionally, this implementation provided thorough unit and
  integrated test coverage in order to improve the resilience, reliability, and
  maintainability of the service.

- Designed and implemented a role based access control system (RBAC) for the
  Harvester API. This provided an authorization and auditing framework for the
  users and agents using the API.

- Designed and implemented the Caption Analysis tool. This tool was intended to
  assist upstream providers with regulatory compliance. This verfied that all
  ingested media objects containing forced narrative files and either a caption
  or subtitle file were aligned. Results were reported via a dedicated slack
  channel and via a web based UI.

- Refactored Harvester to handle an abstract MAM concept. This enabled the
  introduction of an internally developed MAM to replace MPX, potentially
  saving millions of dollars annually.

- Implemented a stand alone Media Metadata backend service. This service was
  used by Harvester to validate the properties of the ingested media.

- Implemented a cloud function to synchronize the TMS IDs of newly created
  content from the Gracenote service with our media assets management (MAM)
  system, MPX.

- Implemented a slackbot in Go to allow upstream providers to query information
  about ingested media objects.

- Rewrote the content metadata service using Go, similar to an online Gracenote
  style TV guide. It was also formerly written in PHP and deployed as a
  monolith. This was converted to a Go microservice running on Kubernetes. This
  service provides content metadata via a RESTful API.


### Strata Identity, Boulder, CO

**Senior Software Engineer**  
1 year (July 2021 - July 2022)

Wrote a REST based API to automate the management of our cloud infrastructure,
including resources in GitHub, ArgoCD, Kubernetes, AWS, Cloudflare and HAProxy.

Worked on the core identity orchestration platform, named Maverics. Helped
implement the OIDC authentication provider. Created a WebAuthn prototype using
a Yubikey to demonstrate multi factor authentication with Maverics.


### JumpCloud, Louisville, CO

**Senior Software Engineer**  
3 years (April 2018 - July 2021)

Worked as a backend engineer and contributed to many components of the
microservices architecture. The backend services were implemented primarily in
Go, with the functional tests written primarily in Python.

#### Key Highlights

- Responsible for the design and implementation of the Software Management for
  Windows feature as part of the Windows Devices feature team. This included the
  design and implementation of the external REST API, the internal gRPC service
  definitions, and the database schema.

- Responsible for the design and implementation of new features for the Policies
  team. Implemented hardening policies for Linux devices, focusing on virtual
  machine instances in cloud providers like AWS.

- Developed a docker based development environment that allowed both developers
  and QA to run a scaled down version of the product on a development machine.
  This increased overall engineering velocity by allowing QA to “shift left” by
  testing developer changes in an isolated environment earlier in the
  development process. This also provided a safety net for developers to do end
  to end testing as part of their development workflow.

- Helped redesign portions of the microservice architecture to move processing
  away from the core directory to the edge services to allow concurrent
  processing. This accomplished the goal of increasing performance by an order of
  magnitude in order to meet future scalability needs.

- Improved the performance of the core directory by incorporating tracing to find
  and quantify performance bottlenecks, and then refactoring those bottlenecks.

- Worked on an application standardization project for the Developer Enablement
  team to help improve developer productivity. The goal was to move boilerplate
  application CI code to a centralized repository, and to create tooling to
  automate the process of keeping all backend microservice projects current.


### Cisco Systems, Denver/Boulder, CO

**Technical Leader / Platform Architect**  
18 years

Worked on a large scale global cloud deployment for enterprise customers. The
team was responsible for the deployment and monitoring of over thirty shared
services such as Consul, Vault, Cassandra, the ELK stack, RabbitMQ and
CloudFoundry. These services were designed to be secure and highly available.

#### Key Highlights

- Designed and implemented the software used to manage our datacenter
  deployments. This software was responsible for creating, provisioning, and
  auditing all AWS resources. These resources included the network, compute
  instances, DNS records, managed storage, managed databases and container
  services. With this software we migrated our cloud deployments from OpenStack
  to AWS in under five months, well ahead of schedule. This tool was written in
  Go.

- Navigated the Cisco open source process to move the ongoing development of
  the deployment tool to GitHub.

- Was the primary owner of five of the platform shared services.

- Responsible for the groups's continuous delivery pipelines. Maintained the
  build servers, the git repositories in Gerrit and the Jenkins jobs. Was a
  very strong proponent of automating our deployment and monitoring processes.

Past projects include the design and implementation of the installation and
upgrade for the Cisco Unified Communications Manager. Worked on the project
through five major releases.


### Lucent Technologies, Denver, CO
**Member of the Technical Staff**  
3 years

Part of a team responsible for the H.323 software stack used by the MMCX
project. MMCX was an enterprise IP PBX that provided a team conferencing and
collaboration solution.


## Education
- University of Colorado, Denver
BS in Computer Science

- Architecting with Google Kubetnetes Engine
Sept 2023

