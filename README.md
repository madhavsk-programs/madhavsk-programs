<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6a11cb,100:2575fc&height=180&section=header&text=Madhav%20Khurana&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Data%20Science%20%C2%B7%20LLM%20Engineering%20%C2%B7%20Agentic%20AI&descAlignY=55&descSize=16" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1200&color=6a11cb&center=true&vCenter=true&width=650&lines=Data+Science+%26+Machine+Learning;Fine-Tuning+LLMs+with+LoRA+%2F+QLoRA;Building+RAG+%26+Multi-Agent+Systems;Learning+everything+from+first+principles" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=madhavsk-programs&color=6a11cb&style=flat&label=Profile+Views" />
  <img src="https://img.shields.io/github/followers/madhavsk-programs?label=Followers&style=flat&color=2575fc" />
</p>

### Hey, I'm Madhav 👋

I'm a data science student who likes building things end-to-end — from statistical models and ML pipelines to retrieval-augmented and agentic LLM systems. I try to understand things from first principles before reaching for the library: I've hand-coded KNN, gradient descent, and attention mechanisms rather than just importing them.

- 🎓 Completed **CampusX DSMP 2.0** — full data science stack (Python, SQL, statistics, ML, feature engineering)
- 🤖 Trained in **Production LLM Engineering** (RAG, Agents & Fine-Tuning) — Krish Naik Academy
- 🕸️ Studying **Agentic AI 3.0** — LangGraph, MCP, A2A, multi-agent systems
- 📚 Currently in intensive coursework at VIT (Theory of Computation, Foundations of Data Science)

<br>

### 🧠 What I work with

**Data Science & ML**
Python · SQL · NumPy / Pandas · Statistics & Hypothesis Testing · Linear/Logistic Regression · Decision Trees, Random Forest, XGBoost · Unsupervised Learning (K-Means, DBSCAN, GMM, PCA) · Feature Engineering · Tableau

**LLM Engineering**
Transformer architecture · Fine-tuning (LoRA, QLoRA, DPO) · Knowledge Distillation · RAG (hybrid retrieval, rerankers, Graph RAG) · Evaluation harnesses & eval-gated CI/CD

**Agentic AI**
LangGraph · Model Context Protocol (MCP) · Agent-to-Agent (A2A) protocol · Multi-agent orchestration · Claude Code · mem0

<br>

### 🎯 Goals
- Ship production-grade RAG & agentic systems, not just notebooks
- Contribute to open-source AI tooling
- Land a Data Science / AI Engineering internship at a product-based company
- Keep up with GenAI without losing the fundamentals underneath it

🎲 **Fun fact:** *(swap this for your own — mine's a placeholder)* Once spent an hour debugging a "broken" RAG pipeline before realizing the vector store was just empty.

<br>

### 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,cpp,c,java,kotlin,js,ts,react&perline=8" />
</p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=sklearn,pytorch,tensorflow,octave,mysql,fastapi,docker,aws&perline=8" />
</p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=git,github,githubactions,linux,vscode&perline=8" />
</p>

<br>

### 📊 GitHub Stats

<p align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=madhavsk-programs&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=madhavsk-programs&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=madhavsk-programs&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=madhavsk-programs&theme=tokyonight&no-frame=true&row=1&column=7" />
</p>

<br>

### 🐍 Contribution Snake
name: generate animated snake

on:
  schedule:
    - cron: "0 */6 * * *"   # regenerates every 6 hours
  workflow_dispatch:         # lets you trigger it manually from the Actions tab
  push:
    branches:
      - main

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - name: generate snake game from GitHub contribution grid
        uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: push snake svg to the output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/madhavsk-programs/madhavsk-programs/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/madhavsk-programs/madhavsk-programs/output/github-contribution-grid-snake.svg" />
    <img alt="a snake eating through my contribution graph" src="https://raw.githubusercontent.com/madhavsk-programs/madhavsk-programs/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2575fc,100:6a11cb&height=100&section=footer" />
</p>
