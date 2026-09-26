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
