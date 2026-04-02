from pathlib import Path

readme = r'''<h1 align="center">Hi, I'm Trisha Dabral 👋</h1>
<h3 align="center">CSE Student • DSA Enthusiast • Building Real-World Projects</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=24&pause=1000&color=8B5CF6&center=true&vCenter=true&width=700&lines=Passionate+about+DSA+and+problem+solving;Building+real-world+projects+with+clean+UI;Learning+Web+Dev%2C+Spring+Boot+and+Machine+Learning" alt="Typing SVG" />
</p>

---

## 🚀 About Me

- 🎓 CSE student passionate about **DSA, OOPs, and development**
- 💻 Currently working on **algorithm-focused real-world projects**
- 📈 Building: **Stock Monitoring & Decision Engine**
- 🌱 Learning: **Web Development, Spring Boot, React, Tailwind, ML**
- 🎯 Goal: Build projects that look good **and** have strong logic behind them

---

## 📊 My GitHub History

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=trishadabral&show_icons=true&theme=tokyonight&hide_border=true&border_radius=12" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=trishadabral&layout=compact&theme=tokyonight&hide_border=true&border_radius=12" />
</p>

<p align="center">
  <img width="95%" src="https://github-readme-streak-stats.herokuapp.com/?user=trishadabral&theme=tokyonight&hide_border=true&border_radius=12" />
</p>

<p align="center">
  <img width="95%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=trishadabral&theme=tokyonight" />
</p>

---

## 🛠️ Some Tools I Have Used and Learned

<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp,c,java,python,js,html,css,react,tailwind,spring,postgres,mysql,mongodb,git,github,vscode,idea,figma,linux&perline=10" />
</p>

---

## 💼 Featured Projects

### 📈 Stock Monitoring & Decision Engine
A real-time stock analysis system focused on algorithmic decision-making.

- Sliding Window for price trend analysis  
- Greedy logic for alert-based decisions  
- Dynamic Programming for optimization ideas  
- React + Spring Boot + PostgreSQL based full-stack workflow  

### 🤖 Smart Resume Analyzer
A project that analyzes resumes and helps match skills with job requirements.

- Resume parsing and skill extraction  
- Clean dashboard-style UI  
- Useful for real-world recruitment support systems  

### 🩺 Multi-Disease Prediction / ML-Based Health Project
A machine learning-based project idea for prediction and assistance.

- Uses ML models for prediction  
- Focus on practical problem-solving  
- Useful for academic demos and hackathons  

---

## 🧠 Coding Profiles

<p align="center">
  <a href="https://github.com/trishadabral">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/YOUR_LINKEDIN/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://leetcode.com/trishaha/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" />
  </a>
</p>

---

## 📬 Connect With Me

<p align="center">
  <a href="mailto:trishadabral@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/YOUR_LINKEDIN/">
    <img src="https://img.shields.io/badge/Let's%20Connect-8B5CF6?style=for-the-badge" />
  </a>
</p>

---

## ✨ Little Quote

<p align="center"><i>"Good projects are not just pretty — they solve real problems."</i></p>

---

## 🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/snake.svg" alt="Snake animation" />
</p>

---



'''

path = Path("/mnt/data/README.md")
path.write_text(readme, encoding="utf-8")
print(f"Saved to {path}")
