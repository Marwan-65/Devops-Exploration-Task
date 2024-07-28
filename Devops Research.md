DevOps is a set of practices, tools, and a cultural philosophy that automate and integrate the processes between software development and IT teams. It emphasizes team empowerment, cross-team communication and collaboration, and technology automation.

# Principles

The core basic principles of DevOps are as follows,

1. **Automation** - The first core DevOps principle is automation. The automation in every phase of the DevOps cycle is a must and the first step in achieving the DevOps culture. Failure to do so may result in poor codes, an increase in delivery time in the long run, and application downtime in the production. Think of automation in the CI/CD pipeline and every phase of the DevOps life cycle management. Not only this is automated, even the management of servers or infrastructure need to be automated in the way they are configured and managed. 

2. **Tools** - Since the DevOps culture is about automation and integrating all the phases the selection of tools that suits your requirement in the organization is a must. The tools must be selected based on team acceptance, project strategy, project goals, and cost and how do you manage the DevOps tools. Whether do you need a dedicated team to customize the custom tools or are you willing to engage with the out-of-box tools is your game. But the main thing is tools need to automate the process, with less cost and less overhead and the entire team must benefit from the tools that you choose.

3. **Culture** - DevOps fosters transparent communication, enhance collaboration, enhance trust, show accountability and responsibilities in their work which is the key to good DevOps culture implementation. The DevOps culture must truly integrate all the phases of the DevOps life cycle. Team acceptance of the DevOps is the key to successful DevOps culture implementation at the grass-root level.

some other DevOps principles include the following,

- **Frequent releases** - One of the main and DevOps principles is that the code must be committed in the version control repository very frequently and the same code must be tested and released to production frequently. This is part of DevOps culture to unify all the phases in the DevOps life cycle. This will produce fewer errors and bugs in the end. The bugs and errors are corrected with every code release at the early stage and a refined codebase is the ultimate aim of this first principle.

- **Customer-oriented action** - The next principle of DevOps is to fulfill the goals and requirements of the projects by keeping the customer in mind and meet the expectations of the customer. This is done by adapting to the changes and scope of the software. Customers must be the prime focus while developing the DevOps cultural strategy. This enhances the team capability and directs the team to achieve and surpass customer goals and requirements.

- **Creating the software with the end in mind** - This is the third principle of DevOps in which all the team members are aware of the progress made and what is operations team, development team, and testing team is doing so that code is ready with faster releases. There is no separation in the minds of the team members and they know what each other is doing in terms of technical and functional requirements and are working together to build the software. One of the key mindset in this principle is the shared goals among the team members.

- **End to End Responsibilities** - The key thing is that every member of the DevOps culture knows what they are doing and what their contribution is and how they can manage the responsibilities from the start to end. Each member of DevOps is entrusted with the end to end responsibilities to accomplish the software with the shared goals. Each member is involved from the scratch till the end of the life of the product.

- **Cross-functional autonomous teams** - The teams adopting DevOps culture must be a truly independent team of DevOps professionals with a mixed and balanced set of skills so that each team member is matured to manage a lot of skills apart from the prime skills required for their action. There are no traditional titles of coding or tester, but only DevOps professional titles.

- **Continuous Improvement** - It also means that adapting to changes, changes in the technology, changes in the scope, and changes in the customer expectations and improves with a small step each cycle. DevOps culture has a strong focus on continuous improvement to minimize waste, take less time and easy delivery, and optimization of the cycle thus improve every activity. So the desire to experiment must be inculcated in principle in the DevOps culture.

- **Make decisions based on data** -
Making decisions based on data is another DevOps principle. This means using facts and information to influence your choices. When you need to pick the proper technology or DevOps tool to optimize your work process, gather data around each option. Look at how well the tool performed in the past. Does it align with your team’s metrics and goals? If so, it is probably the right choice for your team’s needs, and you can proceed.
For example, a common performance metric for many teams is how long it takes to fix an issue. The longer the issue lingers, the more trouble it can cause. By knowing the average time it takes to fix an issue, you can make data-based decisions when implementing new procedures or tools to your pipeline. Compare the results of the procedure/tool versus your benchmark average, and you can figure out if it will be harmful or beneficial




# CI?CD Pipelines

CI/CD, which stands for continuous integration and continuous delivery/deployment, aims to streamline and accelerate the software development lifecycle.

