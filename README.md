# tienda2
2da 
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tienda de Ropa</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #d1e6f9;
    }

    header {
      background-color: #3a3aff;
      color: white;
      text-align: center;
      padding: 10px;
      font-size: 14px;
      font-weight: bold;
    }

    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .product {
      background: url('https://i.imgur.com/4AIwUZM.jpg') no-repeat center;
      background-size: cover;
      padding: 10px;
      display: flex;
      flex-direction: column;
      align-items: center;
      border: 1px solid #eee;
    }

    .product img {
      width: 100%;
      height: auto;
      object-fit: cover;
      max-height: 300px;
    }

    .product-name {
      margin-top: 10px;
      font-weight: bold;
    }

    .product-price {
      font-size: 14px;
      color: #333;
    }
  </style>
</head>
<body>

  <header>
    ENVÍO GRATIS PEDIDOS +100€ // M***SHAKES // Limited Time Items
  </header>

  <section class="product-grid">
    <div class="product">
      <img src="https://i.imgur.com/sY4QR0E.png" alt="Soccer Jeans" />
      <div class="product-name">SOCCER JEANS</div>
      <div class="product-price">€90,00</div>
    </div>

    <div class="product">
      <img src="https://i.imgur.com/jEZ1Fss.png" alt="Iconic Pocket Mirror" />
      <div class="product-name">ICONIC POCKET MIRROR</div>
      <div class="product-price">€10,00</div>
    </div>

    <div class="product">
      <img src="https://i.imgur.com/lphId0O.png" alt="Posh Girl Top" />
      <div class="product-name">POSH GIRL TOP</div>
      <div class="product-price">€55,00</div>
    </div>

    <!-- Agrega más productos aquí -->
  </section>

</body>
</html>

