# **Form Designing using Anvil Works**

## 📌 **Introduction**

This project demonstrates a complete **Form Submission System** built using **Anvil Works** — a powerful platform for developing full-stack web applications with nothing but Python. The system allows users to submit job applications through a custom-designed form, with validation, file uploads, and background processing.

---

## ✨ **Features**

* ✅ User-friendly form interface
* 🛂 Input validation & error handling
* 📄 File uploading functionality (e.g., resumes)
* 🔄 Background task processing to avoid client timeouts
* 📬 Success/Error notifications
* 📁 Stores submissions in Anvil Data Tables
* 📊 Retrieval function for displaying submitted applications

---

## 🔁 **Workflow**

1. **User fills out the form** (name, age, qualifications, skills, etc.)
2. **Frontend calls a server-side function** to validate and submit the application.
3. **Data is stored** in the `job_applications` data table.
4. A **background task** is automatically triggered to process the uploaded file asynchronously (e.g., check file size or scan content).
5. **Notifications** inform users of successful submission or specific errors.
6. An optional function allows **retrieval of all applications**, ordered by submission date.

---

## 🧩 **Project Structure Overview**

| Component               | Role                                               |
| ----------------------- | -------------------------------------------------- |
| **Client Form (Form1)** | Collects user data & handles UI interactions       |
| **Server Module**       | Validates, stores data & launches background tasks |
| **Background Task**     | Handles processing heavy operations asynchronously |
| **Data Table**          | `job_applications` — stores all submissions        |

---

## 🛠️ **Libraries & Modules Used**

* **anvil.server** — Handles client↔server communication
* **anvil.tables** — For interacting with Anvil data tables
* **anvil.media** — Manages file uploads
* **datetime** — Adds timestamp to submissions
* **anvil.Notification** — Displays notifications to users

---

## 🚀 **How to Use**

1. Clone the repository or fork the project.
2. Open the app in **Anvil IDE**.
3. Set up a **Data Table** named `job_applications` with appropriate columns.
4. Configure your **form fields** in the Anvil designer.
5. Click **Run** — submit test applications to see workflow in action.

---

## 🚀 **Application Link**


https://every-good-moose.anvil.app/

