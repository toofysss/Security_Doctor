
# Security Doctor

**Security Doctor** هو نظام متكامل يوفر حماية وأمان متقدمين للمستخدمين. يتكون المشروع من جزئين رئيسيين: **API** و **Mobile Application**.

# Security Doctor API

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
```bash
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
```


### 🚀 كيفية التشغيل

  - قم بتنزيل المشروع 
```bash
  git clone https://github.com/toofysss/Security_Doctor.git
```
### الالوان المستخدمة


| Color             | Hex   |
| --------| --------------------------------------------------- |
| Primary | #325B90 |
| Bg      | #F0F4FC |