Continuous integration (CI) refers to the practice of automatically and frequently integrating code changes into a shared source code repository. Continuous delivery and/or deployment (CD) is a 2 part process that refers to the integration, testing, and delivery of code changes. Continuous delivery stops short of automatic production deployment, while continuous deployment automatically releases the updates into the production 

**How does Continuous Integration Work?**

With continuous integration, developers frequently commit to a shared repository using a version control system such as Git. Prior to each commit, developers may choose to run local unit tests on their code as an extra verification layer before integrating. A continuous integration service automatically builds and runs unit tests on the new code changes to immediately surface any errors.environment.

Continuous delivery lets developers automate testing beyond just unit tests so they can verify application updates across multiple dimensions before deploying to customers. These tests may include UI testing, load testing, integration testing, API reliability testing, etc. This helps developers more thoroughly validate updates discover issues. With the cloud, it is easy and cost-effective to automate the creation and replication of multiple environments for testing, which was previously difficult to do on-premises.


**Continuous Delivery vs. Continuous Deployment:**

Continuous Delivery and Continuous Deployment are very similar in nature and sometimes even used interchangeably but there are some slight differences between them such as, with continuous delivery, every code change is built, tested, and then pushed to a non-production testing or staging environment. There can be multiple, parallel test stages before a production deployment. The difference between continuous delivery and continuous deployment is the presence of a manual approval to update to production. With continuous deployment, production happens automatically without explicit approval.



# Test Automation
Test automation is the practice of automatically reviewing and validating a software product, such as a web application, to make sure it meets predefined quality standards for code style, functionality, and user experience.

Testing practices typically involve the following stages:

- Unit testing: validates individual units of code, such as a function, so it works as expected
- Integration testing: ensures several pieces of code can work together without unintended consequences
- End-to-end testing: validates that the application meets the user’s expectations
- Exploratory testing: takes an unstructured approach to reviewing numerous areas of an application from the user perspective, to uncover functional or visual issues


# Automations tools
DevOps automation tools are software that facilitate the automation of various stages in the software development and deployment cycle. They integrate and streamline processes between software development (Dev) and IT operations (Ops), encompassing tasks like code integration, testing, deployment, and infrastructure management. These tools are central to implementing the DevOps methodology, focusing on continuous delivery and efficient workflow management.

1. **Version Control tools:**
  - GitHub: GitHub is considered as one of the largest and most advanced development platforms in the world. Millions of developers and companies build, ship, and maintain their software on GitHub. Some of its salient features are:

    - Collaborative Coding
    - Automation / CI & CD
    - Security including additional features for enterprise customers
    Project Management


- Bitbucket: Bitbucket is a very popular platform, with over 10 million registered users. Although it is a platform for hosting code, it goes beyond just code management. Teams can plan projects, collaborate on code, test, and deploy from a single platform. Some of its features are:

    - Tighter Jira and Trello integration.
    - Integrated CI/CD to build, test and deploy.
    - Pull requests and approve code review more efficiently.
    - Keep your code secured in the Cloud with IP whitelisting and 2-step verification.
    

- GitLab: It is an all-in-one DevOps Tool for rapid software delivery. It enables teams to perform all tasks right from Planning to SCM to Delivery to Monitoring and Security. Following are a few of its features:

    - Single interface, single conversation thread, and single data store to manage projects effectively – Single source of truth.
    - CI/CD for robust, scalable, and end-to-end automation to work together efficiently – Continuous Everything.
    - Built-in functionality for Automated Security, Code Quality and Vulnerability management & with tight governance, your DevOps speed never slows down.


2. **Container Management tools:**

- Docker: Docker is a light-weight tool that aims to simplify and accelerate various workflows with an integrated approach. A docker container image is a standalone, executable package that includes everything you need to run an application. Some of its primary features are:

    - Standardized Packaging format for diverse applications.
    - Container runtime that runs on various Linux and Windows Server OSs.
    - Developers uses Docker for build, test and collaborate.
    - Docker Hub to explore millions of images from community and verified publishers.
    - Package, Execute and Manage distributed applications with Docker App.

- Kubernetes: Kubernetes is an open-source DevOps tool used to automate deployment and management of containerized applications & perhaps one of the most popular container orchestration tools. Features that differentiate it from other DevOps Tools include:

    - Make changes to your application or its configuration and monitoring application health simultaneously – Automated rollouts & rollbacks.
    - It offers own IP addresses and a single DNS name for a set of Pods
    - Automatically mount the storage system of your choice.
    - Self-healing capability.

