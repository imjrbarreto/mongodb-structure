# mongodb-structure
S2.03: Data structure - MongoDB

**Description**
NoSQL database modeling project for an optical shop called **Cul d'Ampolla**.
The goal is to represent the management of clients, employees, glasses, sales, and suppliers using MongoDB documents.

## 🛠 Technologies

* Database: MongoDB
* Visual tool: MongoDB Compass
* Data format: JSON

## 🚀 Database import

No application installation or build process is required. MongoDB Community Server and MongoDB Compass must be available locally.

1. Clone the repository
git clone https://github.com/imjrbarreto/mongodb-structure.git
cd mongodb-structure

2. Connect to MongoDB
Open MongoDB Compass and connect using:
mongodb://localhost:27017

3. Create the databases
Create the following databases:
cul_ampolla_client_view
cul_ampolla_glasses_view

Create these collections inside each database:
clients
employees
glasses
sales
suppliers

4. Import the JSON files
For each database:

Open the corresponding collection in MongoDB Compass.
Select Add Data → Import JSON or CSV file.
Select the JSON file with the same name as the collection.
Choose JSON as the file type.
Complete the import.

