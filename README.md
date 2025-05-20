# 🕰️ Analog & Digital Clock using HTML, CSS, and JavaScript

A beautiful analog clock with a digital time display built using **HTML**, **CSS**, and **JavaScript**. This project demonstrates DOM manipulation, CSS positioning, and real-time clock synchronization using JavaScript's `Date` object.

---

## 📸 Preview

![Clock Preview](insert-preview-image-url-here)  
*(Replace this with a screenshot or GIF of your clock)*

---

## 🚀 Features

- ✅ Real-time analog clock with rotating hour, minute, and second hands.
- ✅ Embedded digital clock for precise time.
- ✅ Stylish and responsive UI.
- ✅ Color-coded time indicators for clarity.

---

## 🛠️ Technologies Used

- HTML5  
- CSS3  
- JavaScript (Vanilla)

---

## 📂 Project Structure

```plaintext
project-folder/
├── Index.html       # Main HTML file
├── Style.css        # Styling for the clock and layout
├── Script.js        # JavaScript logic for clock movement

🧠 Logic Behind the Clock Hands
📌 Hour Hand:
12 hours = 360°, so 1 hour = 30°

Additional rotation from minutes = 0.5° per minute
Formula: 30 * hours + 0.5 * minutes

📌 Minute Hand:
60 minutes = 360°, so 1 minute = 6°
Formula: 6 * minutes

📌 Second Hand:
60 seconds = 360°, so 1 second = 6°
Formula: 6 * seconds

