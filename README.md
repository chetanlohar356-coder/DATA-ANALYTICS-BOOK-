index.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Data Analytics Handbooks</title>
<link rel="manifest" href="manifest.json">
<style>
body {
    margin: 0;
    font-family: Arial;
    background: #0f172a;
    color: white;
    text-align: center;
}

header {
    padding: 20px;
    font-size: 28px;
    font-weight: bold;
    background: #111827;
    box-shadow: 0 2px 10px rgba(0,0,0,0.4);
}

.container {
    padding: 20px;
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(150px,1fr));
    gap: 20px;
}

.card {
    background: #1e293b;
    border-radius: 20px;
    padding: 20px;
    transition: 0.3s;
}

.card:hover {
    transform: scale(1.05);
    background: #334155;
}

button {
    margin-top: 10px;
    padding: 10px 15px;
    border: none;
    border-radius: 10px;
    background: #38bdf8;
    color: black;
    font-weight: bold;
}
</style>
</head>
<body>

<header>
📘 Hinglish Data Analytics Library
</header>

<div class="container">

<div class="card">
<h2>Excel</h2>
<button onclick="window.open('books/excel.pdf')">Open</button>
</div>

<div class="card">
<h2>Python</h2>
<button onclick="window.open('books/python.pdf')">Open</button>
</div>

<div class="card">
<h2>Power BI</h2>
<button onclick="window.open('books/powerbi.pdf')">Open</button>
</div>

<div class="card">
<h2>SQL</h2>
<button onclick="window.open('books/sql.pdf')">Open</button>
</div>

<div class="card">
<h2>AI Basics</h2>
<button onclick="window.open('books/ai.pdf')">Open</button>
</div>

<div class="card">
<h2>Data Visualization</h2>
<button onclick="window.open('books/dataviz.pdf')">Open</button>
</div>

</div>

<script>
if ('serviceWorker' in navigator) {
  navigator.serviceWorker.register('service-worker.js');
}
</script>

</body>
</html>