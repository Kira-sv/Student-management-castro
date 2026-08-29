# Student Management Application
## Student Information
Name: Castro, Mark Angelo C
Course/Section: BSIT-Net Ad/ CCIS7E
## Project Description
This project is a simple Student Management Application
created using HTML, CSS, JavaScript, Node.js, and Express.js.
The application was developed and executed using
GitHub Codespaces.
## Features
- View students
- Add students
- Edit students
- Delete students
## Technologies Used
- HTML
- CSS
- JavaScript
- Node.js
- Express.js
- GitHub
- GitHub Codespaces
## Cloud Networking
The application runs inside GitHub Codespaces.
The Node.js server listens on port 3000.
GitHub Codespaces forwards the application port so
that the web application can be accessed through
a browser.
Cloud Networking • GitHub Codespaces • Shared Responsibility Page 17
## Cloud Security
Basic cloud security practices used in this activity include:
- No real student information was used.
- No passwords were stored in the source code.
- No API keys or credentials were committed.
- Port visibility was reviewed before sharing the application.
## Shared Responsibility Model
GitHub manages the underlying cloud infrastructure
used by GitHub Codespaces.
As the application developer, I am responsible for
the application code, repository access, credentials,
port configuration, and information stored or processed
by the application.
## Reflection Questions
### 1. What is the role of GitHub Codespaces in this activity?
GitHub Codespaces acts as the cloud-based development environment, which is akin to the Visual Studio Code running on the browser, wherein the code for the application is written and hosted without the requirement of installing any software locally.
### 2. What is the purpose of port 3000?
Port 3000 is used by Node.js/Express web server to listen for HTTP network requests that come to it through the network interface.
### 3. What may happen when the application port is made public?
Opening the port through which the application runs creates a URL through which the application is publicly available and can be accessed by any user on the Internet. This exposes the application to risks of being accessed by unauthorized persons.
### 4. Which parts of the environment are handled by GitHub
or the cloud provider?
GitHub manages the physical hardware, data centers, underlying infrastructure, physical networking, and the hosting platform for GitHub Codespaces.
### 5. Which parts are your responsibility as the
application developer?
As the developer, your role will include ensuring that the code for the application is your responsibility, repository access control management, port management, hard coding of any credentials, application configuration management, and management of the application’s data.
### 6. Why should passwords, API keys, and other secrets
not be uploaded to a public GitHub repository?
Open GitHub repositories are searchable and visible to everyone. Leakage of credentials or secrets may result in unauthorized access to systems, data leaks, unnecessary charges on accounts, or any malicious attacks against your infrastructure.
### 7. How does this activity demonstrate the
Shared Responsibility Model?
This highlights the fact that although the cloud service provider (GitHub) has to make sure of the security and maintenance of the cloud infrastructure and platform, it is the responsibility of the developer to secure his/her code, manage network permissions, application data and access credentials.
