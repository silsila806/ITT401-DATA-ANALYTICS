# Introduction and statistics for data analytics
## Text Books
1. Data Science and Big Data Analytics: Discovering, Analyzing, Visualizing and
Presenting Data. Wiley Publishing(1st. ed.). 2015.
2. Thomas Erl, Wajid Khattak, and Paul Buhler. Big Data Fundamentals: Concepts,
Drivers &Techniques. Prentice Hall Press, USA.(1st. ed.). 2016.
3. Michael Berthold and David J. Hand. Intelligent Data Analysis: An Introduction
Springer-Verlag, Berlin, Heidelberg.(1st. ed.). 1999

## Course Contents and Lecture Schedule
Introduction and statistics for data analytics 7 Hours
1. Introduction and evolution of data analytics (Text1: 1.1, 1.1.2, 1.2) 1
2. Data Analytics Lifecycle (Text1: 2.1 -2.7) 1
3. Types of data analytics (descriptive, prescriptive, predictive, diagnostic) (Text2: 1) 1
4. Statistical Methods for Evaluation (Text1: 3.3) 2
5. Resampling (Text3: 2.6) 2

### 1.1 Introduction and evolution of data analytics

#### What is Big data?
> Big Data is data whose scale,distribution, diversity, and/or timeliness require the use of new technical
architectures and analytics to enable insights that unlock new sources of business value.

*McKinsey & Co.; Big Data: The Next Frontier for Innovation, Competition, and Productivity*

McKinsey’s definition of Big Data implies that organizations will need new data architectures and analytic sandboxes, new tools, new analytical methods, and an
integration of multiple skills into the new role of the data scientist.

Three attributes stand out as defining Big Data characteristics:
* **Huge volume of data**: Rather than thousands or millions of rows, Big Data can be billions of rows and millions of columns.
* **Complexity of data types and structures**: Big Data reflects the variety of new data sources, formats, and structures, including digital traces being left on the web and
other digital repositories for subsequent analysis.
* **Speed of new data creation and growth**: Big Data can describe high velocity data, with rapid data ingestion and near real time analysis.

Big data can come in multiple forms, including structured and non-structured data such as financial data, text files, multimedia files, and genetic mappings. Four main types of data structures are,
* **Structured data**: Data containing a defined data type, format, and structure (that is, transaction data, online analytical processing [OLAP] data cubes, traditional
RDBMS, CSV files, and even simple spreadsheets).
* **Semi-structured data**: Textual data files with a discernible pattern that enables parsing (such as Extensible Markup Language [XML] data files that are selfdescribing
and defined by an XML schema).
* **Quasi-structured data**: Textual data with erratic data formats that can be formatted with effort, tools, and time (for instance, web clickstream data that may contain
inconsistencies in data values and formats). 
* **Unstructured data**: Data that has no inherent

#### Discuss the analyst Perspective on Data Repositories.
* **Spreadsheets and data marts (“spreadmarts”)**: 
  - Spreadsheets and low-volume databases for recordkeeping 
  - Analyst depends on data extracts.
* **Data Warehouses**: 
  - Centralized data containers in a purpose-built space
  - Supports BI and reporting, but restricts robust analyses
  - Analyst dependent on IT and DBAs for data access and schema changes
  - Analysts must spend significant time to get aggregated and disaggregated data extracts from multiple sources.
* **Analytic Sandbox (workspaces)**:
  - Data assets gathered from multiple sources and technologies for analysis
  - Enables flexible, high-performance analysis in a nonproduction environment; can leverage in-database processing
  - Reduces costs and risks associated with data replication into “shadow” file systems
  - “Analyst owned” rather than “DBA owned”
 
 > There are several things to consider with Big Data Analytics projects to ensure the approach fits with the desired goals. Due to the characteristics of Big Data, these projects lend themselves to decision support for high-value, strategic decision making with high processing complexity. 
 The analytic techniques used in this context need to be iterative and flexible, due to the high volume of data and its complexity.
 Performing rapid and complex analysis requires high throughput network connections and a consideration for the acceptable amount of latency.
 
 #### What are the State of the Practice in Analytics?
 Current business problems provide many opportunities for organizations to become more analytical and data driven. Four categories of common business problems that organizations
contend with where they have an opportunity to leverage advanced analytics to create competitive advantage. 
* **Optimize business operations**: Sales, pricing, profitability, efficiency
* **Identify business risk**: Customer churn, fraud, default
* **Predict new business opportunities**: Upsell, cross-sell, best new customer prospects
> Organizations have been trying to reduce customer churn, increase sales, and cross-sell customers for many years. What is new is the opportunity to fuse advanced
analytical techniques with Big Data to produce more impactful analyses for these traditional problems.
* **Comply with laws or regulatory requirements**:Anti-Money Laundering, Fair Lending, Basel II-III,Sarbanes-Oxley (SOX)
> Many compliance and regulatory laws have been in existence for decades, but additional requirements are added every year, which represent additional complexity and data
requirements for organizations. Laws related to anti-money laundering (AML) and fraud prevention require advanced analytical techniques to comply with and manage properly.
Rather than only performing standard reporting on these areas, organizations can apply advanced analytical techniques to optimize processes and derive more value from these common tasks.

##### Compare BI with Data Science.

Figure 1.8  Data Science and Big Data Analytics: Discovering, Analyzing, Visualizing and Presenting Data. Wiley Publishing(1st. ed.). 2015.

##### Explain the Current Analytical Architecture.

Figure 1.9  Data Science and Big Data Analytics: Discovering, Analyzing, Visualizing and Presenting Data. Wiley Publishing(1st. ed.). 2015.

##### What are the drivers of Big data?

* Medical information, such as genomic sequencing and diagnostic imaging
* Photos and video footage uploaded to the World Wide Web
* Video surveillance, such as the thousands of video cameras spread across a city
* Mobile devices, which provide geospatial location data of the users, as well as metadata about text messages, phone calls, and application usage on smart phones
* Smart devices, which provide sensor-based collection of information from smart electric grids, smart buildings, and many other public and industry infrastructures
* Nontraditional IT devices, including the use of radio-frequency identification (RFID) readers, GPS navigation systems, and seismic processing

##### Explain Emerging Big Data ecosystems.

* **Data devices** and the “Sensornet” gather data from multiple locations and continuously generate new data about this data.
* **Data collectors** include sample entities that collect data from the device and users.
* **Data aggregators** make sense of the data collected from the various entities from the “SensorNet” or the “Internet of Things.”
* **Data users and buyers** directly benefit from the data collected and aggregated by others within the data value chain

Figure 1.11 Data Science and Big Data Analytics: Discovering, Analyzing, Visualizing and Presenting Data. Wiley Publishing(1st. ed.). 2015.
