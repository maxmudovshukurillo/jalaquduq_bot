# Jalaquduq Telegram Bot - Deployment Guide

Professional Telegram bot for Jalaquduq region, listing organizations, kindergartens, schools, and MFY details.

## Features
- 🏛 **Hokimlik va Tashkilotlar**: Barcha mas'ul shaxslar ma'lumoti.
- 🎓 **Maktab va Bog'chalar**: Jalaquduq bo'yicha ta'lim maskanlari ro'yxati.
- 🏘 **MFY**: Mahalla fuqarolar yig'inlari va xodimlari ro'yxati.
- 🚀 **Inline Buttons**: Qulay va zamonaviy UI.
- ⚡ **24/7 ishlaydi**: Flask orqali integratsiya qilingan.

## How to Run Locally
1. Clone the project yoki shu papkani oching.
2. Kutubxonalarni o'rnating: `pip install -r requirements.txt`
3. `.env` faylini yaratib, tokenni kiriting: `BOT_TOKEN=your_token_here`
4. Botni ishga tushiring: `python bot.py`

## Deployment (Free Hosting)
You can deploy this bot for free on **Render.com**.

### Render Deployment Steps:
1. Shu barcha fayllarni GitHub ga yuklang (Push to GitHub).
2. Render.com ga kirib, yangi **Web Service** yarating.
3. GitHub repository ni ulang.
4. **Environment Variables** bo'limida quyidigilarni sozlang:
   - `BOT_TOKEN`: Sizning Telegram Bot Tokeningiz.
5. **Start Command**: `python bot.py` yoki shunchaki Procfile o'zi topib oladi.
6. Build Command: `pip install -r requirements.txt` (yoki `render.yaml` faylidan foydalanadi).
7. Deploy! Render botingizni uzluksiz ishlatib beradi (Flask serveri ham ishlaganligi sababli to'xtamaydi).
