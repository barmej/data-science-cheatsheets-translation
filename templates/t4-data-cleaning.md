**Data Science Cheatsheet - Data Cleaning** [[cheatsheet]](https://github.com/ml874/Data-Science-Cheatsheet/blob/master/data-science-cheatsheet.pdf)

<br>

Data Cleaning is the process of turning raw data into a clean and analyzable data set. ”Garbage in, garbage out.” Make sure garbage doesn’t get put in.
<div dir="rtl">
تنظيف البيانات هي عملية تحويل البيانات الأولية إلى مجموعة بيانات نظيفة وقابلة للتحليل. "إدخال قمامة (قيم غير نظيفة) ،  ينتج المزيد من القمامة " تأكد من عدم وضع القمامة.   
</div>
<br>

**Errors vs. Artifacts**
<div dir="rtl">
الأخطاء مقابل الاخلالات   
</div>
<br>

1. Errors: information that is lost during acquisition and can never be recovered e.g. power outage, crashed servers.
<div dir="rtl">
.الأخطاء: المعلومات التي ضاعت خلال تحصيلها ولا يمكن استرجاعها لأسباب مثل  انقطاع التيار الكهربائي أو تعطل الخوادم 
</div>
<br>

2. Artifacts: systematic problems that arise from the data cleaning process. These problems can be corrected but we must first discover them.
<div dir="rtl">
.الاخلالات: مشاكل منهجية تنتج عن عملية تنظيف البيانات . هذه المشاكل قابلة للتصحيح طالما يتم اكتشفها 
</div>
<br>

**Data Compatibility**
<div dir="rtl">
توافق البيانات
</div>
<br>

Data compatibility problems arise when merging datasets. Make sure you are comparing ”apples to apples” and not ”apples to oranges”. Main types of conver- sions/unifications:
<div dir="rtl">
  تنشأ مشاكل توافق البيانات عند دمج مجموعات البيانات. تأكد من أنك تقارن "التفاح بالتفاح" وليس "التفاح بالبرتقال". الأنواع الرئيسية من التقارب / الاتحادات:
</div>
<br>


1. units (metric vs. imperial)
<div dir="rtl">
الوحدات (متري مقابل إمبراطوري)
</div>
<br>
2. numbers (decimals vs. integers)
<div dir="rtl">
الأرقام (الكسور العشرية مقابل الأعداد الصحيحة)
</div>
<br>
3. time/dates (UNIX vs. UTC vs. GMT)
<div dir="rtl">
الوقت / التواريخ (UNIX مقابل UTC مقابل GMT)
</div>
<br>
4. currency (currency type, inflation-adjusted, dividends)
<div dir="rtl">
العملة (نوع العملة ، معدل التضخم ، أرباح الأسهم)
</div>
<br>



**Data Imputation**
<div dir="rtl">
احتساب البيانات
</div>
<br>

Process of dealing with missing values. The proper methods depend on the type of data we are working with. General methods include:
<div dir="rtl">
احتساب البيانات هي عملية التعامل مع القيم المفقودة.يعتمد اختيار الطرق المناسبة لاحتساب البيانات على نوع البيانات التي نتاعمل معها. تشمل الطرق العامة: 
</div>
<br>

1. Dropping all records containing missing data
<div dir="rtl">
إسقاط كافة السجلات التي تحتوي على بيانات مفقودة
</div>
<br>
2. Heuristic-Based: make a reasonable guess based on
knowledge of the underlying domain.
<div dir="rtl">
 على أساس إرشادي : إجراء تخمين معقول بناءً على
معرفة بالمجال الأساسي.
</div>
<br>
3. Random Value
<div dir="rtl">
قيمة عشوائية
</div>
<br>
4. Nearest Neighbor: fill in missing data using similar
data points
<div dir="rtl">
الجيران الأقرب: ملء البيانات المفقودة باستخدام نقاط البيانات مماثلة 
</div>
5. Interpolation: use a method like linear regression to
predict the value of the missing data
<div dir="rtl">
لاستكمال: استخدام طريقة مثل الانحدار الخطي لتوقع قيمة البيانات المفقودة. 
 
</div>


**Outlier Detection**
<div dir="rtl">
الكشف عن القيم المتطرفة 
</div>
<br>

Outliers can interfere with analysis and often arise from mistakes during data collection. It makes sense to run a ”sanity check”.
<div dir="rtl">
يمكن أن تتداخل القيم المتطرفة مع التحليل إذ غالبًا ما تنشأ من أخطاء واردة أثناء جمع البيانات. من المنطقي إجراء "فحص سلامة".
</div>
<br>

**Miscellaneous**
<div dir="rtl">
طرق أخرى متنوعة 
</div>
<br>

Lowercasing, removing non-alphanumeric, repairing, unidecode, removing unknown characters
<div dir="rtl">
 تحويل الأحرف إلى أحرف صغيرة ، إزالة الأحرف غير الأبجدية الرقمية ، الإصلاح ، فك الشفرة ، إزالة الأحرف غير المعروفة
</div>
<br>

Note: When cleaning data, always maintain both the raw data and the cleaned version(s). The raw data should be kept intact and preserved for future use. Any type of data cleaning/analysis should be done on a copy of the raw data.
<div dir="rtl">
ملاحظة: عند تنظيف البيانات ، احتفظ دائمًا بالبيانات الأولية والنسخ(الإصدارات) التي تم تنظيفها. يجب الحفاظ على سلامة البيانات الأولية لاستخدامها مستقبلاً.  كما يجب إجراء أي نوع من تنظيف / تحليل البيانات على نسخة من البيانات الأولية.
</div>
<br>
