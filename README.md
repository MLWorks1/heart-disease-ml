<div style="background: rgba(255, 255, 255, 0.03); padding: 30px; border-radius: 20px; border: 1px solid rgba(255, 255, 255, 0.1); margin-top: 30px; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">
    <h2 style="color: #f8fafc; border-bottom: 2px solid #9d50bb; padding-bottom: 10px; margin-bottom: 20px;">🔍 تحلیل استراتژیک عملکرد</h2>
    <p style="color: #cbd5e1; line-height: 1.8; direction: rtl; text-align: right;">
        در این پروژه، مدل‌ها بر اساس دو معیار <b>دقت اسمی</b> و <b>توانایی تعمیم‌پذیری</b> سنجیده شده‌اند. نتایج نشان‌دهنده یک مرز باریک بین یادگیری عمیق الگوها و حفظ کردن داده‌ها (Overfitting) است.
    </p>
    <div style="background: rgba(239, 68, 68, 0.1); border-right: 5px solid #ef4444; padding: 15px; border-radius: 10px; margin: 20px 0; direction: rtl; text-align: right;">
        <h4 style="color: #f87171; margin: 0 0 10px 0;">🚨 هشدار: بیش‌برازش (Overfitting)</h4>
        <p style="color: #fca5a5; font-size: 0.95em; margin: 0;">
            مدل‌هایی مانند <b>AdaBoost</b> و <b>Decision Tree</b> به دقت ۱۰۰٪ دست یافته‌اند. این یک نشانه کلاسیک از Overfitting است؛ به این معنی که مدل نویزهای داده‌های آموزشی را حفظ کرده و ممکن است روی داده‌های بیمارستان‌های دیگر به درستی عمل نکند.
        </p></div>
    <div style="background: rgba(16, 185, 129, 0.1); border-right: 5px solid #10b981; padding: 15px; border-radius: 10px; margin: 20px 0; direction: rtl; text-align: right;">
        <h4 style="color: #34d399; margin: 0 0 10px 0;">✅ مدل منتخب: Logistic Regression</h4>
        <p style="color: #a7f3d0; font-size: 0.95em; margin: 0;">
            با دقت <b>۹۸.۳۶٪</b> و کمترین فاصله بین داده‌های آموزش و تست، این مدل پایدارترین گزینه برای محیط‌های درمانی واقعی است.
        </p>
    </div>
</div>

<div style="margin-top: 30px; direction: rtl; text-align: right;">
    <h3 style="color: #00d2ff;">🛠 مهندسی ویژگی‌های کلیدی</h3>
    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px;">
        <div style="background: #1e293b; padding: 15px; border-radius: 12px; border: 1px dashed #334155;">
            <span style="color: #9d50bb; font-weight: bold;">Standardization</span>
            <p style="color: #94a3b8; font-size: 0.9em;">یکسان‌سازی مقیاس ویژگی‌های عددی مانند کلسترول و فشار خون.</p>
        </div>
        <div style="background: #1e293b; padding: 15px; border-radius: 12px; border: 1px dashed #334155;">
            <span style="color: #00d2ff; font-weight: bold;">Correlation Analysis</span>
            <p style="color: #94a3b8; font-size: 0.9em;">حذف ویژگی‌های هم‌خط (Collinear) برای جلوگیری از تورم واریانس مدل.</p>
        </div>
    </div>
</div>

<div style="margin-top: 40px;">
    <h3 style="color: #f8fafc; text-align: center; margin-bottom: 15px;">📁 Project Blueprint</h3>
    <div style="background: #020617; padding: 25px; border-radius: 15px; font-family: 'Fira Code', monospace; border: 1px solid #1e293b; color: #94a3b8; line-height: 1.6;">
        <div><span style="color: #9d50bb;">📦 Heart-Disease-ML</span></div>
        <div>&nbsp;┣&nbsp;<span style="color: #00d2ff;">📂 data</span> <span style="color: #475569;"># Raw & Processed Datasets</span></div>
        <div>&nbsp;┣&nbsp;<span style="color: #00d2ff;">📂 notebooks</span> <span style="color: #475569;"># EDA & Model Comparison</span></div>
        <div>&nbsp;┣&nbsp;<span style="color: #00d2ff;">📂 src</span> <span style="color: #475569;"># Feature Engineering Scripts</span></div>
        <div>&nbsp;┗&nbsp;<span style="color: #00d2ff;">📂 models</span> <span style="color: #475569;"># Serialized Trained Models (.pkl)</span></div>
    </div>
</div>

<div style="text-align: center; margin-top: 50px; color: #475569; font-size: 0.85em;">
    <p>Developed with ❤️ for Medical Data Science | 2024</p>
</div>
