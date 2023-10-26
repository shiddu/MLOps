# MLOps
THIS TEST REPOSITORY
All the Ops: DevOps, DataOps, MLOps, and AIOps

All the Ops: DevOps, DataOps, MLOps, and AIOps

In recent years, there has been a rapid increase in acronyms with the “Ops” suffix, which initially started by the merging of development and IT operations (DevOps). This pairing together of disciplines helped enterprises better define their processes, improve the quality of their output, and operate at much faster speed.
In this article, I’ll define the most common Ops – DevOps, DataOps, MLOps, and AIOps – and how they work together. 
Defining all the Ops
Let’s start by defining DevOps, the one that started it all. DevOps is a set of practices that combines software development (Dev) and information technology operations (Ops) that aims to shorten the development lifecycle and provide continuous delivery with high software quality. Because security is a shared responsibility integrated from end to end, DevSecOps was defined and emphasizes the need to build a security foundation into DevOps initiatives. You can learn more about DevOps and DevSecOps by exploring the DevOps content on IBM Developer.
As DevOps improved the quality and scalability of software development, the data analytics discipline sought to bring these same improvements to their practices. Thus, DataOps was defined. In a nutshell, DataOps applies agile development, DevOps, and lean manufacturing to data analytics (Data) and operations (Ops). Read more about DataOps in this introduction to the DataOps discipline.
Here is where machine learning enters the picture, since machine learning models leverage large sets of data. MLOps is meant to standardize and streamline the lifecycle of machine learning models in production by orchestrating the movement of machine learning models, data, and outcomes among the systems.
And now that brings us to AIOps, or artificial intelligence (AI) for IT operations. AIOps replaces many tedious, manual IT operations with an intelligent IT operations platform that collects structured and unstructured data, identifies events and patterns, reduces noise, and reports or remediates issues, thus greatly enhancing the productivity of the team responsible for keeping operations up and running. You can learn more about AIOps by exploring the AIOps content on IBM Developer.
Finally, ChatOps is the use of chat clients, chatbots, and real-time communication tools to facilitate how software development and operation tasks are communicated and executed. This can be used in combination with any of the other Ops above.
How all the Ops work together
Now that we understand the basic definitions of all the Ops, let’s look at how all these Ops – DevOps, DataOps, MLOps, and AIOps – work together.
 

First, we must start with what developers do when developing an application. Typically, you first code the app, then test it by writing some unit tests and integration tests, followed by deployment, and finally you monitor it to see if there are any issues. Whether using waterfall or agile, the overall steps are the same, just iterated more frequently. Over the years, this has become DevOps by adding automation to the coding, building CI/CD pipelines to automatically build the app and run the tests when a pull request is created. DevOps practices traditionally apply to the end-to-end lifecycle of developing applications.
DataOps is simply applying DevOps to data instead of an application or traditional code. DataOps is managing the whole data lifecycle, from creation to deployment to monitoring that data. Similarly, MLOps applies DevOps principles but to machine learning models, which are like applications but requiring training, running interference, and verifying that the results are accurate. Both DataOps and MLOps are DevOps-driven.
AIOps includes DataOps and MLOps. Because AI needs to have data coming in, such as logs or metrics, and that data needs to be managed in terms of the lifecycle to check the accuracy and right stats, AIOps uses DataOps. Because AI is driven by machine learning models and it needs machine learning models to be created, deployed, trained, and analyzed to see if the results are accurate, AIOps includes MLOps as well. DevOps is used in AIOps for lifecycle management and automation of all the applications that comprise the AIOps. And, finally, AIOps can be used to further optimize and make better decisions along the software development lifecycle of DataOps, MLOps and DevOps. In summary, AIOps uses these Ops, and AIOps can also be applied inside each of these Ops.
Applying AIOps
Enterprises are turning to AI-powered automation to ensure faster decision-making, better resource optimization, and proactive resolution. One major area for this is in the IT operations space. So, how do you put AIOps to work for your enterprise?
A good AIOps implementation requires three layers:
1.	Observability -- First and foremost, your AIOps implementation needs to observe, which requires good observability monitoring and data, in the form of metrics, logs, events, and incidents that are happening in real time. Network monitoring is an example that will help you understand any performance issues.
2.	Resource optimization -- The more data you have, the better you’ll understand the topology or resource graph or the grouping. With the topology, you can optimize the usage of resources to help avoid problems altogether or remediate problems quickly. For example, if you have two VMs that don't have enough traffic, then the two VMs could be optimized to just one VM for doing cost optimization in that cloud vendor.
3.	Problem determination -- With what you learn from the results of observability and resource optimization, you can proactively anticipate problems and automate fixes to problems.
When an AIOps solution is first deployed in an enterprise, there is always a journey both in trust and in capabilities. As AIOps uses a variety of machine learning techniques, there is typically a training period where the AIOps solution is gathering baseline data, and then over time it continues to learn from the observed behavior and feedback.
At the same time, there is a lack of trust by the operations team warranting guard rails, and rightly so. One manifestation of this is to allow the AIOps solution to provide suggestions, but require supervision before implementation. Also, AIOps solutions must clearly explain any predictions it makes because AIOps should be transparent and not act like a black box. Over time, trust will increase and automation can be put in place, outages can be avoided, and an enterprise can reap the full rewards with increased productivity and decreased outages.
What is MLOps?
MLOps is a business model that machine learning organizations have devised. The concept of MLOps replaces the traditional vertical silos in which organizations function by sharing resources and expertise across departments. MLOps is a way for data scientists and operations experts to collaborate and communicate in order to manage the production ML lifecycle. It is a culture and practice in machine learning engineering that tries to bring together the creation and operation of machine learning systems (Ops).

