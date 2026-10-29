# ASL FOOD OILAVIY - Internetga Bepul Joylash Yo'riqnomasi

Ushbu veb-sahifani internetga chiqarib, barcha mijozlar ochishi va QR-kod orqali kirishi uchun 3 ta bepul usul mavjud:

---

### 1-Usul: Vercel orqali (Eng tez va tavsiya etilgan) ⚡
1. Kompyuterda PowerShell orqali quyidagi buyruqni ishga tushiring:
   ```bash
   npx vercel
   ```
2. So'rovlarga `Y` (Yes) deb javob bering.
3. 30 soniyada sizga `https://aslfood.vercel.app` kabi bepul, xavfsiz (HTTPS) domen beriladi!

---

### 2-Usul: Netlify Drop (Hech qanday o'rnatishlarsiz) 🌐
1. Brauzerda [app.netlify.com/drop](https://app.netlify.com/drop) saytini oching.
2. Ish stolidagi `asl food` papkasini sichqoncha bilan ushlab, brauzerdagi doiraga tashlang (Drag & Drop).
3. 10 soniyada tayyor internet havolasini olasiz!

---

### 3-Usul: GitHub Pages orqali 🐙
1. GitHub hisobingizda yangi repository oching (masalan, `aslfood`).
2. Fayllarni yuklang:
   ```bash
   git init
   git add .
   git commit -m "ASL FOOD rasmiy menyu va sayt"
   git branch -M main
   git remote add origin <sizning-github-repo-link>
   git push -u origin main
   ```
3. Repository sozlamalarida (`Settings` -> `Pages`) sahifani yoqing. Saytingiz `https://username.github.io/aslfood` manzilida ishlaydi.
