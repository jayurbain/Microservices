CSC 5201 - Microservice and Cloud Computing (4 Credits)
----

### Course Description

This course introduces the concepts, architecture, and practical techniques 
needed to design and implement cloud-native microservices. Students will 
design, implement, deploy, and operate a microservice using widely used
technologies and best practices.

Emphasis will be placed on scalable web and machine learning services. 
Students will apply what they learn in a series of hands-on lab exercises 
and complete a final project using a distributed computing platform.

### Course Learning Outcomes

Upon successful completion of this course, the student will be able 
to:

- Leverage containerization to package and run software.
- Design and implement a cloud-based microservices application that interacts through REST APIs, 
implements access controls, uses a distributed storage systems, and is deployed 
in containerized form.
- Apply access control patterns using authentication and authorization 
following security best practices.
- Analyze and identify potential throughput, scalability, reliability, 
and consistency issues with distributed microservice architectures. 
- Create and manage continuous integration and deployment to automated
software related to microservices and pipelines
- Deploy a multi-service distributed application using a container 
orchestration tool.

### Prerequisites by Topic

- Version control / Git
- Operating systems
- Databases

### Course Topics

- Virtual machines, containers, and associated best practices for
writing containerized, stateless applications.
- Microservice architectures, implementation patterns, 
including event-driven architectures, and designing and implementing REST 
APIs.
- Distributed storage systems (e.g., key-value stores, columnar stores,
object stores, distributed file systems, relational databases, and 
vector stores), tradeoffs between consistency, availability, and partition tolerance. 
- Efficient access patterns.
- Continuous integration and deployment technologies and usage patterns.
- Tooling for orchestration and deployment of multi-service systems.
- Software, Function, Platform, and Infrastructure as service. 
- CAP Theorem.
- Discussion of public cloud services and comparisons of their offerings

Grading (no final exam)  
Weekly labs: 40%  
Final project: 30%   
Midterm 1: 15%   
Midterm 2: 15%   

Class will be structured in three parts: 
- Cloud computing.   
- Architecting microservices.  
- Advanced topics and final project.

Office DH425  
TBD: As needed

