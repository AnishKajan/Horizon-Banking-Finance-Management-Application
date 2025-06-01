# 💳 Horizon – Fintech Banking Web App

A full-stack banking platform built with Next.js, Appwrite, Plaid, and Dwolla. Horizon lets users sign up, link bank accounts, view transactions, and simulate fund transfers.

---

## 📁 Project Structure

```
banking-main/
├── app/
├── components/
├── constants/
├── lib/
├── public/
├── types/
├── .env
├── package.json
├── tailwind.config.ts
├── next.config.mjs
```

---

## 🛠️ Tech Stack

- **Frontend:** Next.js 14, TypeScript, TailwindCSS, ShadCN
- **Backend:** Appwrite (auth, DB), Plaid (bank linking), Dwolla (transfers)
- **Validation & Forms:** React Hook Form, Zod
- **Design:** Figma

---

## ▶️ Running the App

1. **Install Dependencies**
```bash
npm install
```

2. **Add Your Environment Variables** in `.env`
```env
NEXT_PUBLIC_SITE_URL=http://localhost:3000
# Appwrite credentials
# Plaid sandbox keys
# Dwolla sandbox keys
```

3. **Run the App**
```bash
npm run dev
```

Visit: [http://localhost:3000](http://localhost:3000)

---

## 🖼️ Current UI Preview
<img width="1202" alt="Screenshot 2025-06-01 at 5 45 26 PM" src="https://github.com/user-attachments/assets/a4ecdd60-8db9-46c9-811b-90fb5237c52b" />



### 📝 Sign Up Page
<img width="1202" alt="Screenshot 2025-06-01 at 5 45 45 PM" src="https://github.com/user-attachments/assets/a7374e64-9975-421b-90df-295106e40149" />


---

## ❗ Known Issues

- ❌ Sign-up fails silently due to misconfigured API or expired Plaid/Dwolla keys
- 🔑 Make sure to use your own API keys — never copy from GitHub `.env`

---

## 🎓 Credit

Based on the JavaScript Mastery tutorial  
[GitHub Repo](https://github.com/adrianhajdin/banking)
