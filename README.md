# Quantum Mail

A web-based email client for managing multiple email accounts from a single application.

<!-- screenshots to be added -->

### Features

* 📬 **Multiple accounts** — Connect and manage multiple email accounts from one interface
* ✉️ **Email management** — Send, receive, reply to, forward, delete, move, and favorite messages
* 📎 **Attachments** — Send and download file attachments
* 🔎 **Search** — Dynamically search messages by subject or content
* 👥 **Address book** — Automatically save recipients and use them for quick composition
* 🔐 **Authentication** — User registration and secure login
* ⚙️ **Account management** — Add and remove accounts with Google or manual configuration
* 🎨 **Customization** — Choose from multiple color themes and font styles
* 🖥️ **Flexible composer** — Move, resize, minimize, and maximize the compose window

### Tech Stack

**Frontend**

React · Vite · JavaScript · Fetch API

**Backend**

Java · Spring Boot · Spring Security · Spring Data JPA · Hibernate · Maven

**Database & Email**

PostgreSQL · Jakarta Mail · Simple Java Mail · Jsoup · JWT

<br />

## Getting Started

### Requirements

* Java
* IntelliJ IDEA

### Installation

1. Clone or download the repository.
2. Open the project in IntelliJ IDEA.
3. Start the frontend using the `frontend` configuration.
4. Start the backend using the `backend` configuration.
5. Open http://localhost:5137/ in your browser.

After starting both applications, the login page should be available.

### Architecture

Quantum Mail consists of two main components:

* **Frontend** — React application responsible for the user interface and client-side interactions.
* **Backend** — Spring Boot REST API responsible for authentication, email processing, database access, and communication with external mail providers.

### Notes

Email accounts must support **POP or IMAP**. Google accounts can also be connected through the built-in Google integration.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for the full license text.
