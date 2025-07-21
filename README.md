# 🤖 Twitter Auto-Reply AI Bot

An intelligent, open-source Twitter bot that automatically responds to mentions and tweet replies using OpenAI's GPT model. Perfect for creators, businesses, or community accounts looking to automate engagement with smart, human-like responses..
## Contact

[Telegram](https://t.me/ShadowRusii)

## ✨ Key Features

🔁 Auto-replies to mentions on Twitter

💬 Auto-responses to replies on your tweets

🧠 AI-generated responses powered by OpenAI GPT-3.5 / GPT-4

📉 Built-in rate limiter and daily tweet cap

📜 Detailed logging system for transparency and debugging

🔒 .env-based API key management for secure deployment

## Installation

1. Install the required packages:
```bash
pip install -r requirements.txt
```

2. Create the `.env` file and add the following variables:
```
TWITTER_API_KEY=your_api_key
TWITTER_API_SECRET=your_api_secret
TWITTER_ACCESS_TOKEN=your_access_token
TWITTER_ACCESS_TOKEN_SECRET=your_access_token_secret
TWITTER_BEARER_TOKEN=your_bearer_token
OPENAI_API_KEY=your_openai_api_key
```

## Usage

To start the program:
```bash
python main.py
```

You can choose between two modes:
1. Automatically respond to mentions
2. Automatically respond to comments on tweets

## Project Structure

```
.
├── config/
│   └── config.py         # Konfigürasyon ayarları
├── src/
│   ├── twitter_client.py # Twitter API işlemleri
│   ├── openai_client.py  # OpenAI API işlemleri
│   └── tweet_handler.py  # Tweet işleme mantığı
├── utils/
│   ├── logger.py        # Loglama sistemi
│   └── rate_limiter.py  # Rate limiting işlemleri
├── logs/                # Log dosyaları
├── .env                 # Ortam değişkenleri
├── main.py             # Ana program
└── requirements.txt    # Gerekli paketler
```

##🔐 Security & Compliance
🔒 API keys stored securely via .env

⚙️ Rate-limiting prevents spam or overuse

📊 Daily tweet limits protect your account from abuse or bans

## 📄 License
MIT – free to use, modify, and distribute.


