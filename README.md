<p align="center">
  <a href="https://glimpse-of-my-world.netlify.app/">
    <img src="https://raw.githubusercontent.com/Vijay-1289/Vijay-1289/main/Portoflio.png" alt="Screenshot" width="1000"/>
  </a>
</p>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>JP → EN Morph</title>
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
      gap: 16px;
      text-align: center;
    }
    .word {
      position: relative;
      min-width: 120px;
      height: 2.5rem;
    }
    .jp, .en {
      position: absolute;
      left: 0;
      right: 0;
      opacity: 0;
    }

    /* JP first, then EN */
    .jp {
      animation: fadeJP 6s infinite;
    }
    .en {
      animation: fadeEN 6s infinite;
    }

    @keyframes fadeJP {
      0%   { opacity: 0; }
      5%   { opacity: 1; }
      45%  { opacity: 1; }
      55%  { opacity: 0; }
      100% { opacity: 0; }
    }
    @keyframes fadeEN {
      0%   { opacity: 0; }
      45%  { opacity: 0; }
      55%  { opacity: 1; }
      95%  { opacity: 1; }
      100% { opacity: 0; }
    }

    /* Delay each pair so words morph one after another */
    .word:nth-child(1) .jp, .word:nth-child(1) .en { animation-delay: 0s; }
    .word:nth-child(2) .jp, .word:nth-child(2) .en { animation-delay: 1s; }
    .word:nth-child(3) .jp, .word:nth-child(3) .en { animation-delay: 2s; }
    .word:nth-child(4) .jp, .word:nth-child(4) .en { animation-delay: 3s; }
    .word:nth-child(5) .jp, .word:nth-child(5) .en { animation-delay: 4s; }
  </style>
</head>
<body>
  <div id="morph-box">
    <span class="word">
      <span class="jp">🔥 AI愛好家</span>
      <span class="en">🔥 AI Enthusiast</span>
    </span>
    <span class="word">
      <span class="jp">🤖 機械学習探検家</span>
      <span class="en">🤖 Machine Learning Explorer</span>
    </span>
    <span class="word">
      <span class="jp">🐍 パイソン開発者</span>
      <span class="en">🐍 Python Developer</span>
    </span>
    <span class="word">
      <span class="jp">📊 データサイエンス愛好家</span>
      <span class="en">📊 Data Science Lover</span>
    </span>
    <span class="word">
      <span class="jp">⚛️ 量子コンピュータに興味</span>
      <span class="en">⚛️ Quantum Curious</span>
    </span>
  </div>
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






