# git-cheatsheet
dwclass training git
Welcome to the git-cheatsheet wiki!
Working with Git:
1- برای اینکه تمام کد برنامه در یک جا ذخیره بشه و یک منبع اصلی برای ذخیره برنامه داشته باشیم که در این صورت 
چندین برنامه نویس نیز باهم می توانند روی یک پروژه مشترک کار کنند.
2- ریپوزیتوری مخزنی هست که مجموعه ای از کامیت ها و برنچ ها داخل آن هستندو یک ریپوزیتوری خوب شامل فایل های زیر میباشد:
README.md , LICENSE , .gitignore
3- .git , .gitignore , README.md
4- git clone : این دستور برای نمونه گیری از یک پروژه استفاده می شود که در این صورت میتوانیم پروژه را روی لپ تاپ خود داشته باشیم
5- git pull HEAD
6- reset: تغییرات را برمیگرداند و اون کامیت را حذف میکند
revert: بعد از بازگشت تغییرات یک کامیت جدید درست می شود
checkout: تغییرات باز میگردند اما هیچ کار خاصی انجام نمیشه نه کامیتی حذف میشه و نه اضافه
7- merge: تغییرات از یک برنچ به برنچ دیگری منتقل میشه و اینکه چیزی که اضافه میکنیم به خط مبدا یا ورکینگ دایرکتوری بچسبونیم
rebase:تغییرات براساس کامیت و پرنت ها پشت سر هم قرار بگیرن 
8- git log
9- git show HEAD
10- برای ساختن ورژن کاربرد دارند. زمانی که کد برنامه کامل شد از تگ مناسب استفاده میکنیم تا بتونیم ریلیز هم درست کنیم
11- reading README.md and .gitignore and LICENSE 
قدم بعدی ایجاد یک ریپوزیتوری لوکالی وبعد از انجام تست های لازم کامیت میزنیم و تغییرات را اعمال میکنیم.
12- هر کدی که میزنیم در کامیت ها ذخیره میشود و کامیت ها نیز درون برنچ های مختلفی هستند
برای پیش بردن یک پروژه از دو روش مختلف یا اینکه داشتن یک برنچ اصلی و یک برنچ تست که در نهایت با هم merge میشن
 git merge test تغییرات از برنچ main به برنچ test منتقل میشود



