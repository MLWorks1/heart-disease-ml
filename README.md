<div align="center" style="background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%); padding: 40px; border-radius: 20px; border: 1px solid #334155; box-shadow: 0 10px 30px rgba(0,0,0,0.5);">
    <h1 style="color: #00d2ff; font-family: 'Segoe UI'; text-shadow: 0 0 15px rgba(0,210,255,0.5); margin-bottom: 10px;">🫀 Heart Disease Prediction</h1>
    <p style="color: #94a3b8; font-size: 1.1em; max-width: 600px;">Advanced Machine Learning Pipeline for Clinical Data Analysis & Production-Ready Modeling</p>
    <br>
    <img src="https://img.shields.io/badge/Accuracy-98.3%25-00d2ff?style=for-the-badge&logo=target" />
    <img src="https://img.shields.io/badge/Python-3.9+-purple?style=for-the-badge&logo=python" />
    <img src="https://img.shields.io/badge/Framework-Scikit--Learn-orange?style=for-the-badge&logo=scikitlearn" />
</div>

<br>

<h2 style="border-bottom: 2px solid #00d2ff; padding-bottom: 10px; color: #f8fafc;">📁 Project Architecture</h2>

<table style="width: 100%; border-collapse: collapse; border: none; margin-top: 20px;">
    <tr>
        <td width="50%" style="vertical-align: top; border: none; padding: 10px;">
            <div style="background: rgba(0, 210, 255, 0.05); padding: 20px; border-radius: 15px; border-left: 5px solid #00d2ff; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">
                <h3 style="color: #00d2ff; margin-top: 0;">📁 Data & Notebooks</h3>
                <code style="color: #cbd5e1; display: block;">📂 data/</code>
                <span style="color: #64748b; font-size: 0.85em; margin-left: 20px;">└─ heart_processed.csv</span><br>
                <code style="color: #cbd5e1; display: block; margin-top: 10px;">📂 notebooks/</code>
                <span style="color: #64748b; font-size: 0.85em; margin-left: 20px;">└─ 01_Feature_Engineering.ipynb</span>
            </div>
        </td>
        <td width="50%" style="vertical-align: top; border: none; padding: 10px;">
            <div style="background: rgba(157, 80, 187, 0.05); padding: 20px; border-radius: 15px; border-left: 5px solid #9d50bb; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">
                <h3 style="color: #9d50bb; margin-top: 0;">📁 Source & Models</h3>
                <code style="color: #cbd5e1; display: block;">📂 src/</code>
                <span style="color: #64748b; font-size: 0.85em; margin-left: 20px;">└─ model_trainer.py</span><br>
                <code style="color: #cbd5e1; display: block; margin-top: 10px;">📂 models/</code>
                <span style="color: #64748b; font-size: 0.85em; margin-left: 20px;">└─ heart_model_v1.pkl</span>
            </div>
        </td>
    </tr>
</table>

<br>

<h2 style="border-bottom: 2px solid #9d50bb; padding-bottom: 10px; color: #f8fafc;">📊 Model Benchmarks</h2>

<div style="overflow-x: auto; border-radius: 15px; border: 1px solid #334155;">
    <table style="width: 100%; text-align: left; border-collapse: collapse; background: #0f172a; color: #e2e8f0;">
        <thead>
            <tr style="background: linear-gradient(90deg, #00d2ff, #9d50bb);">
                <th style="padding: 15px;">Model Algorithm</th>
                <th style="padding: 15px;">Test Accuracy</th>
                <th style="padding: 15px;">Generalization</th>
            </tr>
        </thead>
        <tbody>
            <tr style="border-bottom: 1px solid #1e293b;">
                <td style="padding: 15px; font-weight: bold;">Logistic Regression</td>
                <td style="padding: 15px; color: #00ff88;">98.36%</td>
                <td style="padding: 15px;"><span style="background: #064e3b; color: #00ff88; padding: 4px 8px; border-radius: 5px; font-size: 0.8em;">STABLE</span></td>
            </tr>
            <tr style="border-bottom: 1px solid #1e293b; background: rgba(255,255,255,0.02);">
                <td style="padding: 15px; font-weight: bold;">Random Forest</td>
                <td style="padding: 15px; color: #00ff88;">98.36%</td>
                <td style="padding: 15px;"><span style="background: #450a0a; color: #f87171; padding: 4px 8px; border-radius: 5px; font-size: 0.8em;">OVERFIT RISK</span></td>
            </tr>
            <tr>
                <td style="padding: 15px; font-weight: bold;">XGBoost</td>
                <td style="padding: 15px; color: #facc15;">93.44%</td>
                <td style="padding: 15px;"><span style="background: #1e293b; color: #94a3b8; padding: 4px 8px; border-radius: 5px; font-size: 0.8em;">ROBUST</span></td>
            </tr>
        </tbody>
    </table>
</div>

<br>

<div style="background: #1e293b; padding: 25px; border-radius: 15px; border: 1px dashed #4ecca3;">
    <h3 style="color: #4ecca3; margin-top: 0;">🚀 Key Takeaways</h3>
    <ul style="color: #cbd5e1; column-count: 2;">
        <li>Outlier detection using IQR & Z-score</li>
        <li>Advanced Feature Interaction terms</li>
        <li>Hyperparameter tuning via Optuna</li>
        <li>Production-ready Pipeline code</li>
    </ul>
</div>
