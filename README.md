Download Link: https://assignmentchef.com/product/solved-lab-3-of-7-database-design-using-visio-and-based-on-data-requirements-and-business-rules
<br>
Lab Overview–Scenario/Summary

TCOs:

2. Given a situation containing entities, business rules, and data requirements, create the conceptual model of the database using a database modeling tool.

3. Given an existing relational database schema, evaluate and alter the database design for efficiency.

4. Given an existing database structure demonstrating efficiency and integrity, design the physical tables.

<strong>Scenario </strong>

You have been asked to create a database model using MS Visio Database Model Diagram Template. The purpose of this lab is to provide experience designing, with limited instructions, a simple database based on a list of data requirements and associated business rules. You will then complete an MS Access database based on the model developed in Visio, creating the necessary tables and relationships. Upon completing this lab, you will be able to

1. create a new Visio file for database design;

2. using the data requirements and the business rules provided, develop a conceptual model (ERD), including attribute data types and required field lengths; and

3. create a new MS Access database based on the ERD.

<strong>D. Deliverables </strong>

Section Deliverable Points Part A Step 7 YourNameLab3.vsd (Visio Diagram) Part B Step 3 YourNameLab3.accdb (Access Database)

<strong>E. Lab Steps</strong>

Page 2 of 6 Preparation

1. If you are using Citrix for MS Visio and/or MS Access, follow the login instructions located in the iLab tab in Course Home. Lab Part A: Create a Visio ERD from Data Requirements and Business Rules

Step 1: Open Visio

a. Open Microsoft Office, Visio application or

b. If you are using Citrix, click on Microsoft Office Applications folder to start Visio.

Step 2: Identify and create the entities

1. Open a new blank Database Model Diagram. If you need assistance with this, refer to the Week 1 Lab Instructions. Be sure that all options are set consistent to those used in previous weeks so that you generate your model in Crows Foot notation.

2. Save the file as YourName_Lab3.vsd.

3. Based on the information provided below, create the necessary entities for the Pages in Time database. If you need assistance to create the entities, refer to labs from Weeks 1 and 2. Pages in Time Pages in Time is a small bookstore carrying a variety of books. The owners have decided to computerize the books available through the store so that they can determine more easily what books are on hand and which books need to be special ordered to meet customer needs. Because customers do not always remember the name of a desired book, the owners want to be able to look for books by author or by type (genre). They also want to be able to find the publisher’s information using the system so that they can order books more easily. After visiting with the owners, you have gathered the following information on data requirements and business rules to develop a conceptual design (ERD), prepare it for conversion to an Access database, and then create the actual database.

DATA REQUIREMENTS

You have determined that you will need at least the following entities to resolve the relationships that exist in the data. CUSTOMERS ID Name (store data in its smallest parts) Address (store data in its smallest parts) Phone: E-mail Address Preferred Contact Method ORDERS Number Date Received Date Customer Contacted (Yes or No) BOOKS ISBN Number Title Purchase Price Year Published Fiction or Nonfiction Type (Genre) In stock AUTHOR ID Name (store data in smallest parts!) Short Biography PUBLISHER ID Name Address Phone number Contact Person Fax Number Website Step 3: Identify and create attributes (fields)

NOTE: Because you are creating your diagram in Visio, it will be easier to create the attributes prior to the relationships. a. Refer to the data requirements from

Step 2 of this lab.

If you have not already created the attributes (fields) in your ERD, add them at this time.

b. Be sure that you store data in its smallest parts.

c. Save your file, and continue to Step 4.

Step 4: Identify and designate the keys

a. Determine whether an attribute exists in each table that will satisfy the requirements of a primary key. If no appropriate field exists, create a field for this purpose.

b. Check the Primary Key property for the field in each table using the Visio column properties.

Step 5: Identify the relationships

a. Using the information below on the business rules for Pages in Time, create the relationships between the entities created in Step 2. b. Notice that when Many-to-Many relationships exist, you will need to create associative entities. If you are not sure of the process to create relationships in Visio, refer to the Labs for Weeks 1 and 2. You created an associative entity in Week 2. c. For any associative entities created, enter necessary fields. You may also need to designate or create a primary key. BUSINESS RULES Business rules help determine the relationships between data that should help you design the relationships between your entities.

1. Each customer can place many orders over time, but each order is placed by only one customer.

2. Each order may include many books, and a book may be included on many orders.

3. Each book may have multiple authors, and each author may have written multiple books.

4. Each book has only one publisher, but a publisher may publish many books.

Step 6: Determine and specify the data types

a. Using the information below, select the data type for each attribute (field) in your diagram, and set the type in the attribute properties. (Refer to the Week Page 5 of 6 2 Lab if you are not sure how to do this. Where allowed, estimate the field length needed.) As the data types and field lengths are not included in the data requirements, you should make a selection based on your knowledge of the type of data and approximation of length required. The Visio and Access data type equivalents are shown below: Access Visio Number Integer Text Text Memo LongText Date/Time DateTime Currency Currency Yes/No Binary AutoNumber Long Hyperlink No equivalent–use Text Step 7: Modify the Visio Settings to show the Data type and field size in the diagram. a. Change your Visio settings so that these appear on the actual diagram. To do this, go to the Database ribbon, Display Options. In the Display Options dialog box, select the Table tab. You will then change the data types to Show Physical. Click the OK button to apply the new setting. They data types will then appear in your diagram. Note that you may need to move the entities so that they are easily viewed as they are now larger. b. Be sure to save the final version of your file. End of Part A Part B: Create the Access Database from the ERD Preparation Open the Visio file created in Part A of this lab, you will reference this file in Part B. Page 6 of 6 Step 1: Start MS Access and Open a New Blank Database. a. Create a new Blank Database; refer to the Week 2 Lab for more detailed instructions. b. Save the database as YourNameLab3. c. Note: If you are unsure how to complete any steps in this iLab, refer to the previous week’s iLabs. Step 2: Create the Tables a. Based on the Visio diagram from Part A, create the tables for your database. b. Enter the field names and the data type. c. Designate the primary keys for each table d. Set the attribute properties as needed for a. Field length b. Required Step 3: Create the relationships a. Open the database relationships window. b. Based on the Visio diagram from Part A, create the relationships for your database. c. Be sure to enforce referential integrity for each relationship. Save your file. End of Part B Lab 3 Final Deliverables a. YourNameLab3.vsd (Visio Diagram)–from Lab 3 Part A b. YourNameLab3.accdb (Access Database)–from Lab 3 Part B Submit these files to the Week 3 iLab Dropbox. END OF LAB