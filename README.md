Security Doctor

Security Doctor هو نظام متكامل يوفر حماية وأمان متقدمين للمستخدمين. ينقسم المشروع إلى جزأين رئيسيين: API و Mobile Application.

🖥 Security Doctor API

✨ الميزات

🔒 إدارة المستخدمين والصلاحيات (Admin, User)

🛡️ حماية متقدمة باستخدام أحدث معايير الأمان

🔑 تسجيل الدخول والمصادقة باستخدام JWT

🔐 تشفير كلمات المرور باستخدام Bcrypt

📊 نظام تسجيل العمليات والأحداث الأمنية

⚙️ Middleware مخصص لمراقبة السجلات والمصادقة

🏗 استخدام ORM مع Entity Framework Core

📜 توثيق API باستخدام Swagger

🚀 إدراج بيانات أولية تلقائيًا عند تشغيل التطبيق

📂 هيكلة المشروع

SecurityDoctor-API
├── Configurations
│   ├── SeedDataConfiguration.cs
├── Entities
│   ├── User.cs, Role.cs, SecurityLog.cs
├── Middleware
│   ├── JwtMiddleware.cs, LoggingMiddleware.cs, ErrorHandlingMiddleware.cs
├── Repositories
│   ├── AuthRepository.cs, SecurityRepository.cs
├── Services
│   ├── AuthService.cs, SecurityService.cs
├── Migrations

🚀 كيفية التشغيل

قم بتنزيل المشروع أو استنساخه:

git clone https://github.com/toofysss/Security_Doctor.git

قم بتحديث appsettings.json بإعدادات قاعدة البيانات.

قم بتشغيل الأوامر التالية لإعداد قاعدة البيانات:

dotnet ef database update

قم بتشغيل التطبيق باستخدام:

dotnet run

📱 Security Doctor Mobile App

✨ الميزات

📲 تسجيل الدخول والتسجيل للمستخدمين

🔔 إشعارات لحظية عند الأحداث الأمنية

🔍 مراقبة الحساب والنشاطات المسجلة

🛠 إعدادات متقدمة لحماية الحساب

🌐 اتصال مباشر مع API لتحديث البيانات بشكل دوري

📂 هيكلة المشروع

SecurityDoctor-Mobile
├── src
│   ├── components
│   ├── screens
│   ├── services
│   ├── utils
├── assets
├── App.js
├── package.json

🚀 كيفية التشغيل

قم بتنزيل المشروع أو استنساخه:

git clone https://github.com/toofysss/Security_Doctor_Mobile.git

قم بتثبيت الحزم المطلوبة:

npm install

قم بتشغيل التطبيق باستخدام:

npm start

