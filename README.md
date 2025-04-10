<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>三高危機與保險解決方案 - 國泰人壽</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/3.7.0/chart.min.css">
    <style>
        /* 整體樣式 */
        body {
            font-family: 'Noto Sans TC', sans-serif;
            line-height: 1.8;
            margin: 0;
            padding: 30px;
            background-color: #f0f4f8;
            color: #2d3748;
        }
        h1 {
            color: #c53030;
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 30px;
        }
        h2 {
            color: #2b6cb0;
            font-size: 1.8em;
            margin-top: 40px;
            text-align: center;
        }
        h3 {
            color: #4a5568;
            font-size: 1.4em;
            margin: 20px 0;
        }
        .container {
            max-width: 1300px;
            margin: 0 auto;
        }
        .section {
            background-color: #ffffff;
            padding: 40px;
            margin: 30px 0;
            border-radius: 12px;
            box-shadow: 0 6px 12px rgba(0,0,0,0.1);
        }
        .chart-container {
            position: relative;
            height: 450px;
            width: 100%;
            margin: 30px 0;
        }
        .highlight {
            background-color: #fefcbf;
            padding: 20px;
            border-left: 6px solid #dd6b20;
            margin: 20px 0;
            font-weight: bold;
            color: #744210;
        }
        .cta-button {
            background-color: #38a169;
            color: white;
            padding: 18px 40px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 20px;
            display: block;
            margin: 40px auto;
            text-align: center;
            text-decoration: none;
        }
        .cta-button:hover {
            background-color: #2f855a;
        }
        footer {
            text-align: center;
            font-size: 14px;
            color: #718096;
            margin-top: 60px;
            padding: 20px;
            background-color: #edf2f7;
            border-radius: 8px;
        }
        /* 響應式設計 */
        @media (max-width: 768px) {
            .chart-container {
                height: 350px;
            }
            h1 { font-size: 2em; }
            h2 { font-size: 1.5em; }
            .section { padding: 20px; }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- 標題 -->
        <h1>三高危機全面解析：國泰人壽保您平安</h1>

        <!-- 引言 -->
        <div class="section">
            <h2>三高威脅有多大？</h2>
            <p>在台灣，三高（<strong>高血壓、高血糖、高血脂</strong>）影響超過500萬人，隨著人口老化，併發症風險與醫療花費逐年攀升。根據國民健康署預估，2025年台灣將有25%人口超過65歲，三高相關支出將成為家庭最大的財務負擔。</p>
            <p><strong>國泰人壽三高平安保險</strong>提供低門檻投保與全面保障，幫您抵禦健康與財務雙重危機。立即行動，才能守護未來！</p>
        </div>

        <!-- 數據展示 -->
        <div class="section">
            <h2>數據告訴您：三高的代價有多高</h2>

            <!-- 圖表1：柱狀圖 - 年齡與併發症機率 -->
            <h3>圖表1：不同年齡層三高併發症機率</h3>
            <div class="chart-container">
                <canvas id="barChart"></canvas>
            </div>
            <p><em>資料來源：台灣健保署2023年統計</em></p>
            <div class="highlight">
                <p><strong>危機警示</strong>：60歲以上三高患者，併發症機率高達55%，您準備好面對這風險了嗎？</p>
            </div>

            <!-- 圖表2：折線圖 - 醫療支出趨勢 -->
            <h3>圖表2：三高醫療支出趨勢（2015-2023）</h3>
            <div class="chart-container">
                <canvas id="lineChart"></canvas>
            </div>
            <p><em>資料來源：台灣健保署2023年報告</em></p>
            <div class="highlight">
                <p><strong>財務警訊</strong>：2023年三高醫療支出達120億元，年增率15%。您的積蓄能承受這壓力嗎？</p>
            </div>

            <!-- 圖表3：圓餅圖 - 併發症比例 -->
            <h3>圖表3：三高併發症類型比例</h3>
            <div class="chart-container">
                <canvas id="pieChart"></canvas>
            </div>
            <p><em>資料來源：台灣醫學研究2023年數據</em></p>
            <div class="highlight">
                <p><strong>健康威脅</strong>：心血管疾病佔比45%，是最致命的併發症。您能忽視這風險嗎？</p>
            </div>

            <!-- 圖表4：區域圖 - 地區醫療花費 -->
            <h3>圖表4：各縣市三高醫療花費比較</h3>
            <div class="chart-container">
                <canvas id="areaChart"></canvas>
            </div>
            <p><em>資料來源：台灣健保署2023年統計</em></p>
            <div class="highlight">
                <p><strong>地區差異</strong>：台北市醫療花費最高，達150億元，顯示醫療資源集中。您所在地區的負擔如何？</p>
            </div>

            <!-- 圖表5：散點圖 - 控制程度與併發症 -->
            <h3>圖表5：三高控制程度與併發症機率關聯</h3>
            <div class="chart-container">
                <canvas id="scatterChart"></canvas>
            </div>
            <p><em>資料來源：台灣醫學研究2023年報告</em></p>
            <div class="highlight">
                <p><strong>控制關鍵</strong>：控制程度越低，併發症機率越高，達60%。您對自己的健康管理有信心嗎？</p>
            </div>

            <!-- 圖表6：熱力圖 - 三高盛行率 -->
            <h3>圖表6：台灣各縣市三高盛行率熱力圖</h3>
            <div class="chart-container">
                <canvas id="heatMap"></canvas>
            </div>
            <p><em>資料來源：國民健康署2023年統計</em></p>
            <div class="highlight">
                <p><strong>盛行警訊</strong>：高雄市三高盛行率達35%，中南部風險顯著。您所在地區安全嗎？</p>
            </div>
        </div>

        <!-- 案例 -->
        <div class="section">
            <h2>真實案例：不保險的沉重代價</h2>
            <p>65歲的林女士，三高患者，因中風住院治療，花費120萬元，健保僅支付40%，自費80萬元幾乎耗盡積蓄。如今她每月藥費1.5萬元，生活品質大幅下降。</p>
            <p><strong>這樣的悲劇，您希望發生在自己身上嗎？</strong></p>
        </div>

        <!-- 保險方案 -->
        <div class="section">
            <h2>國泰人壽三高平安保險：您的最佳選擇</h2>
            <ul>
                <li><strong>低門檻</strong>：三高患者專屬，無需複雜健康檢查。</li>
                <li><strong>全方位保障</strong>：住院、手術、門診費用全涵蓋。</li>
                <li><strong>經濟實惠</strong>：年保費最低僅1.2萬元起。</li>
                <li><strong>快速理賠</strong>：國泰人壽，業界信譽保證。</li>
            </ul>
            <div class="highlight">
                <p><strong>立即行動</strong>：年齡越大，保費越高，風險越大。現在投保，才能省錢又安心！</p>
            </div>
        </div>

        <!-- 風險警示 -->
        <div class="section">
            <h2>不投保的後果有多嚴重？</h2>
            <ul>
                <li><strong>財務危機</strong>：併發症治療費動輒數十萬，掏空積蓄。</li>
                <li><strong>健康惡化</strong>：無資金治療，病情加重，甚至危及生命。</li>
                <li><strong>家庭壓力</strong>：醫療負擔轉嫁子女，影響下一代。</li>
            </ul>
            <p><strong>時間不等人</strong>，健康與財富的雙重危機即將來襲，您還在猶豫什麼？</p>
        </div>

        <!-- 行動呼籲 -->
        <a href="#" class="cta-button">立即聯繫國泰人壽顧問</a>
    </div>

    <!-- 頁腳 -->
    <footer>
        <p>資料來源：台灣健保署2023年統計 | 國民健康署老化趨勢報告 | 台灣醫學研究數據</p>
        <p>版權所有 © 2023 國泰人壽</p>
    </footer>

    <!-- Chart.js 腳本 -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/3.7.0/chart.min.js"></script>
    <script>
        // 圖表1：柱狀圖 - 年齡與併發症機率
        const barCtx = document.getElementById('barChart').getContext('2d');
        const barChart = new Chart(barCtx, {
            type: 'bar',
            data: {
                labels: ['30-39歲', '40-49歲', '50-59歲', '60-69歲', '70歲以上'],
                datasets: [{
                    label: '併發症機率 (%)',
                    data: [10, 20, 35, 55, 70],
                    backgroundColor: ['#ff9f40', '#ffcd56', '#4bc0c0', '#36a2eb', '#ff6384'],
                    borderWidth: 1
                }]
            },
            options: {
                animation: { duration: 1500 },
                scales: { y: { beginAtZero: true, max: 100 } },
                plugins: { legend: { position: 'top' } }
            }
        });

        // 圖表2：折線圖 - 醫療支出趨勢
        const lineCtx = document.getElementById('lineChart').getContext('2d');
        const lineChart = new Chart(lineCtx, {
            type: 'line',
            data: {
                labels: ['2015', '2016', '2017', '2018', '2019', '2020', '2021', '2022', '2023'],
                datasets: [{
                    label: '醫療支出 (億元)',
                    data: [60, 65, 70, 75, 85, 95, 105, 110, 120],
                    borderColor: '#ff6384',
                    backgroundColor: 'rgba(255, 99, 132, 0.2)',
                    fill: true,
                    tension: 0.4
                }]
            },
            options: {
                animation: { duration: 1500 },
                scales: { y: { beginAtZero: true } }
            }
        });

        // 圖表3：圓餅圖 - 併發症比例
        const pieCtx = document.getElementById('pieChart').getContext('2d');
        const pieChart = new Chart(pieCtx, {
            type: 'pie',
            data: {
                labels: ['心血管疾病', '腎臟病', '中風', '視網膜病變', '其他'],
                datasets: [{
                    data: [45, 20, 15, 10, 10],
                    backgroundColor: ['#ff6384', '#36a2eb', '#ffcd56', '#4bc0c0', '#9966ff'],
                    borderWidth: 2
                }]
            },
            options: { animation: { duration: 1500 } }
        });

        // 圖表4：區域圖 - 地區醫療花費
        const areaCtx = document.getElementById('areaChart').getContext('2d');
        const areaChart = new Chart(areaCtx, {
            type: 'line',
            data: {
                labels: ['台北', '新北', '桃園', '台中', '台南', '高雄'],
                datasets: [{
                    label: '醫療花費 (億元)',
                    data: [150, 130, 100, 90, 80, 110],
                    backgroundColor: 'rgba(54, 162, 235, 0.3)',
                    borderColor: '#36a2eb',
                    fill: true,
                    tension: 0.3
                }]
            },
            options: {
                animation: { duration: 1500 },
                scales: { y: { beginAtZero: true } }
            }
        });

        // 圖表5：散點圖 - 控制程度與併發症
        const scatterCtx = document.getElementById('scatterChart').getContext('2d');
        const scatterChart = new Chart(scatterCtx, {
            type: 'scatter',
            data: {
                datasets: [{
                    label: '控制程度 vs 併發症機率',
                    data: [
                        {x: 1, y: 60}, {x: 1.5, y: 55}, {x: 2, y: 45},
                        {x: 2.5, y: 40}, {x: 3, y: 30}, {x: 3.5, y: 25},
                        {x: 4, y: 20}, {x: 4.5, y: 15}, {x: 5, y: 10}
                    ],
                    backgroundColor: '#ff6384'
                }]
            },
            options: {
                animation: { duration: 1500 },
                scales: {
                    x: { title: { display: true, text: '控制程度 (1-5)' } },
                    y: { title: { display: true, text: '併發症機率 (%)' }, max: 100 }
                }
            }
        });

        // 圖表6：熱力圖（模擬為柱狀圖）
        const heatCtx = document.getElementById('heatMap').getContext('2d');
        const heatMap = new Chart(heatCtx, {
            type: 'bar',
            data: {
                labels: ['台北', '新北', '桃園', '台中', '台南', '高雄'],
                datasets: [{
                    label: '三高盛行率 (%)',
                    data: [25, 22, 20, 28, 30, 35],
                    backgroundColor: ['#ff9f40', '#ffcd56', '#4bc0c0', '#36a2eb', '#9966ff', '#ff6384'],
                    borderWidth: 1
                }]
            },
            options: {
                animation: { duration: 1500 },
                scales: { y: { beginAtZero: true, max: 50 } }
            }
        });
    </script>
</body>
</html>
