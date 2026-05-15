# 🛒 TechSurvivor — Frontend

## Про проєкт

TechSurvivor — це веб-застосунок для купівлі та продажу вживаної техніки. Платформа дозволяє користувачам розміщувати оголошення, шукати товари за фільтрами, спілкуватись через чат, оформлювати замовлення та керувати своїм профілем. Проєкт реалізований у рамках навчання Fullstack Development та працює у зв'язці з окремим backend API.

---

Функціональність <br><br>

**Авторизація та реєстрація** <br>
• створення акаунту <br>
• вхід у систему <br>
• захищені маршрути для авторизованих користувачів <br><br>

**Оголошення** <br>
• перегляд каталогу оголошень <br>
• пошук та фільтрація за категорією, ціною, містом, станом <br>
• створення, редагування та видалення оголошень <br>
• перегляд деталей оголошення <br><br>

 **Чат** <br>
• список чатів користувача <br>
• листування з продавцем / покупцем по оголошенню <br><br>

**Замовлення** <br>
• створення замовлення <br>
• перегляд списку замовлень <br>
• деталі замовлення <br><br>

**Профіль користувача** <br>
• перегляд та редагування даних профілю <br><br>

**Адмін-панель** <br>
• керування оголошеннями <br>
• керування категоріями <br>
• керування баннерами <br>
• керування замовленнями <br>
• керування промоакціями <br>
• керування відгуками <br><br>

**Повідомлення та обробка помилок** <br>
• toast-повідомлення <br>
• валідація форм <br>

---

Реалізація <br><br>

• ✅ Next.js 16 (App Router) <br>
• ✅ Публічні та приватні маршрути <br>
• ✅ Захист сторінок на рівні компонентів <br>
• ✅ Tailwind CSS (стилізація) <br>
• ✅ CSS Modules <br>
• ✅ State management — Zustand <br>
• ✅ Data fetching — TanStack Query <br>
• ✅ Форми — Formik + Yup <br>
• ✅ HTTP-запити — Axios <br>
• ✅ Обробка помилок (toast + UI повідомлення) <br>

---

Технології та інструменти <br><br>

**Frontend** <br>
• React 19 / Next.js 16 — побудова інтерфейсу <br>
• Tailwind CSS / CSS Modules — стилізація <br>
• TypeScript — типізація та логіка застосунку <br><br>

 **Backend** <br>
• REST API (окремий репозиторій) <br>
Backend: 🔗 https://github.com/TechSurvivor/TechSurvivor.BackEnd <br>
Swagger API: 🔗 http://localhost:8080/swagger/index.html <br><br>

**Бібліотеки** <br>
• Axios — HTTP-запити <br>
• React Hot Toast — повідомлення <br>
• Zustand — керування станом авторизації <br>
• TanStack Query — кешування та data fetching <br>
• Formik + Yup — форми та валідація <br>
• cookie — робота з cookies <br>

---

Структура проєкту

```
techsurvivornext/
├── app/
│   ├── (auth routes)/        # Авторизація, реєстрація, профіль
│   ├── (private routes)/     # Захищені сторінки (оголошення, чати, замовлення, адмін)
│   ├── api/                  # Next.js API routes (proxy, auth)
│   ├── globals.css
│   └── layout.tsx
├── components/               # Спільні компоненти (Header, Footer, Forms)
├── lib/
│   ├── api/                  # API клієнти (ads, chats, orders, categories...)
│   └── store/                # Zustand store (authStore)
└── types/                    # TypeScript типи
```

---

Environment Variables


```
NEXT_PUBLIC_API_URL=your_backend_url
```

---

 Як запустити проєкт

1. Встановіть Node.js (LTS версію)
2. Клонувати репозиторій:
```bash
git clone https://github.com/TechSurvivor/TechSurvivor.FrontEnd
```
3. Перейдіть у папку проєкту:
```bash
cd TechSurvivor.FrontEnd/techsurvivornext
```
4. Встановіть залежності:
```bash
npm install
```
5. Створіть файл `.env.local` та вкажіть URL backend API
6. Запустіть проєкт:
```bash
npm run dev
```
7. Відкрийте у браузері: http://localhost:3000

---

**Команда** <br><br>

 **Frontend Developers** <br>
• Maksym <br>
• Artem <br>
• Diana <br>
