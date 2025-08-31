# 🩺 Diabetes Prediction (Tabular ML)

این پروژه با داده‌های ساختاریافته (جدولی) از Kaggle، با استفاده از روش‌های پیش‌پردازش و الگوریتم‌های یادگیری ماشین مثل **KNN** و **SVM**، احتمال ابتلا به دیابت را پیش‌بینی می‌کند. نوت‌بوک در Google Colab توسعه داده شده است.

---

## 📂 ساختار پروژه
- `Diabetes_Prediction.ipynb`: نوت‌بوک اصلی شامل:
  - دانلود و بارگذاری دیتاست از Kaggle
  - اکتشاف داده و خلاصه آماری
  - **۴ روش پیش‌پردازش** (imputation / outlier handling / encoding / scaling)
  - آموزش و ارزیابی مدل‌ها (KNN, SVM)

> 📌 توجه: این نوت‌بوک در **Google Colab** نوشته شده. اگر مسیرهایی مثل `/content/...` می‌بینید طبیعی است؛ هنگام اجرا متناسب با محیط خود تنظیم کنید.
> برای دانلود خودکار از Kaggle به فایل `kaggle.json` نیاز دارید (در Colab داخل مسیر `~/.kaggle/`).

---

## 🧰 تکنولوژی‌ها
- Python 3.x
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn
- (اختیاری) Google Colab

---


## 📥 نصب و اجرا
1. مخزن را کلون کنید:

```bash
git clone https://github.com/evi-data-vision/Diabetes-Prediction.git
cd Diabetes-Prediction
pip install -r requirements.txt
```

