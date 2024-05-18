<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Casa de Campo en Ibagué</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 2rem;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .gallery img {
            width: 100%;
            max-width: 300px;
            margin: 10px;
        }
        .form-group {
            margin-bottom: 1rem;
        }
        .form-group label {
            display: block;
            margin-bottom: .5rem;
        }
        .form-group input, .form-group textarea {
            width: 100%;
            padding: .5rem;
            box-sizing: border-box;
        }
        .form-group button {
            padding: 1rem;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }
        .form-group button:hover {
            background-color: #45a049;
        }
        .whatsapp-button {
            display: block;
            width: 100%;
            max-width: 300px;
            margin: 1rem auto;
            text-align: center;
            text-decoration: none;
            padding: 1rem;
            background-color: #25D366;
            color: white;
            font-size: 1.2rem;
            border-radius: 5px;
        }
        .whatsapp-button:hover {
            background-color: #1ebc54;
        }
    </style>
</head>
<body>
    <header>
        <h1>Casa de Campo en Ibagué</h1>
        <p>Disfruta de una estancia tranquila y relajante</p>
    </header>
    <nav>
        <a href="#descripcion">Descripción</a>
        <a href="#galeria">Galería</a>
        <a href="#tarifas">Tarifas</a>
        <a href="#contacto">Contacto</a>
        <a href="#reserva">Reserva</a>
    </nav>
    <div class="container">
        <section id="descripcion">
            <h2>Descripción</h2>
            <p>Nuestra casa de campo ofrece 3 habitaciones, sala, comedor, 2 baños, piscina y amplias zonas verdes, ideal para familias y mascotas. 🌳🏡 Disfruta de la tranquilidad y privacidad durante las fiestas de Ibagué.</p>
        </section>
        <section id="galeria">
            <h2>Galería</h2>
            <div class="gallery">
                <img src="imagen1.jpg" alt="Casa de campo">
                <img src="imagen2.jpg" alt="Piscina">
                <img src="imagen3.jpg" alt="Jardín">
                <img src="imagen4.jpg" alt="Sala">
                <img src="imagen5.jpg" alt="Comedor">
                <img src="imagen6.jpg" alt="Habitación">
            </div>
        </section>
        <section id="tarifas">
            <h2>Tarifas</h2>
            <p>El valor para una familia es de $350.000 por noche. Si desean un pasa día o reservar varios días, los precios pueden variar.</p>
        </section>
        <section id="contacto">
            <h2>Contacto</h2>
            <p>Para obtener descuentos exclusivos y más información, contáctanos al <strong>32167514622</strong>. Estamos atentos por WhatsApp para ayudarte con cualquier consulta.</p>
            <a href="https://wa.me/5732167514622" class="whatsapp-button">Contáctanos por WhatsApp</a>
        </section>
        <section id="reserva">
            <h2>Reserva</h2>
            <form>
                <div class="form-group">
                    <label for="nombre">Nombre</label>
                    <input type="text" id="nombre" name="nombre" required>
                </div>
                <div class="form-group">
                    <label for="email">Correo Electrónico</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="telefono">Teléfono</label>
                    <input type="tel" id="telefono" name="telefono" required>
                </div>
                <div class="form-group">
                    <label for="mensaje">Mensaje</label>
                    <textarea id="mensaje" name="mensaje" rows="4" required></textarea>
                </div>
                <div class="form-group">
                    <button type="submit">Enviar</button>
                </div>
            </form>
        </section>
    </div>
</body>
</html>
