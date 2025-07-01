# Internship Request Management System - La Poste Tunisienne

This project is a web application for managing internship requests, developed as part of an internship at the Training Department of La Poste Tunisienne. The goal of this application is to digitize and streamline the process of submitting and managing internship applications, which was previously handled manually.

----------
## 🌟 Overview

The application provides a user-friendly platform for students to submit their internship requests online and for administrators to efficiently manage the assignment of students to available supervisors. It also centralizes the management of supervisors, student profiles, and the coordination between supervisors and accepted interns.

----------
## ✨ Features

### For Students:

-   **User Authentication**: Secure registration and login for students.
    
-   **Profile Management**: Students can view and update their personal information and password.
    
-   **Internship Application Submission**: An intuitive form to submit internship requests, including personal information and necessary documents (internship request, assignment letter).
    
-   **Application Status Tracking**: Students can track the status of their application (pending, accepted, refused, in progress, completed).
    
-   **Document Download**: Ability to download important documents such as the response form and the end-of-internship certificate.
    
-   **Responsive Design**: A fully responsive interface for an optimal experience on desktops, tablets, and smartphones.
    

### For Administrators (Manager):

-   **Internship Request Management**: View, sort, filter, and process all submitted internship applications.
    
-   **Intern Assignment**: Assign approved interns to the appropriate supervisors based on availability and field of study.
    
-   **Supervisor and Post Location Management**: View and manage the list of available supervisors and internship locations.
    
-   **Automated Email Notifications**: The system automatically sends emails to students to confirm receipt, acceptance, or rejection of their applications.
    
-   **PDF Generation**:
    
    -   Automatically generate a response form upon acceptance of an internship request.
        
    -   Generate and send the end-of-internship certificate upon successful completion of the internship.
        
-   **Advanced Filtering**: Advanced search and filtering options to efficiently manage internship requests based on status, period, and other criteria.
    
----------
## 🛠️ Technologies and Tools

### Frontend

-   **Angular 17**: A robust and high-performance framework for building modern user interfaces.
    
-   **HTML5, CSS3, TypeScript**: For structuring and styling the application.
    
-   **Font-Awesome**: For a wide range of customizable icons.
    
-   **ngx-extended-pdf-viewer**: To display PDF documents directly in the application.
    

### Backend

-   **Node.js (v18.17.0)**: A fast and scalable server-side JavaScript runtime environment.
    
-   **Express.js**: A web framework for Node.js to create robust APIs.
    
-   **MySQL**: A reliable and high-performance relational database management system.
    
-   **Bcrypt**: For secure password hashing.
    
-   **Jsonwebtoken (JWT)**: For user authentication via tokens.
    
-   **Multer**: For handling file uploads.
    
-   **Nodemailer**: For sending automated emails.
    
-   **pdf-lib**: For generating and manipulating PDF documents.
    

### Database

-   **MySQL**: Used with XAMPP for a local development environment.
    
-   **phpMyAdmin**: For database administration.
    

### Development Tool

-   **Postman**: For testing, debugging, and documenting the API.
    

----------
## 🚀 Getting Started

### Prerequisites

-   Node.js and npm
    
-   Angular CLI
    
-   XAMPP (or any other Apache/MySQL server)
    

## 🖼️ Screenshots

### Student part 

**Login Interface**  
<div align="center">
<img src="https://github.com/user-attachments/assets/bee393bb-cca7-4652-a96b-4b4848f8b72d" />
</div><br>

----------

**Registration Interface**  
<div align="center">
<img src="https://github.com/user-attachments/assets/5e94a5bc-4ac0-4668-9d57-5b983480ada1" />
</div><br>


<div align="center">
<img src="https://github.com/user-attachments/assets/88d1db16-3512-4893-9894-ebbb69e876e2" />
</div><br>

----------

**Submit Page**  
the application page that allows adding a new internship request. On this page, the user can choose the type of internship, specify the desired location and region, add the internship period, attach the internship request file in PDF format, then submit the application.  
<div align="center">
<img src="https://github.com/user-attachments/assets/c63f7af1-4543-4765-b0bd-5a80519782c8" />
</div><br>

----------

**Response Page**

1. Waiting page after the submission of an internship request  
<div align="center">
<img src="https://github.com/user-attachments/assets/b5d207a8-c146-4073-a69c-9e2f3e67c266" />
</div><br>


2. Refusal interface  
<div align="center">
<img src="https://github.com/user-attachments/assets/3afada0e-eef9-4288-84eb-3a9fd2bd9577" />
</div><br>


3. Acceptance interface and sending of the assignment letter  
<div align="center">
<img src="https://github.com/user-attachments/assets/54e809ec-db19-4dc1-ad9c-8f39c692617c" />
</div><br>


4. waiting page for the final confirmation  
<div align="center">
<img src="https://github.com/user-attachments/assets/c9df696f-786a-4f09-a795-fbbd72c99c38" />
</div><br>


5. final acceptance page  
<div align="center">
<img src="https://github.com/user-attachments/assets/f301297e-63df-479d-90a9-18c92fc5591c" />
</div><br>


