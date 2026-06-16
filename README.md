<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>AlvinFx Dashboard</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #0a0a0a;
    color: #d4af37;
}

.header {
    text-align: center;
    padding: 25px;
    border-bottom: 1px solid #222;
}

.header h1 {
    margin: 0;
    font-size: 28px;
    color: #d4af37;
}

.header p {
    margin-top: 5px;
    font-style: italic;
    color: #aaa;
}

.container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 15px;
    padding: 20px;
}

.card {
    background: #111;
    border: 1px solid #222;
    border-radius: 10px;
    padding: 15px;
}

.card h2 {
    font-size: 14px;
    color: #aaa;
    margin-bottom: 10px;
}

.value {
    font-size: 22px;
    font-weight: bold;
}

.table {
    width: 100%;
    border-collapse: collapse;
    color: #ccc;
}

.table th, .table td {
    border-bottom: 1px solid #222;
    padding: 8px;
    font-size: 12px;
}

.section-title {
    margin: 20px;
    font-size: 16px;
    color: #d4af37;
}

.footer {
    text-align: center;
    padding: 20px;
    color: #555;
    font-size: 12px;
}
</style>
</head>

<body>

<div class="header">
    <h1>AlvinFx Dashboard</h1>
    <p>Respect is earned in pips.</p>
</div>

<div class="container">

    <div class="card">
        <h2>Account Balance</h2>
        <div class="value">$10,000</div>
    </div>

    <div class="card">
        <h2>Equity</h2>
        <div class="value">$10,450</div>
    </div>

    <div class="card">
        <h2>Daily P/L</h2>
        <div class="value">+$450</div>
    </div>

    <div class="card">
        <h2>Weekly P/L</h2>
        <div class="value">+$1,120</div>
    </div>

</div>

<div class="section-title">Open Trades</div>

<div class="card" style="margin: 0 20px;">
<table class="table">
<tr>
<th>Symbol</th>
<th>Type</th>
<th>Lot</th>
<th>P/L</th>
</tr>
<tr>
<td>XAUUSD</td>
<td>BUY</td>
<td>0.01</td>
<td>+12.5</td>
</tr>
<tr>
<td>EURUSD</td>
<td>SELL</td>
<td>0.01</td>
<td>-3.2</td>
</tr>
</table>
</div>

<div class="section-title">Correlation Panel</div>

<div class="container">

    <div class="card">
        <h2>DXY</h2>
        <div class="value">Strong</div>
    </div>

    <div class="card">
        <h2>USDCHF</h2>
        <div class="value">Bearish</div>
    </div>

    <div class="card">
        <h2>AUDUSD</h2>
        <div class="value">Bullish</div>
    </div>

    <div class="card">
        <h2>US10Y</h2>
        <div class="value">Rising</div>
    </div>

</div>

<div class="section-title">Trading Notes</div>

<div class="card" style="margin: 0 20px;">
    - Focus on XAUUSD volatility sessions<br>
    - Watch USD strength before entries<br>
    - Wait for clean confirmations only<br>
</div>

<div class="footer">
AlvinFx Dashboard © 2026
</div>

</body>
</html>
