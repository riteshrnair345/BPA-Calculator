# WCA Average Tracker & Target Calculator ⏱️🧊

A fast, mobile-friendly web tool designed for speedcubers to use during official WCA (World Cube Association) competitions. 

When you are sitting at the competition table, calculating what you need on your 5th solve can be nerve-wracking. This calculator instantly provides your **Best Possible Average (BPA)**, **Worst Possible Average (WPA)**, and the exact **5th solve required** to hit your target goal.

## ✨ Features

* **Smart Input Formatting (csTimer style):** Save time typing. The app automatically formats integers into proper WCA times:
  * Type `75` ➔ Auto-formats to `0.75`
  * Type `1234` ➔ Auto-formats to `12.34`
  * Type `11243` ➔ Auto-formats to `1:12.43`
* **Auto-DNF:** Just type the letter `D` and it will instantly auto-fill to `DNF`.
* **Target Calculator:** Enter your target average (like your PR goal), and the app will tell you exactly what time you need on your final solve. It will also tell you if your goal is *Impossible* or *Guaranteed*.
* **WCA Regulations Compliant:** Properly handles DNF logic (1 DNF acts as the worst solve, 2 DNFs result in a DNF average).
* **Automatic Dark Mode:** Seamlessly switches between Light and Dark themes based on your device's system settings.
* **Zero Dependencies:** Built entirely with plain HTML, CSS, and JavaScript. No frameworks, no build steps, and works entirely offline.

## 🚀 How to Use

### Run Locally
1. Download or clone this repository.
2. Double-click the `calculator.html` file to open it in any modern web browser.

### Host Online (Free)
You can easily host this on GitHub Pages so you can access it via a link on your phone:
1. Create a new GitHub repository and upload `calculator.html` (you can rename it to `index.html` for easier routing).
2. Go to your repository **Settings** > **Pages**.
3. Under "Build and deployment", select the `main` branch and click **Save**.
4. Within a few minutes, your calculator will be live at `https://yourusername.github.io/your-repo-name/`.
5. Open the link on your phone and add it to your home screen for app-like access!

## 🛠️ Built With
* HTML5
* CSS3 (with CSS Variables & Media Queries)
* Vanilla JavaScript

## 📄 License
This project is open-source and available under the MIT License. Feel free to fork, modify, and improve it!
