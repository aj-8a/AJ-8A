# 🐍 AJ's GitHub Profile

<!--
## 🤖 AUTOMATED BACKGROUND WORKFLOW CONFIGURATION
If you haven't created your workflow file yet, save the code below as `.github/workflows/snake.yml`

name: Generate AJ Snake Animation

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:
  push:
    branches:
    - main

jobs:
  generate:
    permissions: 
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5
    
    steps:
      - name: Generate github-contribution-grid-snake
        uses: Platane/snk@v3
        with:
          github_user_name: aj-8a
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark
            dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9&color_background=#aaaaaa

      - name: Deploy to Output Branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
-->

## 🕹️ AJ's Contribution Snake Game

<p align="center">
  <!-- Responsive Snake SVGs (Swaps automatically on Dark/Light mode) -->
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://githubusercontent.com">
    <source media="(prefers-color-scheme: light)" srcset="https://githubusercontent.com">
    <img alt="AJ's GitHub Contribution Snake" src="https://githubusercontent.com" width="100%">
  </picture>
</p>

<br/>

## 🌊 Custom Ocean Theme
<p align="center">
  <img alt="AJ's Ocean Snake" src="https://githubusercontent.com" width="100%">
</p>

---

### 🚀 Setup Quick-Check
1. Ensure you create a file at `.github/workflows/snake.yml` using the code hidden at the top of this markdown file.
2. Go to your repository **Settings** -> **Actions** -> **General**.
3. Scroll down to **Workflow permissions** and select **Read and write permissions**, then click **Save**.
4. Run the workflow manually once from your **Actions** tab to generate the initial images!
