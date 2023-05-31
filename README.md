# step 0

#### Step 1: Preparethe Data Infrastructure

##### **Create the data lake and upload data**

![1192ce4b-5a46-43eb-90a4-737bcbef3bf2](file:///C:/Users/lenuo01/Pictures/Typedown/1192ce4b-5a46-43eb-90a4-737bcbef3bf2.png)



##### Create an Azure Data Lake Storage Gen2

<img title="" src="file:///C:/Users/lenuo01/Pictures/Typedown/6378dace-02b6-4a42-a81b-46fef3529e25.png" alt="6378dace-02b6-4a42-a81b-46fef3529e25" style="zoom:150%;">

<img src="file:///C:/Users/lenuo01/Pictures/Typedown/6a10922d-b436-49ef-8098-9b982916804e.png" title="" alt="6a10922d-b436-49ef-8098-9b982916804e" style="zoom:150%;">

##### Uploadthese files from the [**project data**](https://video.udacity-data.com/topher/2022/May/6283aff5_data-nyc-payroll/data-nyc-payroll.zip) to the **dirpayrollfiles** folder

·         EmpMaster.csv

·         AgencyMaster.csv

·         TitleMaster.csv

·         nycpayroll_2021.csv

![15a789fe-453f-4205-9375-6860822a995a](file:///C:/Users/lenuo01/Pictures/Typedown/15a789fe-453f-4205-9375-6860822a995a.png)



##### Upload this file (historical data) from the [**projectdata**](https://video.udacity-data.com/topher/2022/May/6283aff5_data-nyc-payroll/data-nyc-payroll.zip) to the **dirhistoryfiles** folder

        nycpayroll_2020.csv

![282397ab-fb58-4eae-9b95-f6ba73719e58](file:///C:/Users/lenuo01/Pictures/Typedown/282397ab-fb58-4eae-9b95-f6ba73719e58.png)

##### **Create an Azure DataFactory Resource**

![03657d1d-6800-450c-8b13-9c09d844d2fd](file:///C:/Users/lenuo01/Pictures/Typedown/03657d1d-6800-450c-8b13-9c09d844d2fd.png)

![385817b3-b373-4707-8304-5054a077f5c9](file:///C:/Users/lenuo01/Pictures/Typedown/385817b3-b373-4707-8304-5054a077f5c9.png)



##### **Create a SQL Databaseto store the current year of the payroll data**

![3c27e68a-4f56-4e1a-a1a3-2c2d7151ae19](file:///C:/Users/lenuo01/Pictures/Typedown/3c27e68a-4f56-4e1a-a1a3-2c2d7151ae19.png)

##### **Create A SynapseAnalytics workspace, or use one you already have created**

![0cf2b11c-dc67-4765-9ce6-7775c7e67cef](file:///C:/Users/lenuo01/Pictures/Typedown/0cf2b11c-dc67-4765-9ce6-7775c7e67cef.png)

![d16b2c19-562b-42b6-8fa4-202c91265bd2](file:///C:/Users/lenuo01/Pictures/Typedown/d16b2c19-562b-42b6-8fa4-202c91265bd2.png)



![9b9f641b-b09c-465e-8561-165f9e29cd8d](file:///C:/Users/lenuo01/Pictures/Typedown/9b9f641b-b09c-465e-8561-165f9e29cd8d.png)

![c7f0fda8-b8ca-4d38-a451-e2f46cbb927a](file:///C:/Users/lenuo01/Pictures/Typedown/c7f0fda8-b8ca-4d38-a451-e2f46cbb927a.png)



![cd79c252-af40-4b78-88bc-1e0d70eea446](file:///C:/Users/lenuo01/Pictures/Typedown/cd79c252-af40-4b78-88bc-1e0d70eea446.png)



### Step 1: Prepare the DataInfrastructure

**Create thedata lake and upload data**

![52fbdc10-0c67-420e-81f4-a09ae54e70b5](file:///C:/Users/lenuo01/Pictures/Typedown/52fbdc10-0c67-420e-81f4-a09ae54e70b5.png)

![cd20f43d-fa80-4455-8b7d-b09b0ef53c69](file:///C:/Users/lenuo01/Pictures/Typedown/cd20f43d-fa80-4455-8b7d-b09b0ef53c69.png)

###### **Create an Azure DataFactory Resource**

![fb27225b-5abf-4154-83f8-fbb00ed2191f](file:///C:/Users/lenuo01/Pictures/Typedown/fb27225b-5abf-4154-83f8-fbb00ed2191f.png)

###### **Create a SQL Databaseto store the current year of the payroll data**

![b8a06091-6732-4faf-93c5-1dbc4eed7361](file:///C:/Users/lenuo01/Pictures/Typedown/b8a06091-6732-4faf-93c5-1dbc4eed7361.png)

![10eb5727-ded2-4d89-a7b1-50aab9a3bc9a](file:///C:/Users/lenuo01/Pictures/Typedown/10eb5727-ded2-4d89-a7b1-50aab9a3bc9a.png)

**Create A SynapseAnalytics workspace, or use one you already have created**

![10c560bc-aa5e-40c9-873f-d962af956ca4](file:///C:/Users/lenuo01/Pictures/Typedown/10c560bc-aa5e-40c9-873f-d962af956ca4.png)

![4914a1ae-08d6-4e3c-a2c5-4aa3167d59d1](file:///C:/Users/lenuo01/Pictures/Typedown/4914a1ae-08d6-4e3c-a2c5-4aa3167d59d1.png)

![18a1144f-4557-469e-a30f-ffbea6497440](file:///C:/Users/lenuo01/Pictures/Typedown/18a1144f-4557-469e-a30f-ffbea6497440.png)



##### ***Instructions: Create Linked Services**

### Step 2: Create LinkedServices

![a7f0fa11-b867-4ac8-a008-d735a61493e8](file:///C:/Users/lenuo01/Pictures/Typedown/a7f0fa11-b867-4ac8-a008-d735a61493e8.png)

 **Create a LinkedService to SQL Database that has the current (2021) data**

![0155cc67-8033-49bc-b4bf-1d76fdbade2b](file:///C:/Users/lenuo01/Pictures/Typedown/0155cc67-8033-49bc-b4bf-1d76fdbade2b.png)

![ad079ae6-d37e-4d71-a986-b98304c835b0](file:///C:/Users/lenuo01/Pictures/Typedown/ad079ae6-d37e-4d71-a986-b98304c835b0.png)

 **Create a LinkedService for Synapse Analytics**

![027cc388-bf47-4c02-990e-f884414b284f](file:///C:/Users/lenuo01/Pictures/Typedown/027cc388-bf47-4c02-990e-f884414b284f.png)

![e88a2b75-adb4-46f1-924b-ffeca3b1c785](file:///C:/Users/lenuo01/Pictures/Typedown/e88a2b75-adb4-46f1-924b-ffeca3b1c785.png)

## **Instructions: Create Datasets**

### Step 3: Create Datasetsin Azure Data Factory

![4b5cad73-5284-4043-9874-4cb58026c850](file:///C:/Users/lenuo01/Pictures/Typedown/4b5cad73-5284-4043-9874-4cb58026c850.png)



![194928ae-e04c-4dd5-b8ff-5d9341c5c76a](file:///C:/Users/lenuo01/Pictures/Typedown/194928ae-e04c-4dd5-b8ff-5d9341c5c76a.png)



![ca8e5e7a-1a05-4561-9497-d231f2f30cca](file:///C:/Users/lenuo01/Pictures/Typedown/ca8e5e7a-1a05-4561-9497-d231f2f30cca.png)



![121358b1-b21c-42dd-b3d2-2f380fd422c8](file:///C:/Users/lenuo01/Pictures/Typedown/121358b1-b21c-42dd-b3d2-2f380fd422c8.png)
**Instructions: Create Data Flows andPipelines**
================================================

### Step 4: Create DataFlows

![32886584-2e90-4b58-8449-3c67d17e6bcd](file:///C:/Users/lenuo01/Pictures/Typedown/32886584-2e90-4b58-8449-3c67d17e6bcd.png)



**1.In Azure Data Factory, create the data flow toload 2021 Payroll Data to SQL DB transaction table (in the future NYC will loadall the transaction data into this table).**

![50dda8a2-82fd-4815-a92e-4afa13fee9a0](file:///C:/Users/lenuo01/Pictures/Typedown/50dda8a2-82fd-4815-a92e-4afa13fee9a0.png)



**2.Create Pipeline to load 2021 Payroll data intotransaction table in the SQL DB**

![3b9e585f-44cd-4779-b09a-4f51569929d6](file:///C:/Users/lenuo01/Pictures/Typedown/3b9e585f-44cd-4779-b09a-4f51569929d6.png)



**3. Create data flows to load the data from thedata lake files into the Synapse Analytics data tables**

![0c89a1a2-3080-4f88-b2e3-0b9d47f9fa1b](file:///C:/Users/lenuo01/Pictures/Typedown/0c89a1a2-3080-4f88-b2e3-0b9d47f9fa1b.png)



![943a307c-dc2e-491a-9095-15046fce3212](file:///C:/Users/lenuo01/Pictures/Typedown/943a307c-dc2e-491a-9095-15046fce3212.png)

![57d516b3-9158-4442-9239-0bfc22820c3e](file:///C:/Users/lenuo01/Pictures/Typedown/57d516b3-9158-4442-9239-0bfc22820c3e.png)



**4. Create a data flow to load 2021 data from SQLDB to Synapse Analytics**

![68f8f531-cb5f-4fc1-bc14-ab9c30269963](file:///C:/Users/lenuo01/Pictures/Typedown/68f8f531-cb5f-4fc1-bc14-ab9c30269963.png)

 **5. Create pipelinesfor Employee, Title, Agency, and year 2021 Payroll transaction data to SynapseAnalytics containing the data flows**

![7bc586eb-63c5-4ef4-b3c3-4d0cea81887e](file:///C:/Users/lenuo01/Pictures/Typedown/7bc586eb-63c5-4ef4-b3c3-4d0cea81887e.png)

![9d5c2802-8993-484a-a80a-94b1b42c8c3b](file:///C:/Users/lenuo01/Pictures/Typedown/9d5c2802-8993-484a-a80a-94b1b42c8c3b.png)

**6. Trigger and monitor the Pipelines**

![fac41370-8dbe-44f5-b22c-94149752be96](file:///C:/Users/lenuo01/Pictures/Typedown/fac41370-8dbe-44f5-b22c-94149752be96.png)

**Instructions:Aggregate Data Flow**
====================================

### Step 5: Data Aggregation and Parameterization

**1.Create a Summary table in Synapse with the followingSQL script and create a dataset named table_synapse_nycpayroll_summary**

CREATE TABLE [dbo].[NYC_Payroll_Summary]( [FiscalYear] [int] NULL,[AgencyName] [varchar](50) NULL,[TotalPaid] [float] NULL )]( [FiscalYear] [int] NULL,[AgencyName] [varchar](50) NULL,[TotalPaid] [float] NULL )

**2.Create a newdataset for the Azure Data Lake Gen2 folder that contains the historical files**

![592e14ab-cf64-4fe9-b07e-cb3170f701f5](file:///C:/Users/lenuo01/Pictures/Typedown/592e14ab-cf64-4fe9-b07e-cb3170f701f5.png)



**3.Create new data flow and name it Dataflow Aggregate Data**

·         Create a data flow level parameter for Fiscal Year

·         Add first Source for table_sqldb_nyc_payroll_data table

·         Add second Source for the Azure Data Lake history folder

**4.Create a new Union activity in the data flow and Union with historyfiles**

**5.Add a Filter activity after Union**

·         In Expression Builder, enter `toInteger(FiscalYear) >= $dataflow_param_fiscalyear`

**6.Derive a new TotalPaid column**

·         In Expression Builder, enter `RegularGrossPaid + TotalOTPaid+TotalOtherPay`

**7.Add an Aggregate activity to the data flow next to the TotalPaidactivity**

·         Under Group By, Select AgencyName and Fiscal Year

**8.Add a Sink activity to the Data Flow**

·         Select the dataset to target (sink) the data into the SynapseAnalytics Payroll Summary table.

·         In Settings, select Truncate Table

**9.Create a new Pipeline and add the Aggregate data flow**

·         Create a new Global Parameter (This will be the Parameter at theglobal pipeline level that will be passed on to the data flow

·         In Parameters, select Pipeline Expression

·         Choose the parameter created at the Pipeline level

![99946690-98cc-439c-8889-d00abc9fdf0f](file:///C:/Users/lenuo01/Pictures/Typedown/99946690-98cc-439c-8889-d00abc9fdf0f.png)



**10.Validate, Publish and Trigger the pipeline.Enter the desired value for the parameter.**

![b49376cf-855b-4a12-9a98-c4a3f9ba2348](file:///C:/Users/lenuo01/Pictures/Typedown/b49376cf-855b-4a12-9a98-c4a3f9ba2348.png)



![f396cb2f-8233-481a-a103-1ddeeb053911](file:///C:/Users/lenuo01/Pictures/Typedown/f396cb2f-8233-481a-a103-1ddeeb053911.png)

![35a6657e-e571-419d-a679-1a2eba971a28](file:///C:/Users/lenuo01/Pictures/Typedown/35a6657e-e571-419d-a679-1a2eba971a28.png)



**Instructions:Connect Project to Github and Submit**
=====================================================

### Step 6: Connect your Project to Github

Inthis step, you'll connect Azure Data Factory to Github

·         Login to your Github account and create a new Repo in Github

·         Connect Azure Data Factory to Github

·         Select your Github repository in Azure Data Factory

·         Publish all objects to the repository in Azure Data Factory




