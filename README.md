# README – Azure Databricks Practical Guide (Beginner-Friendly, No Code)

## A) BIG DATA ANALYTICS

### 1. Create Azure Databricks Workspace
- Go to Azure Portal.
- Click "Create a resource".
- Search for Azure Databricks.
- Select subscription, resource group, region, and pricing tier.
- Click "Review + Create" → "Create".

### 2. Launch Databricks Workspace
- Open Databricks resource.
- Click "Launch Workspace".

### 3. Create a Compute (Cluster)
- Inside Databricks → open "Compute".
- Click "Create Compute".
- Select runtime version, node size, and auto-termination.

### 4. Create a Notebook
- Workspace → Create → Notebook.
- Choose language (Python recommended).
- Attach notebook to your cluster.

### 5. Explore Data (Conceptual)
- Load data into a table (CSV, Excel, JSON, etc.).
- View the first few rows.
- Inspect columns and quality.
- Prepare data for cleaning.

### 6. Perform Data Operations (Conceptual)
- Filter rows.
- Select columns.
- Remove missing values.
- Add new computed columns.
- Group and summarize data.
- Join datasets.

### 7. Create Visualizations
- Display table → click chart icon.
- Choose chart types (bar, line, pie, etc.).

---

## B) NOTEBOOKS & CLUSTERS

### 1. Access Databricks Workspace
- Open through Azure Portal → Launch Workspace.

### 2. Create & Start Compute
- Compute tab → Create Compute → Start the cluster.

### 3. Create Notebook
- Workspace → Create → Notebook.

### 4. Attach Notebook to Cluster
- Select active compute from the notebook header.

### 5. Notebook Features
- Add multiple cells.
- Write markdown.
- Visualize outputs.
- View execution history.

---

## C) DATA TRANSFORMATIONS

### 1. Load Data
- Load CSV, Excel, JSON, or ADLS files.

### 2. Inspect Data
- Preview rows.
- Check column names.
- Check data types and missing values.

### 3. Clean Data
- Remove or replace missing values.
- Standardize date formats.
- Format text.
- Remove extra characters.

### 4. Modify Columns
- Add new computed columns.
- Rename columns.
- Convert data types.

### 5. Aggregate Data
- Count records.
- Calculate averages and totals.
- Group by categories.

### 6. Join DataFrames
- Merge datasets based on a common column.

---

## D) INTEGRATION WITH DATA LAKE & SYNAPSE

### 1. Create Storage Account
- Enable hierarchical namespace (Data Lake Gen2).

### 2. Create Containers
- raw → unprocessed input data  
- curated → cleaned and transformed  
- gold → final ready-for-reporting data  

### 3. Upload Files
- Upload CSV, Excel, JSON, etc., into the raw container.

### 4. Get Storage Access Key
- Storage Account → Access Keys → Copy Key1.

### 5. Configure Databricks to Connect with ADLS
- Add the storage key into Databricks configuration.

### 6. Access Containers
- List raw, curated, and gold data.

### 7. Read Data from ADLS
- Load files as DataFrames for cleaning and analytics.

### 8. Write Processed Data Back to ADLS
- Save cleaned/transformed data into curated or gold layers.

### 9. Connect with Synapse Analytics
- Synapse reads data from ADLS for SQL queries, pipelines, and Power BI.

