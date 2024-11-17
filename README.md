## Hi there 👋

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=sramirez124&layout=compact)

<!--START_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: sramirez124/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{secrets.WAKA_API_KEY}}
          GH_TOKEN: ${{secrets.GH_TOKEN}}
<!--END_SECTION:waka-->

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img height=200 align="center" src="https://github-readme-stats.vercel.app/api?username=sramirez124" />
</a>
<a href="https://github.com/sramirez124/top-language">
  <img height=200 align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=sramirez124&layout=compact&langs_count=8&card_width=320" />
</a>
<!--
**sramirez124/sramirez124** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
