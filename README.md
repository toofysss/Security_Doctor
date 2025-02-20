# Security Doctor

**Security Doctor** هو نظام متكامل يوفر حماية وأمان متقدمين للمستخدمين. يتكون المشروع من جزئين رئيسيين: **API** و **Mobile Application**.

---

## 🖥 Security Doctor API

### ✨ الميزات
- 🔒 **إدارة المستخدمين والصلاحيات** (Admin, User)
- 🛡️ **حماية متقدمة** باستخدام أحدث معايير الأمان
- 🔑 **تسجيل الدخول والمصادقة** باستخدام **JWT**
- 🔐 **تشفير كلمات المرور** باستخدام **Bcrypt**
- 📊 **نظام تسجيل العمليات والأحداث الأمنية**
- ⚙️ **Middleware مخصص** لمراقبة السجلات والمصادقة
- 🏗 **استخدام ORM مع Entity Framework Core**
- 📜 **توثيق API باستخدام Swagger**
- 🚀 **إدراج بيانات أولية تلقائيًا** عند تشغيل التطبيق

### 📂 هيكلة المشروع
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




### 🚀 كيفية التشغيل

1. قم بتنزيل المشروع أو استنساخه:

   ```bash
   git clone https://github.com/toofysss/Security_Doctor.git


## Security Doctor Mobile App



### ✨ الميزات
- 📲 تسجيل الدخول والتسجيل للمستخدمين
- 🔔 إشعارات لحظية عند الأحداث الأمنية
- 🔍 مراقبة الحساب والنشاطات المسجلة
- 🛠 إعدادات متقدمة لحماية الحساب
- 🌐 اتصال مباشر مع API لتحديث البيانات بشكل دوري

SecurityDoctor-Mobile
├── src
│   ├── components
│   ├── screens
│   ├── services
│   ├── utils
├── assets
├── App.js
├── package.json



### 🚀 كيفية التشغيل

1. قم بتنزيل المشروع أو استنساخه:

   ```bash
   flutter pub get


