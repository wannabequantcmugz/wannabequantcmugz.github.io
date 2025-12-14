<!DOCTYPE html>
<html>
<head>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
            background-color: #f8f9fa;
            color: #333;
            line-height: 1.6;
        }
        .header {
            text-align: center;
            border-bottom: 2px solid #2c3e50;
            padding-bottom: 20px;
            margin-bottom: 30px;
        }
        .header h1 {
            color: #2c3e50;
            margin-bottom: 5px;
        }
        .header .subtitle {
            color: #7f8c8d;
            font-size: 0.9em;
        }
        .results-box {
            background: white;
            border-radius: 8px;
            padding: 25px;
            margin: 25px 0;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
            border-left: 4px solid #3498db;
        }
        .metric-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        .metric {
            text-align: center;
            padding: 15px;
            background: #f8f9fa;
            border-radius: 6px;
        }
        .metric-value {
            font-size: 1.8em;
            font-weight: bold;
            color: #2c3e50;
        }
        .metric-label {
            font-size: 0.9em;
            color: #7f8c8d;
            margin-top: 5px;
        }
        .positive { color: #27ae60; }
        .chart-container {
            text-align: center;
            margin: 30px 0;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
        }
        .chart-container img {
            max-width: 100%;
            height: auto;
            border-radius: 4px;
        }
        .phase-box {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            margin-top: 30px;
        }
        .footer {
            text-align: center;
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid #eee;
            color: #7f8c8d;
            font-size: 0.9em;
        }
        a {
            color: #3498db;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Axiom QPAM: Initial Backtest Complete</h1>
        <div class="subtitle">
            <strong>Date:</strong> 15 December 2024 | 
            <strong>Status:</strong> Validation Phase Passed
        </div>
    </div>

    <div class="results-box">
        <h2>Backtest Results (Jan 2020 - Nov 2024)</h2>
        
        <div class="metric-grid">
            <div class="metric">
                <div class="metric-value positive">1.04</div>
                <div class="metric-label">Sharpe Ratio</div>
            </div>
            <div class="metric">
                <div class="metric-value">-23.56%</div>
                <div class="metric-label">Max Drawdown</div>
            </div>
            <div class="metric">
                <div class="metric-value positive">+47.1%</div>
                <div class="metric-label">Total Return</div>
            </div>
            <div class="metric">
                <div class="metric-value">£14,710</div>
                <div class="metric-label">Final Value</div>
            </div>
        </div>
        
        <p><strong>Analysis:</strong> The model demonstrates positive risk-adjusted returns (Sharpe > 1.0) and survives major market volatility (Max DD < -25%). The results validate the core multi-factor logic.</p>
    </div>

    <div class="chart-container">
        <h2>Equity Curve</h2>
        <img src="equity_curve.png" alt="Axiom QPAM Portfolio Growth 2020-2024">
        <p><em>Portfolio growth from £10,000 to £14,710 (2020-2024)</em></p>
    </div>

    <div class="phase-box">
        <h2>Next Research Phase</h2>
        <ul>
            <li>Detailed performance attribution & factor analysis</li>
            <li>Transaction cost & slippage modeling</li>
            <li>Preparation of full Investment Memorandum (Q1 2026)</li>
            <li>Live paper trading implementation</li>
        </ul>
    </div>

    <div class="footer">
        <p>Axiom Capital Research • <a href="/">Return to Home</a> • <a href="https://github.com/wannabequantcmugz" target="_blank">GitHub</a></p>
        <p><em>Independent systematic finance research</em></p>
    </div>
</body>
</html>
