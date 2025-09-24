# Prompts-
An AI tool to generate coloring book prompts.
<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Coloring Book Prompt Generator</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
            max-width: 600px;
            margin: 0 auto;
        }
        input, button, textarea {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            box-sizing: border-box;
            font-size: 16px;
        }
        button {
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }
        textarea {
            height: 150px;
        }
    </style>
</head>
<body>
    <h1>Coloring Book Prompt Generator</h1>
    <input type="text" id="ideaInput" placeholder="Enter your idea (e.g., 'unicorn in garden')">
    <button onclick="generatePrompt()">Generate Prompt</button>
    <textarea id="output" readonly placeholder="Your prompt will appear here..."></textarea>
</body>
</html>
