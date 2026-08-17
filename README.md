# 🗣️ Kanye Says... Quote Generator Application

A fun desktop application built with Python's `tkinter` and the `requests` library. Connects directly to the public Kanye Rest API to generate and display random quotes directly on screen with a single click.

---

## 📌 Features

* **Live API Integration:** Fetches real-time quotes dynamically using `requests` from `https://api.kanye.rest`.
* **Interactive UI:** Custom GUI featuring a speech bubble canvas and a clickable icon button trigger.
* **Text Auto-Wrapping:** Renders quote responses dynamically centered within the speech bubble graphic using canvas text boundary constraints.

---

## 🛠️ Prerequisites & Setup

### 1. Requirements
* Python 3.x installed.
* `requests` library.

### 2. Directory Structure & Assets
Ensure the required PNG assets are present in the same directory as your script:

```text
kanye-quotes-app/
│
├── main.py
├── background.png   # Speech bubble canvas background
└── kanye.png        # Clickable button image
