<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grind & Roll | Catálogo Oficial & Dropshipping</title>
    <style>
        :root {
            --bg-color: #121212;
            --card-bg: #1E1E1E;
            --accent-color: #10B981; /* Verde neón / esmeralda */
            --text-color: #F3F4F6;
            --text-muted: #9CA3AF;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
        }

        /* Header */
        header {
            background-color: #000;
            padding: 20px;
            text-align: center;
            border-bottom: 2px solid var(--accent-color);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        header h1 {
            font-size: 2rem;
            letter-spacing: 2px;
            color: var(--accent-color);
            text-transform: uppercase;
        }

        header p {
            font-size: 0.9rem;
            color: var(--text-muted);
        }

        /* Banner Hero */
        .hero {
            text-align: center;
            padding: 40px 20px;
            background: linear-gradient(180deg, #181818 0%, var(--bg-color) 100%);
        }

        .hero h2 {
            font-size: 1.8rem;
            margin-bottom: 10px;
        }

        .hero p {
            color: var(--text-muted);
            max-width: 600px;
            margin: 0 auto 20px;
        }

        /* Catálogo Grid */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .card {
            background-color: var(--card-bg);
            border-radius: 12px;
            overflow: hidden;
            border: 1px solid #2A2A2A;
            transition: transform 0.2s, border-color 0.2s;
            display: flex;
            flex-direction: column;
        }

        .card:hover {
            transform: translateY(-5px);
            border-color: var(--accent-color);
        }

        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            background-color: #2b2b2b;
        }

        .card-body {
            padding: 15px;
            display: flex;
            flex-direction: column;
            flex-grow: 1;
        }

        .card-title {
            font-size: 1.1rem;
            font-weight: bold;
            margin-bottom: 8px;
        }

        .card-desc {
            font-size: 0.85rem;
            color: var(--text-muted);
            margin-bottom: 15px;
            flex-grow: 1;
        }

        .card-price {
            font-size: 1.2rem;
            font-weight: bold;
            color: var(--accent-color);
            margin-bottom: 12px;
        }

        .btn-buy {
            background-color: var(--accent-color);
            color: #000;
            text-align: center;
            padding: 10px;
            border-radius: 6px;
            text-decoration: none;
            font-weight: bold;
            transition: background 0.2s;
        }

        .btn-buy:hover {
            background-color: #059669;
        }

        /* Banner Dropshipping */
        .info-section {
            background-color: #181818;
            margin: 40px 0;
            padding: 30px 20px;
            border-radius: 12px;
            text-align: center;
            border: 1px dashed var(--accent-color);
        }

        .info-section h3 {
            color: var(--accent-color);
            margin-bottom: 10px;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            background-color: #000;
            color: var(--text-muted);
            font-size: 0.85rem;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <header>
        <h1>GRIND & ROLL</h1>
        <p>Premium Smoke & Roll Supplies</p>
    </header>

    <section class="hero">
        <h2>Catálogo de Productos & Insumos</h2>
        <p>Envíos directos a tu puerta. Calidad, discreción y la mejor selección al por mayor y detal.</p>
    </section>

    <div class="container">

        <!-- Sección Informativa Dropshipping -->
        <div class="info-section">
            <h3>🚚 Servicio de Dropshipping Disponible</h3>
            <p>¿Tienes tu propia tienda o vendes por redes? Nosotros despachamos los pedidos directamente a tus clientes finales sin marcas ni facturas visibles.</p>
        </div>

        <!-- Grid de Productos -->
        <div class="grid">

            <!-- Producto 1 -->
            <div class="card">
                <img src="https://via.placeholder.com/300x200/1e1e1e/10B981?text=Bolsas+Ziplock+Anti-Olor" alt="Bolsas Ziplock">
                <div class="card-body">
                    <div class="card-title">Bolsas Ziplock Anti-Olor 100u</div>
                    <div class="card-desc">Bolsas herméticas de alta densidad metalizadas. Cierre hermético anti-olor y humedad.</div>
                    <div class="card-price">$45.000 COP</div>
                    <a href="https://wa.me/TU_NUMERO?text=Hola,%20quiero%20pedir%20las%20Bolsas%20Ziplock%20Anti-Olor" class="btn-buy" target="_blank">Pedir por WhatsApp</a>
                </div>
            </div>

            <!-- Producto 2 -->
            <div class="card">
                <img src="https://via.placeholder.com/300x200/1e1e1e/10B981?text=Grinder+Metalico+4P" alt="Grinder">
                <div class="card-body">
                    <div class="card-title">Grinder Metálico 4 Piezas</div>
                    <div class="card-desc">Picador de aleación de zinc de 50mm con tamiz y pala recolectora. Dientes tipo diamante.</div>
                    <div class="card-price">$38.000 COP</div>
                    <a href="https://wa.me/TU_NUMERO?text=Hola,%20quiero%20pedir%20el%20Grinder%20Metalico" class="btn-buy" target="_blank">Pedir por WhatsApp</a>
                </div>
            </div>

            <!-- Producto 3 -->
            <div class="card">
                <img src="https://via.placeholder.com/300x200/1e1e1e/10B981?text=Papelillos+King+Size" alt="Papelillos">
                <div class="card-body">
                    <div class="card-title">Caja Papelillos King Size + Tips</div>
                    <div class="card-desc">Papel sin blanquear ultra fino de combustión lenta. Incluye filtros de cartón.</div>
                    <div class="card-price">$65.000 COP</div>
                    <a href="https://wa.me/TU_NUMERO?text=Hola,%20quiero%20pedir%20la%20Caja%20de%20Papelillos" class="btn-buy" target="_blank">Pedir por WhatsApp</a>
                </div>
            </div>

            <!-- Producto 4 -->
            <div class="card">
                <img src="https://via.placeholder.com/300x200/1e1e1e/10B981?text=Bandeja+de+Enrolado" alt="Bandeja">
                <div class="card-body">
                    <div class="card-title">Bandeja de Enrolado M (28x18cm)</div>
                    <div class="card-desc">Bandeja metálica con bordes curvos antifugas y diseño exclusivo Grind & Roll.</div>
                    <div class="card-price">$28.000 COP</div>
                    <a href="https://wa.me/TU_NUMERO?text=Hola,%20quiero%20pedir%20la%20Bandeja%20de%20Enrolado" class="btn-buy" target="_blank">Pedir por WhatsApp</a>
                </div>
            </div>

        </div>
    </div>

    <footer>
        <p>&copy; 2026 Grind & Roll Store. Todos los derechos reservados.</p>
        <p>Contacto / Dropshipping: +57 300 000 0000 | @grindandroll.store</p>
    </footer>

</body>
</html>
