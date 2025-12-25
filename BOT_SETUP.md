# 🤖 Bot Setup Guide

## ✅ Environment Configuration

### Production Setup (Recommended)

Use your deployed URLs:

```bash
# server/.env
BOT_TOKEN=8520934887:AAFBDNnOh7B_8o-bXMVWVwxL_0dui6HFLMw
WEB_APP_URL=https://birrbingo.vercel.app/
```

### Local Development

```bash
# server/.env
BOT_TOKEN=8520934887:AAFBDNnOh7B_8o-bXMVWVwxL_0dui6HFLMw
WEB_APP_URL=https://birrbingo.vercel.app/
```

---

## 🚀 Deploy to Production (Easiest!)

### On Render Dashboard:

1. Go to your service → **Environment** tab
2. Add these variables:
   - `BOT_TOKEN` = `8520934887:AAFBDNnOh7B_8o-bXMVWVwxL_0dui6HFLMw`
   - `WEB_APP_URL` = `https://birrbingo.vercel.app/` (your actual URL)
3. Click **Save** (triggers automatic redeploy)

### Test Immediately:
- Open Telegram
- Find your bot
- Send `/start` → Bot responds! 🎉

---

## 🧪 Test Locally (Optional)

```bash
cd server
npm run dev
```

Open Telegram and test all commands.

---

## 📋 Available Commands

```
/start   - Welcome & main menu
/play    - Game mode selection
/balance - Wallet info
/deposit - Add funds
/withdraw - Cash out
/help    - Support
```

---

## ✅ What Works Now

- ✅ All 6 commands
- ✅ Inline keyboards
- ✅ Ethiopian game modes
- ✅ Beautiful UI
- ✅ Rate limiting
- ✅ Error handling

---

## 🔄 Next: Connect Real Data

Currently using mock data. To connect:
1. Import Firebase services
2. Connect wallet API
3. Integrate Chapa payments
4. Add user authentication

Ready? Let's do it!
