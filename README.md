<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>個人履歷 | Your Name</title>
    <style>
        /* 基本樣式設定 */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f4f7f6;
        }

        header {
            text-align: center;
            padding: 40px 0;
            background: #2c3e50;
            color: white;
            border-radius: 8px;
            margin-bottom: 20px;
        }

        header h1 { margin: 0; font-size: 2.5em; }
        header p { margin: 10px 0 0; opacity: 0.9; }

        /* 區塊樣式 */
        section {
            background: white;
            padding: 25px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        h2 {
            border-bottom: 2px solid #2c3e50;
            padding-bottom: 10px;
            color: #2c3e50;
        }

        .contact-info {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin-top: 15px;
        }

        .contact-info a {
            color: white;
            text-decoration: none;
            background: #34495e;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9em;
        }

        .skill-tag {
            display: inline-block;
            background: #e1e8ed;
            padding: 5px 12px;
            margin: 5px;
            border-radius: 4px;
            font-size: 0.9em;
        }

        .job-title {
            font-weight: bold;
            color: #e67e22;
        }

        footer {
            text-align: center;
            font-size: 0.8em;
            color: #7f8c8d;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <header>
        <h1>您的姓名</h1>
        <p>應徵職位 / 專業頭銜</p>
        <div class="contact-info">
            <a href="mailto:yourname@email.com">📧 yourname@email.com</a>
            <a href="tel:0912345678">📞 0912-345678</a>
            <a href="#">🌐 個人網站/GitHub</a>
        </div>
    </header>

    <section id="summary">
        <h2>關於我</h2>
        <p>在這裡簡短介紹您的背景。例如：具備電子工程背景，目前正積極尋找餐飲服務業相關機會。個性樂觀、學習能力強，能在高壓環境下保持良好溝通。</p>
    </section>

    <section id="education">
        <h2>教育背景</h2>
        <div>
            <span class="job-title">某某大學 - 電子工程系</span> | 2021 - 2025 (預計畢業)
            <ul>
                <li>專注於通訊系統與訊號處理。</li>
                <li>曾參與微型水力發電研究專案。</li>
            </ul>
        </div>
    </section>

    <section id="skills">
        <h2>技能專長</h2>
        <div class="skill-tag">MATLAB</div>
        <div class="skill-tag">訊號處理</div>
        <div class="skill-tag">顧客服務</div>
        <div class="skill-tag">團隊合作</div>
        <div class="skill-tag">Microsoft Office</div>
    </section>

    <section id="experience">
        <h2>工作/實習經歷</h2>
        <div>
            <span class="job-title">職位名稱</span> | 公司/組織名稱 | 2024.07 - 2024.08
            <ul>
                <li>描述工作內容、負責事項與達成目標。</li>
                <li>量化你的成就，例如「提升服務效率 10%」。</li>
            </ul>
        </div>
    </section>

    <footer>
        <p>© 2026 Your Name - 本網頁使用 HTML/CSS 製作</p>
    </footer>

</body>
</html>