MLOps Principles 
MLOps is relatively new, as machine learning has only recently become broadly adopted by companies. MLOps principles are intended to change the game in various sectors. So, let's look at some of the MLOps' core components or principles.
•	Automation - You can easily automate the workflow steps without any manual intervention.
•	CI/CD - MLOps includes CI/CD. Testing and Monitoring. 
•	Versioning - You can efficiently track your ML Models and datasets with version control systems.
•	Experiment Tracking - You can parallely execute multiple experiments on model training. 
•	Testing - Test different features, data, models, infrastructure, and a lot more.‍
•	Monitoring - Get detailed insights on models performance.
 

Why MLOps?
ML is different from standard software because data is at the core of the application. This means that the code is built around servicing the data rather than the application behavior. ML is also an open-loop, ever-evolving system. The task has barely just begun after the models have been deployed. To achieve maximum performance, models in production must be constantly monitored, retrained, and redeployed in response to changing data signals. MLOps drive insights you can trust and put into play more quickly in a controlled manner. It brings back business interest into machine learning operations. 
•	It combines the expertise of all teams for more efficient ML
•	It inculcates best practices & guidelines to ensure a smooth transition from concepts to experiments to production-ready models.
•	It helps avoid bottlenecks with a better division of expertise.
•	You can quickly train your models, track experiments, and deploy strong APIs.

How MLOps Works?
Generally, MLOps lifecycle/workflow involves the following steps-
1.	Data Extraction
2.	Data Analysis
3.	Data Preparation
4.	Model Training
5.	Model Evaluation
6.	Model Validation
7.	Serving & Monitoring 
MLOps can be implemented in three different ways:
Level 1: Manual process
This process is common for businesses just getting started with machine learning. If your models are infrequently altered or trained, a manual ML approach could work.
This is a standard data science technique used at the beginning of machine learning deployment. This level is experimental and iterative in nature. Each pipeline step, including data preparation and validation, model training, and testing, is done manually. Data is frequently handled using Rapid Application Development (RAD) methods like Jupyter Notebooks. When employing the manual process, the probability of model failure in the real world rises.
Level 2: ML Pipeline Automation
This architecture is ideal for deploying new models based on fresh data rather than new machine learning ideas.. It automates the ML pipeline, leading to faster experimentation. It also allows you to achieve CD of model prediction service and automate the process of retraining models in production with new data. You must arrange the ML experimentation processes, introducing things like automatic data, model validation, and metadata management, as seen in the graphic below.
To develop ML pipelines, components must be reusable, compostable, and shareable across the pipeline. As a result, EDA code may be stored in notebooks, but component source code must be modularized. This scenario might be useful for systems that operate in a dynamic environment and need to quickly react to changes in customer behavior, price rates, and other factors. However, if you want to experiment with new machine learning concepts and quickly deploy new ML implementations, you'll need a CI/CD infrastructure to automate the build, test, and deployment of your ML pipelines.
Level 3: CI/CD Pipeline Automation
This level is appropriate for tech-driven businesses that must retrain their models daily, if not hourly, update them in minutes, and redeploy them across thousands of servers simultaneously. Such enterprises will not be able to thrive without an end-to-end MLOps cycle. The Data, Machine Learning Model, and Machine Learning Training Pipeline components are now created, tested, and deployed automatically, which is a significant improvement over the previous level.
This method allows data scientists to rapidly explore new ideas around feature engineering, model design, and hyperparameters.  In the automated level pipeline, you can see the six primary phases of CI/CD, as shown in the graphic below. With this, you can repeatedly test new machine learning algorithms and modeling while orchestrating the experiment phases. The source code for the ML pipeline stages is output from this stage, subsequently published to a source repository.
Advantages Of MLOps
Many businesses now use machine learning operations to optimize their production and distribution systems, as well as further research and development efforts, such as those in self-driving cars. MLOps allow companies to drastically decrease the time needed for data analysis by creating automated feedback loops that can find patterns within a massive dataset without human aid. Here are a few benefits of MLOps:
•	Rapid Innovation.
•	Reproducible Workflow and models.
•	High-precision models can be easily deployed in any situation.
•	Effective management of the entire ML lifecycle
•	A  resource management system and control for ML models.

