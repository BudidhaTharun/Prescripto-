
---

Prescripto

Prescripto is a digital healthcare application that simplifies prescription management, enabling doctors to create and store prescriptions securely and patients to access their prescription history conveniently. Built with a modern tech stack, Prescripto leverages cloud storage and secure database solutions to provide a seamless, secure experience for users.


---

Table of Contents

1. Project Overview


2. Features


3. Tech Stack


4. Data Technologies


5. Installation


6. Usage


7. Contributing


8. License




---

Project Overview

Prescripto is a digital solution for healthcare providers and patients to manage and access prescriptions digitally. Doctors can create, update, and store patient prescriptions, while patients can view their prescription history and receive real-time updates on any new prescriptions added by their healthcare provider. Prescripto emphasizes data privacy and ensures the secure handling of patient information.


---

Features

Doctor Portal: Allows doctors to create, update, and manage patient prescriptions.

Patient Portal: Provides patients with easy access to their prescription history.

Image Upload: Doctors can upload images (e.g., prescription scans) securely using Cloudinary.

Secure Data Storage: All patient and prescription data is securely stored in MongoDB with encryption and access control.

Notifications: Patients are notified of new prescriptions or updates to existing prescriptions.



---

Tech Stack

Frontend: React.js

Backend: Node.js, Express.js

Database: MongoDB

Image Storage: Cloudinary

Authentication: JSON Web Tokens (JWT) for secure sessions



---

Data Technologies

1. MongoDB

Purpose: MongoDB serves as the primary database, storing all structured data related to prescriptions and patient profiles. It offers a flexible schema design, which is essential for managing healthcare data effectively.

Features Used: Document storage, indexing for fast access, and encryption for data security.


2. Cloudinary

Purpose: Cloudinary is used for secure image storage, enabling doctors to upload prescription images or other relevant documents.

Features Used: Image upload, storage, and URL generation for securely accessing images.


3. JWT (JSON Web Tokens)

Purpose: JWTs are used for authenticating users and maintaining secure sessions, ensuring that only authorized patients and doctors can access specific information.

Features Used: Token-based authentication, access control for API endpoints.



---

Installation

1. Clone the repository:

git clone https://github.com/username/Prescripto.git


2. Navigate to the directory and install dependencies:

cd Prescripto
npm install


3. Set up environment variables: Create a .env file with configurations for MongoDB URI, Cloudinary API keys, and JWT secrets.


4. Run the application:

npm start




---

Usage

Doctor Login: Doctors can log in to create and manage patient prescriptions, including uploading prescription images.

Patient Login: Patients can log in to view their prescription history and receive updates when new prescriptions are available.



---

Contributing

1. Fork the repository.


2. Create a new branch: git checkout -b feature-branch


3. Make your changes and commit them: git commit -m 'Add some feature'


4. Push to the branch: git push origin feature-branch


5. Open a pull request.


---
