# Interview Management System

## 🚀 المتطلبات الأساسية
قبل ما تبدأ، تأكد إن عندك:
- [PHP 8.1+](https://www.php.net/)  
- [Composer](https://getcomposer.org/)  
- [MySQL](https://dev.mysql.com/downloads/)  
- [Node.js & NPM](https://nodejs.org/)  

---

## ⚙️ خطوات التشغيل

1. **انسخ المشروع من GitHub**:
   ```bash
   git clone https://github.com/majeedfahad/ims.git
   cd 
   ```

2. **ثبّت مكتبات Laravel باستخدام Composer**:
   ```bash
   composer install
   ```

3. **انسخ ملف البيئة `.env`**:
   ```bash
   cp .env.example .env
   ```
   بعدين عدّل إعدادات قاعدة البيانات داخل ملف `.env`.

4. **ولّد مفتاح التشفير (APP_KEY)**:
   ```bash
   php artisan key:generate
   ```

5. **شغّل الـ migrations لإنشاء الجداول**:
   ```bash
   php artisan migrate
   ```

6. **شغّل السيرفر المحلي**:
   ```bash
   php artisan serve
   ```
   ثم افتح المتصفح على:  
   👉 [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## ✅ ملاحظات
- إذا واجهتك مشاكل مع قاعدة البيانات، تأكد إنك أنشأت قاعدة جديدة وربطتها في `.env`.  
