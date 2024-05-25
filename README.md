# Historical Documents Repository

## Overview

The Historical Documents Repository is a digital archive designed to store, manage, and facilitate access to historical documents such as letters, speeches, videos, and images. Users can upload, search, view, edit metadata, and download documents. This application adheres to the Model-View-Controller (MVC) paradigm, ensuring a clean separation of concerns for enhanced maintainability and scalability.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Objectives](#objectives)
- [Architecture](#architecture)
- [Technology Stack](#technology-stack)
- [Images](#images)
- [Data Management](#data-management)
- [Disclaimer](#disclaimer)

## Features

1. **Document Upload**
    - Form-based document upload with metadata entry.
    - Secure storage of document files and metadata.

2. **Search Functionality**
    - Keyword-based search for quick document retrieval.
    - Category-based filtering for targeted searches.

3. **Document Viewing and Downloading**
    - Easy viewing of search results.
    - Direct downloading of documents.

4. **Edit Metadata**
    - User-friendly interface for editing document metadata.
    - Immediate reflection of metadata updates.

5. **Delete Documents**
    - Comprehensive document deletion, including metadata removal.

## Objectives

- Provide a centralized platform for storing and retrieving historical documents.
- Facilitate easy management and access to documents for educational and research purposes.
- Implement robust search functionality for efficient document location.

## Architecture

### Model-View-Controller (MVC) Paradigm

- **Model**: Manages data and business logic, including document storage, retrieval, updating, and deletion.
- **View**: Handles the presentation layer, displaying documents and metadata.
- **Controller**: Manages user input, processing requests, and rendering the final output.

## Technology Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask (Python micro web framework)
- **Database**: SQLAlchemy ORM with SQLite

## Images

![Login Screen](img/login.png)
![Home Screen](img/home.png)
![Upload Interface](img/upload.png)
![Search Results](img/search.png)
![Edit Metadata](img/edit.png)
![Download Interface](img/download.png)

## Data Management

- **Metadata Storage**: Managed using SQLAlchemy ORM for seamless database interaction.
- **Document Storage**: Documents are stored in server folders, organized by category or upload date.
- **Database Management**: SQLAlchemy interfaces with a relational database to store and manage metadata efficiently, supporting complex queries and enhancing performance.

## Disclaimer

This project cannot be executed due to the inclusion of confidential student and organizational information. Sensitive files and data were removed prior to upload to ensure privacy.

---

Feel free to reach out for more information or if you have any questions regarding the Historical Documents Repository.
