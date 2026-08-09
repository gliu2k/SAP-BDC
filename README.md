# SAP-BDC
Introduction to SAP Business Data Cloud (SAP BDC)

## What Is SAP BDC?

SAP Business Data Cloud (SAP BDC) is SAP's cloud-based data and analytics platform. It provides an integrated environment for managing, sharing, modeling, analyzing, and consuming business data.

SAP BDC brings together several SAP and partner technologies, including:

- SAP Datasphere
- SAP Analytics Cloud (SAC)
- SAP Databricks
- SAP Snowflakes
- SAP BDC Cockpit
- SAP BDC Connector integration with cloud platforms and systems

The main goal of SAP BDC is to create a unified business data foundation where data can be shared across different data and AI platforms without unnecessary data duplication.

## Key Components
### 1. Data Products

A Data Product is a reusable, governed collection of business data and related artifacts.

![alt text](/images/bdc_dataproducts_1.png)

SAP deliver standard SAP Data Products based on business domains and applications. They contain IL/HL/SAC artifacts which are conceptually similar to traditional SAP BW Business Content.

![alt text](/images/bdc_dataproducts_2.png)

Customers can also create their own custom Data Products.

### 2. SAP BDC Cockpit and Data Sharing

The SAP BDC Cockpit provides centralized capabilities for managing and sharing data across SAP BDC components. 

![alt text](/images/bdc_cockpit.png)

Zero-copy / Delta Sharing with other cloud platforms

![alt text](/images/bdc_datasharing1.png)

![alt text](/images/bdc_datasharing2.png)

### 3. Storage Objects

SAP BDC supports different types of storage depending on the workload.

- **In-memory storage:** High-performance transactional and analytical processing
- **HANA Datalake Storage:** Larger datasets and persistence
- **Storage Objects:** HAHA HDFS file-based storage for large historical datasets. We can create space and virtual table on the file in CSV or Parquet format to share with other spaces or applications via data products

![alt text](/images/bdc_objectstore.png)

## Why Should You Consider SAP BDC?

- Large-Scale Data Analytics
- Databricks ML/AI
- SAP Joule AI Platform
