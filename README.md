[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=social)](LICENSE)
[![PHP Version Support](https://img.shields.io/packagist/php-v/chillerlan/php-qrcode?logo=php&style=social)](chatbot-chatgpt.php)

# HackMTY2023 - WordPress Plugin

<p align="center">
    <em>Connected via ChatGPT API and preconfigured with prior context.</em>
</p>

<p>
  This WordPress plugin was created at HackMTY 2023, a hackathon held at the facilities of Tecnologico de Monterrey.
</p>

* Contributors: [Fernando Dilland](https://github.com/fernandodilland), [Omar Najera](https://github.com/theomarnajera), [Miguel del Castillo](https://github.com/migueldelcastillo).
* Tags: plugin, theme, update, api, chat gpt.
* Requires at least: 5.2.
* Requires PHP: 7.2.

![Social image](assets/img/share.png)


---

### Case Study

An example is conducted using information obtained from a national bank (Mexican) to establish parameters and create a financial "Coach" that primarily preloads the context of investment types and relevant yield information.
The user is primarily allowed to provide their general information, such as age, monetary amount capable of investing, timeframe, and goals, so that ChatGPT has the necessary prompt and context to provide general financial advice and guide a path to enter the financial world for beginners or, for experienced investors, introduce investment proposals in banking.

**Live Demo**: <a href="https://asesor.fernandodilland.com" target="_blank">https://asesor.fernandodilland.com</a>

---

### Features

- API/Model:
    - Ability to connect to the ChatGPT API Key (OpenAI).
    - Ability to choose the ChatGPT Model Choice: gpt-3.5-turbo or gpt-4.
    - Ability to choose the Maximum Tokens Setting (100 to 1,000).
    - Ability to provide conversation context.
- Settings:
  - Ability to assign a name to the bot.
  - Configure the initial state and new visitor.
  - Set the initial greeting.
  - Adjust subsequent greetings.
  - Include disclaimer (AI).
  - Chatbot Width Setting.
  - Chatbot Diagnostics.
- Avatar:
    - Avatar Icon Setting.
    - Avatar Greeting.
- Knowledge Navigator:
    - Maximum Depth.
    - Maximum Top Words.
    - Run Knowledge Navigator.

### Installation

- To install and use this plugin, download the zip file by clicking the green "<> Code" button located in the GitHub repository.
- Log in to your WordPress (CMS), whether hosted on a server or locally.
- Go to Plugins > Add New or directly to the link: (domain/subdomain)/wp-admin/plugin-install.php
- Click on "Upload Plugin" and select the zip file downloaded from the GitHub repository.
- Press "Activate plugin" or go to Plugins > Add New and activate the "Chatbot ChatGPT" plugin.

### Configuration

- Go to Settings > Chatbot ChatGPT or directly to the link: (domain/subdomain)/wp-admin/options-general.php?page=chatbot-chatgpt
- Enter your ChatGPT API Key obtained from https://platform.openai.com/account/api-keys
- Choose the model, token settings, and context.

---

### Special thanks
We extend our sincere appreciation to the Instituto Tecnológico y de Estudios Superiores de Monterrey (ITESM), commonly referred to as Tecnológico de Monterrey, located at Av. Eugenio Garza Sada 2501 Sur, Tecnológico, 64849 Monterrey, N.L., as well as the ACM Student Chapter and Major League Hacking for their organization and facilitation of the "HackMTY 2023" Hackathon. This event took place on their premises, where open-source projects were diligently crafted, aiming for pioneering solutions.

<img src="./assets/img/itesm.png" height="50"><br>
