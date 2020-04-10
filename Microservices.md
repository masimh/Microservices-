# Microservices-
Microservices
Microservices are a service-oriented architectural design in which applications are developed as a series of individual modules, or services, as opposed to writing an entire application in a single block of code.

Microservices also known as the microservice architecture is an architectural style that structures an application as a collection of services that are
•	Highly maintainable and testable
•	Loosely coupled
•	Independently deployable
•	Organized around business capabilities
•	Owned by a small team
The microservice architecture enables the rapid, frequent and reliable delivery of large, complex applications. It also enables an organization to evolve its technology stack.

Microservices, as we know them today, evolved in response to the issues and constraints of monolithic applications. Because monolithic applications tend to grow in size and scope over time, the tight coupling between components leads to slower, more challenging deployments.
As such, monoliths take on a high risk of failure, which increases every time a feature is deployed.

Type of Microservices
There are two main types of Microservices: stateless and stateful. The core difference between the two comes down to whether the services retain records of communication between each module or not. Here, we’ll quickly break down the pros and cons of each.

Stateless Microservices
One of the main types of microservices, stateless microservices, is ideal for distributed systems. In this case, each request is treated as an independent unit with no context from previous iterations. The benefit is that stateless components can easily be replaced, without the risk of passing on problems lurking inside the old code.
Stateless microservices don’t keep records of session state between requests. This means that if some part of a service instance is removed, it won’t impact the processing logic for that service.

Stateful Microservices
On the flipside, stateful services are a type of microservices that stores session information right there in the code. This way, when two or more services communicate, they automatically keep a record of services performed.
While there is a wide range of use cases in which stateless services make sense, there are just as many reasons organizations need to retain that information.
For example, something like stateless online banking wouldn’t work, as the services wouldn’t keep historical records of deposits and withdrawals — presenting some serious problems for end-users.

Microservices Used for?
The short answer is, microservices are used to address the issues associated with monolithic applications.
Because services are small in scope and feature a modular design made up of several loosely-coupled components, organizations gain increased fault tolerance and faster deployment times, which in turn enables continuous improvements and frequent feature releases.

Characteristics of Microservices Architecture
To answer the questions, you might look toward some of the defining characteristics of this architectural style.
While there will be considerable variation between individual applications, here are some qualities you’ll find in a successful microservices software system.
	Services should communicate over the network by utilizing technology-agnostic protocols.
	Each service is built with a business goal in mind.
	All services are independently deployable.
	Services should be able to leverage polyglot programming and persistence.
	A microservices architecture should be modular. Each service should be small in size, and contain all elements required to complete its function independently.
	The organizational culture should embrace strong Agile, DevOps and CICD practices to enable automation of testing and deployment.
	A microservices architecture should include decentralized governance and data management.
	Microservices are failure resistant and fault tolerant.

Monolithic Vs Service-Oriented Vs Microservices
When the concept of microservices first began to appear, people had trouble understanding the differences between microservices and service-oriented architecture. On the surface, microservices and SOA architecture patterns look rather similar, but there are some significant differences between the two.
Monolithic, service-oriented, and microservices architectures vary considerably in their granularity, which plays a vital role in software architecture. The reason for this is related to the degree of coupling and cohesion that coarse-grained and fine-grained architectures provide.
Coupling is a term that refers to the degree of interdependence between software modules. Tighter coupling between modules offers the benefit of less fault resistance, but also makes it more difficult to update or reuse individual modules.
Cohesion refers to how well the individual elements within an application work together. As a general rule, developers should aim to build loosely-coupled, highly-cohesive software systems. The reason being, highly-cohesive systems tend to be more robust, reliable, and reusable than those with low cohesion.
A loosely-coupled and highly-cohesive architecture makes multiple processes much easier for the entire team, including design, testing, monitoring, and deployment.
The graphic below offers a visual representation of the granularity offered by monolithic, service-oriented, and microservices architectures.

Monolithic vs SOA vs Microservices Structure
 
Monolithic applications represent the worst-case scenario when considering cohesion and coupling. A monolithic application is a single-tiered architecture where multiple layers are tightly coupled, and multiple components run in the same process. A single data store is utilized throughout the application.
Monolithic applications also exhibit very low cohesion, as the entire application is made from a single block of code and is deployed as a unit. Monolithic architectures require the entire program to be recompiled and deployed every time a change is made due to their inherent interdependencies.
The middle ground between a monolithic and microservice architecture is a service-oriented architecture, or SOA. SOAs are similar to microservices in that they move away from the monolith model and break the application into a series of modules, each with their own specific function. Like microservices, SOAs are much smaller in scope than a typical monolith. But, like monoliths, SOAs operate using a single data store.
While focused around individual services, SOA modules are coarser-grained than the modules within a microservices architecture, where each service operates independently and has its own data store.
Service-oriented modules all communicate through an enterprise service bus. This means that an influx of requests could back up the entire application and cause delays on the user side. It’s also possible that an enterprise serial bus could become a single point of failure that puts the entire application at risk of downtime, security threats, or both.
As a result, SOAs do offer higher cohesion than a monolithic application but are more tightly coupled than microservices.

