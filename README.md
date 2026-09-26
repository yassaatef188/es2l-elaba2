# 📞 Es2al Elaba2

> An interactive educational web application that allows users to explore questions and answers through a phone-call-style interface.

🌐 **Live Website:**  
https://yassaatef188.github.io/es2l-elaba2/

📂 **GitHub Repository:**  
https://github.com/yassaatef188/es2l-elaba2

---

## 📌 About the Project

**Es2al Elaba2** is an interactive web application designed to provide an engaging way to explore questions and answers using a simulated phone-call experience.

The application combines a virtual telephone keypad with audio instructions and video answers. Users can navigate through different categories, select questions using the keypad, listen to the corresponding audio, and watch video explanations.

The project was built as a lightweight, browser-based application without requiring a backend server.

---

## ✨ Features

- 📞 Interactive phone-call interface
- 🔢 Virtual telephone keypad
- 🎧 Audio-based navigation
- ❓ Multiple categories and questions
- 🎥 Video answers and explanations
- ▶️ Built-in video player
- 🔄 Navigation between questions and menus
- ☎️ Call-ending functionality
- ⌨️ Keyboard support for keypad navigation
- 🔁 Replay current menu functionality
- 📱 Responsive and simple user interface
- 🖼️ Custom project branding

---

## 🎮 How It Works

The application follows an **Interactive Voice Response (IVR)** style navigation system.

### 1. Start the Call

Click the **Start** button to begin the experience.

The application displays a short connection sequence before starting the main menu.

### 2. Main Menu

After the connection, the application plays an audio message containing the available options.

Users can select an option using the virtual keypad.

### 3. Select a Category

Each category contains a different group of questions.

Users can navigate between categories using the keypad.

### 4. Select a Question

After choosing a category, the application provides a list of questions.

Select a question by pressing its corresponding number.

### 5. Listen to the Answer

The application plays an audio explanation related to the selected question.

### 6. Watch the Video

When a video answer is available, the application automatically switches to the video screen.

Users can watch the answer and then click **Next** to continue.

### 7. Navigate or End the Call

Users can:

- Return to previous menus
- Replay the current menu
- Continue to another question
- Press `*` to end the call

---

## 🎧 Audio System

The application uses JavaScript to dynamically control audio playback.

Audio files are stored inside the `sounds` directory and are connected to different menus and questions through the application's IVR structure.

The application automatically:

- Starts the required audio
- Stops previously playing audio
- Moves to the next menu after the audio finishes
- Handles audio playback errors
- Provides audio-based navigation

---

## 🎥 Video System

Selected questions can display corresponding video answers.

The application dynamically loads the appropriate video and displays it using the HTML5 `<video>` element.

After watching a video, users can press **Next** to return to the appropriate menu.

---

## 🔢 Keypad Navigation

The application includes a virtual telephone keypad:

```text
1  2  3
4  5  6
7  8  9
*  0  #
```

### Special Keys

| Key | Function |
|-----|----------|
| `0` | Navigate to the main menu |
| `*` | End the call |
| `#` | Replay the current menu |

---

## ⌨️ Keyboard Controls

The application also supports keyboard input for easier navigation.

| Keyboard Key | Action |
|---------------|--------|
| `0 - 9` | Select a keypad option |
| `*` | End the call |
| `#` | Replay the current menu |
| `R` | Replay the current menu |
| `Enter` | Close the video and return to the menu |
| `Esc` | Close the video and return to the menu |

---

## 🛠️ Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript**
- **HTML5 Audio API**
- **HTML5 Video API**
- **Git**
- **GitHub**
- **GitHub Pages**

---

## 📂 Project Structure

```text
es2l-elaba2/
│
├── .github/
│   └── workflows/
│
├── images/
│   └── logo.jpeg
│
├── sounds/
│   ├── welcome.m4a
│   ├── list1.m4a
│   ├── list2.m4a
│   ├── outro.m4a
│   └── ...
│
├── index.html
│
└── README.md
```

---

## 🧩 Application Architecture

The application uses a JavaScript-based **IVR tree structure** to control the navigation flow.

Each menu can contain:

- An audio file
- Available keypad options
- A destination menu
- A video answer
- A next destination

This structure makes it easy to add new menus, questions, audio files, and video answers without changing the overall application architecture.

---

## 🚀 Running the Project Locally

### Clone the repository

```bash
git clone https://github.com/yassaatef188/es2l-elaba2.git
```

### Open the project

Navigate to the project directory:

```bash
cd es2l-elaba2
```

You can then open:

```text
index.html
```

directly in a modern web browser.

For the best development experience, you can also use **VS Code + Live Server**.

---

## 🌐 Live Demo

You can try the application directly from your browser:

### 👉 [Open Es2al Elaba2](https://yassaatef188.github.io/es2l-elaba2/)

No installation or setup is required.

---

## 📸 Project Preview

The application provides a phone-style interface with:

- Project logo
- Start button
- Virtual keypad
- Audio status
- Interactive menus
- Video answer screen

---

## 🎯 Project Goals

The project was created to demonstrate how a web application can combine different browser technologies to create an interactive experience.

The main goals were to:

- Practice JavaScript programming
- Work with events and user interactions
- Implement dynamic navigation
- Handle audio and video in the browser
- Organize application logic using a structured data model
- Build an interactive and user-friendly interface
- Deploy a static web application using GitHub Pages

---

## 👨‍💻 Developer

### Yassa Atef

Computer Science Student  
Faculty of Computers and Artificial Intelligence  
Cairo University

GitHub:  
https://github.com/yassaatef188

LinkedIn:  
https://www.linkedin.com/in/yassa-atef/

---

## 📚 Project Type

**Interactive Web Application**

Built using:

**HTML + CSS + JavaScript**

and deployed using:

**GitHub Pages**

---

## 📄 License

This project was created for educational and demonstration purposes.