Best MLOps Tools & Platform 
There are several end-to-end MLOps and custom-built MLOps tools available; let's have a look at a couple of the best and most widely used platforms.
End-to-end MLOps solution
These are completely managed services for rapidly creating, training, and deploying machine learning models.
•	Amazon Sagemaker
•	Google Cloud MLOps 
Custom-built MLOps platform
End-to-end solutions are excellent, but by separating your MLOps pipeline into numerous microservices, you can create your own MLOps tool stack with your chosen tools. These platforms are best for businesses just getting started with machine learning.
•	MLFlow
•	Neptune.ai
•	Weights & Biases 
•	Cortex 
•	Polyaxon
A variety of Open Source frameworks have arisen in the few short years that MLOps has gained prominence. As data and technology continue to proliferate and reach new heights, implementing solid ML strategies today will help enterprises of all types manage and grow in the future. 
What is DevOps?
Any software company consists of two teams: one is the development team, which designs and develops systems from scratch, and the other is the operations team, which tests and implements the developed products. In most cases, the operations team provides input on bugs and other issues while the development team handles them. There may be times when the development team moves on to a new project while the operations team provides input on the prior one. This pushed back the deadline and delayed the entire software development cycle. T
What if both the development and operations teams collaborated and the barrier of misunderstanding was broken? This is what the DevOps concept is all about. DevOps has become a popular term used in the IT world to describe the process of software development, operation, and management across a system. It is not just one tool or method which can get the job done; instead, it is an approach that allows for greater agility when it comes to changes in operations. DevOps is primarily about collaboration between developers and manual and automated systems. 
How DevOps Works?
Key Components of DevOps lifecycle involves :
•	Source Code Management : Version control and maintaining different versions of code
•	Continuous Integration: Continuous build, compile, validate, code review & unit testing
•	Continuous Delivery: Continuous testing and deploying the build applications to test server
•	Continuous Deployment: Configuration management & containerization, deploying application to prod server for release
•	Continuous Monitoring: monitoring every part of lifecycle
Source Code Management/Version Control
The practice of tracking changes to a source code repository is referred to as source code management (SCM).  SCM keeps track of a code base's history of modifications and assists in resolving disputes when merging updates from various contributors. Version control is also referred to as SCM. There are two types of version control systems:
Centralized Version Control 
Everyone commits and edits the code simultaneously in a single repository with centralized version control. Everyone on the team will be notified when the code is updated, and they will be required to update the code in their workspace.
Distributed Version Control
With distributed version control, each developer has their own repository and software copy. You have to submit the updated code to the central repository. To put it another way, you commit and push the changes while other team members pull and update them.
Continuous Integration
Continuous Integration (CI) is a technique for integrating feature branches into master code that can be automatically generated and tested. This strategy assists developers in discovering and quickly fixing problems. You can fail early and improve rapidly with CI integration, which improves the quality of your process. CI helps create a pipeline from coding an idea to getting it out into the world.
 
Continuous Integration | Image By Author 
‍Continuous Delivery
Following Continuous Integration (CI), you have to test applications for end-user acceptability in the Continuous Delivery stage. Continuous Delivery is a software development approach in which teams generate software in short cycles to be deployed to end-users at any time. The team manages risk by ensuring that each increment is small and contains changes that are only related to one aspect of the product—so if something goes wrong, it won't affect other aspects of the development. 
 
Continuous Delivery | Image By Author
‍Continuous Deployment 
Continuous Deployment is taking the test application and deploying it to the production server— every change is deployed to production. It's the opposite of a big bang release. This is done by automating your deployments, creating small deployments, and using feature flags to control which users get what features. 
 
Continuous Deployment | Image By Author 

Configuration Management
Configuration management (CM) is the process of tracking and ensuring that all instances of a particular product, application, or resource are changed in unison. It is an important part of any infrastructure because it ensures consistency among infrastructure elements. It eliminates dependency issues.  
Continuous Monitoring
Continuous monitoring refers to an organization's capacity to identify, respond to, contain, and mitigate attacks on its infrastructure. It is the process of collecting and analyzing data over time, in order to detect and prevent problems that may not be observable in real-time. Continuous monitoring helps business owners and managers sense changing conditions and trends quicker than traditional approaches. 

Advantages Of DevOps
The whole idea behind DevOps is to create a fast-paced environment where software can get from concept to production quickly without sacrificing quality or performance. This not only increases customer satisfaction but also helps the company grow revenue while. DevOps helps you :
•	Ensure a more rapid deployment
•	Maintain a stable working environment
•	Significantly higher product quality
•	Software delivery on a continuous basis
•	Collaboration and communication improvements

Best DevOps Framework, Tools and Platforms
Here is a list of some of the most popular DevOps tools and frameworks.
Code: Git, JIRA
Build: Sbt, Maven
Test: Testfairy, JUnit
Release: Jenkins, CodeShip
Deploy: Docker, AWS
Operate: Chef, Kubernetes
Monitor: Datadog, Nagios

