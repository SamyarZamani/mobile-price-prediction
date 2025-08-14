# 📄 Mobile Price Prediction

## 📖 Project Overview
This project aims to predict the **price range** of mobile phones based on their specifications using **Machine Learning** techniques.  
We use the **Mobile Price Dataset** that contains different technical features such as battery power, RAM, pixel resolution, and connectivity options.

---

## 📂 Dataset
The dataset is split into:
- **train.csv** → Training data with labels (`price_range`)
- **test.csv** → Testing data without labels

Key features include:
- `battery_power`, `ram`, `px_height`, `px_width`
- `dual_sim`, `four_g`, `three_g`, `wifi`, etc.

---

## ⚙️ Steps
1. **Data Loading & Exploration** – Understanding the dataset  
2. **Data Preprocessing** – Handling missing values, scaling if needed  
3. **Model Training** – Using **XGBoost** for classification  
4. **Model Optimization** – Parameter tuning (Grid Search, Random Search)  
5. **Prediction** – Predicting `price_range` for the test dataset  
6. **Export** – Saving predictions in `submission_xgb.csv`  

---

## 📊 Model Performance
- **Algorithm**: XGBoost Classifier  
- **Final Accuracy**: *depends on your training score*  
- The model was chosen due to its high accuracy and robustness.

---

## 🛠 Technologies Used
- Python 3.x  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib / Seaborn  

---

## 📦 How to Run
```bash
pip install -r requirements.txt
python train_model.py
```
Or run the provided **Jupyter Notebook**: `mobile_price_predict.ipynb`

---

## 📜 Output
- `mobile_price_xgb.pkl` – Trained model  
- `submission_xgb.csv` – Prediction results  

---

## 📌 Future Improvements
- Deploy as a web app using Flask / FastAPI  
- Add more feature engineering steps  
- Try deep learning models for comparison  

---

# 📄 پیش‌بینی قیمت موبایل

## 📖 توضیح پروژه
هدف این پروژه پیش‌بینی **بازه قیمت موبایل** بر اساس مشخصات فنی آن با استفاده از روش‌های **یادگیری ماشین** است.  
ما از دیتاست **Mobile Price** استفاده کردیم که شامل ویژگی‌هایی مثل ظرفیت باتری، رم، رزولوشن تصویر و قابلیت‌های اتصال است.

---

## 📂 دیتاست
دیتاست شامل دو بخش است:
- **train.csv** → داده‌های آموزش با ستون `price_range`
- **test.csv** → داده‌های تست بدون برچسب

ویژگی‌های مهم:
- `battery_power`, `ram`, `px_height`, `px_width`
- `dual_sim`, `four_g`, `three_g`, `wifi` و ...

---

## ⚙️ مراحل کار
1. **بارگذاری و بررسی داده‌ها**  
2. **پیش‌پردازش داده‌ها** (حذف مقادیر گمشده، مقیاس‌بندی در صورت نیاز)  
3. **آموزش مدل** با الگوریتم **XGBoost**  
4. **بهینه‌سازی مدل** با Grid Search یا Random Search  
5. **پیش‌بینی** روی دیتاست تست  
6. **ذخیره خروجی** در فایل `submission_xgb.csv`  

---

## 📊 عملکرد مدل
- **الگوریتم**: XGBoost Classifier  
- **دقت نهایی**: *بسته به نتیجه آموزش*  
- دلیل انتخاب مدل: دقت بالا و پایداری مناسب

---

## 🛠 تکنولوژی‌های استفاده شده
- Python 3.x  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib / Seaborn  

---

## 📦 نحوه اجرا
```bash
pip install -r requirements.txt
python train_model.py
```
یا اجرای نوت‌بوک `mobile_price_predict.ipynb`

---

## 📜 خروجی
- `mobile_price_xgb.pkl` – مدل آموزش‌دیده  
- `submission_xgb.csv` – نتایج پیش‌بینی  

---

## 📌 بهبودهای آینده
- ساخت وب‌اپ با Flask / FastAPI  
- اضافه کردن ویژگی‌های جدید از روی داده‌ها  
- تست مدل‌های یادگیری عمیق برای مقایسه  