Example of Communication in Microservice, SOA, and Monolithic Architectures
 
Microservices offer both the loosest coupling and highest cohesion, as compared to SOAs and monolithic applications. With each service responsible for every element involved in its functionality, messaging, and data storage, microservices are designed to facilitate DevOps and CI/CD due to their autonomous, independently deployable modules.
 
Key Benefits of Microservices
Here, we’ll quickly go through the primary benefits offered by a microservices architecture. For a deeper dive, read our article on microservices advantages.
When a microservice architecture is built to support specific use cases and is implemented properly, organizations stand to see massive improvements compared to a monolithic architecture, including:
	Improved modularity. Organizations now have a program that is easier to understand, develop, and test. This simplifies the process of onboarding new developers, as there is no longer the need to include every single service in the initial training phase.
	Sets the stage for continuous improvement. Microservices help companies leverage the advantages offered by Agile, DevOps, and CI/CD methodologies.
	Independent services. Because microservice modules are developed and deployed independently, organizations can make quick changes to a single service, roll back buggy updates, and implement customer feedback, as needed. As a result, companies can reduce risk and improve deployment speeds.
	Language agnostic. Developers can write code in any programming language, allowing them to build services using the language that delivers the best results for that use case.
	Every service has its own storage solution. Each service can have very different needs when it comes to data storage. As applications become larger and the volume of data grows, the data sets can have very different characteristics and processing requirements. Microservices allow you to choose the best data storage implementation to address the specific need of the service in order to achieve the end goal.
	Enables team autonomy. A small cross-functional team can manage each service, enabling greater autonomy, distributed leadership, and decentralization.
	Designed for the cloud. Microservices help teams leverage the scalability and flexibility of the cloud.
	Massive reduction in unused functionality over monolithic applications. Isolating and resolving issues is much simpler because they can be isolated to a single service.
	High degree of fault isolation. A change or failure in one service will not impact other services.

Disadvantages of A Microservices Architecture
Despite the long list of benefits that come from decoupling monolithic applications into flexible, scalable microservices, there are some potential disadvantages you should know about before launching an initiative.
Many of the issues linked to microservices come out of the complexities introduced when adding more and more independent services to an application.
Some of these challenges include the following:
	While each service is easier to understand, develop, and deploy, the big picture becomes more complicated.
	More communication is required between services. This means that organizations will likely see overhead costs rise, and when implemented incorrectly, they will see an increase in network congestion and latency.
	Network security becomes increasingly complex, as more services are added to an application, requiring teams to secure all communication points that exist between services.
	DevOps maturity is required to overcome the complexities involved with handling communication and automated deployment, as well as the testing and monitoring of microservices.
With the right tools, processes, and preparation, organizations can overcome the challenges presented by microservices and start reaping the benefits.

Has Reached Agile Maturity
For organizations accustomed to working within a structured hierarchy and decentralized departments, microservices require significant cultural change. Before companies can begin a microservices initiative, they must master the Agile methodology, which depends on lean-thinking, cross-departmental collaboration, distributed leadership, accountability, and team autonomy.
By embracing Agile, organizations can prevent the bottlenecks that occur when a few key stakeholders hold the lion’s share of knowledge and influence.
This enables faster decision-making and helps teams avoid losing progress when a key team member leaves or changes roles. Instead, knowledge is distributed throughout the organization, enabling greater collaboration and a goal-driven, shared-values process.

Polyglot Persistence In Microservices
In a monolithic and SOA architecture, a single data store must be utilized across all services.
Unfortunately, the large data volumes involved in larger applications feature data that have extremely varied characteristics and requirements for processing. A single data store is often not the ideal approach to structure and process all the sets of data that can be collected by an application.
In a microservices architecture, each service is able to utilize its own data store, leaving developers free to choose the database type that best fits the characteristics and processing requirements of the service.
The ability of an application to choose different database technologies for individual services is known as polyglot persistence.
Below is an example of what data persistence looks like in a monolithic, service-oriented, and microservices architectures.
