## Hi there 👋
# 👋 Hi — I'm **Tasdida nawaz**

> Undergraduate CSE Engineer | AI & Deep Learning enthusiast | Frontend tinkerer

---

<p align="center">
  <img src="assets/hero.svg" alt="hero" width="780" />
</p>

---

## 🔭 About me

* 🎓 Undergraduate in Computer Science & Engineering (CSE)
* 🧠 Interested in: Deep Learning, Computer Vision, Full‑stack web, and system design
* 🛠️ Building: lip‑reading models, fire‑service dashboards (React + Spring Boot + PostgreSQL), and ML research prototypes
* 🌱 Currently learning: advanced model compression & production model monitoring

---

## ✨ Visual highlights

### 1) Animated hero / banner

```md
<p align="center">
  <img src="assets/hero.svg" alt="hero" width="780" />
</p>
```

### 2) GitHub Stats cards

```md
<a href="https://github.com/preome">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=preome&show_icons=true&theme=tokyonight&count_private=true" />
</a>

<img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=preome&layout=compact&theme=tokyonight" />
```

### 3) Badges

```md
![Stars](https://img.shields.io/github/stars/preome?style=flat-square)
![Followers](https://img.shields.io/github/followers/preome?label=Follow&style=social)
![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin)
```

### 4) Project gallery

```md
## 🚀 Featured Projects

[![Lipreading Model](assets/projects/lipreading-thumb.png)](https://github.com/preome/lipreading-model)  [![Fire Service Dashboard](assets/projects/fire-dashboard-thumb.png)](https://github.com/preome/fire-dashboard)

Lipreading model for Bangla word recognition | Fire service monitoring dashboard
```

---

## 🧰 Skills

* **Languages:** Python • Java • JavaScript • SQL
* **Frameworks & Tools:** TensorFlow • PyTorch • React • Spring Boot • Docker • Git
* **Domains:** Computer Vision • NLP • Model Deployment • Data Engineering

---

## 📂 Pinned repositories

* `lipreading-model` — ResNet/3D CNN model for Bangla word recognition (11-frame sequences)
* `fire-dashboard` — React + Spring Boot dashboard for fire service monitoring
* `multi-task-unet` — U-Net variants for multi-output segmentation

---

## 📈 Dynamic snippets

* GitHub Stats • Wakatime • Commit streaks • Daily quotes

---

## ⚙️ GitHub Action: Daily Quote

```yaml
name: Daily README update
on:
  schedule:
    - cron: '0 0 * * *'
  workflow_dispatch:

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - name: Update quote
        run: |
          QUOTE="$(curl -s https://api.quotable.io/random | jq -r '.content')"
          sed -i "s|<!-- QUOTE -->.*<!-- QUOTE_END -->|<!-- QUOTE -->$QUOTE<!-- QUOTE_END -->|g" README.md
      - name: Commit and push
        run: |
          git config --local user.email "action@github.com"
          git config --local user.name "github-actions[bot]"
          git add README.md
          git commit -m "chore: update quote" || echo "No changes"
          git push
```

---

## 🖼️ Assets structure

```
preome/                        # repository name must be your GitHub username
├─ README.md
├─ assets/
│  ├─ hero.svg
│  ├─ projects/
│  │  ├─ lipreading-thumb.png
│  │  └─ fire-dashboard-thumb.png
│  └─ skills/
│     ├─ python.svg
│     └─ react.svg
└─ .github/workflows/readme.yml
```

---

## 🎨 Design notes

* SVGs for clean scaling & animation
* Keep GIFs < 200 KB
* Use a consistent color palette (blue‑violet theme works well)
* Add alt text for all visuals

---

## ✅ Quick setup

1. Create repo named `preome`.
2. Add this README & `assets/` folder.
3. Push to GitHub — it appears as your profile.

---

## 📬 Contact

* Email: `tasdidanpreome@gmail.com`
* LinkedIn: `https://www.linkedin.com/in/tasdida-nawaz-995682282/`


---

<!-- QUOTE --><!-- QUOTE_END -->

<!--
**Preome/preome** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
