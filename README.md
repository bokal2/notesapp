# **Notes App**

A fully functional **Note-Taking Application** that allows users to **Create**, **Read**, **Update**, and **Delete** (CRUD) notes. This app is built with **React** and leverages **AWS Amplify** for authentication, backend integration, and seamless deployment.

---

## **Features**

- **User Authentication**: Secure sign-up, login, and logout functionality powered by AWS Amplify.
- **CRUD Operations**: Create, view, edit, and delete notes effortlessly.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Scalable Deployment**: Deployed on AWS Amplify for high availability and scalability.

---

## **Tech Stack**

- **Frontend**: React (with Hooks for state management and routing)
- **Backend**: AWS Amplify for authentication and API integration
- **Hosting**: AWS Amplify Hosting

---

## **Getting Started**

### **1. Prerequisites**

Ensure you have the following installed:
- **Node.js** (v14+ recommended)
- **npm** or **yarn**
- **AWS CLI**
- **Amplify CLI**: Install with:
  ```bash
  npm install -g @aws-amplify/cli
  ```

---

### **2. Clone the Repository**

Clone the project to your local machine:
```bash
git clone https://github.com/bokal2/notesapp.git
cd notesapp
```

---

### **3. Install Dependencies**

Install the required dependencies:
```bash
npm install
# or
yarn install
```

---

### **4. Configure AWS Amplify**

Initialize Amplify and configure the backend:
```bash
amplify init
```
Follow the prompts to:
- Set your project name and environment.
- Choose your AWS region.
- Authenticate with your AWS account.

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
