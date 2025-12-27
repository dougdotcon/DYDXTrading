# DydxTradingBot

![License](https://img.shields.io/badge/license-MIT-blue)
![Version](https://img.shields.io/badge/version-1.0.0-green)

A robust automated trading bot designed to monitor and execute operations on the dYdX v4 decentralized exchange. This project leverages algorithmic strategies to navigate the cryptocurrency market efficiently.

## ⚠️ Disclaimer

**This software is for educational purposes only.**
Trading cryptocurrencies involves significant financial risk. The authors are not responsible for any financial losses incurred while using this bot. Always trade responsibly and never risk more than you can afford to lose.

## 📋 Prerequisites

Before you begin, ensure you have the following installed on your system:

*   **Git**: For cloning the repository.
*   **Python 3.10+**: The core language used for the bot.
*   **pip**: Python package installer.
*   **dYdX Account**: You must have an active dYdX v4 wallet with sufficient funds for trading and gas fees.

## 🔧 Installation

Follow these steps to set up the project locally.

1. **Clone the Repository**

   bash
   git clone https://github.com/your-username/DydxTradingBot.git
   cd DydxTradingBot
   

2. **Create a Virtual Environment**

   It is recommended to use a virtual environment to manage dependencies:

   bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   

3. **Install Dependencies**

   bash
   pip install -r requirements.txt
   

4. **Configuration**

   Rename the `config.example.json` file to `config.json` and populate it with your credentials and API keys. **Never commit your `config.json` file to Git.**

   
   {
       "wallet_mnemonic": "your secret mnemonic phrase here",
       "api_key": "your_dYdX_api_key",
       "trading_pair": "BTC-USD",
       "risk_per_trade": 0.01
   }
   

## 🚀 Usage

To start the trading bot, run the main script from your terminal:

bash
python main.py


The bot will initialize, connect to the dYdX v4 network, and begin monitoring the market based on your configuration.

*   **To stop the bot**: Press `Ctrl+C` in the terminal.

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📞 Support

If you have any questions or need support, please open an Issue in the repository.