6. Certificate request page  
<div align="center">
<img src="https://github.com/user-attachments/assets/a7771328-d427-4b11-ad48-196cf8398726" />
</div><br>


7. waiting page for the certificate  
<div align="center">
<img src="https://github.com/user-attachments/assets/1c84f7d6-dcb5-4f38-b3ec-0fb23aadc040" />
</div><br>


8. page to download the certificate  
<div align="center">
<img src="https://github.com/user-attachments/assets/d196360f-48f5-46e2-89a8-2131c04eceaa" />
</div><br>

----------

**list of internship requests**  
<div align="center">
<img src="https://github.com/user-attachments/assets/50fc01b9-0c3d-414e-b94a-4ce4caa2f26b" />
</div><br>

----------

**Profil Page**  
<div align="center">
<img src="https://github.com/user-attachments/assets/de1b6ce2-2ce0-45ae-95ba-4b18b6c0cab5" />
</div><br>

----------
----------

### Admin part 

**Page of the List of all Internships**  
<div align="center">
<img src="https://github.com/user-attachments/assets/30e5d88a-804e-4514-813a-387e96a54ef5" />
</div><br>

----------

**Filter for search**  
<div align="center">
<img src="https://github.com/user-attachments/assets/8e8e54a7-4da6-4427-8b78-00336eead76d" />
</div><br>

----------

**Stage Status in the Filter**  
<div align="center">
<img src="https://github.com/user-attachments/assets/2cc06da3-a165-466e-89dc-919d60594ad4" />
</div><br>

----------

**Pending Internship Request List Page**  
<div align="center">
<img src="https://github.com/user-attachments/assets/b9222d8e-73cd-4a9b-9ef0-4e220a03de15" />
</div><br>

----------

**Page of the List of all Current Internships**  
<div align="center">
<img src="https://github.com/user-attachments/assets/8fcf6a9e-66bc-415f-b241-9a69240d9bbd" />
</div><br>

----------

**Sidebar of the "the posts office" page**  
<div align="center">
<img src="https://github.com/user-attachments/assets/6ff78dc5-56c4-4e23-9faf-fb7b05acda60" />
</div><br>

----------

**Page of the List of all supervisors**  
<div align="center">
<img src="https://github.com/user-attachments/assets/aa76cd37-4074-489e-8bb7-5aca3367ccd0" />
</div><br>

----------

**Page of the List of all places of "the post office"**  
<div align="center">
<img src="https://github.com/user-attachments/assets/fff3f4f3-94e1-418c-985e-36da574ccf11" />
</div><br>

----------

**Supervisor’s Profile Page**  
<div align="center">
<img src="https://github.com/user-attachments/assets/995e1759-bc98-4081-9a9b-1a4826168588" />
</div><br>

----------

**Page de Profil du Lieu de la Poste**  
<div align="center">
<img src="https://github.com/user-attachments/assets/453a9b19-4979-4100-a072-89b4faae4ae6" />
</div><br>

----------

**Specific internship request page**  
<div align="center">
<img src="https://github.com/user-attachments/assets/c84116bc-0e54-4b68-92a1-b5e3b00139b7" />
</div><br>


<div align="center">
<img src="https://github.com/user-attachments/assets/6fac2e8b-6ce7-41a6-81df-7e48e9b7378a" />
</div><br>

----------


**Internship acceptance POP-UP with Generation and Sending of the Response form**  
<div align="center">
<img src="https://github.com/user-attachments/assets/746d53ca-6f3c-41b0-8365-9117ef1e7d3e" />
</div><br>

----------

**POP-UP of Generation and Sending of the End of internship certificate**  
<div align="center">
<img src="https://github.com/user-attachments/assets/38726e48-386b-446f-a6c0-7ed03d3f4398" />
</div><br>

----------

**POP-UP of verification of fiche_de_reponse.PDF**  
<div align="center">
<img src="https://github.com/user-attachments/assets/58f1f40e-da0e-4443-9832-2fd7669d3e0f" />
</div><br>

----------

**POP-UP verification of Attestation.PDF**  
<div align="center">
<img src="https://github.com/user-attachments/assets/eb9a009f-3d0c-4d69-934b-46ad5c8d0f84" />
</div><br>

----------

**email of response has requested an internship**  
<div align="center">
<img src="https://github.com/user-attachments/assets/cc432bbb-5a5f-467e-8336-afc17128e6f9" />
</div><br>

----------

**Interface of the internship request is completed**  
<div align="center">
<img src="https://github.com/user-attachments/assets/864908a0-f258-4115-b75d-97465d31a4d8" />
</div><br>


----------
----------

###Responsivity  
<div align="center">
<img src="https://github.com/user-attachments/assets/c34c3362-9a93-4200-ad63-cff02ea6acf8" />
</div><br>


<div align="center">
<img src="https://github.com/user-attachments/assets/a71bae75-b5b6-4847-9b31-5eeae46fbd3d" />
</div>





----------
## 👨‍💻 Author

**Lounissi Montassar**

-   [LinkedIn](https://www.google.com/search?q=https://www.linkedin.com/in/your-linkedin-profile)
    
-   [GitHub](https://www.google.com/search?q=https://github.com/your-username)
