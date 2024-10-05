<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Teachers' Day, Mam Arooj!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
            color: #333;
            text-align: center;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 20px 0;
            animation: fadeIn 2s;
        }
        h1 {
            font-size: 2.5em;
            margin: 0;
        }
        .message {
            font-size: 1.5em;
            margin: 20px 0;
        }
        .timeline {
            margin: 20px auto;
            width: 80%;
            max-width: 600px;
            border: 1px solid #007bff;
            border-radius: 10px;
            padding: 10px;
            background-color: white;
        }
        .quiz {
            margin: 20px auto;
            width: 80%;
            max-width: 600px;
            padding: 10px;
            background-color: #e9ecef;
            border-radius: 10px;
        }
        button {
            padding: 10px 15px;
            font-size: 1em;
            margin-top: 10px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
            background-color: #28a745;
            color: white;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #218838;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
    <script>
        function showQuiz() {
            alert("Welcome to the fun quiz! Here’s a question: What is the powerhouse of the cell?\n1. Nucleus\n2. Mitochondria\n3. Ribosome\n\nHint: It's where energy is produced!");
        }
    </script>
</head>
<body>
    <header>
        <h1>Happy Teachers' Day, Mam Arooj!</h1>
    </header>
    <div class="message">
        Thank you for being an amazing teacher and a constant source of support and inspiration! <br>
        Even though I’m not in your biology class, your impact on us has been undeniable. <br>
        Wishing you all the happiness and success today and always! <br>
        <strong>P.S.: We all know biology is life, but computers have a cool teacher too!</strong>
    </div>
    <div class="timeline">
        <h2>Teaching Highlights</h2>
        <ul>
            <li>Always makes biology fun with your interesting experiments!</li>
            <li>Encouraged us to ask questions and think critically.</li>
            <li>Made IG1 feel like a second home for us!</li>
        </ul>
    </div>
    <div class="quiz">
        <h2>Fun Quiz!</h2>
        <p>Ready for a fun biology question?</p>
        <button onclick="showQuiz()">Start Quiz</button>
    </div>
</body>
</html>
