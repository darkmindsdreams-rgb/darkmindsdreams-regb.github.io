<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Funkos y Diseños Fallas</title>
  <style>
    body { font-family: Arial, sans-serif; text-align: center; background: #f9f9f9; }
    .producto { border: 1px solid #ddd; border-radius: 10px; padding: 15px; margin: 20px auto; width: 300px; background: #fff; }
    img { max-width: 100%; border-radius: 10px; }
    .boton { background: #0070ba; color: white; padding: 10px 20px; border-radius: 8px; text-decoration: none; }
    .boton:hover { background: #005c99; }
  </style>
</head>
<body>
  <h1>🎨 Tienda de Funkos y Diseños Fallas</h1>

  <!-- Producto Funko -->
  <div class="producto">
    <h2>Funko Personalizado</h2>
    <img src="funko.jpg" alt="Funko personalizado">
    <p>Crea tu propio Funko único, diseñado a medida.</p>
    <a class="boton" href="https://forms.gle/TU_FORMULARIO" target="_blank">Personalizar Funko</a>
    <br><br>
    <!-- Botón PayPal -->
    <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
      <input type="hidden" name="cmd" value="_xclick">
      <input type="hidden" name="business" value="TU_CORREO_PAYPAL">
      <input type="hidden" name="item_name" value="Funko Personalizado">
      <input type="hidden" name="amount" value="39.99">
      <input type="hidden" name="currency_code" value="EUR">
      <input type="submit" value="Comprar con PayPal" class="boton">
    </form>
  </div>

  <!-- Servicio Fallas -->
  <div class="producto">
    <h2>Diseño de Falla</h2>
    <img src="falla.jpg" alt="Diseño de falla">
    <p>Contrata un diseño artístico fallero único y creativo.</p>
    <a class="boton" href="https://forms.gle/TU_FORMULARIO_FALLA" target="_blank">Solicitar Presupuesto</a>
  </div>
</body>
</html>
