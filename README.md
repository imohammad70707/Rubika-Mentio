#🤖 Rubika Mention Bot

🇬🇧 English | 🇮🇷 فارسی

🇬🇧 English
📌 About

Rubika Mention Bot is a simple Rubika bot designed to mention users in groups.

The bot keeps track of users who send messages in an activated group and allows the administrator to mention a selected number of users using a simple command.

✨ Features
🔗 Connect to Rubika using maxrubika
⚡ Activate the bot in a group with فعال
👥 Automatically add users who send messages to the mention list
📢 Mention users with the تگ command
🔢 Choose the number of users to mention
🎯 Default: up to 300 users
📊 Custom range: 1 to 1000 users
📦 Installation

Install the required library:

pip install maxrubika
⚙️ Configuration

In line 8, where the bot token is requested, replace Token with your bot token.

Alternatively, you can run the project without changing the code and enter your bot token directly in the console when requested.

🚀 Usage

First, activate the bot in your group by sending:

فعال

After activation, users who send messages in the group will automatically be added to the bot's mention list.

To mention users, send:

تگ

By default, the bot can mention up to 300 users.

You can also specify the number of users:

تگ 10

This will mention 10 users.

The supported range is:

Minimum: 1
Maximum: 1000
Default: 300
🔄 How It Works
👥 User sends a message
        ↓
📋 User is added to the list
        ↓
📢 Admin sends "تگ"
        ↓
🎯 Bot selects users
        ↓
🔔 Users are mentioned
🛠️ Requirements
Python
maxrubika
👨‍💻 Developer

Original source/contact:

@TheMAXRubika

🇮🇷 فارسی
📌 درباره پروژه

Rubika Mention Bot یک ربات ساده برای تگ (منشن) کردن کاربران در گروه‌های روبیکا است.

ربات کاربران فعال گروه را شناسایی کرده و آن‌ها را در لیست منشن قرار می‌دهد. سپس مدیر گروه می‌تواند با استفاده از یک دستور ساده، تعداد مشخصی از کاربران را منشن کند.

✨ قابلیت‌ها
🔗 اتصال به روبیکا با استفاده از maxrubika
⚡ فعال‌سازی ربات در گروه با دستور فعال
👥 اضافه شدن خودکار کاربران فعال به لیست منشن
📢 منشن کردن کاربران با دستور تگ
🔢 امکان تعیین تعداد کاربران برای منشن
🎯 حالت پیش‌فرض: حداکثر ۳۰۰ نفر
📊 محدوده قابل انتخاب: ۱ تا ۱۰۰۰ نفر
📦 نصب

ابتدا کتابخانه موردنیاز را نصب کنید:

pip install maxrubika
⚙️ تنظیمات

در خط هشتم، جایی که از شما توکن ربات را می‌خواهد، مقدار Token را با توکن ربات خودتان جایگزین کنید.

همچنین می‌توانید بدون تغییر کد، پروژه را اجرا کرده و توکن ربات را مستقیماً در کنسول وارد کنید.

🚀 نحوه استفاده

بعد از اجرای ربات، ابتدا در گروه دستور زیر را ارسال کنید:

فعال

پس از فعال شدن ربات، هر کاربری که در گروه پیام ارسال کند، به لیست کاربران قابل منشن اضافه خواهد شد.

برای منشن کردن کاربران، دستور زیر را ارسال کنید:

تگ

در حالت پیش‌فرض، ربات حداکثر ۳۰۰ کاربر را منشن می‌کند.

همچنین می‌توانید تعداد کاربران را مشخص کنید:

تگ 10

در این حالت، ۱۰ کاربر منشن خواهند شد.

محدوده تعداد:

حداقل: ۱ نفر
حداکثر: ۱۰۰۰ نفر
پیش‌فرض: ۳۰۰ نفر
🔄 نحوه عملکرد
👤 ارسال پیام توسط کاربر
        ↓
📋 اضافه شدن کاربر به لیست
        ↓
📢 ارسال دستور «تگ»
        ↓
🎯 انتخاب کاربران
        ↓
🔔 منشن کردن کاربران
🛠️ پیش‌نیازها
Python
کتابخانه maxrubika
👨‍💻 سازنده / منبع

منبع اصلی:

@TheMAXRubika

⭐ اگر پروژه برایتان مفید بود، می‌توانید Repository را Star کنید.
