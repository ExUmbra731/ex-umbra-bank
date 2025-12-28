<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Ex Umbra Trading Terminal</title>
    <link rel="stylesheet" href="trading.css">
</head>
<body>
    <div class="app-container">
        <!-- Sidebar: Liste d'actifs -->
        <aside class="market-list">
            <h3>Marchés</h3>
            <div class="asset"><span>BTC/USDT</span> <span class="up">+2.4%</span></div>
            <div class="asset"><span>ETH/USDT</span> <span class="down">-1.1%</span></div>
            <div class="asset"><span>SOL/USDT</span> <span class="up">+5.8%</span></div>
        </aside>

        <!-- Main: Graphique -->
        <main class="chart-area">
            <div class="chart-header">
                <h2>BTC / Tether US</h2>
                <span class="price">42 150.20 $</span>
            </div>
            <div id="tradingview_widget">
                <!-- Emplacement pour un widget type TradingView -->
                <div class="fake-chart"></div> 
            </div>
        </main>

        <!-- Right: Panneau d'achat/vente -->
        <section class="order-panel">
            <h3>Passer un Ordre</h3>
            <div class="tabs"><button class="active">Achat</button><button>Vente</button></div>
            <input type="number" placeholder="Quantité">
            <button class="buy-btn">Acheter BTC</button>
            <div class="wallet-info">Disponible: <span>10 450 USDT</span></div>
        </section>
    </div>
</body>
</html>
