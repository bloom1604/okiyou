<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ワンチャン起きる - 完全版プロトタイプ</title>
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

        /* 目的切り替えタブ */
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
            transition: all 0.2s;
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

        /* モード別バナーエリア */
        .group-banner {
            background-color: #f0fdf4;
            border: 1px solid #bbf7d0;
            border-radius: 12px;
            padding: 12px;
            margin-bottom: 15px;
            font-size: 13px;
            color: #166534;
            font-weight: 500;
        }

        .group-banner.private-mode {
            background-color: #eff6ff;
            border-color: #bfdbfe;
            color: #1e40af;
        }

        /* イベント名編集フォーム */
        .edit-input-group {
            display: flex;
            gap: 5px;
            margin-top: 8px;
        }

        .edit-input {
            flex: 1;
            padding: 6px 10px;
            border: 1px solid #bfdbfe;
            border-radius: 6px;
            font-size: 12px;
        }

        .save-btn {
            background-color: var(--secondary-color);
            color: white;
            border: none;
            padding: 6px 12px;
            border-radius: 6px;
            font-size: 12px;
            cursor: pointer;
        }

        /* 時間割テーブルスタイル */
        .timetable-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 8px;
            font-size: 11px;
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
        }

        .timetable-table th, .timetable-table td {
            border: 1px solid #e5e7eb;
            padding: 6px;
            text-align: center;
        }

        .timetable-table th {
            background-color: #f3f4f6;
            color: #4b5563;
        }

        .timetable-input {
            width: 90%;
            border: none;
            background: #f9fafb;
            text-align: center;
            font-size: 11px;
            padding: 4px 0;
            border-radius: 4px;
        }

        .timetable-input:focus {
            background: #fff;
            outline: 1px solid var(--primary-color);
        }

        /* 🎀 ペナルティ専用カード */
        .penalty-card {
            background: linear-gradient(135deg, #fdf2f8, #fce7f3);
            border: 1px solid #fbcfe8;
            border-radius: 12px;
            padding: 10px 12px;
            margin-bottom: 15px;
            font-size: 12px;
            color: #9d174d;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .penalty-icon { font-size: 22px; }
        .penalty-title { font-weight: bold; }

        .status-card {
            background-color: var(--card-bg);
            border-radius: 16px;
            padding: 15px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            margin-bottom: 15px;
            text-align: center;
        }

        .status-title { font-size: 13px; color: #6b7280; margin-bottom: 5px; }
        .status-value { font-size: 24px; font-weight: bold; color: var(--primary-color); }

        .wake-button {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            background: radial-gradient(circle, #ff7e40, var(--primary-color));
            color: white;
            border: none;
            font-size: 18px;
            font-weight: bold;
            box-shadow: 0 6px 15px rgba(255, 90, 95, 0.4);
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

        .wake-button span { font-size: 10px; font-weight: normal; opacity: 0.9; margin-top: 4px; }

        .section-title {
            font-size: 14px;
            font-weight: bold;
            color: var(--text-main);
            margin-bottom: 10px;
            display: flex;
            justify-content: space-between;
        }

        .member-list { display: flex; flex-direction: column; gap: 10px; }
        .member-card {
            background-color: var(--card-bg);
            border-radius: 12px;
            padding: 12px 15px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 4px rgba(0,0,0,0.02);
        }

        .member-info { display: flex; align-items: center; gap: 10px; }
        .member-avatar { width: 36px; height: 36px; border-radius: 50%; background-color: #e5e7eb; display: flex; justify-content: center; align-items: center; font-size: 16px; }
        .member-name { font-size: 14px; font-weight: bold; color: var(--text-main); }
        .member-status { font-size: 11px; padding: 2px 8px; border-radius: 20px; font-weight: 500; }
        .status-sleeping { background-color: #fee2e2; color: #ef4444; }
        .status-awake { background-color: #d1fae5; color: #10b981; }

        .call-btn {
            background-color: var(--secondary-color);
            color: white;
            border: none;
            padding: 6px 12px;
            border-radius: 8px;
            font-size: 12px;
            font-weight: bold;
            cursor: pointer;
        }

        .call-btn:disabled { background-color: #d1d5db; cursor: not-allowed; }

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

        .toast.show { transform: translateX(-50%) translateY(0); }
    </style>
</head>
<body>

    <div class="phone-container">
        <div class="header">
            <h1>ワンチャン起きる</h1>
        </div>

        <div class="tab-bar">
            <button class="tab-btn active" id="tab-class" onclick="switchMode('class')">🎓 授業モード</button>
            <button class="tab-btn" id="tab-private" onclick="switchMode('private')">🍺 プライベート</button>
        </div>

        <div class="content">
            <div id="mode-config-area">
                </div>

            <div class="penalty-card">
                <div class="penalty-icon">💝</div>
                <div>
                    <div class="penalty-title">強制ポジティブペナルティ</div>
                    <div>遅刻確定者は全員の「いいところ」を熱く語る刑に処されます。</div>
                </div>
            </div>

            <div class="status-card">
                <div class="status-title" id="status-label">現在のグループ生存率</div>
                <div class="status-value" id="group-survival">25%</div>
            </div>

            <button class="wake-button" id="wake-master-btn" onclick="triggerWakeUp()">
                <div id="wake-text">起きた！</div>
                <span id="wake-sub">ペナルティ回避</span>
            </button>

            <div class="section-title">
                <span>メンバーの様子</span>
                <span id="time-left" style="font-weight: normal; color: #6b7280; font-size: 12px;">開始まであと 30分</span>
            </div>

            <div class="member-list" id="member-list-container">
                </div>
        </div>

        <div class="toast" id="toast-notification">トースト通知</div>
    </div>

    <script>
        let currentMode = 'class';
        let privateEventName = "🚗 湘南ドライブ旅行";

        // 簡易時間割のデフォルトデータ
        const timetableData = {
            "月": ["経済学", "英語I", ""],
            "火": ["𠮷野ゼミ", "", "プログラミング"],
            "水": ["体育", "文学", "中国語"]
        };

        const dataStore = {
            class: {
                label: "授業への出席できそう率",
                timeLeft: "1限開始まであと 45分",
                color: "#ff5a5f",
                members: [
                    { id: 1, name: "たかし (あなた)", isAwake: false, avatar: "👦" },
                    { id: 2, name: "たくみ", isAwake: false, avatar: "🦁" },
                    { id: 3, name: "ひな", isAwake: true, avatar: "🐱" },
                    { id: 4, name: "けんた", isAwake: false, avatar: "🐻" }
                ]
            },
            private: {
                label: "集合場所への生存率",
                timeLeft: "集合まであと 1時間20分",
                color: "#f472b6",
                members: [
                    { id: 1, name: "たかし (あなた)", isAwake: false, avatar: "👦" },
                    { id: 2, name: "しょうた", isAwake: true, avatar: "🐼" },
                    { id: 3, name: "ゆい", isAwake: true, avatar: "🐰" },
                    { id: 4, name: "だいき", isAwake: false, avatar: "🐸" }
                ]
            }
        };

        function switchMode(mode) {
            currentMode = mode;
            
            document.getElementById('tab-class').classList.toggle('active', mode === 'class');
            document.getElementById('tab-private').classList.toggle('active', mode === 'private');

            // メインカラーをモードに合わせて微調整
            const configArea = document.getElementById('mode-config-area');
            
            if (mode === 'class') {
                document.documentElement.style.setProperty('--primary-color', '#ff5a5f');
                // 授業モード：時間割の表示・編集
                configArea.innerHTML = `
                    <div class="group-banner">
                        <strong>🎓 マイ時間割（タップして編集可能）</strong>
                        <table class="timetable-table">
                            <tr><th>曜</th><th>1限</th><th>2限</th><th>3限</th></tr>
                            ${Object.keys(timetableData).map(day => `
                                <tr>
                                    <td><strong>${day}</strong></td>
                                    ${timetableData[day].map((subject, idx) => `
                                        <td><input type="text" class="timetable-input" value="${subject}" onchange="updateTimetable('${day}', ${idx}, this.value)"></td>
                                    `).join('')}
                                </tr>
                            `).join('')}
                        </table>
                    </div>
                `;
            } else {
                document.documentElement.style.setProperty('--primary-color', '#f472b6');
                // プライベートモード：イベント名編集
                configArea.innerHTML = `
                    <div class="group-banner private-mode">
                        <strong>🎉 イベントグループ名:</strong>
                        <div style="font-size:15px; font-weight:bold; margin-top:4px;" id="event-display-name">${privateEventName}</div>
                        <div class="edit-input-group">
                            <input type="text" id="event-input" class="edit-input" placeholder="新しいイベント名を入力">
                            <button class="save-btn" onclick="saveEventName()">変更</button>
                        </div>
                    </div>
                `;
            }

            // 「起きた」ボタンのカラーと文言リセット
            const btn = document.getElementById('wake-master-btn');
            const myData = dataStore[currentMode].members.find(m => m.id === 1);
            if (myData.isAwake) {
                btn.classList.add('success');
                document.getElementById('wake-text').innerText = '回避成功';
            } else {
                btn.classList.remove('success');
                document.getElementById('wake-text').innerText = '起きた！';
            }

            render();
        }

        // 時間割データの更新
        function updateTimetable(day, idx, value) {
            timetableData[day][idx] = value;
            showToast(`💾 ${day}曜の${idx+1}限を「${value || '空きコマ'}」に保存しました`);
        }

        // イベント名の保存
        function saveEventName() {
            const input = document.getElementById('event-input');
            if (input.value.trim() !== "") {
                privateEventName = "✨ " + input.value;
                document.getElementById('event-display-name').innerText = privateEventName;
                input.value = "";
                showToast("💾 イベント名を更新しました！");
            }
        }

        function render() {
            const currentData = dataStore[currentMode];
            
            document.getElementById('status-label').innerText = currentData.label;
            document.getElementById('time-left').innerText = currentData.timeLeft;

            const container = document.getElementById('member-list-container');
            container.innerHTML = '';

            currentData.members.forEach(member => {
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
                        actionButton = `<span style="font-size:11px; color:var(--primary-color); font-weight:bold;">あなた</span>`;
                    } else {
                        const btnText = currentMode === 'private' ? '💬 褒めろ' : '起こす';
                        actionButton = `<button class="call-btn" style="background-color:var(--primary-color)" onclick="callMember('${member.name}')">${btnText}</button>`;
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

            const awakeCount = currentData.members.filter(m => m.isAwake).length;
            const percentage = Math.round((awakeCount / currentData.members.length) * 100);
            document.getElementById('group-survival').innerText = `${percentage}%`;
        }

        function triggerWakeUp() {
            const myData = dataStore[currentMode].members.find(m => m.id === 1);
            if (myData.isAwake) return;

            myData.isAwake = true;
            switchMode(currentMode);
            showToast("☀️ 起床報告！ガチ褒め刑を回避しました！");
        }

        function callMember(name) {
            const myData = dataStore[currentMode].members.find(m => m.id === 1);
            if (!myData.isAwake) {
                showToast("❌ まずは自分が「起きた！」を押してください！");
                return;
            }
            const msg = currentMode === 'private' 
                ? `💖 ${name}に「早く俺のいい所を用意しとけよ」と通知しました`
                : `🚀 ${name}にワンチャンコールを送信しました！`;
            showToast(msg);
        }

        function showToast(message) {
            const toast = document.getElementById('toast-notification');
            toast.innerText = message;
            toast.classList.add('show');
            setTimeout(() => { toast.classList.remove('show'); }, 2500);
        }

        // 初期起動時は授業モード
        switchMode('class');
    </script>
</body>
</html>
