# Exam DP-200: Implementing an Azure Data Solution

## Implement data storage solutions (25-30%)

### Implement Azure cloud data warehouses

 - design Data Lake architecture (https://azure.microsoft.com/en-us/solutions/architecture/modern-data-warehouse/)
 - design the data schema (https://docs.microsoft.com/en-us/azure/architecture/data-guide/)
 - provision the data warehouse (https://docs.microsoft.com/en-us/azure/sql-data-warehouse/create-data-warehouse-portal)

References:
- Modern data warehouse https://azure.microsoft.com/en-us/solutions/architecture/modern-data-warehouse/
- Modern data warehouse https://docs.microsoft.com/en-us/learn/paths/modern-data-warehouse/
- Implement a Data Warehouse with Azure SQL Data Warehouse https://docs.microsoft.com/en-us/learn/paths/implement-sql-data-warehouse/
- Design a Data Warehouse with Azure SQL Data Warehouse https://docs.microsoft.com/en-us/learn/modules/design-azure-sql-data-warehouse/index

### Implement No-SQL Databases

 - manage data distribution and partitions (https://docs.microsoft.com/en-us/azure/architecture/best-practices/data-partitioning)
 - select the database platform (https://azure.microsoft.com/en-us/product-categories/databases/)
 - model data storage based on use cases (https://docs.microsoft.com/en-us/azure/architecture/guide/technology-choices/data-store-comparison)
 - select storage types (https://docs.microsoft.com/en-us/azure/architecture/guide/technology-choices/data-store-overview)
 - provision storage accounts (https://docs.microsoft.com/en-us/azure/storage/common/storage-quickstart-create-account?tabs=azure-portal)
 - provision Data Lake storage (https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-quickstart-create-account)
 - integrate WebHDFS applications with Data Lake Storage (https://docs.microsoft.com/en-us/rest/api/datalakestore/webhdfs-filesystem-apis)
 - provision in CosmosDB (https://docs.microsoft.com/en-us/azure/cosmos-db/how-to-manage-database-account)

References:
- Azure for the data engineer https://docs.microsoft.com/en-us/learn/paths/azure-for-the-data-engineer/
- Azure Cosmos DB Documentation https://docs.microsoft.com/en-us/azure/cosmos-db/
- Azure Storage Documentation https://docs.microsoft.com/en-us/azure/storage/
- Introduction to Azure Data Lake Storage Gen2 https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-introduction
- Introduction to Azure Data Lake storage https://docs.microsoft.com/en-us/learn/modules/introduction-to-azure-data-lake-storage/index
- Compare storage options for use with Azure HDInsight
https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-compare-storage-options
- Data partitioning strategies https://docs.microsoft.com/en-us/azure/architecture/best-practices/data-partitioning-strategies#partitioning-cosmos-db

### Implement Azure SQL Database

 - provision Azure SQL Database (https://docs.microsoft.com/en-us/azure/sql-database/sql-database-single-database-get-started)
 - configure elastic pools (https://docs.microsoft.com/en-us/azure/sql-database/sql-database-elastic-pool-manage)
 - configure data backup strategies (https://docs.microsoft.com/en-us/azure/sql-database/sql-database-automated-backups)
 - configure elastic jobs (https://docs.microsoft.com/en-us/azure/sql-database/elastic-jobs-overview)
 - provision Azure SQL database managed instance (https://docs.microsoft.com/en-us/azure/sql-database/sql-database-managed-instance-get-started)
 - configure connections (https://docs.microsoft.com/en-us/azure/sql-database/sql-database-server-level-firewall-rule https://docs.microsoft.com/en-us/azure/sql-database/sql-database-managed-instance-configure-vm https://docs.microsoft.com/en-us/azure/sql-database/sql-database-managed-instance-configure-p2s https://docs.microsoft.com/en-us/azure/sql-database/sql-database-connect-query)
 - manage data synchronization (https://docs.microsoft.com/en-us/azure/sql-database/sql-database-get-started-sql-data-sync)

References:
- Provision an Azure SQL database to store application data https://docs.microsoft.com/en-us/learn/modules/provision-azure-sql-db/
- Step-by-Step tutorials and learning materials
- Store Azure SQL Database backups for up to 10 years https://docs.microsoft.com/en-us/azure/sql-database/sql-database-managed-instance-index#step-by-step-tutorials-and-learning-materials
- Sync data across multiple cloud and on-premises databases with SQL Data Sync https://docs.microsoft.com/en-us/azure/sql-database/sql-database-sync-data

### Implement hybrid data scenarios

 - design hybrid solution (https://docs.microsoft.com/en-us/sql/sql-server/stretch-database/stretch-database?view=sql-server-2017)
 - design data replication and synchronization (https://docs.microsoft.com/en-us/azure/sql-database/replication-to-sql-database https://docs.microsoft.com/en-us/azure/sql-database/sql-database-high-availability https://docs.microsoft.com/en-us/azure/sql-database/sql-database-get-started-sql-data-sync)

References
- SQL Server Stretch Database Documentation https://docs.microsoft.com/en-us/azure/sql-server-stretch-database/
- Overview of Always On Availability Groups (SQL Server) https://docs.microsoft.com/en-us/sql/database-engine/availability-groups/windows/overview-of-always-on-availability-groups-sql-server?view=sql-server-2017

### Manage Azure DevOps Pipelines

 - use a build service (https://docs.microsoft.com/en-us/azure/devops/pipelines/process/tasks?view=azure-devops&tabs=yaml)
 - deploy using Azure Resource Manager templates (https://docs.microsoft.com/en-us/azure/devops/pipelines/tasks/deploy/azure-resource-group-deployment?view=azure-devops)

References
- Azure SQL database deployment https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/azure-sqldb?view=azure-devops&tabs=yaml
- How-To: CI/CD with App Service and Azure Cosmos DB https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/cosmos-db?view=azure-devops
- Service Fabric Application Deployment task https://docs.microsoft.com/en-us/azure/devops/pipelines/tasks/deploy/service-fabric-deploy?view=azure-devops
- Azure Resource Manager templates for Azure SQL Database https://docs.microsoft.com/en-us/azure/sql-database/sql-database-resource-manager-samples

## Manage and Develop Data Processing (30-35%)

### Implement big data environments

 - implement Hadoop clusters (https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-administer-use-portal-linux)
 - implement Databricks environment (https://docs.microsoft.com/en-us/azure/azure-databricks/quickstart-create-databricks-workspace-portal)

References
- What is Azure HDInsight and the Apache Hadoop technology stack https://docs.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-introduction
- What is Azure Databricks? https://docs.microsoft.com/en-us/azure/azure-databricks/what-is-azure-databricks

### Develop batch processing solutions

 - develop batch processing solutions using Spark (https://github.com/azure/aztk https://azure.microsoft.com/en-us/blog/on-demand-spark-clusters-on-docker/)
 - develop batch processing solutions using Azure Databricks (https://docs.azuredatabricks.net/delta/delta-batch.html#table-batch-reads-and-writes)

References
- Choosing a batch processing technology in Azure https://docs.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/batch-processing

### Develop streaming solutions

 - implement event processing using Azure stream analytics
 - query data using Azure Stream Analytics
 - configure Azure Stream Analytics to read from Event Hub
 - configure Azure Stream Analytics to read from BLOB storage

### Develop integration solutions

 - create data pipeline systems in Azure
 - develop data integration pipelines with Azure Data Factory
 - develop data integration pipelines with Azure Databricks

### Implement data migration

 - transform data
 - bulk load data with PolyBase

### Automate Data Factory Pipelines

 - deploy data factory pipelines
 - configure Data Factory

## Manage Data Security (15-20%)

### Manage source data access security

 - connect to sources
 - create connection objects
 - install Gateways

### Configure authentication and authorization

 - set up firewall rules
 - integrate Azure AD
 - design Cosmos DB security
 - design Data Lake security
 - design Azure SQL DB security
 - manage Access Control
 - manage permissions on resources

### Manage and enforce data policies and standards

 - mask data
 - encrypt data at rest
 - encrypt data in motion
 - encrypt data elements
 - configure audit

### Set up notifications

 - set up alerts on security threats
 - set up alerts on unexpected resource usage

## Monitoring Data Solutions (10-15%)

### Monitor data storage

 - implement BLOB storage monitoring
 - implement Data Lake Store monitoring
 - implement HDInsight monitoring

### Monitor databases for a specified scenario

 - implement SQL Database monitoring
 - implement SQL Data Warehouse monitoring
 - implement Cosmos DB monitoring

### Monitor data processing

 - design and implement Data Factory monitoring
 - monitor Azure Databricks
 - monitor HDInsight processing
 - monitor stream analytics

## Manage and Troubleshoot Azure Data Solutions (10-15%)

### Manage Optimization

 - troubleshoot data partitioning bottlenecks
 - optimize HIVE processing
 - optimize Data Lake
 - optimize SPARK processing
 - optimize Azure Stream Analytics
 - optimize Data Warehouse
 - optimize SQL DB
 - manage data life cycle

### Manage business continuity

 - implement a disaster recovery strategy
 - design for High Availability
 - import and export data
 - design a data retention policy
