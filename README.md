<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Valle Encantado - Hotel en Valle de Bravo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5dc; /* Beige */
            color: #800000; /* Vino */
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #800000; /* Vino */
            padding: 20px;
            text-align: center;
            color: #ffd700; /* Dorado */
            font-size: 2.5em;
            font-family: 'Georgia', serif;
            position: relative;
        }
        section {
            padding: 20px;
        }
        h2 {
            color: #800000; /* Vino */
            font-weight: bold;
        }
        img {
            max-width: 300px; /* Reducir tamaño de las imágenes */
            height: auto;
            margin: 10px 0;
        }
        .mision-vision-valores img {
            display: block;
            margin: 20px auto;
        }
        .itinerario img {
            float: right;
            max-width: 45%; /* Más pequeño */
            height: auto;
            margin: 0 0 10px 20px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #800000; /* Vino */
            color: #ffd700; /* Dorado */
        }
    </style>
</head>
<body>
    <header>
        Valle Encantado
    </header>

    <section class="mision-vision-valores">
        <h2>Misión, Visión y Valores</h2>
        <p><strong>Misión:</strong> Ofrecer una experiencia única y relajante en un entorno natural, combinando confort y lujo con un servicio de calidad.</p>
        <p><strong>Visión:</strong> Ser el hotel líder en ecoturismo en la región, reconocido por nuestro compromiso con el medio ambiente y la satisfacción del cliente.</p>
        <p><strong>Valores:</strong> Sostenibilidad, hospitalidad, integridad y excelencia en el servicio.</p>
        <img src="images/cabañas.jpg" alt="Imagen de cabañas">
    </section>

    <section class="itinerario">
        <h2>Itinerario de Actividades</h2>

        <h3>Mañana</h3>
        <ul>
            <li>8:00 am - 9:00 am: Desayuno buffet en el restaurante "La Cabaña"</li>
            <li>9:00 am - 10:00 am: Actividad de yoga en el jardín "El Olivo"</li>
            <li>10:00 am - 12:00 pm: Paseo por la viña y degustación de vinos en la bodega "La Bodega del Vino"</li>
        </ul>
        <img src="images/buffet.jpg" alt="Desayuno buffet">

        <h3>Tarde</h3>
        <ul>
            <li>2:00 pm - 4:00 pm: Actividad de pintura en el estudio "El Artista" (opcional)</li>
            <li>4:00 pm - 6:00 pm: Merienda en el salón "La Chimenea" con música en vivo</li>
            <li>6:00 pm - 8:00 pm: Cena en el restaurante "La Cabaña" con menú especial de la casa</li>
        </ul>
        <img src="images/rzr.jpg" alt="Paseo en RZR">

        <h3>Noche</h3>
        <ul>
            <li>8:00 pm - 10:00 pm: Actividad de observación de estrellas en el telescopio "El Observatorio"</li>
            <li>10:00 pm - 12:00 am: Música en vivo en el salón "La Chimenea"</li>
        </ul>

        <h3>Actividades adicionales</h3>
        <ul>
            <li>Paseos a caballo por la viña (opcional)</li>
            <li>Clases de cocina con el chef del hotel (opcional)</li>
            <li>Masajes y tratamientos de spa en el centro de bienestar "El Retiro" (opcional)</li>
            <li>Paseo en RZR (opcional)</li>
        </ul>
        <img src="images/caballo.jpg" alt="Paseos a caballo">

        <h3>Notas</h3>
        <ul>
            <li>Todas las actividades están sujetas a cambios y cancelaciones sin previo aviso.</li>
            <li>Se recomienda reservar con anticipación para las actividades opcionales.</li>
            <li>El hotel no se responsabiliza por lesiones o daños causados durante las actividades.</li>
        </ul>
    </section>

    <section class="reservaciones">
        <h2>Reservaciones</h2>
        <form action="#" method="post">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>

            <label for="email">Correo Electrónico:</label>
            <input type="email" id="email" name="email" required>

            <label for="telefono">Teléfono:</label>
            <input type="tel" id="telefono" name="telefono" required>

            <label for="fecha">Fecha de Llegada:</label>
            <input type="date" id="fecha" name="fecha" required>

            <label for="habitaciones">Número de Habitaciones:</label>
            <select id="habitaciones" name="habitaciones" required>
                <option value="1">1</option>
                <option value="2">2</option>
                <option value="3">3</option>
                <option value="4">4</option>
                <option value="5">5</option>
                <option value="6">6</option>
                <option value="7">7</option>
                <option value="8">8</option>
                <option value="9">9</option>
                <option value="10">10</option>
                <option value="11">11</option>
                <option value="12">12</option>
            </select>

            <button type="submit">Hacer Reserva</button>
        </form>
    </section>

    <footer>
        &copy; 2024 Valle Encantado. Todos los derechos reservados. <br>
        C. del Tambor 523, La Peña, 51200 Valle de Bravo, Méx.
    </footer>
</body>
</html>
