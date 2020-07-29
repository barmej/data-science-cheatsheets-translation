**Data Science Cheatsheet - Feature Engineering** [[cheatsheet]](https://github.com/ml874/Data-Science-Cheatsheet/blob/master/data-science-cheatsheet.pdf)

<br>

Feature engineering is the process of using domain knowledge to create features or input variables that help machine learning algorithms perform better. Done correctly, it can help increase the predictive power of your models. Feature engineering is one of the most important steps in creating a good model.

<br>


**Continuous Data**
<div dir="rtl">
اكتب ترجمة النص هنا
</div>
<br>


* Raw Measures: data that hasn’t been transformed yet
<div dir="rtl">
اكتب ترجمة النص هنا
</div>
<br>

* Rounding: sometimes precision is noise; round to nearest integer, decimal etc..
<div dir="rtl">
اكتب ترجمة النص هنا
</div>
<br>

* Scaling: log, z-score, minmax scale.
<div dir="rtl">
اكتب ترجمة النص هنا
</div>
<br>

* Imputation: fill in missing values using mean, median, model output, etc..
<div dir="rtl">
اكتب ترجمة النص هنا
</div>
<br>


* Binning: transforming numeric features into categorical ones (or binned) e.g. values between 1-10 belong to A, between 10-20 belong to B, etc.
<div dir="rtl">
اكتب ترجمة النص هنا
</div>
<br>

* Interactions: interactions between features: e.g. sub- traction, addition, multiplication, statistical test Statistical: log/power transform (helps turn skewed distributions more normal), Box-Cox
<div dir="rtl">
اكتب ترجمة النص هنا
</div>
<br>


* Row Statistics: number of NaN’s, 0’s, negative values, max, min, etc
Dimensionality Reduction: using PCA, clustering, factor analysis etc
<div dir="rtl">
اكتب ترجمة النص هنا
</div>
<br>


**Discrete Data**
* Encoding: since some ML algorithms cannot work on categorical data, we need to turn categorical data into numerical data or vectors
<div dir="rtl">
اكتب ترجمة النص هنا
</div>
<br>
* Ordinal Values: convert each distinct feature into a random number (e.g. [r,g,b] becomes [1,2,3])
<div dir="rtl">
اكتب ترجمة النص هنا
</div>
<br>
* One-Hot Encoding: each of the m features becomes a vector of length m with containing only one 1 (e.g. [r, g, b] becomes [[1,0,0],[0,1,0],[0,0,1]])
<div dir="rtl">
اكتب ترجمة النص هنا
</div>
<br>
* Feature Hashing Scheme: turns arbitrary features into indices in a vector or matrix
<div dir="rtl">
اكتب ترجمة النص هنا
</div>
<br>
* Embeddings: if using words, convert words to vectors (word embeddings)
<div dir="rtl">
اكتب ترجمة النص هنا
</div>
<br>