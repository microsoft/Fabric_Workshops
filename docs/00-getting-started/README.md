# Getting Started with Microsoft Fabric

Microsoft Fabric is an end-to-end analytics platform that provides a single, integrated environment for data professionals and the business to collaborate on data projects. Fabric provides a set of integrated services that enable you to ingest, store, process, and analyze data in a single environment.

Microsoft Fabric provides tools for both citizen and professional data practitioners, and integrates with tools the business needs to make decisions.

Fabric includes the following services:

- Data engineering
- Data integration
- Data warehousing
- Real-time analytics
- Data science
- Business intelligence

## Explore Fabric's experiences

Fabric offers a set of analytics experiences that are designed to accomplish specific tasks and work together seamlessly.

Fabric's experiences include:

- **Synapse Data Engineering**: data engineering with a Spark platform for data transformation at scale.
- **Synapse Data Warehouse**: data warehousing with industry-leading SQL performance and scale to support data use.
- **Synapse Data Science**: data science with Azure Machine Learning and Spark for model training and execution tracking in a scalable environment.
- **Synapse Real-Time Analytics**: real-time analytics to query and analyze large volumes of data in real-time.
- **Data Factory**: data integration combining Power Query with the scale of Azure Data Factory to move and transform data.
- **Power BI**: business intelligence for translating data to decisions.

Fabric provides a comprehensive data analytics solution by unifying all these experiences on a single platform.

## Enable Microsoft Fabric indvidual user Trial 
Microsoft Fabric is provided free of charge when you sign up for the Fabric trial. Your use of the Microsoft Fabric trial includes access to the Fabric product experiences and the resources to create and host Fabric items. The Fabric trial lasts for 60 days.
You get the following:
Full access to all of the Fabric experiences and features.
OneLake storage up to 1 TB.
Users can create Fabric items and collaborate with others in the Fabric trial capacity. This includes:
Creating Workspaces (folders) for projects that support Fabric capabilities.
Sharing Fabric items, such as semantic models, warehouses, and notebooks, and collaborate on them with other Fabric users.
Creating analytics solutions using Fabric items.

When you start a Fabric trial, your trial capacity has 64 capacity units (CU). You don't have access to your capacity until you put something into it. To begin using your Fabric trial, add items to My workspace or create a new workspace. Assign that workspace to your trial capacity using the Trial license mode, and then all the items in that workspace are saved and executed in that capacity.
For more details see [documentation here](https://learn.microsoft.com/en-gb/fabric/get-started/fabric-trial#administer-user-access-to-a-fabric-preview-trial/?WT.mc_id=academic-114547-leestott)

## Enable Microsoft Fabric Trial on your existing tenant

Before you can explore the end-to-end capabilities of Microsoft Fabric, it must be enabled for your organization.

The permissions required to enable Fabric are either:

- *Fabric admin*
- *Power Platform admin*
- *Microsoft 365 admin*

Fabric can be enabled at the tenant level or capacity level, meaning that it can be enabled for the entire organization or for specific groups of users. To learn how to enable Fabric for your organization, see the [documentation here](https://learn.microsoft.com/en-gb/fabric/admin/fabric-switch#enable-for-your-tenant/?WT.mc_id=academic-114547-leestott).

> [!NOTE]
> You can't modify or access the settings to enable Microsoft Fabric if you do not have any of the listed permissions. Please, contact your administrator to confirm that Microsoft Fabric is enabled in your tenant.

## Microsoft Fabric Capacity

Capacity units (CUs) are units of measure representing a pool of compute power. Compute power is required to run all queries, jobs, or tasks in Fabric from data modeling and data warehousing to business intelligence and AI experiences.

The benefits of Fabric Capacity:

- Simplified purchasing with a single pool of compute for every workload.
- The ability to use the same set of Capacity Units (CUs) wherever you have the need without pre-allocating capacity.
- All CUs are pooled and are not locked in an idle workload to reduce costs.
-Transparent monitoring through a centralized dashboard to monitor usage and costs.

## Microsoft Fabric Workspace

Fabric workspaces allows you to access all Fabric items (lakehouses, notebooks, pipelines, etc.).

Workspaces must be in Premium capacity to use Fabric. If you don't have access to Premium capacity, you aren't able to use Fabric.

You may notice that Fabric experiences look similar to other Microsoft data offerings. Fabric is built on Power BI and Azure Data Lake Storage, and includes capabilities from Azure Synapse Analytics, Azure Data Factory, Azure Databricks, and Azure Machine Learning. What makes Fabric unique is that it brings these capabilities together in a single, SaaS, integrated experience without the need for access to Azure resources.

*Head over to the next exercise to learn about [creating a fabric capacity](../01-create-fabric-capacity/README.md?WT.mc_id=academic-114547-leestott)!*

# Resources

- [Introduction to end-to-end analytics using Microsoft Fabric](https://learn.microsoft.com/training/modules/introduction-end-analytics-use-microsoft-fabric/?WT.mc_id=academic-114547-leestott) | Microsoft Learn Training
- [Data Analytics | Microsoft Fabric](https://www.microsoft.com/microsoft-fabric/?WT.mc_id=academic-114547-leestott) | Microsoft
- [What is Microsoft Fabric?](https://learn.microsoft.com/fabric/get-started/microsoft-fabric-overview/?WT.mc_id=academic-114547-leestott) | Microsoft Learn Documentation
