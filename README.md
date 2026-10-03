<div align="center">

# #Radhey

### Pharmacy Study Hub: Python Basics and Human Anatomy

*Learn the topic. Take the quiz. Repeat.*

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Single Page](https://img.shields.io/badge/App-Single%20Page-3B6CF6?style=for-the-badge)
![Mobile Friendly](https://img.shields.io/badge/Mobile-Friendly-2E9B5A?style=for-the-badge)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-F5B800?style=for-the-badge)

**[Live Demo](#live-demo)** · **[Features](#-features)** · **[Syllabus](#-syllabus-covered)** · **[Run Locally](#-run-locally)** · **[Contact](#-contact-the-owner)**

</div>

---

## About the Project

**#Radhey** is a clean, fast, single-page web app built for **pharmacy students**. It puts short, clear notes and a random quiz in one place, so you can read a topic and test yourself straight away.

> **Why this project?**
> Pharmacy students study Human Anatomy and, increasingly, Python for data and automation. Notes are scattered across books, PDFs and screenshots. This app brings them together in one mobile-friendly page.

---

## Features

| | Feature | Details |
|---|---|---|
| 📚 | **Subject menu** | Switch between *Python Basics* and *Human Anatomy* with one tap |
| 🗂️ | **Unit dropdowns** | Every subject is split into units, and each unit holds topics |
| ⏭️ | **Previous / Next** | Move through topics in order without reopening the menu |
| 🎲 | **Random quiz** | 10 random questions every attempt, with shuffled answer options |
| 🎯 | **Quiz filters** | Choose *Mixed*, *Python only* or *Anatomy only* |
| ✅ | **Instant feedback** | Correct answer is highlighted right after you pick |
| 📊 | **Score screen** | Final score with a short encouraging message |
| 🌗 | **Dark and light mode** | Follows your device setting, with a manual toggle |
| 📱 | **Mobile first** | Works on phones, tablets and desktops |
| ⚡ | **Zero dependencies** | Plain HTML, CSS and JavaScript in a single file |

---

## Syllabus Covered

### Python Basics

| Unit | Topics |
|---|---|
| **Unit 1: Introduction and IDEs** | Python introduction, Why Python, PyCharm, Spyder, PyDev, Atom, Wing, Jupyter Notebook, Thonny, Rodeo, Microsoft Visual Studio, Eric Python |
| **Unit 2: Variables** | What is a variable, identifier naming rules, naming styles (camel, Pascal, snake), declaring and assigning, multiple assignment, object references, object identity with `id()`, local and global variables |
| **Unit 3: Data types** | Numbers, strings, booleans, lists, tuples, sets, dictionaries |

### Human Anatomy

| Unit | Topics |
|---|---|
| **Unit 1: Introduction** | Anatomical terms, planes, levels of organisation, four basic tissues |
| **Unit 2: Skeletal system** | 206 bones, axial and appendicular skeleton, types of joints |
| **Unit 3: Muscular system** | Skeletal, smooth and cardiac muscle, muscle contraction |
| **Unit 4: Cardiovascular system** | Heart chambers and valves, circulation, blood pressure |
| **Unit 5: Respiratory system** | Airway, alveoli, gas exchange, breathing mechanics |
| **Unit 6: Nervous system** | CNS and PNS, neuron structure, sympathetic and parasympathetic systems |
| **Unit 7: Digestive system** | GI organs, enzymes, digestion and absorption |

> 💊 **Pharmacy links:** many topics include a short *pharmacy use* note, for example how antihypertensives act on the blood pressure equation.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox) |
| Logic | Vanilla JavaScript (ES6) |
| Fonts | Fraunces and Quicksand via Google Fonts |
| Hosting | Any static host: GitHub Pages, Netlify, Vercel |

---

## Project Structure

```
radhey/
├── index.html     # the whole app: markup, styles and scripts
├── README.md      # you are here
└── LICENSE        # MIT license (add this file)
```

---

## Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/<repo-name>.git

# 2. Open the folder
cd <repo-name>

# 3. Open index.html in any browser
```

No install, no build step, no server needed.

### Deploy free on GitHub Pages

1. Go to **Settings → Pages**
2. Under *Source*, choose the `main` branch and `/ (root)`
3. Save, and your site goes live at `https://<your-username>.github.io/<repo-name>/`

---

## Live Demo

> 🔗 Add your deployed link here: `https://<your-username>.github.io/<repo-name>/`

---

## Add Your Own Content

All content lives in two JavaScript objects inside `index.html`.

**Add a topic** to the `SUB` object:

```js
["Topic title", `<p>Your explanation in HTML.</p>`]
```

**Add a quiz question** to the `Q` array:

```js
["p", "Your question?", ["Option A", "Option B", "Option C"], 1]
// "p" = Python, "a" = Anatomy
// last number = index of the correct option (starts at 0)
```

---

## Roadmap

- [x] Python Basics: IDEs, variables, data types
- [x] Human Anatomy: 7 units
- [x] Random quiz with filters
- [x] Dark and light mode
- [ ] Pharmacognosy and Pharmacology units
- [ ] Plant scientific-name search
- [ ] Symptom-to-disease learning tool
- [ ] Bookmarks and progress tracking
- [ ] Downloadable PDF notes

---

## Contributing

Contributions are welcome.

1. **Fork** the repository
2. Create a branch: `git checkout -b feature/new-topic`
3. Commit your change: `git commit -m "Add new topic"`
4. Push: `git push origin feature/new-topic`
5. Open a **Pull Request**

Spotted a mistake in a note? Please open an **Issue** so it can be fixed quickly.

---

## Disclaimer

> ⚠️ This project is for **educational purposes only**. It does not give medical advice, diagnosis or treatment. Always follow your syllabus, textbooks and teachers for exams.

---

## License

Released under the **MIT License**. You may use, copy and modify it freely with credit.

---

## Contact the Owner

<div align="center">

| | |
|---|---|
| 👤 **Owner** | **#Radhey** |
| ✉️ **Email** | [radheyjii@proton.me](mailto:radheyjii@proton.me) |
| 📞 **Phone** | [9395137349](tel:+919395137349) |
| ✈️ **Telegram** | [t.me/Youradhey](https://t.me/Youradhey) |

</div>

---

<div align="center">

## ⭐ Enjoyed this project?

### Please give it a **star**. It takes one second and keeps the project growing.

[![Star this repo](https://img.shields.io/badge/⭐_Star_this_repo-F5B800?style=for-the-badge&logoColor=black)](#)
[![Fork](https://img.shields.io/badge/🍴_Fork-3B6CF6?style=for-the-badge)](#)
[![Telegram](https://img.shields.io/badge/Chat_on_Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Youradhey)

**Made with ❤️ by #Radhey**

*Love from Radhey*

</div>
