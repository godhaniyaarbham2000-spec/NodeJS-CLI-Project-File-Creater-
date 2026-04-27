
# 📝 File Creator (Node.js CLI Tool)

A simple command-line based File Creator built using Node.js.  
This project allows users to create files by entering a filename and content through terminal input.

---

## 🚀 Features

* Create files from terminal input
* Accept custom filename from user
* Accept file content dynamically
* Automatically generates `.txt` file
* Displays success message after file creation

---

## 🛠️ Tech Stack

* Node.js
* JavaScript (ES Modules)
* File System (fs module)

---

## 📂 Project Structure
```
File Creator/
│── filecreater.js
│── package.json
│── package-lock.json
│── .gitignore
```
---

## ⚙️ Installation

Clone the repository:
```
git clone https://github.com/your-username/node-file-creator.git
cd node-file-creator
```
Install dependencies:
```
npm install
```
---

## ▶️ Usage

Run the project:
```
node filecreater.js
```
---

## 💻 Writing File

In this project, the user is prompted to enter a filename and content through the terminal.  
The application then creates a new `.txt` file with the given name and writes the provided content into it.

Process:

* User enters filename
* User enters file content
* Node.js creates a new file
* Content is written into the file
* Success message is shown

---

## 💻 Example

Enter your filename: test  
Enter the Content: hi arbham mer  
File "test.txt" created successfully  

---

## ⚠️ Notes

* File will always be created with `.txt` extension
* Ensure valid filename input

---

## 📌 Future Improvements

* Add delete file feature
* Add rename file feature
* Add folder creation support
* Add interactive CLI menu system

---

## 👨‍💻 Author

Arbham Godhaniya  
MERN Stack Developer
