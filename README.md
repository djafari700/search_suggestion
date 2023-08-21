# search suggestion | پیشنهاد خودکار
به یک تمرین جالب و کاربردی از پردازش زبان طبیعی (NLP) خوش آمدید! در این تمرین به سراغ یک مسئله‌ی کاملاً واقعی و چالش‌برانگیز صنعت خواهیم رفت. مشاهده کرده‌اید که در وب‌سایت‌ها هنگامی‌که در حال تایپ داخل یک فیلد متنی هستید معمولاً لیستی از متن‌های مشابه به شما پیشنهاد می‌شود. نمونه‌ای از این قابلیت که در وب سایت مستربلیط به کار گرفته شده را در تصویر زیر مشاهده می‌کنید.

![Alt Text](/notebook/screenshot.png)



با این حال معمولاً چنین لیست‌های پیشنهادی‌ای بسیار ساده هستند و تنها عباراتی را که با رشته‌ی تایپ‌شده‌ی کاربر شروع می‌شوند پیشنهاد می‌دهند تا کاربر نیازی به تکمیل تایپ خود نداشته باشد و زودتر به نتیجه برسد. اما در این تمرین قصد داریم پیشنهاددهنده‌ای بسازیم که هوشمندتر و منعطف‌تر عمل کند. به‌عنوان مثال شاید کاربر عبارت «بابل» را تایپ کرده اما در ابتدا غلط املایی داشته و منظورش «زابل» بوده باشد.  یا شاید همان‌طور که حتماً برای شما هم پیش آمده و روی اعصاب‌تان رفته یادش رفته باشد که کیبورد خود را روی زبان فارسی تنظیم کند و عبارتی مثل «fhfg» را تایپ کرده باشد. همچنین چرا اسم‌های انگلیسی شهرها را هم در نظر نگیریم و وقتی شخص مثلاً «Zahedan» را تایپ کرده باشد متوجه نشویم که منظورش «زاهدان» بوده است؟ با این حال، این‌ها تنها تعدادی از الگوهای ممکن هستند که منجر به بهبود پیشنهادهای سیستم خواهند شد. ما می‌توانیم به کمک داده‌های جمع‌آوری‌شده از آن‌چه که کاربران مرحله به مرحله تایپ کرده‌اند و آن‌چه که در نهایت انتخاب کرده‌اند مدلی طراحی کنیم که با توجه به ورودی کاربر، لیستی از محتمل‌ترین انتخاب‌ها را به وی پیشنهاد دهد.



