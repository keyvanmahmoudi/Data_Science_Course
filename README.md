# Data Science Course

<div dir="rtl">

دورهٔ **علم داده** به زبان فارسی، برای کسانی که برنامه‌نویسی پایتون را بلدند و می‌خواهند با داده کار کنند. این دوره ترم دوم از یک مسیر شش ترمی است و در ۱۱ جلسه، از NumPy و pandas تا رسم نمودار، تحلیل اکتشافی، SQL، احتمال، آمار، جبر خطی پایه و یک پروژهٔ پایانی کامل را پوشش می‌دهد.

برای هر جلسه سه فایل وجود دارد:

- **نوت‌بوک درس** (پوشهٔ `sessions`): توضیحات کامل، مثال‌های اجراشده و تمرین‌های پایان جلسه
- **پاسخ تمرین‌ها** (پوشهٔ `solutions`): پاسخ پیشنهادی هر تمرین
- **اسلاید** (پوشهٔ `slides`): ارائهٔ پاورپوینت جلسه برای کلاس

## جلسه‌ها

| جلسه | موضوع | درس | پاسخ‌ها | اسلاید |
|---|---|---|---|---|
| ۱ | NumPy، پایهٔ محاسبات عددی در پایتون | [نوت‌بوک](sessions/Session01_numpy_fundamentals.ipynb) | [پاسخ تمرین‌ها](solutions/Session01_numpy_fundamentals_solutions.ipynb) | [اسلاید](slides/Session01_numpy_fundamentals.pptx) |
| ۲ | مبانی Pandas، کار با دادهٔ جدولی | [نوت‌بوک](sessions/Session02_pandas_fundamentals.ipynb) | [پاسخ تمرین‌ها](solutions/Session02_pandas_fundamentals_solutions.ipynb) | [اسلاید](slides/Session02_pandas_fundamentals.pptx) |
| ۳ | پاک‌سازی داده با Pandas | [نوت‌بوک](sessions/Session03_data_cleaning.ipynb) | [پاسخ تمرین‌ها](solutions/Session03_data_cleaning_solutions.ipynb) | [اسلاید](slides/Session03_data_cleaning.pptx) |
| ۴ | گروه‌بندی، ادغام و تغییر شکل جدول‌ها | [نوت‌بوک](sessions/Session04_groupby_merge_reshape.ipynb) | [پاسخ تمرین‌ها](solutions/Session04_groupby_merge_reshape_solutions.ipynb) | [اسلاید](slides/Session04_groupby_merge_reshape.pptx) |
| ۵ | رسم نمودار با Matplotlib و Seaborn | [نوت‌بوک](sessions/Session05_data_visualization.ipynb) | [پاسخ تمرین‌ها](solutions/Session05_data_visualization_solutions.ipynb) | [اسلاید](slides/Session05_data_visualization.pptx) |
| ۶ | تحلیل اکتشافی داده (EDA)، یک مطالعهٔ موردی کامل | [نوت‌بوک](sessions/Session06_exploratory_data_analysis.ipynb) | [پاسخ تمرین‌ها](solutions/Session06_exploratory_data_analysis_solutions.ipynb) | [اسلاید](slides/Session06_exploratory_data_analysis.pptx) |
| ۷ | SQL کاربردی برای تحلیل داده | [نوت‌بوک](sessions/Session07_sql_for_data_analysis.ipynb) | [پاسخ تمرین‌ها](solutions/Session07_sql_for_data_analysis_solutions.ipynb) | [اسلاید](slides/Session07_sql_for_data_analysis.pptx) |
| ۸ | احتمال برای علم داده | [نوت‌بوک](sessions/Session08_probability.ipynb) | [پاسخ تمرین‌ها](solutions/Session08_probability_solutions.ipynb) | [اسلاید](slides/Session08_probability.pptx) |
| ۹ | آمار برای علم داده | [نوت‌بوک](sessions/Session09_statistics.ipynb) | [پاسخ تمرین‌ها](solutions/Session09_statistics_solutions.ipynb) | [اسلاید](slides/Session09_statistics.pptx) |
| ۱۰ | جبر خطی پایه برای علم داده | [نوت‌بوک](sessions/Session10_linear_algebra.ipynb) | [پاسخ تمرین‌ها](solutions/Session10_linear_algebra_solutions.ipynb) | [اسلاید](slides/Session10_linear_algebra.pptx) |
| ۱۱ | پروژهٔ پایانی، تحلیل سفرهای تاکسی نیویورک | [نوت‌بوک](sessions/Session11_final_project.ipynb) | [پاسخ تمرین‌ها](solutions/Session11_final_project_solutions.ipynb) | [اسلاید](slides/Session11_final_project.pptx) |

## مسیر یادگیری

| ترم | دوره |
|---|---|
| ۱ | [برنامه‌نویسی پایتون](https://github.com/keyvanmahmoudi/Python_Course) |
| ۲ | **علم داده** (همین دوره) |
| ۳ | [یادگیری ماشین](https://github.com/keyvanmahmoudi/Machine_Learning_Course) |
| ۴ | [یادگیری عمیق و شبکه‌های عصبی](https://github.com/keyvanmahmoudi/Deep_Learning_Course) |
| ۵ | [مهندسی مدل‌های زبانی بزرگ (LLM) و برنامه‌نویسی با کمک هوش مصنوعی (Vibe Coding)](https://github.com/keyvanmahmoudi/LLM_Engineering_Course) |
| ۶ | [ساخت محصول هوش مصنوعی با FastAPI و کسب درآمد](https://github.com/keyvanmahmoudi/AI_Product_Course) |

## اجرا

ساده‌ترین راه، باز کردن نوت‌بوک‌ها در Google Colab با دکمهٔ **Open in Colab** بالای هر نوت‌بوک است. داده‌ها مستقیم از همین مخزن خوانده می‌شوند و نیازی به آپلود فایل نیست. برای اجرا روی سیستم خودتان:

</div>

```bash
git clone https://github.com/keyvanmahmoudi/Data_Science_Course.git
cd Data_Science_Course
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

<div dir="rtl">

## داده‌ها

همهٔ داده‌ها در پوشهٔ [`data`](data) هستند و توضیح و منبع هر فایل در [`data/README.md`](data/README.md) آمده است. دادهٔ فروشگاه اینترنتی **ساختگی** است و برای تمرین پاک‌سازی طراحی شده است؛ بقیهٔ داده‌ها عمومی‌اند.

## فونت‌ها

اسلایدها با فونت **Times New Roman** برای متن انگلیسی، **وزیرمتن (Vazirmatn FD)** برای متن فارسی و **لاله‌زار (Lalezar)** برای تیترها طراحی شده‌اند. قبل از باز کردن اسلایدها، فونت‌های پوشهٔ [`fonts`](fonts) را روی سیستم نصب کنید (هر دو فونت با مجوز آزاد SIL OFL منتشر شده‌اند).

## مدرس

**کیوان محمودی**، دانشجوی دکتری مهندسی کامپیوتر گرایش نرم افزار، دانشگاه تهران
[LinkedIn](https://www.linkedin.com/in/keyvan-mahmoudi-7b3280103) · [Hugging Face](https://huggingface.co/KeyvanMahmoudi)

## مجوز

این مخزن تحت [مجوز MIT](LICENSE) منتشر شده است. مجموعه‌داده‌های شخص ثالث مجوز خودشان را دارند (فهرست در [`data/README.md`](data/README.md)).

</div>
