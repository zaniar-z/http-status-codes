# HTTP Status Codes

A bilingual, fully interactive reference for HTTP status codes — from informational responses (1xx) to server errors (5xx).

## Run

### Online (GitHub Pages)

https://zaniar-z.github.io/http-status-codes/

### Local

Open `index.html` directly in your browser — no install or build step needed.

> Note: keep the `locales/` folder next to `index.html` (same directory). The page loads translations via `fetch('locales/<lang>.json')`; if the folder is missing or renamed, the language switch breaks.

## Features

- Fast search & filtering of status codes
- Copy button for each code
- Persian/English language switch (`locales/fa.json`, `locales/en.json`)
- Dark/Light theme

## Structure

```
index.html          Main page (plain HTML/CSS/JS)
locales/            Translation files
  ├── fa.json       Persian (RTL)
  └── en.json       English
```

## License

MIT

---

# کدهای وضعیت HTTP

مرجع فارسی-انگلیسی و کاملاً تعاملی کدهای وضعیت HTTP — از پاسخ‌های اطلاعاتی (1xx) تا خطاهای سرور (5xx).

## اجرا

### آنلاین (GitHub Pages)

https://zaniar-z.github.io/http-status-codes/

### لوکال

فایل `index.html` را مستقیماً در مرورگر باز کنید — نیاز به نصب یا build نیست.

> نکته: پوشه `locales/` را کنار `index.html` (در همان پوشه) نگه دارید. صفحه ترجمه‌ها را با `fetch('locales/<lang>.json')` بارگذاری می‌کند؛ اگر پوشه نباشد یا تغییر نام بدهد، سوییچ زبان از کار می‌افتد.

## امکانات

- جستجوی سریع و فیلتر کردن کدهای وضعیت
- دکمه کپی برای هر کد
- تغییر زبان فارسی/انگلیسی (`locales/fa.json`، `locales/en.json`)
- تم تیره/روشن

## ساختار

```
index.html          صفحه اصلی (HTML/CSS/JS خالص)
locales/            فایل‌های ترجمه
  ├── fa.json       فارسی (RTL)
  └── en.json       انگلیسی
```

## لایسنس

MIT
