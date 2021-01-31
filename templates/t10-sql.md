**Data Science Cheatsheet - SQL** [[cheatsheet]](https://github.com/ml874/Data-Science-Cheatsheet/blob/master/data-science-cheatsheet.pdf)

<br>

**1. SQL**
<div dir="rtl">
SQL أو سيكوال
</div>
<br>

**2. Structured Query Language (SQL) is a declarative language used to access & manipulate data in databases.**
<div dir="rtl">
هل لغة استعلامية مهيكلة، تستخدم للوصول للبيانات في قواعد البيانات والتعديل عليها.
</div>
<br>

**3. Usually the database is a Relational Database Management System (RDBMS), which stores data arranged in relational database tables.**
<div dir="rtl">
عادةً ما تكون قواعد البيانات هذه على شكل RDBMS وهو نظام إدارة قواعد البيانات المبنية على العلاقات، والتي تقوم بتخزين البيانات في جداول مترابطة.
</div>
<br>

**4. A table is arranged in columns and rows, where columns represent characteristics of stored data and rows represent actual data entries.**
<div dir="rtl">
الجدول مبني من أعمدة وصفوف، بحيث تمثل الأعمدة الخصائص للبيانات المخزنة، وتمثل الصفوف البيانات المدخلة.
</div>
<br>

**5. Basic Queries**
<div dir="rtl">
الاستعلامات الأساسية
</div>
<br>

**6. - filter columns: SELECT col1, col3... FROM table1**
<div dir="rtl">
لفرز الأعمدة:
SELECT col1, col3... FROM table1
</div>
<br>

**7. - filter the rows: WHERE col4 = 1 AND col5 = 2**
<div dir="rtl">
لفرز الصفوف:
WHERE col4 = 1 AND col5 = 2
</div>
<br>

**8. - aggregate the data: GROUP BY. . .**
<div dir="rtl">
لتجميع البيانات:
GROUP BY ...
</div>
<br>

**9. - limit aggregated data: HAVING count(*) > 1**
<div dir="rtl">
لوضع شروط على التجميع:
HAVING count(*) > 1
</div>
<br>

**10. - order of the results: ORDER BY col2**
<div dir="rtl">
لترتيب النتائج:
ORDER BY col2
</div>
<br>

**11. Useful Keywords for SELECT**
<div dir="rtl">
كلمات دلالية مفيدة يتم استخدامها مع SELECT:
</div>
<br>

**12. DISTINCT- return unique results**
<div dir="rtl">
DISTINCT:
لارجاع نتائج فريدة (غير مكررة)
</div>
<br>

**13. BETWEEN a AND b- limit the range, the values can be numbers, text, or dates**
<div dir="rtl">
BETWEEN a AND b:
لجعل النتائج ضمن مدى محدد، حيث أن قيم a و b قد تكون أرقام أو نص أو تواريخ.
</div>
<br>

**14. LIKE- pattern search within the column text**
<div dir="rtl">
LIKE:
للبحث باستخدام نمط محدد داخل عمود معين، مثل a% والتي تعني إيجاد كل كلمة تبدأ بحرف a.
</div>
<br>

**15. IN (a, b, c) - check if the value is contained among given**
<div dir="rtl">
IN (a, b, c):
للتحقق من أن قيم النتائج ضمن مجموعة القيم المعطاة (a, b, c).
</div>
<br>

**16. Data Modification**
<div dir="rtl">
تعديل البيانات
</div>
<br>

**17. - update specific data with the WHERE clause:**
<div dir="rtl">
تحديث بيانات معينة باستخدام WHERE في جملة الاستعلام.
</div>
<br>

**18. UPDATE table1 SET col1 = 1 WHERE col2 = 2**
<div dir="rtl">
UPDATE table1 SET col1 = 1 WHERE col2 = 2
</div>
<br>

**19. - insert values manually**
<div dir="rtl">
لادخال البيانات بشكل يدوي
</div>
<br>

**20. INSERT INTO table1 (col1,col3) VALUES (val1,val3);**
<div dir="rtl">
INSERT INTO table1 (col1,col3) VALUES (val1,val3);
</div>
<br>

**21. - by using the results of a query**
<div dir="rtl">
لادخال البيانات باستخدام نتائج جملة استعلام
</div>
<br>

**22. INSERT INTO table1 (col1,col3) SELECT col,col2 FROM table2;**
<div dir="rtl">
INSERT INTO table1 (col1,col3) SELECT col,col2 FROM table2;
</div>
<br>

**23. Joins**
<div dir="rtl">
الربط
</div>
<br>

**24. The JOIN clause is used to combine rows from two or more tables, based on a related column between them.**
<div dir="rtl">
يستخدم الربط في جمل الاستعلام لدمج الصفوف بين جدولين وأكثر، يتم الدمج بناءً على العمود المشترك بين الجداول المطلوب دمجها.</div>
<br>