<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>연세 신규 건기식 라인업: 시장 잠재력 분석</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;500;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Noto Sans KR', sans-serif;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 900px;
            margin-left: auto;
            margin-right: auto;
            height: 350px;
            max-height: 40vh;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 400px;
            }
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800">

    <div class="container mx-auto p-4 md:p-8">

        <header class="text-center mb-12">
            <h1 class="text-4xl md:text-5xl font-extrabold text-[#003876] mb-2">연세 신규 건기식 라인업</h1>
            <p class="text-xl md:text-2xl font-bold text-[#00A6FB]">시장 잠재력 및 성장 전망 분석</p>
            <p class="mt-4 text-slate-600 max-w-3xl mx-auto">
                현대인의 건강 트렌드를 반영한 3대 핵심 시장의 과거 데이터를 분석하고, 미래 성장성을 예측하여 연세 브랜드의 성공적인 시장 진입 전략을 뒷받침합니다.
            </p>
        </header>

        <main class="space-y-16">
            
            <section id="market-relax" class="bg-white p-6 md:p-8 rounded-2xl shadow-lg transition-all duration-300 hover:shadow-2xl">
                <div class="text-center mb-6">
                    <h2 class="text-3xl font-bold text-[#DC0073] mb-2">1. 멘탈 웰니스: 스트레스 & 수면 케어 시장</h2>
                    <p class="text-lg text-slate-700 font-medium">YONSEI URBAN RELAX™</p>
                    <p class="mt-2 text-slate-500 max-w-2xl mx-auto">
                        디지털 시대 2030세대의 핵심 고민인 스트레스와 수면 문제를 정조준한 시장입니다. 삶의 질을 중시하는 트렌드와 함께 가파른 성장세를 보이고 있습니다.
                    </p>
                </div>
                <div class="chart-container">
                    <canvas id="relaxChart"></canvas>
                </div>
            </section>

            <section id="market-beauty" class="bg-white p-6 md:p-8 rounded-2xl shadow-lg transition-all duration-300 hover:shadow-2xl">
                <div class="text-center mb-6">
                    <h2 class="text-3xl font-bold text-[#F5B700] mb-2">2. 이너뷰티: 먹는 화장품 시장</h2>
                    <p class="text-lg text-slate-700 font-medium">YONSEI LUMINOUS AURA™</p>
                    <p class="mt-2 text-slate-500 max-w-2xl mx-auto">
                        '헬시플레저' 열풍을 타고 폭발적으로 성장하는 시장입니다. MZ세대를 중심으로 건강한 아름다움에 대한 투자가 확대되며 시장 규모가 급격히 팽창하고 있습니다.
                    </p>
                </div>
                <div class="chart-container">
                    <canvas id="beautyChart"></canvas>
                </div>
            </section>

            <section id="market-vision" class="bg-white p-6 md:p-8 rounded-2xl shadow-lg transition-all duration-300 hover:shadow-2xl">
                <div class="text-center mb-6">
                    <h2 class="text-3xl font-bold text-[#00D29A] mb-2">3. 눈 건강: 디지털 시대 필수 영양제 시장</h2>
                    <p class="text-lg text-slate-700 font-medium">YONSEI VISION SHIELD™</p>
                    <p class="mt-2 text-slate-500 max-w-2xl mx-auto">
                        전 연령대에서 가장 높은 건강 염려도를 보이는 분야입니다. 스마트 기기 사용의 보편화로 안정적이고 꾸준한 성장이 기대되는 가장 큰 규모의 시장입니다.
                    </p>
                </div>
                <div class="chart-container">
                    <canvas id="visionChart"></canvas>
                </div>
            </section>

        </main>

        <footer class="mt-16 pt-8 border-t border-slate-200 text-center">
            <h3 class="text-lg font-semibold text-slate-700">데이터 출처 및 근거</h3>
            <div class="mt-4 text-sm text-slate-500 space-y-2 max-w-4xl mx-auto">
                <p>
                    <strong>멘탈 웰니스(스트레스/수면) 시장:</strong> 한국건강기능식품협회 '건강기능식품 시장 결산 및 전망' 보고서, 식품의약품안전처 식품 등 생산실적 데이터, 주요 증권사 리서치 자료 종합 분석. (연평균 성장률 약 18% 적용)
                </p>
                <p>
                    <strong>이너뷰티 시장:</strong> 칸타월드패널 소비자 조사 데이터, 오픈서베이 '뷰티 트렌드 리포트', 신한금융투자 리서치센터 자료 기반 추정. (보고서 내 2025년 2조원 전망치 및 연평균 성장률 약 15% 적용)
                </p>
                <p>
                    <strong>눈 건강 시장:</strong> 식품의약품안전처 '건강기능식품 품목별 생산실적', 한국건강기능식품협회 소비자 실태조사 데이터 기반. (안정적 시장으로 연평균 성장률 약 8% 적용)
                </p>
                <p class="pt-4 text-xs text-slate-400">
                    * 본 인포그래픽의 시장 규모 데이터는 공개된 자료를 바탕으로 추정한 값이며, 실제 수치와 다소 차이가 있을 수 있습니다. (E): 추정치, (F): 전망치
                </p>
            </div>
        </footer>

    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const commonTooltipOptions = {
                plugins: {
                    tooltip: {
                        callbacks: {
                            title: function(tooltipItems) {
                                const item = tooltipItems[0];
                                let label = item.chart.data.labels[item.dataIndex];
                                if (Array.isArray(label)) {
                                    return label.join(' ');
                                } else {
                                    return label;
                                }
                            }
                        }
                    }
                }
            };

            const formatYAxisLabel = (value, unit, divisor) => {
                if (value === 0) return '0';
                const num = value / divisor;
                if (num >= 10000) {
                    return (num / 10000).toFixed(1).replace(/\.0$/, '') + '조 ' + unit;
                }
                return num.toFixed(0) + unit;
            };

            const relaxChartCtx = document.getElementById('relaxChart').getContext('2d');
            new Chart(relaxChartCtx, {
                type: 'bar',
                data: {
                    labels: ['2022', '2023', '2024(E)', '2025(F)', '2026(F)', '2027(F)'],
                    datasets: [{
                        label: '시장 규모 (억원)',
                        data: [850, 1100, 1350, null, null, null],
                        backgroundColor: 'rgba(220, 0, 115, 0.6)',
                        borderColor: 'rgba(220, 0, 115, 1)',
                        borderWidth: 1,
                        order: 2
                    }, {
                        type: 'line',
                        label: '성장 전망',
                        data: [null, null, 1350, 1600, 1900, 2250],
                        borderColor: '#DC0073',
                        backgroundColor: '#DC0073',
                        tension: 0.3,
                        fill: false,
                        order: 1
                    }]
                },
                options: {
                    ...commonTooltipOptions,
                    responsive: true,
                    maintainAspectRatio: false,
                    scales: {
                        y: {
                            beginAtZero: true,
                            ticks: {
                                callback: function(value) { return formatYAxisLabel(value, '억원', 1); }
                            }
                        }
                    },
                    plugins: {
                        ...commonTooltipOptions.plugins,
                        title: { display: true, text: '스트레스 & 수면 케어 시장 규모 (단위: 억원)' }
                    }
                }
            });

            const beautyChartCtx = document.getElementById('beautyChart').getContext('2d');
            new Chart(beautyChartCtx, {
                type: 'bar',
                data: {
                    labels: ['2022', '2023', '2024(E)', '2025(F)', '2026(F)', '2027(F)'],
                    datasets: [{
                        label: '시장 규모 (억원)',
                        data: [11000, 13500, 16500, null, null, null],
                        backgroundColor: 'rgba(245, 183, 0, 0.6)',
                        borderColor: 'rgba(245, 183, 0, 1)',
                        borderWidth: 1,
                        order: 2
                    }, {
                        type: 'line',
                        label: '성장 전망',
                        data: [null, null, 16500, 20000, 23000, 26000],
                        borderColor: '#F5B700',
                        backgroundColor: '#F5B700',
                        tension: 0.3,
                        fill: false,
                        order: 1
                    }]
                },
                options: {
                    ...commonTooltipOptions,
                    responsive: true,
                    maintainAspectRatio: false,
                    scales: {
                        y: {
                            beginAtZero: true,
                            ticks: {
                                callback: function(value) { return formatYAxisLabel(value, '억원', 1); }
                            }
                        }
                    },
                    plugins: {
                        ...commonTooltipOptions.plugins,
                        title: { display: true, text: '이너뷰티 시장 규모 (단위: 억원)' }
                    }
                }
            });

            const visionChartCtx = document.getElementById('visionChart').getContext('2d');
            new Chart(visionChartCtx, {
                type: 'bar',
                data: {
                    labels: ['2022', '2023', '2024(E)', '2025(F)', '2026(F)', '2027(F)'],
                    datasets: [{
                        label: '시장 규모 (억원)',
                        data: [3800, 4200, 4550, null, null, null],
                        backgroundColor: 'rgba(0, 210, 154, 0.6)',
                        borderColor: 'rgba(0, 210, 154, 1)',
                        borderWidth: 1,
                        order: 2
                    }, {
                        type: 'line',
                        label: '성장 전망',
                        data: [null, null, 4550, 4900, 5300, 5700],
                        borderColor: '#00D29A',
                        backgroundColor: '#00D29A',
                        tension: 0.3,
                        fill: false,
                        order: 1
                    }]
                },
                options: {
                    ...commonTooltipOptions,
                    responsive: true,
                    maintainAspectRatio: false,
                    scales: {
                        y: {
                            beginAtZero: true,
                            ticks: {
                                callback: function(value) { return formatYAxisLabel(value, '억원', 1); }
                            }
                        }
                    },
                    plugins: {
                        ...commonTooltipOptions.plugins,
                        title: { display: true, text: '눈 건강기능식품 시장 규모 (단위: 억원)' }
                    }
                }
            });
        });
    </script>
</body>
</html>
