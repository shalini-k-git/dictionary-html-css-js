# 📘 Dictionary Web App

A simple and responsive **Dictionary Application** built using **HTML, CSS, and JavaScript**, powered by a free **Online Dictionary API**.  
Users can search any word and instantly view its **meaning, pronunciation, and example usage**.

---

## 🚀 Features

- 🔍 Search any English word  
- 📖 Shows definitions and meanings  
- 🎨 Clean and minimal UI  
- ⚡ Fast API response  

---

## 🛠️ Tech Stack

- **HTML5**  
- **CSS3**  
- **JavaScript (Vanilla JS)**  
- **Dictionary API** (Free Dictionary API)

---

## 📂 Project Structure

```
/dictionary-app
│── index.html
│── style.css
│── script.js
└── README.md
```


---

## 📦 How It Works

1. User enters a word  
2. JavaScript fetches results from the Dictionary API  
3. App displays the meaning and pronunciation  

```js
fetch(`https://api.dictionaryapi.dev/api/v2/entries/en/${word}`)
  .then(res => res.json())
  .then(data => {
      // Display results here
  });
```

![App Screenshot](./demo_images/demo_1.png)

---

## 👩‍💻 Author
**Shalini K**  

- 🌐 GitHub: [Shalini_K](https://github.com/shalini-k-git)  
- 💼 LinkedIn: [Shalini K](https://www.linkedin.com/in/shalini-k10/)  
- 📧 Email: shalinikandaswamy10@gmail.com

