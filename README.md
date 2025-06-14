# 🌟 Microsoft Rewards Automation Bot

![Microsoft Rewards Automation](https://img.shields.io/badge/Microsoft%20Rewards%20Automation-v1.0-blue.svg)

Welcome to the **Microsoft Rewards Automation Bot** repository! This project features a Python script that automates Microsoft Rewards tasks using Selenium and Microsoft Edge. The bot performs Bing searches, completes Daily Set activities, and logs reward points—all with a persistent browser session.

## 📦 Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Configuration](#configuration)
5. [Contributing](#contributing)
6. [License](#license)
7. [Contact](#contact)
8. [Releases](#releases)

## 🚀 Features

- **Automated Bing Searches**: The bot performs searches automatically to help you earn points.
- **Daily Set Activities**: It completes Daily Set tasks, ensuring you maximize your rewards.
- **Persistent Session**: Maintains a browser session, so you don't need to log in repeatedly.
- **Cross-Platform**: Works on both Windows and Linux environments.
- **Scheduled Tasks**: Can be set up to run at specific intervals using task schedulers.

## 🛠️ Installation

To get started with the Microsoft Rewards Automation Bot, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/mouath12/ms-rewards-automation.git
   ```

2. **Navigate to the Directory**:
   ```bash
   cd ms-rewards-automation
   ```

3. **Install Required Packages**:
   Make sure you have Python installed. Then, install the required libraries using pip:
   ```bash
   pip install -r requirements.txt
   ```

4. **Download the Latest Release**:
   You can download the latest version of the bot from the [Releases section](https://github.com/mouath12/ms-rewards-automation/releases). Follow the instructions to execute the script.

## 📜 Usage

After installation, you can run the bot with the following command:

```bash
python main.py
```

### Command-Line Options

- `--help`: Display help information.
- `--config <path>`: Specify a custom configuration file.

## ⚙️ Configuration

Before running the bot, you need to configure it:

1. **Edit the Configuration File**:
   Open `config.json` and fill in your Microsoft account details and preferences.

   Example configuration:
   ```json
   {
       "email": "your_email@example.com",
       "password": "your_password",
       "search_count": 10,
       "daily_set": true
   }
   ```

2. **Browser Setup**:
   Ensure you have Microsoft Edge installed. The bot uses Selenium to control the browser.

## 🤝 Contributing

We welcome contributions to improve the Microsoft Rewards Automation Bot. To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a Pull Request.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📬 Contact

For questions or suggestions, please open an issue or contact the maintainer:

- **Name**: Mouath
- **Email**: mouath@example.com

## 📦 Releases

To get the latest version of the Microsoft Rewards Automation Bot, visit the [Releases section](https://github.com/mouath12/ms-rewards-automation/releases). Download the file, execute it, and start automating your Microsoft Rewards tasks!

## 🛠️ Topics

This project covers various topics including:

- Automation
- Background Processes
- Bots
- Microsoft Edge
- Linux
- Microsoft Rewards
- Python
- Selenium
- Task Scheduler
- Web Scraping
- Windows

## 🎉 Conclusion

The Microsoft Rewards Automation Bot simplifies the process of earning rewards. By automating mundane tasks, you can focus on more important things while still benefiting from the rewards program. 

Thank you for checking out this project! We hope it enhances your Microsoft Rewards experience. Happy automating!