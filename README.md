# ✈️ Flight Deal Tracker

A Python project that tracks cheap flight deals and sends WhatsApp alerts when the price drops below a set threshold.

## 🚀 How It Works

1. Fetches destination data from a Google Sheet (via Sheety API).
2. Uses Amadeus API to search for flight deals from London.
3. Compares current prices with your minimum price.
4. Sends a WhatsApp message using Twilio if a cheaper deal is found.

## 📁 Project Files

- `main.py`: Main script to run the whole flow.
- `data_manager.py`: Handles interaction with Sheety API (Google Sheets).
- `flight_search.py`: Handles authentication and flight search via Amadeus API.
- `flight_data.py`: Parses and finds the cheapest flight data.
- `notification_manager.py`: Sends SMS or WhatsApp alerts using Twilio.
- `.env`: Stores API keys and credentials (not shared publicly).

## 🛠️ Setup

1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
