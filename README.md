# i3_typing_master
i3 typing master midterm

# Typing Master Project

## Overview
Typing Master is a web app where users can test how fast and accurately they type. It has pages for signing up, logging in, resetting password, doing typing tests, checking results, and an About Us page.

## Pages Included
1. First/Landing Page — made by me
2. User Register Page — made by classmates
3. Password Reset Page — made by classmates
4. Login Page — made by classmates
5. Test Results Page — made by classmates
6. Typing Test Page — made by classmates
7. About Us Page — made by me

---

## How to Setup, Compile, and Run the Project Locally

### Requirements
- A modern web browser (Chrome, Firefox, Edge, etc.)
- (Optional but recommended) A simple HTTP server (such as VSCode Live Server extension or Python's built-in server)

### Steps

#### 1. Download or Clone the Project
- Download the ZIP from your repository or use Git:
  ```
  git clone <your-repo-url>
  ```
- Extract or open the folder on your computer.

#### 2. Open the Project Folder
- Open the folder in your file explorer or in Visual Studio Code.

#### 3. Run the Project

**Option 1: Open Directly in Browser**
- Double-click `index.html` to open it in your browser.
- _Note: Some features (like saving/loading data) may not work perfectly due to browser security restrictions when opening files directly._

**Option 2: Use a Local Server (Recommended)**
- Open a terminal/command prompt in the project folder.
- If you have Python 3 installed, run:
  ```
  python -m http.server 8000
  ```
  Or with Python 2:
  ```
  python -m SimpleHTTPServer 8000
  ```
- Open your browser and go to: [http://localhost:8000](http://localhost:8000)
- All features will work as expected.

**Option 3: Use VSCode Live Server**
- If you use Visual Studio Code, install the "Live Server" extension.
- Right-click `index.html` and select "Open with Live Server".

---

### How to Use the App

- Use the navigation bar to move between pages.
- Register a new user, then log in.
- Take the typing test and view your results.
- Try the password reset page (demo only, no real emails sent).

---

## Technologies Used

- HTML for structure
- CSS for styling
- JavaScript for interactivity and saving data in the browser (localStorage)

---

## Notes

- All data (like test results) is saved in your browser only.
- There is no backend or database.
- Password reset is for demonstration and does not send real emails.