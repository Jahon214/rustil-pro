# RusTil PRO — Interaktiv Rus Tili O'rganish Platformasi 🇷🇺✨

[![Vercel Deployment](https://img.shields.io/badge/Vercel-Deployed-black?logo=vercel)](https://rustil-pro.vercel.app)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![CEFR Standard](https://img.shields.io/badge/CEFR-A1_to_C1-indigo)](#)
[![Web Audio & Speech](https://img.shields.io/badge/Voice-Web_Speech_TTS-green)](#)

> Rus tilini zamonaviy interaktiv o'yinlar, CEFR diagnostik testlari, sof ovozli audio talaffuz va kundalik topshiriqlar orqali o'rganing. Tangalar yig'ib haqiqiy sovg'alarga ega bo'ling!

---

## 🚀 Asosiy Imkoniyatlar (Key Features)

### 1. 📊 Shaxsiy Asosiy Panel (Dashboard)
- O'quvchi darajasi (A1, A2, B1, B2, C1) va uzluksiz ketma-ketlik (Streak fire) ko'rsatkichi.
- To'plangan hamjamiyat tangalari (🪙 Coins) va tajriba ballari (⚡ XP).
- Moslashuvchan kunlik topshiriqlar tizimi (Daily Quests).
- Homiylar oylik sovrin jamg'armasi hisoblagichi.

### 2. 📖 Kunlik Lug'at va 3D Kartochkalar (Vocabulary & 3D Flashcards)
- **5 ta CEFR Darajasi**: A1 (Boshlang'ich), A2 (Bazaviy), B1 (Mustaqil), B2 (Yuqori), C1 (Mukammal).
- **3D Flip Animatsiyali Kartochkalar**: So'z, transkripsiya, o'zbekcha tarjima, toifa va misol gaplar.
- **Sof Ruscha Audio (TTS)**: Har bir so'z va iborani sof talaffuzda eshitish imkoniyati.
- **Nutqni tekshiruvchi Ovozli AI (Voice Recognition)**: Mikrofon orqali o'quvchi talaffuzini real vaqtda baholash.
- **Jonli qidiruv va filtr**: Ruscha va o'zbekcha so'zlarni tezkor qidirish.

### 3. 🎯 CEFR Daraja Aniqlash Testi (Diagnostic Test)
- Grammatika, leksika va situatsion savollardan iborat 10 ta sifatli test.
- Har bir savolga javob bergach: to'g'ri/noto'g'ri ko'rsatkichi va **batafsil tushuntirish (Explanation)**.
- Test yakunida yangi CEFR darajasi beriladi, +120 🪙 tanga va +250 XP bonus qo'shiladi va sertifikat avtomatik yangilanadi.

### 4. 🎮 O'yinlar Maydoni (3 ta O'yin Rejimi)
- **🔗 Цепочка Слов (So'z Zanjiri)**:
  - Raqib yozgan so'zning oxirgi harfiga so'z yozish (ь, ъ, ы, й qoidasi hisobga olingan).
  - Platforma AI boti yoki jonli onlayn o'yinchi simulyatsiyasi.
  - Ruscha virtual klaviatura va tezkor maslahat so'zlar (Hint chips).
- **🧩 Собери Слово (Harflardan so'z tuzish)**:
  - Aralashtirilgan harflardan to'g'ri so'zni yig'ish boshqotirmasi.
- **⚡ Tezkor Ruscha Blitz (Speed Challenge)**:
  - 45 soniyada berilgan ruscha so'zlarning o'zbekcha tarjimasini imkon qadar tez va ko'p topish o'yini. Rekordlar saqlanadi.

### 5. 💬 Situatsion Ruscha Dialoglar (Real-Life Dialogues)
- Hayotiy vaziyatlar: "Aeroportda", "Qahvaxonada", "Ish suhbati (Intervyu)" va "Shaharda yo'l so'rash".
- To'liq audio bilan eshitish va o'zbekcha tarjimasi bilan birga o'rganish.

### 6. 📚 Grammatika Shpargalkasi (Grammar Cheatsheet)
- Otlarning 3 xil rodi (Мужской, Женский, Средний).
- 6 ta Kelishik (Падежи: Именительный, Родительный, Дательный, Винительный, Творительный, Предложный) qoidalari.
- Harakat fe'llari (Идти vs Ехать, Летать vs Лететь).

### 7. 🏆 Oylik Liga va Homiylar (Leaderboard & Sponsors)
- Oltin, Kumush, Bronza, Olmos ligalari.
- Bosh homiylar (Uzum Market, Payme, Yoshlar Agentligi, IT Park) taqdim etgan sovg'alar jamg'armasi (1,000,000 UZS, AirPods, Smart Watch, Kitoblar).
- Foydalanuvchining o'z o'rni dinamik hisoblanadi.

### 8. 🛍️ Tangalar Do'koni va Inventar (Coin Shop & Inventory)
- Tangalar evaziga sovg'alar: Streak himoyasi, darslik kitoblar, termos krujka, Uzum vaucheri, xudi, aqlli soat, AirPods va VIP maqomi.
- Unikal promokod (RU-SHOP-XXXX) generatsiyasi va xaridlar tarixi (Inventory).

### 9. 🎓 Rasmiy Sertifikat Generator (Canvas & PNG/Print)
- 1200x800 yuqori sifatli rasmiy sertifikat.
- Talabaning to'liq ismi, unikal sertifikat ID, berilgan sana, rasmiy oltin muhr, tasdiqlovchi QR-kod.
- Bir klik bilan HD PNG formatda yuklab olish.

### 10. 💾 Doimiy Saqlash (LocalStorage) & Tungi Rejim (Dark/Light Mode)
- Foydalanuvchi ma'lumotlari, tangalari va darajasi qurilmada avtomatik saqlanib qoladi.
- Qorong'i va yorug' rejim to'liq integratsiyalangan.

---

## 🛠️ Texnologiyalar (Tech Stack)

- **Frontend**: HTML5, Tailwind CSS, Vanilla JavaScript (ES6+)
- **Styling & Icons**: Plus Jakarta Sans, Font Awesome 6.5, Canvas Confetti
- **Audio & Voice**: Web Audio API (Sintezlangan tovush effektlari), Web Speech API (TTS `ru-RU`), Web Speech Recognition
- **Graphics**: HTML5 Canvas (1200x800 Sertifikat renderlash)
- **Deployment**: Vercel & GitHub

---

## 📦 O'rnatish va Mahalliy Ishga Tushirish

```bash
# Repozitoriyni klonlash
git clone https://github.com/Jahon214/rustil-pro.git

# Loyiha papkasiga o'tish
cd rustil-pro

# Mahalliy server orqali ochish
npx serve .
# Yoki index.html faylini brauzerda to'g'ridan-to'g'ri oching
```

---

## 👤 Muallif

- **Muallif**: [Jahon214](https://github.com/Jahon214)
- **Litsenziya**: MIT License
