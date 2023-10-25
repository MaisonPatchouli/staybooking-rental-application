# Staybooking: Online Stay Rental Application

[![Demo](https://img.shields.io/badge/Demo-Live-brightgreen?style=for-the-badge)](https://prod.d1u6xpx3sk5u5j.amplifyapp.com/)

"Staybooking" is an online stay rental application aimed at offering users an intuitive, fast, and secure experience for short-term apartment bookings. The inception of this project stemmed from my keen interest in online platforms for short-term apartment bookings, wanting to delve deeper into the technical and business requirements of this domain.

## Features
- **User Authentication**: Token-based server-side user authentication using Spring Security.
- **Stay Management**: Facilitates uploading, deleting, searching, and reserving stays.
- **Geo-based Search**: Elasticsearch geo-indexing to support location-based stay searches.

## Technologies Used
- **Frontend**: React, AntD
- **Backend**: Spring Boot
- **Database**: MySQL, Google Cloud Storage
- **Search**: Elasticsearch for geo-based search
- **Deployment**: Google App Engine

## Technical Components:
1. **Frontend**:
   - A Single Page Application built using **React**, providing a smooth user interface and interaction experience.
   - To improve development efficiency, I opted for **AntD**, a mature React component library, offering a plethora of ready-to-use high-quality components.
  
2. **Backend**:
   - The backend services, built with **Spring Boot**, offer APIs for functionalities like accommodation upload, deletion, search, and booking.
   - These APIs ensure efficient interaction between the frontend and backend.
  
3. **Database & Storage**:
   - Given the structured nature of the data, I chose **MySQL** for storing user data and booking history.
   - For media files, such as property images, I use **Google Cloud Storage** ensuring efficient access speeds and data security.
  
4. **Search Functionality**:
   - Incorporated **Elasticsearch** for geo-indexing, making accommodation searches based on geographical locations simple and efficient.
  
5. **Security**:
   - To guarantee the security of user data, a token-based user authentication mechanism was implemented in the backend using **Spring Security**.
  
6. **Deployment & Scalability**:
   - To ensure high availability and scalability of the project, I deployed the backend services on **Google App Engine**.

A significant highlight of the project is its geographical search feature, realized through Elasticsearch, offering users an intuitive and efficient search experience. Furthermore, by integrating with Spring Security, the safety and privacy of user data are ensured.

## Future Plans:
- Further refine the frontend interface to enhance user experience.
- Introduce new features like
