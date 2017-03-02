<p align="center"> <img src="http://www.pic98.ir/upload/bniu_untitled-3.png" width="240">
<h1><p align="center">تبلیغ‌گر
<h2><p align="center">سرعت 💠 دقت 💠 قدرت
<div align="center">
    <a href="https://telegram.me/Naji_MessengerRobot">
        <img src="http://upir.ir/951/guest/Untitled-5.png" hspace="10" width="150">
    </a>
    <a href="https://telegram.me/i_advansitor">
        <img src="http://upir.ir/951/guest/Untitled-7.png" hspace="10" width="150">
    </a>
    <a href="https://telegram.me/i_naji">
        <img src="http://upir.ir/951/guest/Untitled-6.png" width="150">
    </a>
</div>

<h3><p dir="rtl">تبلیغ‌گر رباتی هوشمند, بسیار ساده و البته رایگان جهت امور تبلیغاتی در تلگرام است.<br>
نوشته شده توسط <a href="https://telegram.me/i_naji">ناجی</a> برپایه اخرین نسخه <a href="https://valtman.name/telegram-cli">تلگرام</a>.
<br>
<h3 align="right"> <strong> نصب و راه‌اندازی</strong> 🚀
</h3>
<hr>
<h4 dir="rtl">ابتدا سورس <em>ربات تبلیغ‌گر</em> را کپی کرده و پیش‌زمینه‌ها را نصب کنید.</h4>
<h6>(موارد زیر را در ترمینال وارد کنید)</h6>
<pre>
<span>git clone https://github.com/i-naji/tabchi.git -b persian</span>
<span>cd tabchi</span>
<span>chmod +x bot</span>
<span>./bot install</span>
</pre>
<h4 dir="rtl"> برای ساخت ربات جدید <strong>bot create/.</strong> را وارد کنید.
</h4>
<pre>
<span>./bot create</span>
</pre>
<h4 dir="rtl">حال با توجه به شناسه ای که برای ربات جدید داده شده تبلیغ‌گر خود را راه‌اندازی کنید.
<br>مثال:</h4>
<pre>
<span>./bot 1</span>
</pre>
<h5 dir="rtl">توجه داشته باشید برای اولین بار که ربات را راه اندازی می‌کنید،از شما شناسه عددی مدیر ربات (شما و یا هرکس که می خواهید مدیر ربات شود) ، شماره ربات و کد ورود به حساب کاربری خواسته می‌شود.
<h6 dir="rtl"> شما می توانید با استفاده از ربات <a href="https://telegram.me/id_probot">@ID_ProBot</a> شناسه عددی خود را بدست آورید.</h6>
<h6 dir="rtl">از <a href="#help">راهنمای‌تبلیغ‌گر</a> برای ثبت گروه مدیریتی و آشنا شدن با طرز کار رباتتان استفاده کنید.</h6>
<br>
<h3 align="right"><strong>جلوگیری از قطع شدن عملکرد تبلیغ‌گر</strong>🛡
<hr>
<h4 dir="rtl">یکی از مشکلات کار با SSH، قطع شدن آن در زمان قطع اتصال اینترنت است.<br>وقتی اتصال اینترنت قطع می‌شود اجرای تمامی برنامه‌ها و فرامینی که در حال استفاده از SSH بودند، متوقف می‌شود. فرمان screen این‌جا به‌کمک شما می‌آید. کافی است این دستور را قبل از دستورراه‌اندازی تبلیغ‌گر قرار دهید.</h4>
<h6 dir="rtl">مثال:</h6>
<pre>
<span><strong>screen ./bot 1</strong></span>
</pre>
<h4 dir="rtl">برای خارج شدن از محیط screen کلید‌های ترکیبی Ctrl+A و سپس کلید D را بفشارید.<br>برای مشاهده فهرست screen های موجود می‌توانید از دستور<strong>  screen -ls  </strong>  استفاده کنید.<br>این دستور فهرست تمامی screen های در حال اجرا را نمایش می‌دهد.<br>برای مشاهده screen اجرا‌شده، کافی است دستور زیر را وارد کنید:</h4>
<pre>
<span><strong>screen -r [screen name]</strong></span>
</pre>
<br>
<h4 id="help" dir="rtl">&#x272F; راهنمای تبلیغ‌گر :</h4>
<table style="width:100%" dir="rtl">
  <tr>
    <th colspan="3">مخصوص مدیر</th>
  </tr>
  <tr>
    <th colspan="2">دستور</th>
    <th>عملکرد</th>
    <th></th>
    <th>فقط در گروه (&#x2724;)<br>فقط در ریپلای (&#x21BB;)</th>
    </tr>
   <tr>
    <td colspan="2">reload/</td>
    <td align="center">بارگذاری مجدد ربات و راه‌اندازی دوباره</td>
  </tr>
  <tr>
    <td colspan="2">بروزرسانی ربات</td>
    <td align="center">بروزرسانی ربات به آخرین نسخه<br> و بارگذاری مجدد</td>
  </tr>
  <tr>
    <td>تنظیم مدیر</td>
    <td>شناسه</td>
    <td align="center">جایگزینی مدیر جدید با شناسه عددی</td>
  </tr>
  <tr>
    <td colspan="2">تنظیم گروه مدیریت</td>
    <td align="center">در نظر گرفتن گروه به‌عنوان گروه مدیریتی</td>
    <td align="center">&#x2724;</td>
  </tr>
  <tr>
    <td colspan="2">حذف گروه مدیریت</td>
    <td align="center">حذف گروه از دیتابیس به‌عنوان گروه مدیریتی</td>
  </tr>
  <tr>
    <td colspan="2">ترک کردن</td>
    <td align="center">خارج شدن از گروه و حذف<br>از اطلاعات گروه‌ها</td>
    <td align="center">&#x2724;</td>
  </tr>
   <tr>
    <th colspan="3">مخصوص مدیر و گروه مدیریتی</th>
  </tr>
  <tr>
    <td colspan="2">شناسه من</td>
    <td align="center">ارسال شناسه عددی شما</td>
  </tr>
  <tr>
    <td colspan="2">شناسه مدیر</td>
    <td align="center">ارسال شناسه عددی مدیر</td>
  </tr>
  <tr>
   <td>بگو</td>
    <td>متن</td>
    <td align="center">ارسال متن</td>
    </tr>
  <tr>
   <td>تنظیم نام</td>
    <td>"نام" نام‌خانوادگی</td>
    <td align="center">تغییر نام</td>
    </tr>
      <tr>
   <td>تنطیم نام کاربری</td>
    <td>نام کاربری</td>
    <td align="center">جایگزینی نام کاربری داده شده<br>(دفعات استفاده محدود در زمان کوتاه)</td>
    </tr>
    <tr>
   <td colspan="2">حذف نام کاربری</td>
    <td align="center">حذف نام کاربری<br>(دفعات استفاده محدود در زمان کوتاه)</td>
    </tr>
  <tr>
   <td rowspan="2">افزودن با شماره</td>
    <td>روشن</td>
    <td rowspan="2" align="center">تغییر وضعیت اشتراک شماره تبلیغ‌گر<br>در جواب شماره به اشتراک گذاشته شده</td>
    </tr>
    <tr>
    <td>خاموش</td>
    </tr>
     <tr>
   <td rowspan="2">افزودن با پیام</td>
    <td>روشن</td>
    <td rowspan="2" align="center">تغییر وضعیت ارسال پیام در جواب<br>شماره به اشتراک گذاشته شده</td>
    </tr>
    <tr>
    <td>خاموش</td>
    </tr>
    <tr>
    <td>تنظیم پیام افزودن مخاطب</td>
    <td>متن</td>
    <td align="center">تنظیم متن داده شده به عنوان جواب<br>شماره به اشتراک گذاشته شده</td>
  </tr>
  <tr>
    <td colspan="2">لیست مخاطبین</td>
    <td align="center">ارسال تمام مخاطبین ذخیره شده<br>در قالب پرونده متنی</td>
  </tr>
  <tr>
    <td>مسدودیت</td>
    <td>شناسه</td>
    <td align="center">مسدود‌کردن(بلاک) کاربر با شناسه داده شده</td>
  </tr>
  <tr>
    <td>رفع مسدودیت</td>
    <td>شناسه</td>
    <td align="center">رفع مسدودیت کاربر با شناسه داده شده</td>
  </tr>
  <tr>
   <td rowspan="2">وضعیت مشاهده</td>
    <td>روشن</td>
    <td rowspan="2" align="center">خاموش و یا روشن‌کردن وضعیت مشاهده پیام‌ها<br>(فعال و غیر‌فعال‌کردن تیک دوم)</td>
    </tr>
    <tr>
    <td>خاموش</td>
    </tr>
  <tr>
    <td colspan="2">امار</td>
    <td align="center">ارسال آمار و وضعیت تبلیغ‌گر</td>
  </tr>
  <tr>
    <td rowspan="4">ارسال به</td>
    <td>همه</td>
    <td rowspan="4" align="center">ارسال پیام جواب داده شده<br> به مورد خواسته شده</td>
    <td rowspan="4">&#x21BB;</td>
    </tr>
    <tr>
    <td>خصوصی</td>
    </tr>
    <tr>
    <td>گروه</td>
    </tr>
    <tr>
    <td>سوپرگروه</td>
  </tr>
  <tr>
    <td>ترک کردن</td>
    <td>شناسه</td>
    <td align="center">خروج از گروه با‌شناسه وارد شده<br>و حذف از اطلاعات گروه</td>
  </tr>
</table>
<h6 dir="rtl">اساس کار تبلیغ‌گر تشخیص لینک و عضویت در هر گروه‌ها و پیروی از دستورات تعیین شده است.</h6>
<br>
<h3 dir="rtl">نسخه &#x2780; :</h3>
<hr>
<h4 dir="rtl"><strong>امکاناتی که در نسخه &#x2780; افزوده خواهند شد + انتشار نسخه رسمی :</strong>
<br>&#x25A3; افزودن تمام مخاطبین و کاربران گفت‌و‌گو خصوصی به گروه
<br>&#x25A3; افزودن کاربری خاص به تمامی گروه ها و سوپرگروه ها
<br>&#x25A3; ارسال پیام به یک چت خاص یا دسته ای از چت ها
<br>&#x25A3; حالت پاسخگوی خودکار،حساس به برخی عبارات
<br>&#x25A3; افزودن و حذف کردن عبارات پاسخگویی خودکار
<br>&#x25A3; پایه ای با برنامه نویسی خلاصه تر و سریعتر
<br>&#x25A3; حذف و اضافه کردن عکس پروفایل
</h4>
<br>
<h3 dir="rtl">در آینده :</h3>
<hr>
<h4 dir="rtl"><strong>امکاناتی که پروژه تبلیغ‌گر  بعد ها به خود خواهد دید</strong>
<br>&#x25A3; تعیین حد مجاز برای عضویت در گروه ها
<br>&#x25A3; خارج شدن از گروه در صورت اسپم
<br>&#x25A3; مسدود کردن کاربر در صورت اسپم
<br>&#x25A2; تغییر شماره توسط مدیر
<br>&#x25A2; حذف حساب کاربری تبلیغ‎گر توسط مدیر
<br>&#x25A2; افزودن و یا تغییر ایمیل تایید دو مرحله ای
<br>&#x25A2; غیر فعال کردن دیگر نسشت ها
<br>&#x25A2; عضویت در گروه ها با حداقل و یا حداکثر ظرفیت مشخص
<br>&#x25A2; خارج شدن از گروه در صورت عدم فعالیت در بازه زمانی مشخص
<br>&#x25A2; فرستادن نوع خاصی از رسانه دریافت شده به گروه مدیریت
<br>&#x25A2; ربات کمک رسان با قابلیت سازماندهی(ارسال پیام در زمان خاص,کیبورد شیشه ای)
<br>&#x25A2; سازماندهی چند تبلیغ‌گر جهت جلوگیری از عضویت در گروه های یکسان
<br>&#x25A2; فرستادن پیام ها از یک گفت و گوی خصوصی خاص
<br> .
<br> .
<br> .
</h4>
<br>
<h4 dir="rtl"><strong>🆓بهترین سرور‌های رایگان</strong>
<div align="center">
    <a href="https://codeanywhere.com/">
        <img src="http://upir.ir/951/guest/codeanywhere.png" width="150">
    </a>
    <a href="https://www.c9.io/">
        <img src="http://upir.ir/951/guest/c9.png" hspace="20" width="150">
    </a>
    <a href="https://codenvy.io/dashboard/">
        <img src="http://upir.ir/951/guest/codenvy.png" hspace="20" width="150">
    </a>   
</div>
<br>
<h2 dir="rtl">پشتیبانی
<hr>
<h4 dir="rtl">پذیرای انتقادات وپیشنهاداتان هستیم ♚ NajiTeam ♚ <a href="https://telegram.me/i_naji"> @i_naji </a> <a href="https://telegram.me/Naji_MessengerRobot"> @Naji_MessengerRobot</a>
<br>راهنمای استفاده از تبلیغ‌گر بسیار ساده و قابل درک است<br>فیلم آموزشی نصب و اطلاع از آخرین اخبار تبلیغ‌گر در کانال ما 
<a href="https://telegram.me/i_advertiser"> @i_advertiser</a>
</h4>