- Mesos: Apache Mesos is a DevOps tool to manage computer clusters. It is a distributed systems kernel for resource management and scheduling across entire data center and cloud environments. Its features include:

    - Offers native support to launch containers with Docker and AppC images.
    - Supports cloud-native and legacy applications to run in the same cluster with pluggable scheduling policies.
    - Runs on cross platforms like Linux, OSX and Windows.
    - Scale to 10,000s of nodes easily.


3. **Application Performance Monitoring tools:**

- Prometheus: Prometheus is an open-source and community driven performance monitoring solution. It also supports container monitoring and creates alerts based on time series data. Solution includes the following features:

    - Scaling with the help of functional sharding and federation.
    - Numerous client libraries allow easy service instrumentation.
    - Powerful reporting capabilities through PromQL.

- Dynatrace: Covers all monitoring needs such as application performance, digital experience, business analytics, AIOps, and infrastructure monitoring. Its features are:

    - Automate orchestration with open APIs.
    - Provides extensive cloud support and compatible with all major db technologies.
    - Dynatrace APM solution provides automatic quality checks and KPIs.
    - AI Driven problem detection and resolution.

- AppDynamics: AppDynamics facilitates real-time insights into application performance. This DevOps tool monitors and reports on the performance of all transactions flowing through your application. Its features are:

    - Agents are Intelligent and know when to capture the details of transactions.
    - Solves performance problems through an analytics-driven approach.
    - Automatically finds out normal performance and stop false alarms.
    - Smart Analytics enables to find and fix issues from the very beginning.
    - Enables full system-wide data recording.

4. **Continuous integration tools:**

    Continuous integration tools are used for integrating code into a shared repository frequently and can achieve automated tests and build. Jenkins, Bamboo, Teamcity, and CircleCI, etc can be remembered for CI tools. 

- Jenkins is a free and open source server used to automate rapid build, tests, deploy and release as a part of continuous integration and continuous deployment. 

- Bamboo is a server used for continuous integration and deployment that is similar to Jenkins.

- IBM UrbanCode: As a deployment automation and release management solution, IBM UrbanCode enables uninterrupted delivery for any combination of on-premises, mainframe and cloud applications. Some of its features are:

9. **Testing tools:**

    These tools help in continuous testing functionality in DevOps with features such as an end to end testing and environment management. These automation testing tools are familiar among the testers namely SonarQube, Katalon, Pytest, and Selenium. 

- Test.ai: It is an AI-powered automation testing tool to release apps faster and with better quality. Its AI-Bots:

    - Build tests without coding or scripting.
    - Accelerate testing to the speed of DevOps.
    - Scale testing to any platform, any app.
    - Maintain tests automatically and improve quality everywhere.

- Ranorex: An all-in-one solution for any type of automated testing, whether it is cross-browser testing or cross-device testing. Its features include:

    - All the tools you need for test automation comes in a single license.
    - Test on real devices or simulators/emulators.
    - Allows simple integration with CI servers, issue tracking tools, and more

- Selenium is an open source and free testing tool to test web applications in various browsers and platforms. 

- SonarCube is a testing tool used for Maven-based Java projects. It consists of code quality checkpoints such as Complexities, Architecture & Design, Unit test, Bug fixing, coding rules, and duplications.






# References

- [What is Continuous Delivery? – Amazon Web Services. (n.d.). Amazon Web Services, Inc.]( https://aws.amazon.com/devops/continuous-delivery/)

- [What is CI? - Continuous Integration Explained - AWS. (n.d.). Amazon Web Services, Inc.](https://aws.amazon.com/devops/continuous-integration/)

- [Atlassian. (n.d.). DevOps Test Automation | Atlassian.](https://www.atlassian.com/devops/devops-tools/test-automation)

- [StarAgile. (2024, July 27). 3 Core basic and 7 key principles of DevOps. staragile.com.](https://staragile.com/blog/devops-principles#:~:text=DevOps%20pipeline%20with%20continuous%20development,provides%20automation%20at%20every%20phase.)

- [Qentelli. (2024)](https://qentelli.com/thought-leadership/insights/devops-tools)

- [StarAgile. (2024b, July 27). Best DevOps Tools in 2024. staragile.com.](https://staragile.com/blog/devops-tools)

