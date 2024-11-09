# CS340_Module_Two_Assignment_Noah_Khomer
CS 340 MongoDB CRUD Assignment
Course: CS 340 – Client/Server Development
Assignment: MongoDB CRUD Operations
Author: Noah Khomer
Date: November 8th, 2024

Overview
This repository contains the completed MongoDB CRUD assignment for the CS 340 Client/Server Development course. The assignment demonstrates CRUD (Create, Read, Update, Delete) operations using MongoDB on a dataset of city inspection records. This project provides hands-on experience with MongoDB commands, JSON document manipulation, and database operations within the MongoDB shell.

Contents
CS340_Module_Two_Assignment_Noah_Khomer.docx: A Word document containing screenshots and explanations for each step of the assignment, as outlined in the instructions.
README.md: Documentation providing an overview of the project, instructions, and a summary of challenges faced.
Project Details
Objectives
Data Import: Load a JSON dataset (city_inspections.json) into MongoDB using the mongoimport tool.
Querying Data: Use MongoDB’s find() command to retrieve specific documents based on unique IDs, result types, and business names.
Inserting New Documents: Insert a new document into the inspections collection to simulate adding a new business entry.
Updating Documents: Update specific fields of a document based on ID, including adding comments and changing business status.
Deleting Documents: Remove documents based on specific criteria to manage data cleanliness and accuracy.
Key MongoDB Commands
Data Import: mongoimport
Database Selection: use city
Querying: find(), distinct(), and countDocuments()
Inserting: insertOne()
Updating: updateOne(), updateMany()
Deleting: deleteOne()
Instructions for Use
Environment Setup: This project was completed using the Apporto virtual lab environment provided by SNHU. Ensure MongoDB is properly set up and running in your environment.

Executing Commands:

Open the MongoDB shell (mongosh) to connect to the database.
Run the provided CRUD commands as outlined in the Word document to interact with the dataset.
Reviewing Results:

The Word document includes screenshots for each step, verifying that the commands were executed successfully and showing the output of each CRUD operation.
Challenges and Solutions
Syntax Errors: Initially encountered syntax errors when importing data and running commands in the Linux terminal. Switching to mongosh resolved these issues.
Complex Queries: Writing queries to retrieve specific data and handle nested JSON structures was challenging. Proper use of JSON structure and syntax helped in managing subdocuments effectively.
Updating and Deleting: Ensuring the correct documents were updated or deleted required careful query writing to avoid unintended changes in the dataset.
Conclusion
This project provided valuable experience with MongoDB’s CRUD operations, error troubleshooting, and the unique structure of JSON-based databases. The skills gained through this assignment are foundational for working with NoSQL databases and handling real-world data.
