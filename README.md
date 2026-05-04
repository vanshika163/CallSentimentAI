<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Call Sentiment AI</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f5f7fa;
            color: #333;
        }

        header {
            background: #4a90e2;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .container {
            width: 85%;
            margin: 20px auto;
        }

        h2 {
            color: #4a90e2;
            border-bottom: 2px solid #ddd;
            padding-bottom: 5px;
        }

        .card {
            background: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        ul {
            padding-left: 20px;
        }

        code {
            background: #eee;
            padding: 5px;
            display: block;
            border-radius: 5px;
            margin: 10px 0;
        }

        footer {
            text-align: center;
            padding: 15px;
            background: #4a90e2;
            color: white;
            margin-top: 20px;
        }

        .tag {
            display: inline-block;
            background: #e1ecf4;
            color: #39739d;
            padding: 5px 10px;
            margin: 5px;
            border-radius: 5px;
            font-size: 14px;
        }
    </style>
</head>
<body>

<header>
    <h1>Call Sentiment AI</h1>
    <p>Analyze customer call recordings using AI</p>
</header>

<div class="container">

    <div class="card">
        <h2>Overview</h2>
        <p>
            Call Sentiment AI is a web application that analyzes customer call recordings by converting speech into text 
            and detecting the sentiment of the conversation. It classifies calls as <b>positive, negative, or neutral</b>.
        </p>
    </div>

    <div class="card">
        <h2>Features</h2>
        <ul>
            <li>Upload audio files</li>
            <li>Speech-to-text transcription</li>
            <li>Sentiment analysis</li>
            <li>Clear result display</li>
            <li>Responsive UI</li>
        </ul>
    </div>

    <div class="card">
        <h2>How It Works</h2>
        <ol>
            <li>User uploads an audio file</li>
            <li>System converts speech to text</li>
            <li>Text is analyzed for sentiment</li>
            <li>Result is displayed</li>
        </ol>
    </div>

    <div class="card">
        <h2>Technologies Used</h2>
        <div class="tag">Python</div>
        <div class="tag">Streamlit</div>
        <div class="tag">Whisper</div>
        <div class="tag">PyTorch</div>
        <div class="tag">Transformers</div>
        <div class="tag">FFmpeg</div>
        <div class="tag">GitHub</div>
    </div>

    <div class="card">
        <h2>Project Structure</h2>
        <code>
CallSentimentAI/<br>
├── app.py<br>
├── requirements.txt<br>
├── README.md<br>
└── other files
        </code>
    </div>

    <div class="card">
        <h2>Installation</h2>
        <code>
git clone https://github.com/vanshika-gupta/CallSentimentAI.git<br>
cd CallSentimentAI<br>
pip install -r requirements.txt
        </code>
        <p>Ensure FFmpeg is installed.</p>
    </div>

    <div class="card">
        <h2>Run Application</h2>
        <code>
streamlit run app.py
        </code>
    </div>

    <div class="card">
        <h2>Use Case</h2>
        <p>
            Helps analyze customer support calls to understand sentiment and improve service quality.
        </p>
    </div>

    <div class="card">
        <h2>Future Upgrades</h2>
        <ul>
            <li>Real-time monitoring</li>
            <li>Live microphone input</li>
            <li>Analytics dashboard</li>
            <li>Call history tracking</li>
            <li>Advanced emotion detection</li>
        </ul>
    </div>

</div>

<footer>
    <p>Created by Vanshika Gupta</p>
</footer>

</body>
</html>
