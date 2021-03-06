---
layout: doc-rtl
title: ثبت راه‌ها، ساختمانها، آبها و کاربری اراضی 
permalink: /fa/coordination/remote-tracing/
lang: fa
category: coordination
---

ردیابی راه‌ها، ساختمانها، آبها و کاربری اراضی
===========================================

> تاریخ بازبینی ۱۳۹۴/۱۱/۱۹  

در ادامه بخش [Remote, Armchair & Mapathon Section of LearnOSM](/en/coordination/remote/) و در صورتی که با نقشه‌کشی برای HOT آشنایی ندارید به این نیاز پیدا خواهید کرد.  


فهرست بخش
=====

[جاده‌ها و بزرگراه‌ها، و نیز مسیرها و گذرگاه‌ها](/fa/coordination/remote-tracing/#roads)  
[شبکه بزرگراه‌ها](/fa/coordination/remote-tracing/#the-highway-network)  
[محدوده اراضی با کاربری مسکونی](/fa/coordination/remote-tracing/#residential-boundaries)  
[ساختمانها، دیواره‌ها، نرده‌ها، ترکیبها و موانع](/fa/coordination/remote-tracing/#buildings-walls-compounds-barriers)  


##  راه‌ها

در OpenStreetMap هرگونه جاده‌ای از آزادراه گرفته تا گذرگاه‌ها و مسیرها با عنوان 'راه' شناخته می‌شوند. بسیار مهم است که جاده‌ها به طور صحیحی به پایگاه داده (داده‌های OpenStreetMap) اضافه شوند چونکه به روشهای زیادی مورد استفاده قرار می‌گیرند:  

- نرم‌افزارهای مسیریاب مانند دستگاههای گارمین و برنامه‌های موجود برای گوشی‌های هوشمند مانند Osmand قابلیت این را دارند که اطلاعات مسیریابی را در فواصل بسیار طولانی ارائه کنند به شرطی که اطلاعات درستی به آنها داده شود. از آنجا که این دستگاه‌ها برای تشخیص موقعیت نسبت به نقشه پایه‌ای که درون آنها بارگزاری شده است متکی به GPS درونی گوشی هستند، بسیار مهم است که راه‌ها دقیقاً با فاصله حداکثر ۱۵ متری از جای اصلی صحیح خود قرار داشته باشند والا درست کار نمی‌کنند.  
- برنامه‌ریزی مسیر برای یک کامیون بزرگ امدادی بسیار ساده‌تر خواهد بود چنانچه بتوانید بین یک مسیر و جاده بزرگراه و همه دسته‌های بینابینی این دو افتراق قائل شوید.  
دانستن اینکه سطح جاده آسفالت یا خاک نرم است در برنامه‌ریزی مسیر شما تأثیر خواهد گذاشت.
- زمانی که شیوع یک بیماری را بررسی می‌کنید، توصیف اینکه یک مصدوم  "نزدیک صلیب سرخ" می‌باشد بسیار مهم است اگر بتوانید صلیب سرخ را بر روی نقشه ببینید.

###  راه‌ها - چگونه نقشه بکشیم

![iD 3][]

1. هنگام کشیدن راهها اطمینان حاصل کنید که به قدر کافی زوم کرده‌اید. به عنوان شروع مقیاس را روی ۲۰ متر تنظیم کنید و جاده را طوری ترسیم کنید که حتی‌المکان شکل آن حفظ شود و یا خیلی نزدیک به آن جاده‌ای باشد که در تصاویر ماهواره‌ای می‌بینید. در تصویر بالا می‌بینید که من جاده‌ای رسم کرده‌ام که به طرف پائین کشیده شده و از میان درختان عبور می‌کند و در ادامه به سمت ساختمانی رفته که به نظر می‌رسد در انجا تمام می‌شود. در آنجایی که درختها نزدیک جاده هستند و تصاویر ماهواره‌ای از بالا گرفته شده به نظر میرسد که جاده برای  عبور از میان درختان باریک می‌شود - گرچه این به خاطر اثر درختان است که جلو دید را می‌گیرد و عرض جاده در تمام مسیر یکسان است.  
2. همچنین بخش دیگری از جاده را ترسیم کرده‌ام تا به انتهای جاده دیگری بچسبد - iD این نقطه اتصال را با شکل یک نقطه بزرگتر و تیره‌تر نشان می‌دهد. اتصال جاده‌ها به هم و داشتن 'یک نقطه مشترک' جهت راهنمایی صحیح نرم‌افزارهای مسیریاب حیاتی است.  
3. جاده با تگهای 'highway=residential' و نیز 'surface=unpaved' تگ زده شده است.  
4. جهت شرح کاملی از تگ زنی در آفریقا به صفحه ویکی [تگ جاده‌های آفریقا]() رجوع کنید.  

> ریسک زیادی در ویرایش جاده‌هایی که به مربع‌های مجاور که شاید سایر کاربران در حال ویرایش آنها هستند و موجب ایجاد تداخل می‌گردد، وجود دارد. توصیه می‌شود همه تغییرات خود را قبل از ویرایش جاده‌ها ذخیره کنید و نیز با فواصل معین مثلا پس از اضافه کردن هر شش نقطه یکبار تغییراتتان را ذخیره کنید.


### شبکه جاده‌ای

![JOSM 4][]

این تصویر JOSM را در حال استفاده از طرح HOT-OSM-Validate نشان می‌دهد [طرح‌های JOSM](https://josm.openstreetmap.de/wiki/Styles). گر چه این طرح برای کمک به اعتبارسنج‌ها طراحی شده، اما می‌تواند در هنگام انجام نقشه‌کشی اولیه نیز بسیار مفید باشد. هر چیزی که رنگ قرمز دارد، دارای نوعی مشکل است - دیگر رنگها در راهنمای تصویر توضیح داده شده است.  

1. این قسمت از بزرگراه قرمز رنگ است چرا که برچسب به اشتباه تایپ شده و از حروف بزرگ استفاده شده است. برچسب باید highway=unclassified باشد، که در تصویر رنگ قهوه ای کم رنگ دارد.  
2. این بخشی از شبکه بزرگراه شهر تا جنوب غربی است. این شبکه به بقیه شبکه بزرگراههای آفریقا متصل می‌شود.  
3. این بخش بزرگراه از "جدا شده" است. اینها به هیچ وجه به شهر یا بزرگراه دیگری متصل نمی‌شوند. در حالت فعلی این بزرگراهها کاربرد زیادی ندارند و باید دید که آیا می‌توان آنها را به بقیه شبکه متصل کرد یا خیر، و یا اینکه برای خرف کردن آنها باید تحقیقات بیشتری انجام شود.  


**بزرگراه یا جریان آبی؟**

![iD 5][]

هیچ سبک نمایشی برای استفاده در  iD وجود ندارد، اما در این تصویر می‌توانید یک منطقه پوشیده شده از گیاه و یک منطقه زمین بایر را ببینید. زمین به نظر می‌رسد خرد و یا شاید حتی یک منطقه از marshland بدون وجود آب باشد. خطوط نقطه‌چین سیاه و سفید نشان‌دهنده مسیرهایی در iD هستند که من موقتاْ آنها را پررنگ کرده‌ام و سپس یکی از آنها را برای نمایش پستی و بلندی زمین حذف کرده‌ام.  

1.  highway=path یا بستر رودخانه. شاید هر دو! جاده‌ها در هر اندازه‌ای اغلب از مسیر دره رودخانه پیروی می‌کنند و در بسیاری از موارد احتمال دارد مسیر رودخانه یا جریان فصلی را دنبال کنند. در این مورد، به نظر می‌رسد که یک بستر سیلاب است که در زمان گرفتن تصاویر ماهواره‌ای خشک بوده و از آن به عنوان مسیر استفاده می‌شده است. بهتر است این مورد را اینطور برچسب‌گذاری کرد:  
highway=path  
seasonal=yes  
surface=unpaved  
2. می‌توان به وضوح مسیر را  دید که به طرف و به درون درختان و درختچه‌ها میرود، اما امکان مشاهده دقیق مسیر آن از بین درختان نیست. در این شرایط می‌توانید مطمئن باشید که مسیر، جاده‌ای وجود دارد، و فقط به خاطر درختان از معرض دید خارج می‌شود. من این را با ادامه دادن مسیر تا جایی که روی زمین کاملاْ دیده می‌شود و کشیدن یک خط مستقیم از بین درختان تا جایی که به وضوح از طرف مقابل خارج می‌شود رسم کردم. از این حالت با احتیاط استفاده کنید، اما در این مثال واضح است که مسیری وجود دارد و مسیرش نیز احتمالا بسیار نزدیک به خطی است که من کشیده‌ام. از این کار استفاده زیادی می‌شود  - معمولتر است که مسیر جاده‌ها را در مواردی که توسط یک یا چند درخت پوشیده شده با تخمین حدود چند متر بکشیم.  
3. با حذف کردن مسیر می‌توان زمین را به وضوح دید، و به راحتی می‌توانم آن را با استفاده از ویژگی 'برگرداندن' iD به سر جایش برگردانم.  

***


## محدوده‌های مسکونی

از مرزهای مسکونی برای مقاصد بسیاری در OpenStreetMap استفاده می‌شود.  

+ ساده‌ترین کاربرد این است که بتوانید هنگام مشاهده [OpenStreetMap.org](http://www.openstreetmap.org) در زوم‌های بالاتر مناطق  ببینید، که در نمای استاندارد دارای رنگ خاکستری کمرنگ هستند.  
+ جایی که از ابتدا وقت نقشه‌کشی جزئیات نیست، پروژه درون مدیر وظایف اغلب نیاز به چیزی شبیه به این دارد:  

> نقشه مکانهای زیربنایی ضروری مانند مدارس، محل عبادت و بازار را بکشید.  
> محدوده‌های مسکونی و گورستانها را بکشید.  
> ما بعدا در یک وظیفه دیگر مسیرها را خواهیم کشید.   
+ همچنین از landuse=residential برای اهداف آماری نیز می‌توان استفاده کرد و پس از آن نقشه دقیق با اهمیت می‌شود.  

* اگر بتوانید تعیین کنید که چگونه بسیاری از مردم به طور معمول در هر محل اقامت جایگزین می‌شوند، و  
 چه تعداد  محل اقامت در یک منطقه مشخص ساخته شده، سپس  
 به محض کشیدن همه مناطق مسکونی با محدوده landuse=residential،  
 می‌توانید جمعیت تقریبی آن منطقه را تخمین بزنید.  
  برآورد تعداد کمک‌رسانان و تعداد نیاز پزشکی اکنون واقعی‌تر است.
* نام محلها و مرزها اغلب از منابع دیگر وارد می‌شود، اما مکان آن همیشه دقیق نیست. هنگامی که مرزهای مسکونی را بکشید کسی کهایمپورت اطلاعات را انجام می‌دهد می‌تواند ببیند که نام محل احتمالا کجا قرار بگیرد.


### landuse=residential - چگونه نقشه‌اش را بکشیم


**در جهان ایده‌ال**  

*مرحله ۱* - تصمیم به نقشه‌کشی یک منطقه گرفته می‌شود، و یک نقشه‌کش سریعاْ محدوده بسیار غیردقیق landuse=residential را در اطراف یک منطقه می‌کشد،  
*مرحله ۲* - پروژه مدیر وظیفه ایجاد می‌شود و هر نقشه‌کش دیگری محدوده را اصلاح می‌کند به طوری که به ساختمانها و سلیر عوارض نزدیکتر باشد.  

![JOSM residential][]

![iD residential][]
 
تصاویری از iD و JOSM در بالا یک مرز صحیح landuse=residential را نشان می‌دهد.  

1. مرز باید بسته باشد، به طوری که نقطه شروع خط (مسیر)، به نقطه انتهایی می رسد.  
2. هیچ قطعه یا نقطه‌ای از مرز نباید به راه‌ها، مسیرهای آبی، ساختمان‌ها، و یا سایر عوارض بچسبد. *یعنی اینکه* نباید هیچ گره مشترکی داشته باشند اما می‌توانند از هم عبور کنند.  
3. مرز باید نسبتاْ نزدیک به ساختمانها و هر باغ یا حیاطی که بخشی از یک گروه است، باشد.  


در تصویر زیر، مربع من شامل بخشی از یک landuse=residential است. فردی که مربع سمت راست من را تکمیل کرده، یک مرز landuse=residential را از مربع‌اش به مربع من گسترش داده و سپس به درستی با قرار دادن آن در لبه محدوده مربع من، می‌توانم آن را در جای صحیحش قرار دهم و آنرا کامل کنم.  


![JOSM residential 1][]

من گره‌های بیشتری را به مرز اضافه می‌کنم، آن را به صورت افقی در سراسر مربع خودم در اطراف ساختمانها گسترش می‌دهم، و آنرا در مرز پایینی به صورت یک خط مستقیم دقیقاْ داخل لبه مربع زیری میکشم به طوری که فردی که مربع پایینی را انتخاب می‌کند قادر خواهد بود آن را در اطراف همه ساختمانهایی که در آن مربع قرار دارد گسترش دهد.  

این یک کار دشوار است - شما فقط می‌توانید بخش کوچکی از کل شهر/شهرستان/روستا را مشاهده کنید و اگرچه بهترین مرز landuse=residential می‌کشید، احتمال دارد شخصی که اعتبارسنجی را انجام میدهد و دارای دیدی از چندین مربع است نیاز داشته باشد تا برای مرتب کردن مرز پس از اینکه هر شخص مربع خود را نقشه کشیده کارهای اضافه‌تری انجام دهد.  

> در هنگام کار روی یک مرز landuse=residential خطر بالقوه تداخل وجود دارد، چونکه از یک مربع به مربع‌های دیگر کشیده می‌شود که نقشه‌کشهای دیگری در حال ویرایش آنها هستند. توصیه می‌شود قبل از ویرایش مرزها همه تغییرات خود را ذخیره کنید و سپس تغییرات خود را یطور متوالی، مثلاْ پس از اضافه کردن هر 6 گره، ذخیره کنید.

***


## دیوارهای ساختمانها موانع ترکیبی  

به دلایل مختلف ساختمانها به داده نقشه اضافه می شوند؛  

* تراکم ساختمانها در یک منطقه به خوبی تعداد افراد ساکن در آن منطقه را نشان می‌دهد.  
* اندازه، شکل و موقعیت یک ساختمان می‌تواند به شناسایی آن به عنوان یک محل تخلیه یا مکان درمانی احتمالی کمک کند.  
* اندازه، شکل و موقعیت نسبی ساختمانها می‌تواند برای شناسایی مکانهای خاص مانند چاه‌ها، ایستگاه‌های کمک، مدارس و غیره استفاده شود.  
* پتانسیل برآورد میزان خسارت ساختمان وجود دارد که می‌تواند برای تخمین تلفات بالقوه و سطح پشتیبانی مورد نیاز باشد - این کاربرد در حال حاضر (ژانویه ۲۰۱۵) برای استفاده در آینده مورد بحث است.  


### ساختمانها - چگونه نقشه بکشیم

اکثریت قریب به اتفاق ساختمانهایی که نیاز به نقشه‌کشی توسط HOT دارند، بر اساس شکال یا زوایای قائم دارند یا گرد هستند. اگر ساختمانی ترکیبی از دو به نظر می‌رسد، بیشتر احتمال دارد که به یک ساختمان نگاه کنید که محدوده آن با سایه، انعکاس، گیاهان سبز و یا موارد مشابه پوشیده شده باشد.  

برای برخی از وظایف که تنها یک نقشه از یک منطقه مورد نیاز است، مدیر پروژه شاید مشخص کند که ساختمانها را می‌توان با یک نقطه نقشه‌کشی کرد، اما این حالت در حال حاضر نادر است.  


#### building=yes

تا وقتی که دستورالعمل پروژه چیز دیگری مشخص نکرده است، ساختمانها باید به صورت **building=yes**  برچسب‌گذاری شوند.  

* اغلب اوقات تأخیر زمانی بین گرفتن تصاویر ماهواره‌ای تا انجام نقشه‌کشی وجود دارد. این امکان وجود دارد که ساختمانی که به آن نگاه می‌کنید سقف نداشته باشد، اما اکنون تکمیل شده و در آن زندگی می‌کنند. همچنین ممکن است که شما به یک ساختمان چندطبقه نگاه کنید، که در طبقات پایین آن زندگی می‌کنند و طبقه بالا بدون سقف باشد و در حال حاضر در آن زندگی نمی‌شود.  

> **نقشه‌کشی ساختمانها با استفاده از iD** - هنگام استفاده از ابزار area در iD برای ایجاد شکل پایه، باید به یاد داشته باشید که پس از آن برچسب را به building=yes تغییر دهید. تنظیم پیش‌فرض فقط به شکل تگ area=yes را میدهد. اگر ردیابی شما از یک ساختمان با زوایای قائم است، لطفاْ وقت گذاشته و شکل‌تان را قائم کنید (آنرا انتخاب کنید و کلید میانبر 's' را بزنید).  

* JOSM برای ساخت کشیدن ساختمانها بسیار سریعتر است - [ابزار ساختمان JOSM در اینجا توضیح داده شده است.](/fa/josm/more-tools/#the-buildings-tools-plugin)  

![Buildings iD][]

این تصویر یک قسمت از مربع در حال ویرایش را نشان می‌دهد. به مقیاس ۱۵ در پایین توجه داشته باشید. هنگام ردیابی، باید در نظر داشته باشید که ساختمان را در جایی که با زمین اتصال دارد قرار دهید:  

1. **ساختمان‌های گرد.** در این مورد اینها نسبتاْ کم ارتفاع هستند و سایه آنها به سختی قابل مشاهده است. اگر در میان آنها بایستید، مانند گنبد به نظر میرسند. من تا کنون فقط یکی از اینها را **building=yes** کشیده‌ام. برای اضافه کردن سریع بقیه ساختمانها در JOSM یا iD، یکی را انتخاب کرده (برجسته کردن آن)، کلید میانبر *Ctrl+c*، مکان نما من را به مرکز ساخت یک ساختمان دیگر گرد و هم‌اندازه برده و کلید، *Ctrl+v* را میزنم. هنگامی که تمام ساختمانهای گرد هم اندازه در مربع من اضافه شد، یک ساختمان گرد دیگر با اندازه دیگر را می‌کشم، JOSM - از *Alt+Ctrl* و ماوس برای تغییر اندازه آن به اندازه درست استفاده کنید، آن را کپی کنید و سپس آن را روی همه ساختمانهای گرد آن اندازه الصاق کنید.  
2. **ساختمان‌های مستطیلی.** این ساختمانها یک سایه قابل توجه روی زمین می‌اندازند. سایه می‌تواند به شناسایی شکل ساختمانی که بخشی از آن توسط عوارض دیگر پوشیده شده کمک کند، شاید متوجه شوید که اغلب ساختمانها ساده نیستند و دارای بالکن یا به شکل L هستند. شما باید شکل واقعی ساختمان را ردیابی کنید زیرا این امر به شناسایی آن وقتی که در بررسی زمینی به آن نام و سایر داده‌ها داده میشود، کمک می‌کند.  
3. **موانع - دیوارها(یا حصاره)ی یک ترکیب.** پس از بررسی تصاویر، بزرگنمایی و کوچکنمایی آنها تا زمانی که از شکل شی راضی شوم (همچنین از سایه‌اش نیز برای شناسایی استفاده کنید)، معتقدم که این یک دیوار است و برچسب **barrier=wall** را برای آن می‌گذارم. موارد جایگزین شامل barrier=fence و barrier=hedge است.  
4. من barrier=wall را به گوشه building=yes متصل کردم.  


### تصاویر ماهواره‌ای شکل جسم را مشوش می‌کند.


![Buildings_2][]

1. تصاویر ماهواره‌ای از بالای ساختمان است، اما ماهواره به طور مستقیم عمود بر ساختمان قرار ندارد، به طوری که ساختمان به نظر کج به نظر میرسد و یک دیوار آن در تصویر قابل مشاهده است. به دلیل این زاویه، سقف فوقانی مستطیل شکل نیست. خورشید عملاْ بطور مستقیم بالای ساختمان است، به طوری که سایه ساختمان که در شکل ۱ با فلش نشان داده شده است، مستطیل شکل بودن ساختمان را تأیید می‌کند.  

2. برای نقشه‌کشی این ساختمان، یک مستطیل را از فلش نقطه ۲ ایجاد کنید تا جایی که تخمین می‌زنید انتهای ساختمان است که در این تصویر توسط نقطه ۳ مشخص شده است.  


***


جهت پیگیری بیشتر - لینک های زیر را برای راهنمایی بیشتر ببینید.


# بیشتر بخوانید

-  [West African HOT Mapping Tips by user Bgirardot](http://wiki.openstreetmap.org/wiki/User:Bgirardot/Typical_Road_and_Residential_Task)  
-  [OSM wiki entry concerning validating](http://wiki.openstreetmap.org/wiki/OSM_Tasking_Manager/Validating_data)  
-  [Highway Tag Africa - the preferred reference for highway tagging in Africa](http://wiki.openstreetmap.org/wiki/Highway_Tag_Africa)  
-  [Short Tutorial in French for remote mapping](http://blog.cartong.org/2014/07/24/tuto-digitaliser-sous-openstreetmap-avec-le-tasking-manager-et-josm-premiers-pas/)

[iD 3]: /images/coordination/iD_3.png
[JOSM 4]: /images/coordination/JOSM_4.png
[iD 5]: /images/coordination/iD_5.png
[iD residential]: /images/coordination/iD_residential.png
[JOSM residential]: /images/coordination/JOSM_residential.png
[JOSM residential 1]: /images/coordination/JOSM_residential_1.png
[Buildings iD]: /images/coordination/Buildings_iD.png
[Buildings_2]: /images/coordination/Buildings_2.png