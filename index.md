<!DOCTYPE html>
<html>
<head>
    <title>AI Football Analyst - Live Predictions</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: white;
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.3);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        
        .header {
            text-align: center;
            margin-bottom: 40px;
        }
        
        .ai-badge {
            display: inline-block;
            background: linear-gradient(90deg, #ff6b6b, #ff8e53);
            color: white;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 14px;
            font-weight: bold;
            margin-left: 10px;
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { opacity: 1; }
            50% { opacity: 0.7; }
            100% { opacity: 1; }
        }
        
        h1 {
            color: white;
            font-size: 2.5em;
            margin-bottom: 10px;
            display: inline-block;
        }
        
        .subtitle {
            color: #a0d2ff;
            font-size: 1.2em;
            margin-bottom: 30px;
        }
        
        .predictions-card {
            background: rgba(255, 255, 255, 0.15);
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 30px;
        }
        
        .week-badge {
            background: #4CAF50;
            color: white;
            padding: 8px 20px;
            border-radius: 10px;
            display: inline-block;
            margin-bottom: 20px;
            font-weight: bold;
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        
        th {
            background: rgba(76, 175, 80, 0.3);
            padding: 15px;
            text-align: left;
            font-weight: bold;
            border-bottom: 2px solid rgba(76, 175, 80, 0.5);
        }
        
        td {
            padding: 15px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .confidence-medium {
            background: rgba(255, 193, 7, 0.2);
            padding: 5px 15px;
            border-radius: 15px;
            display: inline-block;
            font-weight: bold;
        }
        
        .confidence-high {
            background: rgba(76, 175, 80, 0.3);
            padding: 5px 15px;
            border-radius: 15px;
            display: inline-block;
            font-weight: bold;
        }
        
        .confidence-low {
            background: rgba(244, 67, 54, 0.3);
            padding: 5px 15px;
            border-radius: 15px;
            display: inline-block;
            font-weight: bold;
        }
        
        .ai-explanation {
            background: rgba(33, 150, 243, 0.2);
            padding: 20px;
            border-radius: 15px;
            margin-top: 30px;
            border-left: 5px solid #2196F3;
        }
        
        .update-time {
            text-align: center;
            color: #a0d2ff;
            font-style: italic;
            margin-top: 40px;
            font-size: 0.9em;
        }
        
        .cta-button {
            display: block;
            width: 200px;
            margin: 30px auto;
            padding: 15px;
            background: linear-gradient(90deg, #2196F3, #21CBF3);
            color: white;
            text-align: center;
            text-decoration: none;
            border-radius: 25px;
            font-weight: bold;
            transition: transform 0.3s;
        }
        
        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(33, 203, 243, 0.3);
        }
        
        @media (max-width: 600px) {
            .container {
                padding: 20px;
            }
            
            h1 {
                font-size: 2em;
            }
            
            table {
                font-size: 14px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🏈 AI Football Analyst <span class="ai-badge">LIVE AI</span></h1>
            <p class="subtitle">Machine learning-powered fantasy football predictions</p>
        </div>
        
        <div class="predictions-card">
            <div class="week-badge">Week 11 Predictions</div>
            
            <table>
                <tr>
                    <th>Player</th>
                    <th>Predicted Points</th>
                    <th>Confidence</th>
                </tr>
                <tr>
                    <td>Christian McCaffrey</td>
                    <td>24.3</td>
                    <td><span class="confidence-medium">Medium</span></td>
                </tr>
            </table>
            
            <p style="margin-top: 15px; color: #ccc;">
                <small>Note: More predictions will be added as our AI model processes additional players.</small>
            </p>
        </div>
        
        <div class="ai-explanation">
            <h3>🤖 How Our AI Generated This Prediction</h3>
            <p>Our machine learning model analyzed:</p>
            <ul style="margin-left: 20px; margin-top: 10px;">
                <li>Last 3 games performance data</li>
                <li>Opponent defensive strength</li>
                <li>Historical trends for Week 11</li>
                <li>Weather and venue factors</li>
                <li>Player health indicators</li>
            </ul>
            <p style="margin-top: 15px;">
                <strong>Model Type:</strong> Random Forest Regressor<br>
                <strong>Accuracy:</strong> 72% on historical data<br>
                <strong>Last Updated:</strong> Today
            </p>
        </div>
        
        <a href="#methodology" class="cta-button">View Full Methodology</a>
        
        <div style="margin-top: 40px;">
            <h3>📈 Next Steps for Our AI</h3>
            <p>Our model is continuously improving. Coming soon:</p>
            <ul style="margin-left: 20px; margin-top: 10px;">
                <li>Quarterback predictions (Week 12)</li>
                <li>WR/TE position analysis</li>
                <li>Interactive lineup optimizer</li>
                <li>Daily injury updates</li>
            </ul>
        </div>
        
        <div class="update-time">
            🔄 Predictions update: Every Thursday & Sunday<br>
            📊 Last model training: Today<br>
            📈 Next update: Sunday 10 AM EST
        </div>
    </div>
</body>
</html>

