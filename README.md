# Deep Blue Divers Case Study
### Company Background:
Deep Blue Divers is a renowned scuba diving training and certification organization operating globally, providing recreational and professional courses to individuals and dive centers. With a strong focus on safety, environmental conservation, and quality education, Deep Blue Divers has certified over a million divers since its inception. The organization is now looking to leverage the vast amount of data it has collected over the years to develop data products that can improve the overall diving experience and streamline training processes.
### Challenge:
Deep Blue Divers aims to expand its offerings and add value to its customers by creating innovative data products. The organization wants to utilize its data to enhance training methods, optimize dive planning, and promote safety, while maintaining data privacy and adhering to relevant regulations.
### Data:
Deep Blue Divers has access to a range of data sources, including:
- Diver profiles: Basic demographic information, certification levels, and dive history.
- Training records: Course completion dates, skills assessed, and instructor feedback.
- Dive logs: Dive locations, depths, durations, and environmental conditions.
- Incident reports: Accidents, near misses, and safety-related incidents.
- Dive center information: Facilities, equipment, and staff qualifications.
### Objectives:
The goal of the workshop is for participants to design data products that can solve data use case coming from the Course Developer.
### Constraints:
While designing data products, participants must consider the following constraints:
- Privacy and compliance: Deep Blue Divers operates in various jurisdictions with different data protection laws. Data products must adhere to the highest privacy standards and relevant legal requirements.
- Scalability: The data product must be designed to handle the large volume of data generated by Deep Blue Divers' community and scale as the organization continues to grow.
- Interoperability: The data product should be able to integrate with Deep Blue Divers' existing systems and services, as well as with other third-party applications that divers and dive centers might use.
## IT Landscape
![DDD EU workshops - IT Landscape](https://github.com/JacekMajchrzak/data-product-workshop/assets/16057690/28d6cc3b-adb3-4c59-94ab-1186715df538)

The IT system landscape of Deep Blue Divers consists of various components that help manage and support its operations, training, and certification processes. The following is an overview of key components of the organization's IT landscape:
- Learning Management System (LMS): The LMS is responsible for delivering online training materials, hosting e-learning modules, and tracking student progress. It allows instructors to manage their courses, monitor student performance, and provide feedback.
- Dive Center Management System: This system supports the operations of affiliated dive centers, enabling them to manage schedules, allocate resources, track equipment usage, monitor staff qualifications, record training and certify divers.
- Data Analytics Platform: A data analytics platform is essential for transforming raw data into meaningful insights that can drive decision-making and inform the development of data products. This platform must be capable of processing large volumes of data from various sources, such as the Dive Center Management, LMSa and Divers Application.
- Divers Application: A app for divers provides easy access to training materials, dive logs, and personalized recommendations. The app can also help divers connect with fellow divers, find local dive centers, and receive real-time updates on weather conditions and dive site information. Divers are reporting incidents, like equipment failure, dive accidents, safety concerns etc.
## Data Use Case
#### Course Developer (Mike)
**As a** course developer,
**I want to** identify correlations between training effectivness, its safety, participants well being and curriculum of the course,
**So that** I can create relevant and safe courses or update existing ones.
## Data Persona
![DDD EU workshops - data persona](https://github.com/JacekMajchrzak/data-product-workshop/assets/16057690/9f792a88-be30-46a4-aad7-976bf1dc2942)

# Theoretical introduction
## Data Mesh definition
Data mesh is a **decentralization paradigm**. It decentralizes the **ownership of data**, the **transformation** of data into information, and data **serving**. It aims to **increase the value extraction from data** by **removing bottlenecks** in the data value stream. The data mesh paradigm is guided by four principles, helping to make data operations efficient at scale: 
- domain ownership, 
- domain data as a product, 
- federated computational governance, 
- and self-serve data platform. 
Data mesh implementations may differ in scope and in the degree to which they use each principle.
## Treat your data as a product
- To make data valuable, we should treat it as more than just an asset.
- To treat data as a product, we apply product thinking to it.
- - Love the problem, not the solution
- - Think in products, not features
- Data products should be created with users in mind.
- A data product should address clearly defined user needs.
## Data Product definition
![Data Product and ports](https://github.com/JacekMajchrzak/data-product-workshop/assets/16057690/c81c1fce-59c6-40cb-87f0-6eb4ef9e52d6)
```"A data product is an autonomous, read-optimized, standardized data unit, a node in the data mesh architecture, containing at least one dataset (the domain dataset), created for satisfying user needs."``` *Data Mesh in Action*
## Data Product characteristics
- Viable quality
- Anticipation of user needs
- Secured availability
- Focus on user goals
- Findable
- Interoperable
## Data Product ownership
Data Product development team and Data Product Owner is not only owning datasets, they own everything that constitutes data product shown on the picture below.
![data product ownership](https://github.com/JacekMajchrzak/data-product-workshop/assets/16057690/926a2af1-c6e4-4515-97af-28f480ff0674)
## Data Product design heuristics
- **Align data products with domains/business capabilities**
- **Align data products with possible usage or use cases**
- **Create a data product for a cohesive group of domain datasets**
- Align data products with the source system
- Avoid data products with a canonical model of the whole enterprise
- Align with organizational boundaries
- Align with usage contract
- Align data products with personas of consumers
- Align data products with the consuming dashboard/visualization/bi tool
- Build the data product as a registry for a core business entity
## Data Mesh in Action book
If you want to learn more you can take a look at [my book on Data Mesh](https://www.amazon.com/Data-Mesh-Action-Jacek-Majchrzak/dp/1633439976)
:
![data mesh in action](https://github.com/JacekMajchrzak/data-product-workshop/assets/16057690/5508a91d-6740-4833-943a-86175cb613da)
