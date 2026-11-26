# Xodim Hisobot — joylash qo'llanmasi

Papkadagi fayllar: `index.html`, `manifest.json`, `sw.js`, `vercel.json`, `icons/` (5 ta rasm).
Hammasini birga joylang (icons papkasi bilan).

## 1) GitHub'ga yuklash
1. github.com → **New repository** → nomi: `xodim-hisobot` → **Create repository**.
2. **uploading an existing file** havolasini bosing.
3. Zip'ni ochib, ichidagi hamma fayl va `icons` papkasini sudrab tashlang.
4. **Commit changes** bosing.

## 2) Vercel'da chop etish
1. vercel.com → GitHub bilan kiring → **Add New → Project**.
2. `xodim-hisobot` repozitoriyasini tanlang → **Import**.
3. Framework Preset: **Other** (hech narsani o'zgartirmang) → **Deploy**.
4. Tayyor havola chiqadi, masalan `xodim-hisobot.vercel.app`. Shu havolani xodimlarga yuboring.

## 3) Xodim telefoniga o'rnatish
- **Android (Chrome):** havolani oching → ⋮ menyu → *Ilovani o'rnatish*.
- **iPhone (Safari):** havolani oching → «Ulashish» → *Bosh ekranga qo'shish*.
- Birinchi kirishda xodim o'z 4 xonali PIN-kodini yaratadi.

## 4) Birinchi sozlash (har bir telefonda bir marta)
Sozlamalar bo'limida: ism, soatbay haq, bonus foizi, obed puli, Telegram bot tokeni va rahbarning chat ID raqami, do'kon joylashuvi («Joriy joyni do'kon deb belgilash» — do'konda turib bosiladi).
Hamma xodim uchun bitta bot va bitta rahbar chat ID ishlatiladi.

## Yangilash
GitHub'da `index.html` ni yangi fayl bilan almashtiring (Commit). Vercel o'zi qayta joylaydi, xodimlar keyingi ochilishda yangisini oladi.

## Muhim cheklovlar (bu versiya serversiz)
- Ma'lumotlar har bir xodimning telefonida saqlanadi. Telefon almashsa yoki brauzer ma'lumotlari tozalansa, tarix yo'qoladi (Sozlamalar → Ma'lumotlar → zaxira nusxa oling).
- Haq va bonus sozlamalarini xodimning o'zi o'zgartira oladi; rahbar hisobotni faqat Telegramdan ko'radi.
- Bot tokeni xodim telefonida saqlanadi.
- Internet uzilsa, Telegram xabarlari navbatga qo'yiladi va ulanganda yuboriladi.
