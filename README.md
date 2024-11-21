······································ Overview ······································

"PoC of Microsoft Fabric with a Medallion Architecture Approach"

This repository showcases a Proof of Concept (PoC) project that implements Microsoft Fabric using the Medallion Architecture. The goal is to demonstrate how to ingest raw data, transform it, and deliver high-quality, business-ready data for extracting valuable insights. Additionally, this project includes a dashboard design to visualize the results and provide actionable analytics.

The project was designed as part of my learning journey in Microsoft Fabric, combining both theory and hands-on application to deepen my understanding of the platform and its capabilities.

···································· Key Features ····································

Architecture Layers:

* Bronze (Raw Data Ingestion & Validation)
	- Ingests raw data from a SQL Server DB.
	- Performs basic validations and schema checks.
* Silver (Data Cleaning & Structuring)
	- Transforms and organizes the validated data for further processing.
	- Utilizes Functional Programming principles for transformation logic.
* Gold (Business-Ready Data Modeling)
	- Models data using the Star Schema approach.
	- Prepares the dataset for dashboards and BI reporting with clean and understandable column names.
* Business Workspace
	- Provides reports, dashboards, and semantic models.
	- Enables users to perform ad-hoc analysis with pre-processed datasets.

··································· Key Takeaways ····································

* Importance of balancing trade-offs to design efficient, transparent data solutions.
* Value of thorough planning to optimize workflows and maintain consistency.
* Benefits of incorporating feedback from peers and learning from alternative solutions.
* Use of Object-Oriented Programming (OOP) for maintainable Bronze-level ingestion and Functional Programming for transformations in Silver-level processing.

······························ Tools & Technologies Used ·····························
	
* Microsoft Fabric: 
	- Synapse Datawarehouse
		- Warehouse
		- Dataflow Gen2
	- Synapse Engineering
		- Lakehouse
		- Notebooks
		- Pipelines 
	- Power BI Service
		- Reports
	
* SQL Server 18: Local instance for raw data

································ Repository Contents ·································

The folder structure includes:

/ MF_images: Microsoft Fabric print screens of the implementation. (Workspace, pipelines, lakehouses, warehouses)
/ scripts: Contains all Python/Spark and SQL scripts used for ingestion, transformation, and modeling.
PBI: Power Bi report located in the Business Workspace
architecture: Diagram implementation of medallion architecture

······································· Author ·······································

Feel free to connect with me on LinkedIn or share feedback on this project! ---> www.linkedin.com/in/ivangennaro
