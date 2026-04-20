# Claude Telegram Bot

Claude AI (Anthropic) asosidagi Telegram bot. O'zbek, rus va ingliz tillarida suhbat qurish imkonini beradi.

## Xususiyatlar

- Claude Sonnet modeli bilan real vaqtda suhbat
- Har bir foydalanuvchi uchun alohida suhbat tarixi
- `/clear` buyrug'i bilan tarixni tozalash
- O'zbek, rus va ingliz tili qo'llab-quvvatlash

## O'rnatish

### 1. Repozitoriyani klonlash

```bash
git clone https://github.com/Abdulvahobjon/claude-telegram-bot.git
cd claude-telegram-bot
```

### 2. Kerakli kutubxonalarni o'rnatish

```bash
pip install -r requirements.txt
```

### 3. Muhit o'zgaruvchilarini sozlash

```bash
export TELEGRAM_BOT_TOKEN="your_telegram_bot_token"
export ANTHROPIC_API_KEY="your_anthropic_api_key"
```

Yoki `.env` fayl yarating:

```
TELEGRAM_BOT_TOKEN=your_telegram_bot_token
ANTHROPIC_API_KEY=your_anthropic_api_key
```

### 4. Botni ishga tushirish

```bash
python claude_telegram_bot.py
```

## Telegram Bot Token olish

1. Telegramda [@BotFather](https://t.me/BotFather) ga murojaat qiling
2. `/newbot` buyrug'ini yuboring
3. Bot nomini kiriting
4. Token olasiz

## Anthropic API Key olish

1. [console.anthropic.com](https://console.anthropic.com) saytiga kiring
2. API Keys bo'limiga o'ting
3. Yangi kalit yarating

## Buyruqlar

| Buyruq | Tavsif |
|--------|--------|
| `/start` | Botni ishga tushirish va xush kelibsiz xabari |
| `/clear` | Suhbat tarixini tozalash |

## Litsenziya

MIT
