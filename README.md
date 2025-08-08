<div align="center">

# SW Ultra - GitHub Edition

<p>
  <a href="#-english">English</a> •
  <a href="#-العربية">العربية</a>
</p>

<p>
  <img src="https://img.shields.io/badge/Version-3.0-blue?style=for-the-badge" alt="Version">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
</p>

</div>

---

## 🇬🇧 English

An advanced and powerful automation tool to create accounts on multiple platforms automatically, with full support for captcha solving, proxies, and webhook notifications.

### 🚀 Key Features
* **Full Automation:** The script handles the entire registration process without manual intervention.
* **Multi-Platform Support:** Works on 8 different platforms like Solpick, Tronpick, and more.
* **Automatic Captcha Solving:** Supports multiple modes for solving reCAPTCHA using external extensions.
* **Advanced Proxy Support:** Can run directly, through a proxy website, or by using a custom proxy list with account distribution.
* **Easy Config Generator:** A user-friendly web interface to generate your `config.json` file without editing code.
* **Webhook Notifications:** Sends notifications to a Discord webhook on successful account creation, including the cookie file.

### ▶️ How to Run via GitHub Actions

This script is designed to be run directly from GitHub. No local installation is needed.

**Step 1: Fork the Repository**
Click the **Fork** button at the top right of this page to create your own copy of this project.


**Step 2: Generate Your Configuration**
You must create a configuration file to tell the script what to do.
-   Go to the configuration generator website: **[https://swultra.ct.ws](https://swultra.ct.ws)**
-   Fill out the form with your preferences and download the `config.json` file.
-   **Copy the entire content** of the downloaded file. You will need it in the next step.

**Step 3: Create a Repository Secret**
Secrets are used to securely store your configuration.
-   In your forked repository, go to **Settings** > **Secrets and variables** > **Actions**.
-   Click **New repository secret**.
-   Name the secret exactly: `CONFIG_JSON`
-   Paste the content you copied from your `config.json` file into the **Value** field.
-   Click **Add secret**.


**Step 4: Run the Workflow**
Now you are ready to run the automation.
-   Go to the **Actions** tab in your forked repository.
-   In the left sidebar, click on the **"Run Automation"** workflow.
-   Click the **Run workflow** button, and then click the green **Run workflow** button again to confirm.
-   The automation will now start. You can click on the running job to see the logs in real-time.

### ✨ Upcoming Features
-   A user-friendly **Web Version** with more features is coming soon! Stay tuned.

### 💬 Support & Community
Need help or have a question? Join our community on Discord!

[![Join our Discord](https://img.shields.io/discord/1101968289758711868?color=5865F2&logo=discord&logoColor=white&style=for-the-badge)](https://discord.com/invite/DMBhp6Ce)

---

## 🇦🇪 العربية

أداة أتمتة متقدمة وقوية لإنشاء حسابات على عدة منصات بشكل آلي، مع دعم كامل للكابتشا، البروكسي، وإشعارات الويب هوك.

### 🚀 الميزات الرئيسية
* **أتمتة كاملة:** يقوم السكربت بعملية التسجيل بالكامل بدون تدخل يدوي.
* **دعم منصات متعددة:** يعمل على 8 منصات مختلفة مثل Solpick, Tronpick, وغيرها.
* **حل الكابتشا الآلي:** يدعم عدة أوضاع لحل reCAPTCHA باستخدام إضافات خارجية.
* **دعم متقدم للبروكسي:** يدعم العمل بدون بروكسي، عبر موقع بروكسي، أو باستخدام قائمة بروكسيات مخصصة مع توزيع الحسابات عليها.
* **مولد إعدادات سهل:** واجهة ويب سهلة لإنشاء ملف الإعدادات `config.json` بدون الحاجة لتعديل الكود.
* **إشعارات ويب هوك:** يرسل إشعارات إلى Discord عند إنشاء حساب جديد بنجاح، مع ملف الكوكيز.

### ▶️ كيفية التشغيل عبر GitHub Actions
تم تصميم هذا السكربت ليتم تشغيله مباشرة من GitHub. لا حاجة لتثبيت أي شيء على جهازك.

**الخطوة 1: اعمل فورك (Fork) للمشروع**
اضغط على زر **Fork** الموجود في أعلى يمين الصفحة لإنشاء نسخة خاصة بك من هذا المشروع.

**الخطوة 2: قم بإنشاء ملف الإعدادات**
يجب عليك إنشاء ملف إعدادات ليتمكن السكربت من العمل.
-   اذهب إلى موقع إنشاء الإعدادات: **[https://swultra.ct.ws](https://swultra.ct.ws)**
-   املأ النموذج بالإعدادات التي تريدها وقم بتنزيل ملف `config.json`.
-   **انسخ محتوى الملف الذي تم تنزيله بالكامل.** ستحتاجه في الخطوة التالية.

**الخطوة 3: أضف سيكرت (Secret) للمشروع**
تُستخدم الـ Secrets لتخزين إعداداتك بشكل آمن.
-   في مشروعك الذي قمت بنسخه (Fork)، اذهب إلى **Settings** > **Secrets and variables** > **Actions**.
-   اضغط على **New repository secret**.
-   اكتب اسم السيكرت تمامًا بهذا الشكل: `CONFIG_JSON`
-   في حقل **Value**، الصق المحتوى الذي نسخته من ملف `config.json`.
-   اضغط على **Add secret**.

**الخطوة 4: قم بتشغيل الورك فلو (Workflow)**
أنت الآن جاهز لبدء الأتمتة.
-   اذهب إلى تبويب **Actions** في مشروعك.
-   في الشريط الجانبي الأيسر، اضغط على الورك فلو المسمى **"Run Automation"**.
-   اضغط على زر **Run workflow**، ثم اضغط على الزر الأخضر **Run workflow** مرة أخرى للتأكيد.
-   ستبدأ عملية الأتمتة الآن. يمكنك الضغط على المهمة قيد التشغيل لمشاهدة سجلات التنفيذ مباشرة.

### ✨ الميزات القادمة
-   نسخة ويب سهلة الاستخدام مع ميزات إضافية **قادمة قريبًا**! ترقبوا.

### 💬 الدعم والمجتمع
هل تحتاج إلى مساعدة أو لديك سؤال؟ انضم إلى مجتمعنا على ديسكورد!

[![Join our Discord](https://img.shields.io/discord/1101968289758711868?color=5865F2&logo=discord&logoColor=white&style=for-the-badge)](https://discord.com/invite/DMBhp6Ce)

---

<div align="center">
  <h3>Made By MoGlitch</h3>
</div>
