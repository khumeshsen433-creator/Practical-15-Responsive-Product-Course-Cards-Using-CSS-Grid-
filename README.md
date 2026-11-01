# Practical-15-Responsive-Product-Course-Cards-Using-CSS-Grid-

<!DOCTYPE html>
<html>
<head>
    <title>Course Grid</title>
    <meta name="viewport"
          content="width=device-width, initial-scale=1">

    <style>
        body {
            font-family: Arial;
            padding: 20px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 15px;
        }

        .card {
            background: lightblue;
            padding: 30px 10px;
            text-align: center;
            border-radius: 10px;
            border: 1px solid navy;
        }

        @media (max-width: 600px) {
            .grid {
                grid-template-columns: repeat(2, 1fr);
            }
        }
    </style>
</head>
<body>
    <h1>Our Courses</h1>

    <div class="grid">
        <div class="card">HTML</div>
        <div class="card">CSS</div>
        <div class="card">JavaScript</div>
        <div class="card">Python</div>
        <div class="card">Java</div>
        <div class="card">C++</div>
    </div>
</body>
</html>
