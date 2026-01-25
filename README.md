<div align="center" style="background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%); padding: 50px 20px; border-radius: 30px; border: 1px solid #334155; box-shadow: 0 20px 50px rgba(0,0,0,0.6); margin-bottom: 30px;">
    <h1 style="color: #ffffff; font-family: 'Segoe UI', Arial; font-size: 3em; text-shadow: 0 0 20px #00d2ff; margin: 0;">🫀 Heart Disease Analysis</h1>
    <p style="color: #00d2ff; font-size: 1.2em; font-weight: 300; letter-spacing: 1px; margin-top: 10px;">Predictive Health Analytics • Advanced Machine Learning Pipeline</p>
    <div style="margin-top: 20px;">
        <img src="https://img.shields.io/badge/Status-Production--Ready-success?style=for-the-badge&logo=github" />
        <img src="https://img.shields.io/badge/Accuracy-98.3%25-blue?style=for-the-badge" />
        <img src="https://img.shields.io/badge/Data-UCI--Repository-orange?style=for-the-badge" />
    </div>
</div>

<div style="background: rgba(255, 255, 255, 0.03); padding: 25px; border-radius: 20px; border: 1px solid rgba(255, 255, 255, 0.1); margin-bottom: 30px;">
    <h2 style="color: #f8fafc; border-bottom: 1px solid #00d2ff; padding-bottom: 10px;">📌 مرور کلی پروژه</h2>
    <p style="color: #cbd5e1; line-height: 1.8; direction: rtl;">
        این پروژه یک خط لوله (Pipeline) کامل یادگیری ماشین برای پیش‌بینی بیماری‌های قلبی است. تمرکز اصلی بر روی <b>مهندسی ویژگی (Feature Engineering)</b> و <b>تعمیم‌پذیری (Generalization)</b> مدل بوده تا از بیش‌برازش (Overfitting) جلوگیری شود.
    </p>
</div>

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-bottom: 30px;">
    <div style="background: #111827; padding: 20px; border-radius: 15px; border-top: 5px solid #00d2ff; box-shadow: 0 10px 20px rgba(0,0,0,0.2);">
        <h3 style="color: #00d2ff; margin-top: 0;">🧹 پاکسازی داده‌ها</h3>
        <ul style="color: #94a3b8; padding-right: 20px;">
            <li>مدیریت داده‌های گم‌شده</li>
            <li>اصلاح توزیع و مقیاس‌بندی</li>
            <li>بررسی آماری Sanity Checks</li>
        </ul>
    </div>
    <div style="background: #111827; padding: 20px; border-radius: 15px; border-top: 5px solid #9d50bb; box-shadow: 0 10px 20px rgba(0,0,0,0.2);">
        <h3 style="color: #9d50bb; margin-top: 0;">🧠 تحلیل داده (EDA)</h3>
        <ul style="color: #94a3b8; padding-right: 20px;">
            <li>بررسی همبستگی فیچرها</li>
            <li>شناسایی فیچرهای زائد</li>
            <li>بصری‌سازی روابط غیرخطی</li>
        </ul>
    </div>
</div>



<h2 style="color: #f8fafc; text-align: center; margin-bottom: 20px;">📊 بنچمارک و عملکرد مدل‌ها</h2>
<div style="overflow-x: auto; border-radius: 20px; border: 1px solid #334155; box-shadow: 0 15px 35px rgba(0,0,0,0.4);">
    <table style="width: 100%; border-collapse: collapse; background: #0f172a; color: #f8fafc; text-align: center;">
        <thead style="background: linear-gradient(90deg, #00d2ff, #9d50bb);">
            <tr>
                <th style="padding: 20px;">Model</th>
                <th style="padding: 20px;">Test Accuracy</th>
                <th style="padding: 20px;">Status</th>
            </tr>
        </thead>
        <tbody>
            <tr style="border-bottom: 1px solid #1e293b;">
                <td style="padding: 15px; font-weight: bold;">AdaBoost</td>
                <td style="padding: 15px; color: #4ecca3;">1.0000</td>
                <td style="padding: 15px;"><span style="background: #064e3b; color: #4ecca3; padding: 5px 12px; border-radius: 20px; font-size: 0.8em;">PERFECT</span></td>
            </tr>
            <tr style="border-bottom: 1px solid #1e293b; background: rgba(255,255,255,0.02);">
                <td style="padding: 15px; font-weight: bold;">Logistic Regression</td>
                <td style="padding: 15px; color: #00d2ff;">0.9836</td>
                <td style="padding: 15px;"><span style="background: #1e3a8a; color: #00d2ff; padding: 5px 12px; border-radius: 20px; font-size: 0.8em;">RECOMMENDED</span></td>
            </tr>
            <tr>
                <td style="padding: 15px; font-weight: bold;">XGBoost</td>
                <td style="padding: 15px; color: #facc15;">0.9344</td>
                <td style="padding: 15px;"><span style="background: #422006; color: #facc15; padding: 5px 12px; border-radius: 20px; font-size: 0.8em;">STABLE</span></td>
            </tr>
        </tbody>
    </table>
</div>

<br>

<h2 style="color: #f8fafc; margin-top: 40px; border-right: 5px solid #9d50bb; padding-right: 15px;">📁 ساختار فایل‌های پروژه</h2>
<div style="background: #020617; padding: 25px; border-radius: 15px; font-family: 'Courier New', monospace; border: 1px solid #1e293b; line-height: 1.5;">
    <span style="color: #9d50bb;">📂 root/</span><br>
    <span style="color: #00d2ff;">&nbsp;&nbsp;├── 📂 data/</span> <span style="color: #475569;"># مجموعه‌ داده‌های خام و مهندسی شده</span><br>
    <span style="color: #00d2ff;">&nbsp;&nbsp;├── 📂 notebooks/</span> <span style="color: #475569;"># مراحل گام‌به‌گام تحلیل و آموزش</span><br>
    <span style="color: #00d2ff;">&nbsp;&nbsp;├── 📂 src/</span> <span style="color: #475569;"># کدهای منبع پردازش داده</span><br>
    <span style="color: #00d2ff;">&nbsp;&nbsp;└── 📂 models/</span> <span style="color: #475569;"># مدل‌های ذخیره شده (Pickle files)</span>
</div>

<div style="margin-top: 40px; text-align: center; border-top: 1px solid #334155; padding-top: 20px;">
    <p style="color: #64748b;">توسعه داده شده برای محیط‌های درمانی با دقت بالا</p>
</div>
