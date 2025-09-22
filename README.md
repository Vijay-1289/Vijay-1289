<p align="center">
  <a href="https://glimpse-of-my-world.netlify.app/">
    <img src="https://raw.githubusercontent.com/Vijay-1289/Vijay-1289/main/Portoflio.png" alt="Screenshot" width="1000"/>
  </a>
</p>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: #0d1117;
      color: #fff;
      font-family: 'Fira Code', monospace;
      font-size: 2rem;
      font-weight: bold;
    }
    #morph-box {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      text-align: center;
    }
    .word {
      position: relative;
      min-width: 60px;
      text-align: center;
    }
    .jp, .en {
      position: absolute;
      left: 0; right: 0;
      opacity: 0;
      transition: opacity 0.8s ease;
    }
    .show {
      opacity: 1;
    }
  </style>
</head>
<body>
  <div id="morph-box"></div>

  <script>
    const phrases = [
      { jp: ["🔥", "AI愛好家"], en: ["🔥", "AI Enthusiast"] },
      { jp: ["🤖", "機械学習探検家"], en: ["🤖", "Machine", "Learning", "Explorer"] },
      { jp: ["🐍", "パイソン開発者"], en: ["🐍", "Python", "Developer"] },
      { jp: ["📊", "データサイエンス愛好家"], en: ["📊", "Data", "Science", "Lover"] },
      { jp: ["⚛️", "量子コンピュータに興味"], en: ["⚛️", "Quantum", "Curious"] }
    ];

    const morphBox = document.getElementById("morph-box");
    let index = 0;

    function createWord(jpText, enText) {
      const wrapper = document.createElement("span");
      wrapper.classList.add("word");

      const jpSpan = document.createElement("span");
      jpSpan.textContent = jpText;
      jpSpan.classList.add("jp");

      const enSpan = document.createElement("span");
      enSpan.textContent = enText || "";
      enSpan.classList.add("en");

      wrapper.append(jpSpan, enSpan);
      return wrapper;
    }

    function showPhrase() {
      morphBox.innerHTML = "";
      const { jp, en } = phrases[index];

      // Step 1: Show JP words one by one
      jp.forEach((word, i) => {
        const wrapper = createWord(word, en[i]);
        morphBox.appendChild(wrapper);
        setTimeout(() => wrapper.querySelector(".jp").classList.add("show"), i * 300);
      });

      // Step 2: Morph JP → EN word by word
      setTimeout(() => {
        const wrappers = morphBox.querySelectorAll(".word");
        wrappers.forEach((wrapper, i) => {
          const jpSpan = wrapper.querySelector(".jp");
          const enSpan = wrapper.querySelector(".en");
          setTimeout(() => {
            jpSpan.classList.remove("show");
            enSpan.classList.add("show");
          }, i * 500);
        });
      }, 2000);

      // Step 3: Loop to next phrase
      index = (index + 1) % phrases.length;
      setTimeout(showPhrase, 5000);
    }

    showPhrase();
  </script>
</body>
</html>


---

## 🔭 I’m currently working on
- Exciting AI and ML projects  
- Expanding my knowledge in Data Science

## 🌱 I’m currently learning
- Deep Learning and Neural Networks  
- Advanced Python and Machine Learning Techniques

## 👯 I’m looking to collaborate on
- Open-source AI projects  
- Innovative Machine Learning applications

## 💬 Ask me about
- Python, Machine Learning, Data Science  
- AI and Deep Learning

## 📫 How to reach me
- **LinkedIn**: [Siruvuru Vijay Rama Raju](https://www.linkedin.com/in/siruvuru-vijay-rama-raju-137a062b9)

## ⚡ Fun fact
- I love solving complex data problems and building real-world AI applications!

---

## 🛠️ Tech Stack

- **Languages**:  
  ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  
  ![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)  
  ![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)

- **Libraries & Frameworks**:  
  ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)  
  ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)  
  ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)  
  ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)  
  ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)

---

## 🚀 Projects

### 🩺 Smart Heal | Python + Streamlit + AI  
- Developed an AI-powered health assistant using Streamlit that predicts diseases based on user symptoms using machine learning  
- Demonstrated end-to-end pipeline including data preprocessing, model training, and interactive UI integration  
- A practical and intuitive project that showcases applied data science in the healthcare domain  
🔗 [GitHub Repo](https://github.com/Vijay-1289/AI-Health)

---

### ⚛️ Quantum Warrior | Qiskit + Python  
- Designed an interactive quantum-themed game leveraging Qiskit, simulating quantum principles in a gamified environment  
- Implemented basic quantum gates and measurement logic to introduce players to foundational quantum computing concepts  
- A creative and educational project bridging quantum mechanics with game development for intuitive learning  
🔗 [GitHub Repo](https://github.com/Vijay-1289/Quantum-Warrior)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Vijay-1289&show_icons=true&theme=radical" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Vijay-1289&layout=compact&theme=radical" />
</p>

---

## 💡 Dev Quote of the Day

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" />
</p>

---

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212721374-c8f75e3b-54f5-46ec-8450-0386d92fd255.gif" width="700"/>
</p>

---

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/Vijay-1289/Vijay-1289/main/output/dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/Vijay-1289/Vijay-1289/main/output/light.svg"
  />
  <img alt="GitHub Breakout Game" src="https://raw.githubusercontent.com/Vijay-1289/Vijay-1289/main/output/light.svg" />
</picture>

---

<p align="center">
  <b>“Keep learning, keep building!”</b> 🚀
</p>




