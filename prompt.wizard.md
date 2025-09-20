<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prompt.Wizard - Infographic</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Exo+2:wght@700&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Open Sans', sans-serif;
            background-color: #003262;
        }
        .header-font {
            font-family: 'Exo 2', sans-serif;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            height: 350px;
            max-height: 450px;
        }
        @media (max-width: 768px) {
            .chart-container {
                height: 300px;
            }
        }
        .flow-step {
            background-color: #003B73;
            border: 2px solid #60A3D9;
            box-shadow: 0 5px 15px rgba(191, 215, 237, 0.1);
        }
        .flow-arrow {
            color: #60A3D9;
            font-size: 2.5rem;
            line-height: 1;
        }
    </style>
</head>
<body class="text-gray-200">

    <div class="container mx-auto p-4 md:p-8">

        <header class="text-center mb-12 md:mb-16">
            <h1 class="header-font text-5xl md:text-7xl font-bold text-white tracking-wide">PROMPT.WIZARD</h1>
            <p class="text-lg md:text-xl text-blue-200 mt-2">Engineering Just, Allied, and Non-Harmful AI Prompts</p>
        </header>

        <section id="process" class="mb-12 md:mb-20">
            <div class="bg-gray-900/30 rounded-lg shadow-2xl p-6 md:p-8 border border-blue-800">
                <h2 class="header-font text-4xl text-center mb-4 text-blue-200">How It Works: A Feedback-Driven Framework</h2>
                 <p class="text-center max-w-3xl mx-auto mb-10 text-blue-300">
                    Prompt.Wizard employs an automated, four-stage process to rapidly generate and refine high-quality AI prompts. This iterative cycle ensures every output is safe, effective, and aligned with ethical guidelines.
                </p>
                <div class="flex flex-col md:flex-row justify-center items-center gap-4 md:gap-0">
                    <div class="flow-step p-4 rounded-lg text-center w-52 h-36 flex flex-col justify-center">
                        <h3 class="font-bold text-white">1. Generation</h3>
                        <p class="text-sm text-blue-300">Creates diverse candidate prompts from a core intent.</p>
                    </div>
                    <div class="flow-arrow transform md:-rotate-0 rotate-90">→</div>
                    <div class="flow-step p-4 rounded-lg text-center w-52 h-36 flex flex-col justify-center">
                        <h3 class="font-bold text-white">2. Refinement</h3>
                        <p class="text-sm text-blue-300">Uses LLM self-critique to filter and improve prompts.</p>
                    </div>
                    <div class="flow-arrow transform md:-rotate-0 rotate-90">→</div>
                    <div class="flow-step p-4 rounded-lg text-center w-52 h-36 flex flex-col justify-center">
                        <h3 class="font-bold text-white">3. Pairing</h3>
                        <p class="text-sm text-blue-300">Joins instructions with clear examples for context.</p>
                    </div>
                    <div class="flow-arrow transform md:-rotate-0 rotate-90">→</div>
                    <div class="flow-step p-4 rounded-lg text-center w-52 h-36 flex flex-col justify-center">
                        <h3 class="font-bold text-white">4. Output</h3>
                        <p class="text-sm text-blue-300">Delivers safe, compliant, and context-rich prompts.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="features" class="mb-12 md:mb-20">
            <h2 class="header-font text-4xl text-center mb-8 text-blue-200">Core Features & Guarantees</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="bg-gray-900/30 p-6 rounded-lg text-center border border-blue-800">
                    <div class="text-5xl mb-3">🛡️</div>
                    <h3 class="text-xl font-bold text-white mb-2">Safety & Ethics</h3>
                    <p class="text-blue-300 text-sm">Automatically filters for bias and harm, ensuring non-escalatory and just outputs.</p>
                </div>
                <div class="bg-gray-900/30 p-6 rounded-lg text-center border border-blue-800">
                    <div class="text-5xl mb-3">🚀</div>
                    <h3 class="text-xl font-bold text-white mb-2">Efficiency & Scale</h3>
                    <p class="text-blue-300 text-sm">Rapidly generates and customizes large prompt sets across multiple domains.</p>
                </div>
                 <div class="bg-gray-900/30 p-6 rounded-lg text-center border border-blue-800">
                    <div class="text-5xl mb-3">📜</div>
                    <h3 class="text-xl font-bold text-white mb-2">Audit & Compliance</h3>
                    <p class="text-blue-300 text-sm">Embeds logging and metadata for full transparency and reviewability of all prompts.</p>
                </div>
                <div class="bg-gray-900/30 p-6 rounded-lg text-center border border-blue-800">
                    <div class="text-5xl mb-3">🤝</div>
                    <h3 class="text-xl font-bold text-white mb-2">Clarity & Context</h3>
                    <p class="text-blue-300 text-sm">Pairs instructions with examples to support specific roles and allied interpretations.</p>
                </div>
            </div>
        </section>

        <section id="visualizations" class="grid grid-cols-1 lg:grid-cols-2 gap-8 mb-12 md:mb-20">
            <div class="bg-gray-900/30 rounded-lg shadow-2xl p-6 md:p-8 border border-blue-800">
                <h3 class="header-font text-3xl mb-2 text-blue-200">Example Use-Case Applications</h3>
                <p class="text-blue-300 mb-6 text-sm">Prompt.Wizard excels in creating communication templates for sensitive and complex scenarios, ensuring that all AI-generated content promotes trust, equity, and transparency.</p>
                <div class="chart-container">
                    <canvas id="useCaseChart"></canvas>
                </div>
            </div>
            <div class="bg-gray-900/30 rounded-lg shadow-2xl p-6 md:p-8 border border-blue-800">
                <h3 class="header-font text-3xl mb-2 text-blue-200">Conceptual Backing & Influence</h3>
                 <p class="text-blue-300 mb-6 text-sm">The framework's design is informed by leading research and tools in the prompt engineering field, combining academic rigor with practical application for robust results.</p>
                <div class="chart-container">
                    <canvas id="sourceInfluenceChart"></canvas>
                </div>
            </div>
        </section>

        <footer class="text-center text-blue-400 text-sm mt-12">
            <p>Prompt.Wizard: A framework for building a safer, more aligned AI future.</p>
        </footer>

    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const processLabel = (label) => {
                if (typeof label !== 'string' || label.length <= 16) {
                    return label;
                }
                const words = label.split(' ');
                const lines = [];
                let currentLine = '';
                words.forEach(word => {
                    if ((currentLine + ' ' + word).trim().length > 16) {
                        if (currentLine) lines.push(currentLine.trim());
                        currentLine = word;
                    } else {
                        currentLine = (currentLine + ' ' + word).trim();
                    }
                });
                if (currentLine) lines.push(currentLine.trim());
                return lines;
            };

            const tooltipTitleCallback = (tooltipItems) => {
                const item = tooltipItems[0];
                if (!item || !item.chart.data.labels) return '';
                let label = item.chart.data.labels[item.dataIndex];
                if (Array.isArray(label)) {
                    return label.join(' ');
                }
                return label;
            };

            const sharedChartOptions = {
                maintainAspectRatio: false,
                plugins: {
                    legend: {
                        labels: {
                            color: '#BFD7ED',
                            font: {
                                family: "'Open Sans', sans-serif",
                            }
                        }
                    },
                    tooltip: {
                        callbacks: {
                            title: tooltipTitleCallback
                        }
                    }
                }
            };
            
            const brilliantBlues = ['#0074B7', '#60A3D9', '#BFD7ED', '#003B73'];

            const useCaseCtx = document.getElementById('useCaseChart').getContext('2d');
            const useCaseLabels = [
                'Diplomatic negotiation templates',
                'Rights-sensitive AI queries',
                'Compliance statements',
                'Gratitude artifacts'
            ];
            new Chart(useCaseCtx, {
                type: 'bar',
                data: {
                    labels: useCaseLabels.map(processLabel),
                    datasets: [{
                        label: 'Application Suitability Score',
                        data: [95, 90, 88, 82],
                        backgroundColor: brilliantBlues,
                        borderColor: '#003262',
                        borderWidth: 2,
                    }]
                },
                options: {
                    ...sharedChartOptions,
                    indexAxis: 'y',
                    scales: {
                        x: {
                            beginAtZero: true,
                            grid: { color: 'rgba(191, 215, 237, 0.1)' },
                            ticks: { color: '#BFD7ED' }
                        },
                        y: {
                            grid: { display: false },
                            ticks: { color: '#BFD7ED' }
                        }
                    }
                }
            });

            const sourceInfluenceCtx = document.getElementById('sourceInfluenceChart').getContext('2d');
            new Chart(sourceInfluenceCtx, {
                type: 'bubble',
                data: {
                    datasets: [{
                        label: 'Microsoft',
                        data: [{ x: 20, y: 30, r: 25 }],
                        backgroundColor: brilliantBlues[0]
                    }, {
                        label: 'MaxAI',
                        data: [{ x: 40, y: 55, r: 20 }],
                        backgroundColor: brilliantBlues[1]
                    }, {
                        label: 'arXiv',
                        data: [{ x: 65, y: 25, r: 15 }],
                        backgroundColor: brilliantBlues[2]
                    }]
                },
                options: {
                    ...sharedChartOptions,
                    scales: {
                        x: {
                            display: false,
                            min: 0,
                            max: 100,
                        },
                        y: {
                            display: false,
                            min: 0,
                            max: 100,
                        }
                    }
                }
            });
        });
    </script>
</body>
</html>
