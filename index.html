<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ワンチャン起きる - ガチ褒めペナルティ版</title>
    <style>
        :root {
            --bg-color: #f3f4f6;
            --primary-color: #ff5a5f;
            --secondary-color: #3b82f6;
            --success-color: #10b981;
            --pink-accent: #f472b6;
            --text-main: #1f2937;
            --card-bg: #ffffff;
        }

        body {
            font-family: 'Helvetica Neue', Arial, 'Hiragino Kaku Gothic ProN', 'Hiragino Sans', Meiryo, sans-serif;
            background-color: var(--bg-color);
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .phone-container {
            width: 375px;
            height: 780px;
            background-color: #fafafa;
            border-radius: 40px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.15);
            border: 8px solid #333;
            overflow: hidden;
            display: flex;
            flex-direction: column;
            position: relative;
        }

        .header {
            background: linear-gradient(135deg, var(--primary-color), #ff7e40);
            color: white;
            padding: 25px 20px 15px;
            text-align: center;
        }

        .header h1 {
            margin: 0;
            font-size: 22px;
            font-weight: bold;
        }

        .tab-bar {
            display: flex;
            background-color: rgba(0, 0, 0, 0.06);
            padding: 4px;
            margin: 10px 15px 0;
            border-radius: 12px;
        }

        .tab-btn {
            flex: 1;
            background: none;
            border: none;
            padding: 8px;
            font-size: 13px;
            font-weight: bold;
            color: #6b7280;
            cursor: pointer;
            border-radius: 10px;
        }

        .tab-btn.active {
            background-color: var(--card-bg);
            color: var(--text-main);
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .content {
            padding: 15px 20px;
            flex: 1;
            overflow-y: auto;
        }

        .group-banner {
            background-color: #eff6ff;
            border: 1px solid #bfdbfe;
            color: #1e40af;
            border-radius: 12px;
            padding: 10px;
            margin-bottom: 15px;
            font-size: 13px;
            text-align: center;
            font-weight: 500;
        }

        /* 🎀 ペナルティ専用カード */
        .penalty-card {
            background: linear-gradient(135deg, #fdf2f8, #fce7f3);
            border: 1px solid #fbcfe8;
            border-radius: 12px;
            padding: 12px;
            margin-bottom: 15px;
            font-size: 12px;
            color: #9d174d;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .penalty-icon {
            font-size: 24px;
        }

        .penalty-title {
            font-weight: bold;
            margin-bottom: 2px;
        }

        .status-card {
            background-color: var(--card-bg);
            border-radius: 16px;
            padding: 15px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            margin-bottom: 15px;
            text-align: center;
        }

        .status-title {
            font-size: 13px;
            color: #6b7280;
            margin-bottom: 5px;
        }

        .status-value {
            font-size: 24px;
            font-weight: bold;
            color: var(--pink-accent);
        }

        .wake-button {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            background: radial-gradient(circle, #f472b6, var(--pink-accent));
            color: white;
            border: none;
            font-size: 18px;
            font-weight: bold;
            box-shadow: 0 6px 15px rgba(244, 114, 182, 0.4);
            cursor: pointer;
            transition: transform 0.2s;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            margin: 0 auto 20px;
        }

        .wake-button.success {
            background: radial-gradient(circle, #34d399, var(--success-color));
            box-shadow: 0 6px 15px rgba(16, 185, 129, 0.4);
        }

        .wake-button span {
            font-size: 10px;
            font-weight: normal;
            opacity: 0.9;
            margin-top: 4px;
        }

        .section-title {
            font-size: 14px;
            font-weight: bold;
            color: var(--text-main);
            margin-bottom: 10px;
            display: flex;
            justify-content: space-between;
        }

        .member-list {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        .member-card {
            background-color: var(--card-bg);
            border-radius: 12px;
            padding: 12px 15px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 4px rgba(0,0,0,0.02);
        }

        .member-info {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .member-avatar {
            width: 36px;
            height: 36px;
            border-radius: 50%;
            background-color: #e5e7eb;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 16px;
        }

        .member-name {
            font-size: 14px;
            font-weight: bold;
            color: var(--text-main);
        }

        .member-status {
            font-size: 11px;
            padding: 2px 8px;
            border-radius: 20px;
            font-weight: 500;
        }

        .status-sleeping {
            background-color: #fee2e2;
            color: #ef4444;
        }

        .status-awake {
            background-color: #d1fae5;
            color: #10b981;
        }

        .call-btn {
            background-color: var(--pink-accent);
            color: white;
            border: none;
            padding: 6px 12px;
            border-radius: 8px;
            font-size: 12px;
            font-weight: bold;
            cursor: pointer;
        }

        .call-btn:disabled {
            background-color: #d1d5db;
            cursor: not-allowed;
        }

        .toast {
            position: absolute;
            bottom: 30px;
            left: 50%;
            transform: translateX(-50%) translateY(100px);
            background-color: #333;
            color: white;
            padding: 10px 20px;
            border-radius: 20px;
            font-size: 13px;
            white-space: nowrap;
            transition: transform 0.3s ease;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
            z-index: 10;
        }

        .toast.show {
            transform: translateX(-50%) translateY(0);
        }
    </style>
</head>
<body>

    <div class="phone-container">
        <div class="header">
            <h1>ワンチャン起きる</h1>
        </div>

        <div class="tab-bar">
            <div style="flex:1; text-align:center; padding:8px; font-size:13px; font-weight:bold; background:#fff; border-radius:10px; color:var(--text-main);">
                🍺 プライベートモード
            </div>
        </div>

        <div class="content">
            <div class="group-banner">🚗 7月4日：湘南ドライブ旅行の約束</div>

            <div class="penalty-card">
                <div class="penalty-icon">💝</div>
                <div>
                    <div class="penalty-title">遅刻ペナルティ発動中！</div>
                    <div>遅刻確定者は全員から「ガチ褒め（100文字）」される刑に処されます。</div>
                </div>
            </div>

            <div class="status-card">
                <div class="status-title">現在の「ガチ褒め」回避率</div>
                <div class="status-value" id="group-survival">50%</div>
            </div>

            <button class="wake-button" id="wake-master-btn" onclick="triggerWakeUp()">
                <div id="wake-text">起きた！</div>
                <span>お詫び回避</span>
            </button>

            <div class="section-title">
                <span>メンバーの様子</span>
                <span style="font-weight: normal; color: #6b7280; font-size: 12px;">集合まであと 15分（絶望）</span>
            </div>

            <div class="member-list" id="member-list-container">
                </div>
        </div>

        <div class="toast" id="toast-notification">トースト通知</div>
    </div>

    <script>
        const members = [
            { id: 1, name: "たかし (あなた)", isAwake: false, avatar: "👦" },
            { id: 2, name: "しょうた", isAwake: true, avatar: "🐼" },
            { id: 3, name: "ゆい", isAwake: true, avatar: "🐰" },
            { id: 4, name: "だいき", isAwake: false, avatar: "🐸" }
        ];

        function render() {
            const container = document.getElementById('member-list-container');
            container.innerHTML = '';

            members.forEach(member => {
                const card = document.createElement('div');
                card.className = 'member-card';

                let statusBadge = member.isAwake 
                    ? `<span class="member-status status-awake">安全</span>`
                    : `<span class="member-status status-sleeping">遅刻危機</span>`;

                let actionButton = '';
                if (member.isAwake) {
                    actionButton = `<button class="call-btn" style="background:#e5e7eb; color:#9ca3af;" disabled>免除</button>`;
                } else {
                    if (member.id === 1) {
                        actionButton = `<span style="font-size:11px; color:var(--pink-accent); font-weight:bold;">大ピンチ</span>`;
                    } else {
                        actionButton = `<button class="call-btn" onclick="demandPraise('${member.name}')">💬 褒めろ</button>`;
                    }
                }

                card.innerHTML = `
                    <div class="member-info">
                        <div class="member-avatar">${member.avatar}</div>
                        <div class="member-name">${member.name}</div>
                    </div>
                    <div style="display: flex; align-items: center; gap: 10px;">
                        ${statusBadge}
                        ${actionButton}
                    </div>
                `;
                container.appendChild(card);
            });

            const awakeCount = members.filter(m => m.isAwake).length;
            const percentage = Math.round((awakeCount / members.length) * 100);
            document.getElementById('group-survival').innerText = `${percentage}%`;
        }

        function triggerWakeUp() {
            const myData = members.find(m => m.id === 1);
            if (myData.isAwake) return;

            myData.isAwake = true;
            
            const btn = document.getElementById('wake-master-btn');
            btn.classList.add('success');
            document.getElementById('wake-text').innerText = '回避成功';

            showToast("✨ 起床報告！ガチ褒め刑を回避しました！");
            render();
        }

        // 「褒めろ」ボタンを押したときの処理
        function demandPraise(name) {
            const myData = members.find(m => m.id === 1);
            if (!myData.isAwake) {
                showToast("❌ 自分が起きてから要求してください！");
                return;
            }
            showToast(`💖 ${name}に「早く俺のいい所を用意しとけよ」と通知しました`);
        }

        function showToast(message) {
            const toast = document.getElementById('toast-notification');
            toast.innerText = message;
            toast.classList.add('show');
            setTimeout(() => { toast.classList.remove('show'); }, 2500);
        }

        render();
    </script>
</body>
</html>
