---
title: ArxivChainLitDemo
emoji: 💻
colorFrom: indigo
colorTo: gray
sdk: docker
pinned: false
license: openrail
---

# How to run the project on your localhost
- Pre-requisites: install git, vscode and docker on your local machine
- Clone the project for them git repo
- Open the project in a vscode
- Type CMD + SHIFT + P (On MAC) and select 'Dev containers: Rebuild container' option => it will execute the content of Dockerfile in an isolated vscode devcontainer environment which means it will also install all the dependencies specified requirements.txt file
- Copy open api key from ChatGPT platform (https://platform.openai.com/account/api-keys). It requires premium ChatGPT account
- Create .env file within the project and set OPENAI_API_KEY=YOUR_API_KEY
- Open the terminal using an option in vscode Terminal >> New Terminal
- Type command 'chainlit run app.py --port 7860'
- It will run the server and we can access ChatGPT like frontend at http://localhost:7860