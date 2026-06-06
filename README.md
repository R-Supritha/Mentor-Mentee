# Mentor-Mentee System

A **mentor–mentee management application** designed to facilitate communication, meeting scheduling, and task tracking between mentors and mentees. The project combines **C backend logic** with a **web-based frontend (HTML, CSS, JavaScript)** and a lightweight **Node.js server** for handling interactions.

---

## 📂 Project Structure

| File | Description |
|------|-------------|
| **login.cpp** / **login.html** | Handles user authentication for mentors and mentees. |
| **register.html** | Registration page for new users. |
| **mentor-home.html** / **mentee-home.html** | Dashboards for mentors and mentees. |
| **mentor-chatbox.html** / **mentee-chatbox.html** | Chat interfaces for communication. |
| **meetings.cpp** / **meetings.csv** | Meeting scheduling logic and storage. |
| **tasks.cpp** / **tasks.csv** | Task assignment and tracking. |
| **menteeslist.cpp** / **menteeslist.csv** | Maintains mentee records. |
| **mentors.csv** | Stores mentor details. |
| **messages.csv** | Stores chat messages. |
| **server.js** | Node.js server for backend communication. |
| **styles.css** | Styling for the web interface. |
| **sha256.c** / **sha256.h** | Implements SHA-256 hashing for secure password storage. |

---

## 🚀 Features

- **User Authentication**: Secure login and registration with SHA-256 hashing.
- **Mentor & Mentee Dashboards**: Separate views for mentors and mentees.
- **Meeting Scheduling**: Create, view, and manage meetings.
- **Task Management**: Assign and track tasks between mentors and mentees.
- **Chat System**: Simple message exchange stored in CSV files.
- **Cross-platform**: Combines C++ executables with a web-based interface.

---

## ⚙️ Installation & Setup

1. **Clone the repository**  
   ```bash
   git clone https://github.com/R-Supritha/Mentor-Mentee.git
   cd Mentor-Mentee
   ```

2. **Install Node.js dependencies**  
   ```bash
   npm install
   ```

3. **Run the server**  
   ```bash
   node server.js
   ```

4. **Compile C++ files (if needed)**  
   ```bash
   g++ login.cpp -o login
   g++ meetings.cpp -o meetings
   g++ tasks.cpp -o tasks
   g++ menteeslist.cpp -o menteeslist
   ```

5. **Open the application**  
   Launch `login.html` or `mentor-home.html` / `mentee-home.html` in your browser.

---

## 📊 Data Storage

- **CSV files** (`meetings.csv`, `tasks.csv`, `mentees.csv`, `mentors.csv`, `messages.csv`) are used for lightweight data persistence.
- **Executables** (`.exe`) demonstrate compiled versions of C++ modules for Windows users.

---

## 🔮 Future Improvements

- Replace CSV storage with a **database (MySQL/PostgreSQL)**.
- Add **real-time chat** using WebSockets.
- Improve UI with **Bootstrap/React**.
- Deploy on **Heroku/Netlify** for online access.

---

## 🤝 Contributing

Contributions are welcome! Fork the repo, create a branch, and submit a pull request to enhance features or fix bugs.

---

