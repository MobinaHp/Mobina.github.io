---
layout: posts
title: My Travel Blog Project 
---
## Travel Blog
<html>
<title>My Travel Blog Project</title>
    <h1 style="color: blue; text-align: center;">Travel Blog Website</h1>
</head>
<body>
    <div>
        <p style="text-align: center;">
            <a href="https://mobinahop.pythonanywhere.com" target="_blank">Visit the Blog Section</a>
        </p>
        <p dir="rtl" style="text-align: right;">
            برای این وبسات من از فریم‌ورک جنگو و اچ‌تی‌ام‌ال استفاده کردم. در ابتدا صفحات مختلف وبسایت را با استفاده از قالب‌های آماده‌ی Bootstrap طراحی کردم. پس از نصب پایتون و جنگو پروژه‌ی جنگو را با استفاده از دستور django-admin startproject projectname و اپ را با دستور python manage.py startapp appname در پروژه‌ی جنگو درست کردم.
            سپس در قسمت models.py با استفاده از کلاس ساختار جدول دیتابیس را تعریف کردم و بعد برای ساختن جدول‌های دیتابیس از دستورهای python manage.py makemigrations و python manage.py migrate استفاده کردم. در بخش views.py توابع مورد نیاز برای وبسایت را تعریف کردم که این قسمت مسئول مدیریت و پردازش اطلاعات است.
            مثلا برای
            <code>
                def home(request):
                    return render(request, 'index.html')
            </code>
            این تابع یک request دریافت می‌شود و با استفاده از render پاسخ برای کاربر ارسال می‌شود.
            بعد از تعریف توابع در قسمت views.py، URLهای وبسایت را در قسمت urls.py تنظیم کردم. بعد با استفاده از دستور python manage.py runsrver وبسایت را بر روی لوکال‌هاست بررسی کردم.
            در مرحله آخر وبسایت را بر روی سایت pythonanywhere دیپلوی کردم تا از طریق اینترنت قابل دسترسی باشد.
            در این وبسایت کاربر می‌تواند در بخش blog در بالای صفحه بلاگ‌های کاربرهای دیگر را بررسی کند و با کلیک بر روی Write New Blog وبلاگی جدید اضافه کند.
        </p>
    </div>
</body>
</html>