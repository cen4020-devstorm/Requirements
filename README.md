# Software Requirements Specifications
## 1. Purpose Statement  

The purpose of this **Software Requirements Specification (SRS)** is to define the functional and non-functional requirements for the **SAFE Team Web Application** at the **University of South Florida (USF)**. This document serves as a reference for the **DevStorm development team**, project stakeholders, and future developers who may maintain or expand the system. The SRS outlines the system’s objectives, features, constraints, and expected performance to ensure the final product meets user needs and integrates effectively with existing campus operations.  

## 2. Overview  

This SRS provides a structured overview of the **SAFE Team system’s objectives, features, and requirements**:  
- **Introduction** – Background, purpose, and objectives.  
- **System Features** – Real-time tracking, notifications, and ride management.  
- **Product Requirements** – Functional and non-functional specifications.  
- **System Design Considerations** – Technical choices and scalability.  

This organization ensures a clear and comprehensive understanding of the system.  

## 3. Product Perspective  

The SAFE Team web application aims to **enhance and modernize USF’s current phone-based ride request system** by introducing **real-time tracking, wait time estimates, and notifications**. It operates independently but aligns with **USF’s campus safety and transportation services**. While not dependent on other software, it may integrate with **Google Maps API** for location tracking, improving service efficiency and user experience.  

## 4. Functional Requirements

Category      | Priority | The system shall...
--------------|---------|------------------------------------------
Mandatory     | 1       | Allow students to request SAFE Team rides through a web interface.
Mandatory     | 2       | Provide real-time tracking of SAFE Team vehicles.
Mandatory     | 3       | Send notifications when a ride is nearby.
Mandatory     | 2       | Display estimated wait times based on ride availability.


For a detailed list of functional requirements, view them in the [Functional Requirements Board](https://github.com/orgs/cen4020-devstorm/projects/3/views/3?filterQuery=-role%3A%22Non-functional%22&visibleFields=%5B%22Title%22%2C170702992%2C170703498%2C170704266%2C170704320%2C170704058%2C170704441%2C%22Status%22%5D)  

## 5. Non-Functional Requirements

Category      | Priority |  Requirements
--------------|---------|------------------------------------------
Mandatory     | 1       | Availability: The system must ensure high availability and minimal downtime.
Mandatory     | 2       | Usability: The system must provide an intuitive and user-friendly interface.
Mandatoru     | 3       | Security: The system must support a secure authentication system for user accounts.
Mandatory     | 3       | Capacity: The system must be able to handle an increasing number of users without significant degradation.

For a detailed list of non-functional requirements, view them in the [Non-Functional Requirements Board](https://github.com/orgs/cen4020-devstorm/projects/3/views/4?filterQuery=role%3A%22Non-functional%22&visibleFields=%5B%22Title%22%2C%22Status%22%2C170703498%2C170702992%2C170703837%2C170704058%5D)

## 6. Defined Terms  

- **SAFE Team** – A student-operated service providing on-campus transportation at USF.  
- **Dispatchers** – SAFE Team staff responsible for managing ride requests.  
- **ETA (Estimated Time of Arrival)** – The predicted time when a ride will arrive.  
- **Real-Time Tracking** – Live GPS-based updates on vehicle locations.  

## 7. References  

- University of South Florida SAFE Team website: [USF SAFE Team](https://www.usf.edu/student-affairs/student-government/tampa-sg/tampa-safeteam/index.aspx)  
- Google Maps API Documentation: [Google Maps API](https://developers.google.com/maps/documentation)  
- Ruby on Rails Documentation: [Ruby on Rails Guide](https://guides.rubyonrails.org/)  

## 8. End-User Characteristics  

- **Students** – Primary users requesting rides; expected to have basic web navigation skills.  
- **Dispatchers** – SAFE Team staff managing rides; must be able to operate a simple web-based system.  
- **Campus Safety Staff** – May oversee operations; technical expertise varies.  

## 9. Constraints  

- Must be compatible with **modern web browsers** (Chrome, Firefox, Safari, Edge).  
- Must integrate **Google Maps API** for live location tracking.  
- Must adhere to **USF’s data security policies**.  
- Development must be completed by **April 30** (end of the semester).  

## 10. Standards  

- **Programming Language** – Ruby on Rails for backend, JavaScript (HTML/CSS) for frontend.  
- **Version Control** – Git and GitHub for source code management.  
- **Coding Standards** – Follow Ruby on Rails best practices and web accessibility guidelines.  

## 11. Assumptions  

- Users will access the system via **desktop or mobile browsers**.  
- The system will be hosted on a **cloud-based platform** like Heroku or AWS.  
- Google Maps API will be used for **GPS tracking**.  
- USF SAFE Team operations will remain **phone-based as a backup option**.  
