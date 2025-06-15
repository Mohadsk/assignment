# Web Form Management System

This is a simple web-based application for managing user data using **HTML, CSS, and JavaScript**. It allows users to:

- Login using a Gmail address
- Add new entries through a form
- View the list of submitted data
- Edit or delete existing entries
- Search/filter records in real-time
- View form data in read-only mode
- Validate input fields before submission

---

## 📁 Folder Structure

project-folder/
├── login.html
├── listpage.html
├── form.html
├── login.css
├── liststyle.css
├── form.css
├── script.js (optional if separated)
├── icons/
│ ├── view.png
│ ├── edit.png
│ └── delete.png

markdown
Copy
Edit

---

## 🚀 Features

### 1. Login Page
- Validates **username must end with `@gmail.com`**
- Password must be **at least 6 characters**
- Redirects to `listpage.html` on success

### 2. List Page
- Displays user-submitted records in a table format
- Includes:
  - **View** → read-only form
  - **Edit** → prefilled form in edit mode
  - **Delete** → removes entry
- **Search functionality** filters entries live

### 3. Form Page
- Used for both:
  - **Add New** (`Save` button)
  - **Edit** (`Update` button)
- All fields are **mandatory**
- Supports:
  - Text inputs
  - Dropdown (Department)
  - Date
  - Radio (Gender)
  - Checkbox (Hobbies)
- View mode disables form and shows selected hobbies below a label

---

## 🛠 Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**
- **LocalStorage** – for saving user data temporarily

---

## 📦 Setup Instructions

1. Clone or download the project files into a local folder.
2. Open `login.html` in a browser to start.
3. Use a Gmail-like username (e.g., `user@gmail.com`) and password (min 6 chars).
4. Add new entries, view/edit/delete them.
5. Data is stored in browser’s `LocalStorage`.

---

## 📝 Notes

- No backend used — all data is handled in the browser only.
- Refreshing the browser will **preserve** your data until LocalStorage is cleared.
- This is a **demo system** and not meant for production.

---

## 📧 Contact

Made with ❤️ by Shaikh Mohammad  
