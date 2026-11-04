نصب پورتال HSE به‌صورت اپ (PWA)

شرط اصلی: برنامه فقط از روی آدرس https قابل نصب است. باز کردن فایل از روی گوشی/کامپیوتر (file://) یا آدرس http ساده قابل نصب نیست.

۱) هر شش فایل این پوشه را کنار هم، در یک پوشه روی یک هاست https بگذارید:
   index.html  manifest.webmanifest  sw.js  icon-192.png  icon-512.png  icon-maskable-512.png
   (گزینه‌های ساده: Netlify Drop، Cloudflare Pages، GitHub Pages، یا هاست/سرور خودتان با گواهی SSL)
۲) آدرس https را در Chrome گوشی باز کنید؛ دکمه «📲 نصب برنامه» پایین صفحه ظاهر می‌شود (یا منوی ⋮ ← Install app).
۳) آیفون: در Safari دکمه اشتراک‌گذاری ← Add to Home Screen.
۴) اگر بعد از به‌روزرسانی فایل‌ها نسخه قدیمی دیدید، یک بار صفحه را کاملاً ببندید و باز کنید (کش سرویس‌ورکر).
آدرس سیستم مادر (Google Apps Script /exec) داخل index.html تنظیم شده است.
