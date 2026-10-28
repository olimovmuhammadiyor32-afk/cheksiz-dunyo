CHEKSIZ DUNYO — Mini App boshlang‘ich paketi

Tarkib:
- index.html: mobilga mos, bosiladigan o‘yin interfeysi (demo).
- bot.py: Telegram bot, o‘yinni HTTPS Web App tugmasi bilan ochadi.
- .env.example: kerakli sozlamalar namunasi.

MUHIM:
1) index.html ni HTTPS qo‘llaydigan hostingga joylash kerak. Oddiy Termuxning o‘zi Telegram Mini App uchun ommaviy HTTPS manzil bermaydi.
2) .env.example nusxasini .env qilib, BOT_TOKEN va WEBAPP_URL ni kiriting. Tokenni hech kimga yubormang.
3) Hozirgi o‘yin prototipida progress shu qurilmaning brauzer/localStorage xotirasida saqlanadi. Server bazasi, haqiqiy ko‘p foydalanuvchili reyting, jang serveri va Telegram foydalanuvchi identifikatsiyasini tekshirish hali ulanmagan.
4) Haqiqiy ishga tushirishdan oldin backend/API, ma’lumotlar bazasi, Telegram WebApp initData tekshiruvi va hosting sozlanishi kerak.
