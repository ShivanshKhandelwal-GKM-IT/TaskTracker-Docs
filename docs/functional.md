# Functional Requirements Documentation

---

## 1. Functional Requirements

| ID   | Requirement          | Description |
|------|----------------------|-------------|
| **FR1** | **User Registration** | New users can sign up using **email and password**. |
| **FR2** | **User Login** | Secure login with session management and a **Remember me** option. |
| **FR3** | **Create Task** | Authenticated users can add tasks with **title**, **description**, and **due date**. |
| **FR4** | **Edit Task** | Users can edit any field of an existing task; **updates** sync instantly. |
| **FR5** | **Delete Task** | Tasks can be permanently deleted with a **5-second undo** option. |
| **FR6** | **Mark Complete** | One-tap toggle between **Complete** and **Incomplete** states. |
| **FR7** | **View Tasks** | Dashboard displays **All** tasks. |
| **FR8** | **Real-Time Sync** | Updates are pushed instantly across **all connected devices**. |
| **FR9** | **Mobile Support** | Fully **responsive interface** with offline caching and installation support (PWA). |
| **FR10** | **User Logout**   | Ends the user session and **redirects** to the Login Screen. |

---

## 2. Non-Functional Requirements

| ID   | Requirement        | Description |
|------|-----------------|-------------|
| **NFR1** | **Performance** | The app should load user tasks within **2 seconds**. |
| **NFR2** | **Usability** | UI must be simple, intuitive, and user-friendly for non-technical users. |
| **NFR3** | **Security** | Only authenticated users can access their tasks and data. |
| **NFR4** | **Reliability** | The app should handle **network loss** gracefully and sync once reconnected. |
| **NFR5** | **Scalability** | The system should handle **multiple concurrent users** efficiently. |
| **NFR6** | **Maintainability** | Code should be **modular, reusable, and well-documented** for easy updates. |
| **NFR7** | **Testability** | Application should support **automated UI, API, and mobile testing**. |

---

**Next:** [Use Cases →](usecase.md)
