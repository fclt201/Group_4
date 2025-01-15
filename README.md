# Overview

A repository containing information on a hospital database which is designed to store, organise, and manage hospital-related files. 

Please see a more detailed descriptions of the database components below.

# Table of contents

•	File descriptions
•	Table descriptions
•	Usage instructions
•	Query descriptions

## File descriptions

The repository is made up of the following files:
•	‘code_for_tables’ is a file which contains the SQL codes used to create tables for the hospital database.
•	‘QueriesFlowchart.pdf’ is a file which contains the flow chart planning for SQL queries.
•	‘Relationship planning and pseudocode.docx’ is a file which contains: entity and relationship plans for tables, an entity relationship diagram showing the relationship between tables, pseudocode for MS Access queries.
•	‘queries_for_ms_access_and_mysql.txt’ is a file which contains all the SQL query codes used for mySQL and MS Access
•	‘mysql_query_outputs.txt’ is a file which shows all outputs from the mySQL queries used.
•	‘team_portfolio.zip’ is a zipped folder which contains the meeting minutes, agenda, and action plans noted during group meetings to discuss the creation of the database.

## Table descriptions

•	The 'hospitals' table contains details on 40 hospitals, including information on: hospital ID, hospital name, hospital address, hospital size (number of beds), hospital type, whether the hospital provides emergency services, and year of accreditation.
•	The 'doctors' table contains details on 100 doctors, including information on: doctor ID, doctor name, doctor’s date of birth, doctor’s address, as well as the name and ID of the hospital the doctor works at.
•	The 'patients' table contains details on 600 patients, including information on: patient ID, patient name, patient’s date of birth, patient’s address, as well as the ID and name of the doctor in which the patient is registered to.
•	The 'medications' table contains details on 30 medications, including information on: medication ID, medication name, medication category, and the pharmaceutical company in which the medication comes from.
•	The 'prescriptions' table contains details on 500 prescriptions, including information on: prescription ID, the name and ID of the patient in which the prescription is given to, the name and ID of the medication prescribed, the name and ID of the doctor who gave the prescription, as well as the prescription date.
•	The 'diseases' table contains details on relevant medications used to specific diseases, as well as details on doctors which specialise in dealing with Rach disease.
•	The 'appointments' table stores details on individual appointments that are currently scheduled.
•	The 'lab_results' table stores details on patient lab tests, including: test results, and the name of the doctor who requested the test.

## Usage instructions

•	To clone the repository, use the following command: git clone https://github.com/StephMbaka/Group_4
•	When adding files, place the files in the appropriate directory, then commit the changes

## Query descriptions

•	Retrieve a list of all doctors based at a particular hospital. 
•	Retrieve a list of all prescriptions for a particular patient, ordered by prescription date. 
•	Retrieve a list of all prescriptions that a particular doctor has prescribed. 
•	Retrieve a list of all prescriptions ordered by the patient’s name alphabetically. 
•	Add a new patient to the database, and register the patient to one of the doctors. 
•	Modify the address details of an existing patient. 
•	Retrieve a list of all patient names and addresses for patients registered to doctors based at one particular hospital.
•	Retrieve a list of all doctors based at teaching hospitals which were accredited between 2015-2024. 
•	Retrieve a list of all patients who may have a particular disease, based on which medication they have been prescribed.
•	Retrieve a list of all doctors who specialize in a particular disease. 
•	Retrieve a list all lab results for all patients over the age of 60. 
•	Retrieve a list of all appointments for a given patient. 
•	Retrieve a list of all appointments for a given doctor. 
•	Retrieve a list of all prescriptions made from a particular hospital, ordered alphabetically by the name of the medication being prescribed.
•	Retrieve a list of all lab results from all hospitals that were accredited between 2013-2020. 
•	Identify which doctor has made the most prescriptions. 
•	Retrieve a list of all doctors at the hospital with the biggest size (determined by most number of beds). 
•	Retrieve a list of all hospitals which were accredited prior to 2015, and do have Emergency Service facilities. 
•	Retrieve a list of patients registered with doctors, who are based at hospitals with less than 400 beds. 
