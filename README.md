<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>EDA Project - Dev Chauhan</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(135deg, #0f172a, #020617);
    color: #e2e8f0;
}

/* HEADER */
header {
    text-align: center;
    padding: 60px 20px;
    background: linear-gradient(90deg, #1e293b, #020617);
}

header h1 {
    font-size: 2.5rem;
    color: #38bdf8;
}

header p {
    margin-top: 10px;
    color: #94a3b8;
}

/* SECTION */
section {
    max-width: 1000px;
    margin: auto;
    padding: 30px 20px;
}

/* CARD */
.card {
    background: rgba(30, 41, 59, 0.6);
    backdrop-filter: blur(10px);
    padding: 25px;
    margin: 20px 0;
    border-radius: 15px;
    border: 1px solid rgba(255,255,255,0.1);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 25px rgba(0,0,0,0.6);
}

/* HEADINGS */
h2 {
    color: #22c55e;
    margin-bottom: 10px;
}

/* LIST */
ul {
    line-height: 1.8;
    color: #cbd5f5;
}

/* LINKS */
a {
    color: #38bdf8;
    text-decoration: none;
    font-weight: bold;
}

a:hover {
    color: #22c55e;
}

/* BUTTON STYLE */
.btn {
    display: inline-block;
    padding: 10px 20px;
    margin-top: 10px;
    background: #38bdf8;
    color: #020617;
    border-radius: 8px;
    transition: 0.3s;
}

.btn:hover {
    background: #22c55e;
    color: white;
}

/* FOOTER */
footer {
    text-align: center;
    padding: 25px;
    background: #020617;
    color: #64748b;
    margin-top: 30px;
}
</style>
</head>

<body>

<header>
    <h1>📊 Exploratory Data Analysis Project</h1>
    <p>By Dev Chauhan 🚀</p>
</header>

<section>

<div class="card">
    <h2>🚀 Overview</h2>
    <p>
        This project performs Exploratory Data Analysis (EDA) on a sales dataset
        to uncover insights, identify trends, and support data-driven decisions.
    </p>
</div>

<div class="card">
    <h2>📂 Dataset</h2>
    <ul>
        <li><b>fact_sales</b> → Transaction data</li>
        <li><b>dim_customers</b> → Customer details</li>
        <li><b>dim_products</b> → Product details</li>
    </ul>
</div>

<div class="card">
    <h2>🎯 Objectives</h2>
    <ul>
        <li>Analyze sales performance</li>
        <li>Understand customer behavior</li>
        <li>Identify top & low-performing products</li>
        <li>Study country-wise trends</li>
    </ul>
</div>

<div class="card">
    <h2>📊 Key Insights</h2>
    <ul>
        <li>🚀 High revenue products identified</li>
        <li>⚠️ Underperforming products detected</li>
        <li>🌍 Regional trends analyzed</li>
        <li>👥 Customer contribution evaluated</li>
    </ul>
</div>

<div class="card">
    <h2>🛠️ Tools Used</h2>
    <ul>
        <li>SQL (SQL Server / Hive)</li>
        <li>Data Analysis Techniques</li>
        <li>Git & GitHub</li>
    </ul>
</div>

<div class="card">
    <h2>💡 Business Impact</h2>
    <ul>
        <li>📈 Improved decision-making</li>
        <li>🎯 Better customer targeting</li>
        <li>💰 Increased profitability</li>
    </ul>
</div>

<div class="card">
    <h2>🔗 Links</h2>
    <a class="btn" href="https://github.com/DEVCHAUHAN2004" target="_blank">💻 GitHub</a>
    <a class="btn" href="https://www.linkedin.com/in/dev-chauhan-422420329/" target="_blank">🔗 LinkedIn</a>
</div>

</section>

<footer>
    <p>© 2026 Dev Chauhan | Data Analyst Portfolio</p>
</footer>

</body>
</html>
