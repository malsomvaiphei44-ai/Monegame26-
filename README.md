# 💰 Monegame26 - Earn Coins App

A Telegram Web App for earning coins through ads, daily bonuses, and a spinning wheel mini-game.

## 🚀 Live Demo

**[Play Now](https://malsomvaiphei44-ai.github.io/Monegame26-/)**

## ✨ Features

- 🎁 **Watch Ads**: Earn 5 coins per ad
- 🎲 **Daily Bonus**: Get 50 coins once per day
- 🎡 **Spinning Wheel**: Win 5, 10, 20, or 50 coins (5 free spins daily + unlimited ad spins)
- 📊 **Level System**: Level up every 500 coins
- 💳 **Redeem**: Convert 5000 coins to rewards
- 💾 **Persistent Storage**: Your progress is saved locally
- 🔒 **Error Handling**: Robust error management and validation

## 🎯 How to Play

1. **Watch Ads** - Click "Watch Ad" to earn 5 coins
2. **Daily Bonus** - Claim 50 coins once per day
3. **Spin Wheel** - Use 5 free daily spins or watch ads for extra spins
4. **Level Up** - Reach higher levels by collecting coins
5. **Redeem** - Redeem 5000 coins for real rewards via Telegram

## 🛠️ Technology Stack

- Pure HTML5
- Vanilla JavaScript
- Telegram Web App API
- Local Storage for persistence
- Canvas API for the spinning wheel

## 📱 Telegram Integration

This app is designed to run as a Telegram Mini App. To use it:

1. Add it to a Telegram bot as a web app
2. Users launch it from within Telegram
3. Telegram provides user data automatically

## 💾 How It Works

- **Data Storage**: All progress is saved in your browser's localStorage
- **Daily Reset**: Spin count resets daily
- **Bonus Tracking**: Bonuses tracked by date
- **Offline Support**: Works completely offline after first load

## 🔧 Customization

Edit these values in `index.html`:

```javascript
// Reward amounts
let rewards = [5, 10, 20, 50];

// Ad URL
const adUrl = "https://omg10.com/4/10916425";

// Telegram username for redeem
const telegramUsername = "malsom_vaiphei";
```

## 📄 License

This project is public and open-source.

## 👨‍💻 Author

[@malsomvaiphei44-ai](https://github.com/malsomvaiphei44-ai)
