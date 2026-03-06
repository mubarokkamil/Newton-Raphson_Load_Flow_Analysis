<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Ultimate Newton-Raphson Load Flow Guide</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f7f6;
            color: #333;
            text-align: center;
            padding: 50px 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }
        h1 {
            color: #0066CC; /* Matches your LaTeX mainblue */
        }
        p {
            font-size: 1.1em;
            line-height: 1.6;
            color: #555;
            margin-bottom: 30px;
        }
        .btn {
            display: inline-block;
            margin: 10px;
            padding: 15px 30px;
            font-size: 1.1em;
            font-weight: bold;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s;
        }
        .btn-pdf {
            background-color: #0066CC;
        }
        .btn-pdf:hover {
            background-color: #004C99;
        }
        .btn-latex {
            background-color: #00994C; /* Matches your LaTeX conceptgreen */
        }
        .btn-latex:hover {
            background-color: #006633;
        }
        .footer {
            margin-top: 40px;
            font-size: 0.9em;
            color: #888;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>The Ultimate Newton-Raphson Load Flow Guide</h1>
    <p>By <strong>Mubarok Hossen Kamil</strong></p>
    
    <p>A complete, step-by-step pedagogical guide to solving Power System Load Flows. This guide bridges the gap left by most textbooks by providing full mathematical expansions for Iteration 1 <strong>and</strong> Iteration 2, dynamically building the Jacobian matrix, and highlighting common exam traps (like Radian vs. Degree calculator settings and Inverse Tangent Quadrant errors).</p>
    
    <!-- Here is the updated link pointing to your exact PDF name! -->
    <a href="Newton_Raphson_Guide.pdf" class="btn btn-pdf" target="_blank">📄 Read / Download the PDF</a>
    
    <!-- Assumes your LaTeX file is named main.tex. Update if it's different! -->
    <a href="main.tex" class="btn btn-latex" target="_blank">💻 View LaTeX Source Code</a>

    <div class="footer">
        Created for Electrical Engineering students everywhere.
    </div>
</div>

</body>
</html>
