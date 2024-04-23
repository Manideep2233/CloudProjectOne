**Project Title: EMS with MongoDB & Azure Blob Storage:**

**Description:**
This project is an Employee Management System developed using Spring MVC, Thymeleaf, MongoDB, and Azure Blob Storage. It allows users to upload CSV files containing information about people, such as name, state, salary, grade, room, telephone number, keywords, and image URL. The data from CSV files is stored in MongoDB for CRUD (Create, Read, Update, Delete) operations, and users can perform filtering based on salary, keywords, and other criteria. When adding a new person, the profile image is saved in Azure Blob Storage and fetched from Azure for display.

**Features:**
- **CSV File Upload:** Users can upload CSV files containing people information.
- **Database Integration:** Data from CSV files is stored in MongoDB for efficient CRUD operations.
- **Filtering:** Users can filter employee records based on salary, keywords, and other attributes.
- **Azure Blob Storage Integration:** Profile images are saved in Azure Blob Storage and fetched from Azure for display.
- **CRUD Operations:** Users can add new people, update existing records, and delete employee profiles.

**Technologies Used:**
- Spring MVC: Framework for building web applications using the Model-View-Controller architecture.
- Thymeleaf: Template engine for server-side Java applications, facilitating dynamic content generation.
- MongoDB: NoSQL database for storing and managing unstructured data efficiently.
- Azure Blob Storage: Cloud-based object storage solution for storing large amounts of unstructured data, such as images.

**Installation Instructions:**
1. Clone the repository to your local machine.
2. Ensure that MongoDB is installed and running on your system.
3. Set up an Azure Blob Storage account and obtain the necessary credentials.
4. Import the project into your preferred IDE.
5. Configure the MongoDB connection settings and Azure Blob Storage credentials in the application properties.
6. Run the application to start the server

Changes to make in Code for running it: https://www.mongodb.com/products/platform/cloud
go to this url and signup and host your MongoDB and update it in spring application, in application.properties
and go to the Azure account and create your blob and provide the connection string in the code.(Controller class) and update the image fetching link which accessing the images.

spring.data.mongodb.uri=mongodb+srv://root:root@cluster0.crkygpz.mongodb.net/test

**Usage:**
1. Upload a CSV file containing people information using the provided interface.
2. View and manage employee records through the web interface.
3. Use the filtering options to narrow down search results based on salary, keywords, and other criteria.
4. Add new people to the database, with profile images saved in Azure Blob Storage.
5. Update existing records or delete employee profiles as needed.



**Contributing:**
Contributions to the project are welcome! Feel free to submit bug reports, feature requests, or pull requests to help improve the Employee Management System.
