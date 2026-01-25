<style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap');

    .project-container {
        font-family: 'Inter', sans-serif;
        background: #0f172a;
        padding: 40px;
        border-radius: 20px;
        color: #f8fafc;
        max-width: 900px;
        margin: 20px auto;
        border: 1px solid #1e293b;
        box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5);
    }

    .header-title {
        text-align: center;
        text-transform: uppercase;
        letter-spacing: 2px;
        color: #38bdf8;
        margin-bottom: 30px;
        font-weight: 600;
        border-bottom: 2px solid #38bdf8;
        display: inline-block;
        padding-bottom: 5px;
    }

    .structure-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 20px;
    }

    .folder-card {
        background: #1e293b;
        border-left: 5px solid #38bdf8;
        padding: 20px;
        border-radius: 12px;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
        cursor: default;
    }

    .folder-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 10px 20px rgba(56, 189, 248, 0.1);
        border-left-color: #f472b6;
    }

    .folder-icon {
        font-size: 1.5rem;
        margin-bottom: 10px;
        display: block;
    }

    .folder-name {
        font-weight: 600;
        color: #38bdf8;
        font-size: 1.1rem;
        margin-bottom: 8px;
    }

    .file-list {
        list-style: none;
        padding: 0;
        margin: 0;
        font-size: 0.9rem;
        color: #94a3b8;
    }

    .file-item {
        padding: 4px 0;
        display: flex;
        align-items: center;
    }

    .file-item::before {
        content: "📄";
        margin-right: 8px;
        font-size: 0.8rem;
    }

    .tech-badge {
        display: inline-block;
        background: rgba(56, 189, 248, 0.1);
        color: #38bdf8;
        padding: 2px 8px;
        border-radius: 4px;
        font-size: 0.7rem;
        margin-top: 10px;
        border: 1px solid rgba(56, 189, 248, 0.2);
    }
</style>

<div class="project-container">
    <div style="text-align: center;">
        <h2 class="header-title">Project Architecture</h2>
    </div>
    <div class="structure-grid">
        <div class="folder-card">
            <span class="folder-icon">📂</span>
            <div class="folder-name">Data/</div>
            <ul class="file-list">
                <li class="file-item">raw_heart_disease.csv</li>
                <li class="file-item">processed_features.pkl</li>
                <li class="file-item">data_dictionary.md</li>
            </ul>
            <span class="tech-badge">Storage Layer</span>
        </div>
        <div class="folder-card" style="border-left-color: #a78bfa;">
            <span class="folder-icon">📓</span>
            <div class="folder-name" style="color: #a78bfa;">Notebooks/</div>
            <ul class="file-list">
                <li class="file-item">01_EDA_Exploration.ipynb</li>
                <li class="file-item">02_Feature_Engineering.ipynb</li>
                <li class="file-item">03_Model_Training.ipynb</li>
            </ul>
            <span class="tech-badge" style="color: #a78bfa; border-color: rgba(167, 139, 250, 0.2);">Research Lab</span>
        </div>
        <div class="folder-card" style="border-left-color: #4ade80;">
            <span class="folder-icon">⚙️</span>
            <div class="folder-name" style="color: #4ade80;">Src/</div>
            <ul class="file-list">
                <li class="file-item">preprocessing_pipeline.py</li>
                <li class="file-item">model_factory.py</li>
                <li class="file-item">evaluation_metrics.py</li>
            </ul>
            <span class="tech-badge" style="color: #4ade80; border-color: rgba(74, 222, 128, 0.2);">Core Logic</span>
        </div>
        <div class="folder-card" style="border-left-color: #f472b6;">
            <span class="folder-icon">🧠</span>
            <div class="folder-name" style="color: #f472b6;">Models/</div>
            <ul class="file-list">
                <li class="file-item">adaboost_final.bin</li>
                <li class="file-item">scaler_config.json</li>
                <li class="file-item">ensemble_stack.joblib</li>
            </ul>
            <span class="tech-badge" style="color: #f472b6; border-color: rgba(244, 114, 182, 0.2);">Production Artifacts</span>
        </div>
    </div>
</div>
