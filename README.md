<p dir='rtl' align='right'>
# persian_subwords
مجموعه persian_subwords از ۱۹۷۸۲ تصویر ساخته شده از زیرکلمات فارسی با فونت ها و سایزهای متفاوت تشکیل شده است. 

 داده ها به دو مجموعه ی آموزش و آزمایشی دسته بندی شده اند. مجموعه ی آموزش (train_set) متشکل از  ۲۰۰۰ تصویر با فونت بی نازنین به سایزهای ۸،۱۰،۱۲،۱۴و ۱۶  می باشد.در مجموعه آزمایشی (test_set)،  تصاویر ۴۰ صفحه از متون فارسی به همراه فایل متنی آن ها قرار داده شده است.

* از این مجموعه می توان برای حل مساله ی تشخیص نوری کلمات (ocr) استفاده نمود.

* برای دریافت مجموعه داده کامل شامل ۱۹۷۸۲ زیرکلمه ی مختلف با فونت های Bnazanin.BLotus,BTitr,BZar,BKoodak,Arial,TimesNewRoman,Tahoma و به سایزهای ۸،۱۰،۱۲،۱۴، و ۱۶ با آدرس الکترونیکی info@partdp.ai در تماس باشید.

ساختار فولدر train_set:
در این فولدر داده های آموزشی در فولدرهایی با نام های سه بخشی مثل 1_8_1  آمده است. همان طور که در فایل font_size.txt آمده است. بخش اول نشان دهنده ی اسم فونت. بخش دوم نشان دهنده سایز فونت و بخش آخر نشان دهنده نوع قلم (bold,italic,normal,undeline) می باشد.
 
* تصاویر به صورت ۴ بخشی نام گذاری شده اند. که بخش اول نشان دهنده ی شماره تصویر است و نظیر متنی آن در فایل subwords.txt قرار داده شده است.

ساختار فولدر test_set:
مجموعه ی تست شامل ۳ فولدر مجزا است که در هریک از این فولدرها تصاویری از متون فارسی قرار داده شده است. فایل متنی ای که تصاویر هر فولدر با استفاده از آن تولید شده اند به صورت فایل txt در فولدر test_set قرار گرفته است.
</p>