References:  
[Building Microservices, Second Edition, Sam Newman](https://www.oreilly.com/library/view/building-microservices-2nd/9781492034018/) (BM)

Extra reference:   
[Python Microservices Development, Second Edition, Simon Fraser and Tarek Ziade](https://www.packtpub.com/product/python-microservices-development-second-edition/9781801076302) (PMD)

---

### Week 1: Introduction to Microservices

Note: No class Monday

[Introduction to Microservices](https://docs.google.com/presentation/d/1ky-Oj19UXCS4EycsV4bXkY2JojuUW1idTY6mxip15G8/edit?usp=sharing)

[Lab 1 - Introduction to Cloud Computing using AWS](https://docs.google.com/document/d/1umFyMuCpuccp9mrPfZk4ygAGBxkZIVNvUsSXPyjq8h8/edit?usp=sharing)

Reading: Chapter 1 (BM).

David Parnas in “Information Distribution Aspects of Design Methodol‐
ogy”, Information Processing: Proceedings of the IFIP Congress 1971 (Amsterdam: North-Holland, 1972),
1:339–44. https://oreil.ly/rDPWA 

[Alistair Cockburn, “Hexagonal Architecture,” January 4, 2005.](https://oreil.ly/NfvTP)
 
[M. Armbrust, A. Fox, R. Griffith, A. Joseph, R. Katz, A. Konwinski, G. Lee, D. Patterson, A. Rabkin, I. Stoica, and M. Zaharia. Above the Clouds: A Berkeley View of Cloud Computing, Technical Report No. UCB/EECS-2009-28.](http://jayurbain.com/msoe/cs4230/Readings/Above%20the%20Clouds%20-%20A%20Berkeley%20View%20of%20Cloud%20Computing.pdf)

References:  
[Nano Cheat Sheet](https://www.reddit.com/r/bashonubuntuonwindows/comments/iv3qcx/nano_cheatsheet/)  
[Ubuntu Guides](https://help.ubuntu.com/community/ExternalGuides)     
[Ubuntu/Linux command Line cheat sheet](http://files.fosswire.com/2007/08/fwunixref.pdf)    
  
---

### Week 2: Virtual Machines, Infrastructure as a Service

[Virtual Machines](https://docs.google.com/presentation/d/1_DLK6JmCaVyFRZKHaDKI9uZ8kLI039rGquLinosDfUc/edit?usp=sharing)   

[Lab 2 Virtual Machines](https://docs.google.com/document/d/1VAXeCc17Z4HqEgFeUSkYEe4BCAhcAMiVMU2CpoBTb00/edit?usp=sharing)

[Lab 3: Most Excellent Flask EC2 Web App on AWS](https://docs.google.com/document/d/1SeYCrRIlKWzPCu04Jx4rJGFggfuHj2FbDh7IVQAO0LY/edit?usp=sharing)

[Auto Scaling Computing Clusters](http://jayurbain.com/msoe/cs4230/slides/cs4230-autoscaling-4.pdf)

Reading:   
[Virtual Machine Monitors](http://pages.cs.wisc.edu/~remzi/OSTEP/vmm-intro.pdf)  
[Xen and the Art of Virtualization](http://jayurbain.com/msoe/cs4230/Readings/Xen%20and%20the%20Art%20of%20Virtualization.pdf)  
[Amazon Web Services (AWS) Documentation](http://aws.amazon.com/documentation/)   

---

### Week 3: Platform as a Service, Containers 

[State of the Cloud](https://docs.google.com/presentation/d/12BXwNZB_w8kj9oiQtrqrg4OJZPnuBYlXBYJ3a7C247k/edit?usp=sharing)

[Lab 4 Platform as a Service Mulligan - DigitalOcean](https://docs.google.com/document/d/1hSLSXYpqaIg4u30UxgmwJg0QFAFNmME3-XY1g_Te3Ek/edit?usp=sharing)  

<!--
[Lab 4: Flask Elastic Beanstalk Web App on AWS](https://docs.google.com/document/d/1uYprsSkgjhWwgJF-JydYWFAFy6oKtbZzX9kVOaeGSMY/edit?usp=sharing)
-->

[Intro to Docker and Containers](https://docs.google.com/presentation/d/1CbYr7ITk-0SB0dH-EWYjeEdfF22DHbL9aEzAKfVuqvw/edit?usp=sharing)

[Lab 5: Docker Lab Extraordinaire](https://docs.google.com/document/d/1dNN8bvMcV8j8gWYEwvSqTG6QAMawbhImnlt-FkL6968/edit?usp=sharing)

Reference:  
Install Python, pip, and the EB CLI on Linux (Thanks Harry Kubiak!)     
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-install-linux.html    

---

### Week 4: Containers, Container Orchestration with Docker Compose and Kubernetes

Monday:    
[Container Orchestration](https://docs.google.com/presentation/d/1T4N9rcsfKk_Qlj6E3wxb-Js58_ifsG9wGLyVTKMYcRA/edit?usp=sharing)

[Lab 6: Composing a Flask-MySQL app with docker and docker-compose](https://docs.google.com/document/d/19ehdRBdGwGS2LC5-WNqttChIFvu-iDW_HOIaU23Nw8E/edit?usp=sharing)

Wednesday September 25th. Guest lecturer James Grant, VP Engineering, Direct Supply.  

- Refactoring legacy systems  
- Data-first or interface-first approach  
- Importance of consistent "plumbing" (e.g. Security, deployment, etc)  

References:  

[Docker Compose](https://docs.docker.com/compose/overview/)  
[Kubernetes Concepts](https://kubernetes.io/docs/concepts/overview/)

---

### Week 5: Kubernetes Clusters, Review

[Container Orchestration - Kubernetes](https://docs.google.com/presentation/d/1T4N9rcsfKk_Qlj6E3wxb-Js58_ifsG9wGLyVTKMYcRA/edit?usp=sharing)

[Lab 7: Deploy a Flask API Service on Kubernetes](https://docs.google.com/document/d/16fPx_CXs9WBDWvlw6R5SVsM5e36gaf7jeGOKqXVjVRk/edit?usp=sharing)

[Midterm 1 Exam Review Guide](https://docs.google.com/document/d/1VKyQVOl4YkPpmmEfrA6KF33yd3nTbFV5/edit?usp=sharing&ouid=114095891007675323509&rtpof=true&sd=true)

<!--

[Technologies for Scalable Distribution, AWS Dynamo](slides/dynamo-5.pdf)

[Lab : Deploy a Flask API Service on Kubernetes](https://docs.google.com/document/d/1z6fkpfDdjuaPl9_zOaI7Hk-yhioZoXKSsg-jwJt1ZNE/edit?usp=sharing)

-->
<!--
[Lab 17: DynamoDB Web App](https://docs.google.com/document/d/1crUDhpT3c5uzKunTMMiwFSU2IPuiN0YJKNvMcrSeTKs/edit?usp=sharing)
-->
---

### Week 6: Midterm, Autoscaling and Load Balancing

[Midterm 1 Exam](https://docs.google.com/document/d/1VKyQVOl4YkPpmmEfrA6KF33yd3nTbFV5/edit?usp=sharing&ouid=114095891007675323509&rtpof=true&sd=true)  
 - Online, written format, no notes

[Auto Scaling and Load Balancing](https://docs.google.com/presentation/d/1bNsVBHAtkEFOljHatV1_ygPA2LQ7BCR0sHkR2QLlxMQ/edit?usp=sharing)

[Lab 8: Deploy Flask on Kubernetes Cluster Hosted by Digital Ocean](https://docs.google.com/document/d/1tQSmogs_YZcs7pxzbCIQ2XFzm9EW3KO9a08_goS1XM0/edit?usp=sharing)

---

### Week 7: Modeling Microservices, Refactoring Applications into Microservices

[Modeling Microservices](https://docs.google.com/presentation/d/1HLOVjrULeWjiZ6RvGBDaSnabpKrf--OHs8cszqLFNxA/edit?usp=sharing)

Lab 8 continued. 

Reading: Chapter 2 (BM).

[Refactoring Services into Microservices](https://docs.google.com/presentation/d/10yYPltEhJgGRFV_my4fRGf1A5Tt-qznXjxf3832XIpU/edit?usp=sharing)

Lab 8 continued. 

Reading: Chapter 3 (BM).

[Making the Move from Monolithic Architecture to Microservices](65d4f248-making-the-move-from-monolithic-architectures-to-microservices-1.pdf)

---

### Week 8: Communication Styles, Implementing Microservice Communication

[Implementing Microservice Communication Styles (both weekly lectures)](https://docs.google.com/presentation/d/1dq887MXI_--nbDTRwJOCZBgLCo3BU9xpKo-KPp3Ez5A/edit?usp=sharing)

[Implementing Microservice Communication]

Lab 8 continued. 

Reading: Chapter 4 and 5 (BM).  

---

### Sprint Break: 3/9 - 3/17/2024

---


### Week 9: Distributed Data Platforms, Spark

[CAP Theorem](https://docs.google.com/presentation/d/14az2LNnlih-u7FtB7JtQ7ckJA88zLL0J8iDkf2FJWgc/edit?usp=sharing)  

[Data Platforms](https://docs.google.com/presentation/d/1u0OmWbPpD6pTgLehT25ZV28LtKsfH_xmTFWQkqkALMk/edit?usp=sharing)

[Lab 9 Part 1: Apache Spark](https://docs.google.com/document/d/1mnORjsRg634MG5JCOO6dU3wGlIyBHqQPEqzJ1yOlroQ/edit?usp=sharing)

References:    

[Resilient Distributed Datasets: A Fault-Tolerant Abstraction for In-Memory Cluster Computing](https://www.usenix.org/conference/nsdi12/technical-sessions/presentation/zaharia)

[Google's BigTable](http://jayurbain.com/msoe/cs4230/slides/cs4230-googleBigTable.pdf)

Reading: Chapter 12 Resiliency and Chapter 13 Scaling (BM).  

---


### Week 10: Machine Learning on Large Distributed Datasets   

[Scalable Machine Learning](https://docs.google.com/presentation/d/1XIHAxrk4uE2CMW2d3rFkXdAY9w1lDTSLwrsW-dwAPr0/edit?usp=sharing)

[Machine Learning Intro](https://docs.google.com/presentation/d/1R6A_0nqWS7H_6AVnm0L1K8zPy6aReFBFMT0auo5l7Dc/edit?usp=sharing)

[Apache Spark Architecture](https://docs.google.com/presentation/d/1-hMfwAIBVw5zbl1poSDSCgN6zDwuJixl7_TY-kN1twg/edit?usp=sharing)

[Lab 9 Part 2: Apache Spark](https://docs.google.com/document/d/1lj1Ly7L8gFLdL_GX6wUzqaIJt6vyHSyT2CfZMhtQ8P0/edit?usp=sharing)

References:

[The Big Book of MLOps - Databricks](2023-10-eb-big-book-of-mlops-2nd-edition-v2-102723-final.pdf)


---

### Week 11: Event Streaming

[Event Streaming, Apache Kafka](https://docs.google.com/presentation/d/1PuJN96ZNfNNzE2Tu4PRWDvfO6DK_aU978YHpy6snSWw/edit?usp=sharing)

[Lab 10 Apache Kafka - Part 1](https://docs.google.com/document/d/1id8l_L_bu2D58WbTwoU5ZDbpMVXUMx3pCWT13csI4uU/edit?usp=sharing)

[Lab 10 Apache Kafka - Part 2](https://docs.google.com/document/d/1Mfa7RNdrMN0kvAvWg9ZWBdVL3CD5iq7sYWFEVg-43rY/edit?usp=sharing)

[Midterm 2 Exam Review Guide](https://docs.google.com/document/d/1a2sXv7dq_2aONe5A_aiiCCOYcp8HI5P9/edit?usp=sharing&ouid=114095891007675323509&rtpof=true&sd=true)

---

### Week 12: Midterm 2, Authentication and Authorization

[Midterm 2 Exam](https://docs.google.com/document/d/1a2sXv7dq_2aONe5A_aiiCCOYcp8HI5P9/edit?usp=sharing&ouid=114095891007675323509&rtpof=true&sd=true)

[Securing Microservices](https://docs.google.com/presentation/d/1h7oCHDBupFok1m_yobXKWDB58-eVth2pRdYzafp38R4/edit?usp=sharing)

Reading: Chapter 11 (BM).


---

### Week 13: Machine Learning Services, Additional Topics, Final Project 

[Machine Learning Services](https://docs.google.com/presentation/d/1KA-pJfNPpuwMmj9ODOb1NvzCj8y3_ajoZqdmyXMV0qw/edit?usp=sharing)

[Monitoring Microservices](https://docs.google.com/presentation/d/1jxEu6G1Y1fd3sDA3dS_UH5g60Oz743wclIOjMsRU0qg/edit?usp=sharing)
 
[Final Project](https://docs.google.com/document/d/1X6aJZ8jhi3XlAsKcghK0CWbOqylcsl4r9vFMff2SkD0/edit?usp=sharing)


---

### Week 14: Final Project Presentations

[Final Project](https://docs.google.com/document/d/1X6aJZ8jhi3XlAsKcghK0CWbOqylcsl4r9vFMff2SkD0/edit?usp=sharing)

[Dashboards](https://docs.google.com/presentation/d/1Eah6-_9jAQfUimjA2ZotkGv6x9KNguCptomaKVtOjRo/edit?usp=sharing)

[Microservices for Machine Learning](https://docs.google.com/presentation/d/1zkNq0XgbrKJ5z_xPkWN4TlQxa7Rk5R7OH0OOGMaG8U4/edit?usp=sharing)

---

### Week 15: Final Projects Presentations

Monday and Wednesday 5-minute boaster session for each project:
- What is your project?
- What problem does it solve?
- Why were you interested in this project?
- Brief explanation of your design and functionality.
- Status and lessons learned

[Final Project](https://docs.google.com/document/d/1X6aJZ8jhi3XlAsKcghK0CWbOqylcsl4r9vFMff2SkD0/edit?usp=sharing)    


---

