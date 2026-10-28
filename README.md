# سینا اصغرزاده | وبسایت نمونه‌کار

این نسخه **تک‌فایل** است: همه‌ی عکس‌ها داخل `index.html` قرار دارند، پس برای انتشار فقط همین فایل کافی است
(مشکل لود نشدن عکس‌ها بعد از انتشار، از آپلود نشدن پوشه‌ی `img` بود).

## انتشار روی GitHub Pages
1. در ریپو روی **Add file ← Upload files** بزن و `index.html` (و اگر خواستی `.nojekyll`) را آپلود کن، بعد **Commit changes**.
2. به **Settings ← Pages** برو؛ Source را روی **Deploy from a branch**، شاخه‌ی `main` و پوشه‌ی `/ (root)` بگذار و Save بزن.
3. بعد از ۱ تا ۲ دقیقه آدرس سایت بالای همان صفحه نوشته می‌شود.

## آدرس (دامین)
آدرس `نام‌کاربری.github.io` به **نام کاربری گیت‌هاب** وابسته است، نه نام ریپو.
- نام کاربری فعلی `mathland12349-arch` است، پس ریپوی `sinadev.github.io` در آدرس
  `https://mathland12349-arch.github.io/sinadev.github.io/` باز می‌شود، نه `sinadev.github.io`.
- راه ساده: ریپو را به `mathland12349-arch.github.io` تغییر نام بده (Settings ← Repository name).
  آدرس می‌شود `https://mathland12349-arch.github.io`.
- اگر آدرس `sinadev.github.io` را می‌خواهی، باید یک اکانت گیت‌هاب با نام کاربری `sinadev` بسازی (اگر آزاد باشد) و ریپو را آنجا بسازی.
- دامین اختصاصی (مثل `sinadev.ir`) اختیاری است: بعد از خرید، در Settings ← Pages قسمت Custom domain را پر کن.

## افزودن نمونه‌کار
داخل `index.html` دنبال `var PROJECTS=[` بگرد و یک آیتم به لیست اضافه کن (`kind` یا `app` است یا `web`، `link` اختیاری است).
عکس جدید را هم می‌توانی به‌صورت `img/نام.jpg` کنار فایل بگذاری و همان مسیر را در `image` بنویسی.
