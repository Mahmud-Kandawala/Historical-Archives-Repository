# Historical Documents Repository

The Historical Document Repository aims to serve as a digital archive for historical documents such as letters, speeches, videos, and images. The application will allow users to upload, search, view, and download documents. It will also support editing metadata and deleting outdated documents. This project will utilize the Model-View-Controller (MVC) paradigm to ensure a clean separation of concerns, making it maintainable and scalable.

# Images

<img src="img/login.png" alt="Image 1" style="width: 100%; height: auto;" />
<img src="img/home.png" alt="Image 2" style="width: 100%; height: auto;" />
        <img src="img/upload.png" alt="Image 3" style="width: 70%; height: auto;" />
        <img src="img/search.png" alt="Image 4" style="width: 70%; height: auto;" />
        <img src="img/edit.png" alt="Image 5" style="width: 70%; height: auto;" />
<img src="img/download.png" alt="Image 6" style="width: 100%; height: auto;" />


## Objectives
-	To provide a centralized platform for storing and retrieving historical documents.
-	To facilitate easy management and access to historical documents for educational and research purposes.
-	To implement robust search functionality to easily locate documents based on keywords or categories.


## Programming Paradigm: MVC (Model-View-Controller)
-	Model: Manages the data and business logic. For this project, the model will handle the storage, retrieval, updating, and deletion of document data and metadata.
-	View: Displays data (the user interface). Views will present documents and metadata in an easy-to-navigate format.
-	Controller: Handles user inputs and interacts with the model to render the final output. Controllers will manage the workflow for document uploads, searches, edits, and deletions.


## Application Features and Functionalities

1) **`Document Upload`**
    -	Interface: A form to upload document files and enter metadata (e.g., title, author, date).
    -	Storage: Documents will be stored in a designated server folder, while metadata will be saved in a CSV file.

2) **`Search Functionality`**
    -	Search by Keywords: Users can search documents by keywords in the metadata.
    -	Search by Categories: Users can filter documents based on predefined categories like document type, era, or author.

3) **`Document Viewing and Downloading`**
    -	Viewing: Users can view a list of documents that match their search criteria.
    -	Downloading: Documents can be downloaded directly from the repository.

4) **`Edit Metadata`**
    -	Editable Fields: Users can edit metadata for each document, such as title or author.
    -	Updates: Metadata updates are reflected immediately in the CSV file.

5) **`Delete Documents`**
    -	Deletion: Users can delete documents. This includes both the document file and its associated metadata.


## Data Management
-	Metadata Storage: Metadata will be managed using SQLAlchemy, an ORM (Object Relational Mapping) library, to facilitate easy interaction with the database.
-	Document Storage: Actual document files will be stored in a folder on the server, organized by categories or upload date for easy retrieval.
-	Database Management: SQLAlchemy will interface with a relational database to store and manage all metadata efficiently, allowing for complex queries and better performance.


## Technology Stack
-	Frontend: HTML, CSS, & JavaScript
-	Backend: Flask, a Python micro web framework, used for server-side logic. 
-	Database: SQLAlchemy ORM for database management, interfacing with SQLite.
  

## Note
Regrettably, this project cannot be executed due to the presence of confidential student and organizational information. Prior to uploading, certain files and data had to be carefully removed
