# Note Taker Application

The **Note Taker** application is designed to help small business owners and individuals efficiently organize their tasks and thoughts. With a user-friendly interface and robust backend, it allows you to create, view, and delete notes seamlessly.

<br/>
<p align="center">
    <a href="https://nodejs.org/">
        <img alt="Node.js" src="https://img.shields.io/static/v1.svg?label=Node.js&message=JavaScript runtime&color=lightyellow" />
    </a>
    <a href="https://expressjs.com/">
        <img alt="Express.js" src="https://img.shields.io/static/v1.svg?label=Express.js&message=Web Framework&color=blue" />
    </a>
    <a href="https://www.render.com/">
        <img alt="Render (Deployment)" src="https://img.shields.io/static/v1.svg?label=Render&message=Deployment&color=red" />
    </a>
    <a href="https://www.npmjs.com/">
        <img alt="npm" src="https://img.shields.io/static/v1.svg?label=npm&message=Packages&color=lightblue" />
    </a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript">
        <img alt="JavaScript (ES6)" src="https://img.shields.io/static/v1.svg?label=JavaScript&message=ES6&color=violet" />
    </a>
    <a href="https://opensource.org/license/mit/">
        <img alt="MIT License" src="https://img.shields.io/static/v1.svg?label=License&message=MIT&color=lightgreen" />
    </a>
</p>
<br/>

## ✨ Features

- **Create Notes**: Add new notes with a title and body text.
- **View Notes**: Access a list of all saved notes in the sidebar.
- **Delete Notes**: Remove notes from the database (bonus feature).
- **Persistent Storage**: Notes are saved to and retrieved from a JSON file.

---

## 📋 Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Routes](#api-routes)
- [Starter Code](#starter-code)
- [Additional Resources](#additional-resources)
- [State Flow Diagram](#state-flow-diagram)
- [Contributing](#contributing)
- [License](#license)

---

## 🎥 Demo

Try the live application: [Note Taker App][live-application]

---

## 🚀 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/naturuplift/NoteTaker.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd NoteTaker
   ```

3. **Install dependencies**:
   ```bash
   npm install
   ```

4. **Verify Node.js and npm installation**:
   Make sure you have Node.js and npm installed on your system.

---

## ▶️ Usage

1. **Start the application**:
   ```bash
   npm start
   ```

2. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

3. **Application Flow**:
   - On the landing page, click "Get Started" to begin creating notes.
   - Add, view, and delete notes using the user-friendly interface.

   ![Landing Page](https://github.com/naturuplift/NoteTaker/assets/23546356/f7ab71c7-9a11-467f-809b-4e3d9f86dd6a)
   ![Note List and Form](https://github.com/naturuplift/NoteTaker/assets/23546356/e9a6f869-789d-4d7b-9f91-e13d85930bac)

---

## 🔄 API Routes

### **HTML Routes**

- `GET /notes`: Returns the `notes.html` file.
- `GET *`: Returns the `index.html` file.

### **API Routes**

- `GET /api/notes`: Retrieves all saved notes as JSON.
- `POST /api/notes`: Saves a new note to the database and returns it.
- `DELETE /api/notes/:id`: Deletes a note by its `id`.

### Test Routes with [Insomnia][insomnia]:
![Insomnia API Test](https://github.com/naturuplift/NoteTaker/assets/23546356/01d6524f-546d-4934-961e-b0450cb1b78f)

---

## 🔗 Starter Code

This project is based on the [Starter Code][starter-code]. Additional features and improvements have been added for enhanced functionality.

---

## 📚 Additional Resources

- [Node.js Documentation][node-doc]
- [Express.js Documentation][express-doc]
- [Render (Deployment Platform)][render]
- [Insomnia REST Client][insomnia]

---

## 🔍 State Flow Diagram

A visual representation of the application flow can be found here: [State Flow Diagram][state-flow]

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Commit your changes and push the branch.
4. Submit a pull request with a description of your changes.

Feel free to reach out or suggest ideas to make this application even better!

---

## 📜 License

This project is licensed under the [MIT License][MIT]. See the `LICENSE` file for details.

---

[live-application]: <https://notetaker-c6xh.onrender.com>
[node-doc]: <https://nodejs.org/en/docs/>
[render]: <https://dashboard.render.com/>
[express-doc]: <https://expressjs.com/>
[insomnia]: <https://insomnia.rest/>
[starter-code]: <https://github.com/coding-boot-camp/miniature-eureka>
[state-flow]: <https://github.com/naturuplift/NoteTaker/blob/main/assets/Note%20Taker%20State%20Diagram%20v1.png>
[MIT]: <https://github.com/naturuplift/NoteTaker/blob/main/LICENSE>
