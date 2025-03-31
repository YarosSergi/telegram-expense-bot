# Telegram Expense Bot

This is a no-code project for a Telegram bot that helps users track their expenses and incomes by uploading receipt photos.

## 🧩 Stack & Tools

- **Make.com** – for building the automation logic
- **Google Cloud Vision API** – for extracting text from receipt images
- **Airtable** – for storing structured financial data
- **OpenAI (GPT-4)** – for analyzing spending and generating reports
- **Telegram Bot** – user interface for submitting data

## ⚙️ How It Works

1. User sends a receipt photo to the Telegram bot  
2. Make receives the image and sends it to Google Vision API  
3. The extracted text is parsed and structured  
4. Data is saved into Airtable with categories and amounts  
5. GPT-4 can generate summaries or savings suggestions on request

## 📝 Status

Currently in prototype phase. Next steps:
- Add monthly summary reports
- Enable income tracking
- Improve receipt parsing accuracy

## 📌 Author

[Yaroslav Serhienko](https://github.com/YarosSergi)
