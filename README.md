# 📝 React Contact Enquiry App (CURD Operation)

## 🖼️ Screenshot
Here is a preview of the Contact Enquiry App:
![Screenshot form](https://github.com/user-attachments/assets/3ab3b4bf-f724-4f7c-9e82-7e548b21d7fb)

This is a dynamic Contact Enquiry form built with **React**, allowing users to submit, update, and delete contact information. The form includes fields like Name, Email, Phone, and Message. Duplicate Email and Phone numbers are restricted using validation logic. A live data table displays all submissions and supports inline editing.




## 🚀 Features

✅ Add user enquiries (Name, Email, Phone, Message)  
🚫 Prevent duplicate Email or Phone numbers  
✏️ Update existing entries  
❌ Delete entries from the table  
📋 Live table rendering with dynamic state management  
🎯 Built using React functional components and **Hooks (`useState`)**  
🔔 Toast notifications for actions like delete or duplicate alerts (`react-toastify`)  
🎨 Styled with Bootstrap components  

---

## 📁 Project Structure

├── App.css
├── App.js
├── index.js
├── logo.svg


---

## 🧠 How It Works

### 1. `App.js`

- Maintains two main states:  
  - `formData` (for the input form)  
  - `userData` (list of submitted users)
- Includes form logic for:
  - Creating a new record
  - Editing an existing one
  - Validation against duplicate Email/Phone
- Uses `react-toastify` for user-friendly notifications

### 2. Data Table

- Displays all form submissions
- Provides inline **Update** and **Delete** buttons
- Reactively updates on any form interaction

---

## 💻 Usage

### ✅ To Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/rajat-chourasiya/react-enquiry-app.git
   cd react-enquiry-app

2. Install dependencies: 
        npm install

3.  Start the development server: 
        npm start

The app will run on http://localhost:3000

📌 Notes
Duplicate email or phone entries will trigger a toast error.

Clicking Update loads the user’s data into the form for editing.

All updates reflect instantly in the UI.

Notifications require react-toastify — ensure it's installed:

🛠️ Dependencies
React

React Bootstrap

React Toastify

