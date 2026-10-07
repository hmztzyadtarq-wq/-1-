# حلو الملك — 4 ملفات بس

- `index.html`  الموقع كله (CSS + JS جواه)
- `admin.html`  لوحة التحكم كلها
- `firestore.rules`  قواعد الأمان (تتلصق في Firebase، مش جزء من الموقع)
- `README.md`

## Firebase
1. Authentication ← Sign-in method ← فعّل Email/Password.
2. Firestore Database ← Create database، وبعدين Rules والصق `firestore.rules` واضغط Publish.
3. Authentication ← Users ← Add user:
   الإيميل `01140090339@helwelmalek.app` والباسورد اللي تختاره (ده حساب الأدمن، ويدخل برقم 01140090339).
4. افتح admin.html وجرّب تدخل. هتظهر رسالة فيها الـ UID: اعمل في Firestore مجموعة `admins` وdocument الـ ID بتاعه هو الـ UID، وفيه حقل `ok` = true.
5. Authentication ← Settings ← Authorized domains: أضف `hmztzyadtarq-wq.github.io`.

## الرفع
ارفع الملفات الأربعة في جذر الريبو، وفعّل Settings ← Pages. اللوحة: `.../admin.html`.
أول مرة: الإعدادات ← "نقل البيانات الأولية"، وبعدها ارفع صور المنتجات والأقسام والبانرات.
