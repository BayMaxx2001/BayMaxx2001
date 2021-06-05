### Hi there 👋

A second-year college student looking for an developer internship. Good algorithm for problem 
optimization, a contestant of the ACM-ICPC contest, ability to quickly understand the problem, good 
communication. Express fondness to new technology and responsibility for the job. Ambition in gaining more 
experience and contributing for the company. Desire to learn in a real international environment and adapt 
different cultures
- 🔭 I’m currently study in FPT University ...
- 🌱 I’m currently learning Software Engineer and Machine Learning
- 👯 I’m looking to collaborate on inter company
- 📫 How to reach me: https://www.linkedin.com/in/vutrihien/
- ⚡ Fun fact


![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)

name: GitHub-Profile-Summary-Cards

on:
  schedule: # execute every 24 hours
    - cron: "* */24 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    name: generate-github-profile-summary-cards

    steps:
      - uses: actions/checkout@v2
      - uses: vn7n24fzkq/github-profile-summary-cards@release
        env: # default use ${{ secrets.GITHUB_TOKEN }}, you should replace with your personal access token
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        with:
          USERNAME: ${{ github.repository_owner }}
          
<!--
**BayMaxx2001/BayMaxx2001** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
