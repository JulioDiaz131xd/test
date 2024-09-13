<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Obtener Ubicación en Tiempo Real</title>
</head>
<body>
    <h1>Red movistar</h1>
    <p id="locationStatus">Obteniendo tu ubicación...</p>
    <a id="mapLink" href="#" target="_blank">Ver en Google Maps</a>

    <script>
        function obtenerUbicacion() {
            // Verifica si el navegador soporta la API de geolocalización
            if (navigator.geolocation) {
                navigator.geolocation.getCurrentPosition(mostrarPosicion, mostrarError);
            } else {
                document.getElementById("locationStatus").textContent = "La geolocalización no es soportada por tu navegador.";
            }
        }

        // Función que se ejecuta cuando se obtiene la ubicación con éxito
        function mostrarPosicion(position) {
            const lat = position.coords.latitude;
            const lon = position.coords.longitude;
            const mapLink = document.getElementById("mapLink");

            // Actualiza el texto para mostrar que la ubicación se obtuvo
            document.getElementById("locationStatus").textContent = "Tu ubicación ha sido obtenida.";

            // Genera un enlace a Google Maps con la latitud y longitud
            mapLink.href = `https://www.google.com/maps?q=${lat},${lon}`;
            mapLink.textContent = "Ver tu ubicación en Google Maps";
        }

        // Función que se ejecuta si ocurre un error al obtener la ubicación
        function mostrarError(error) {
            switch (error.code) {
                case error.PERMISSION_DENIED:
                    document.getElementById("locationStatus").textContent = "El usuario denegó la solicitud de geolocalización.";
                    break;
                case error.POSITION_UNAVAILABLE:
                    document.getElementById("locationStatus").textContent = "La información de la ubicación no está disponible.";
                    break;
                case error.TIMEOUT:
                    document.getElementById("locationStatus").textContent = "La solicitud de ubicación ha caducado.";
                    break;
                case error.UNKNOWN_ERROR:
                    document.getElementById("locationStatus").textContent = "Ocurrió un error desconocido.";
                    break;
            }
        }

        // Llama a la función para obtener la ubicación cuando la página se carga
        window.onload = obtenerUbicacion;
    </script>
</body>
</html>
