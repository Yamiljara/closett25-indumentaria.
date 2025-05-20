<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Closett 25 - Tu Tienda de Indumentaria</title>
    <meta name="description" content="Closett 25 es tu tienda online de ropa, donde encontrarás las últimas tendencias en moda para todos los estilos.">
    <meta name="keywords" content="ropa, moda, tienda online, indumentaria, tendencias, Closett 25, comprar ropa, ropa de mujer, ropa de hombre, accesorios">
    <link rel="canonical" href="https://www.closett25.com.ar/">
    <meta property="og:title" content="Closett 25 - Tu Tienda de Indumentaria">
    <meta property="og:description" content="En Closett 25 encontrarás la mejor selección de ropa para todos los estilos. ¡Descubre las últimas tendencias!">
    <meta property="og:image" content="https://i.postimg.cc/Gt8X5Wdk/CLOSETT-25.png">
    <meta property="og:url" content="https://www.closett25.com.ar/">
    <meta property="og:type" content="website">
    <meta name="robots" content="index, follow">
    <link rel="icon" href="/favicon.ico" type="image/x-icon">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        header {
            background-image: url('https://i.postimg.cc/Gt8X5Wdk/CLOSETT-25.png'); /* URL del logo como fondo */
            background-repeat: no-repeat;
            background-position: center top; /* Centrado horizontalmente, pegado al top */
            background-size: contain; /* Ajustar para que el logo se vea completo */
            min-height: 150px; /* Altura mínima para asegurar que se vea el logo */
            display: flex; /* Para alinear el contenido del header verticalmente */
            align-items: center; /* Centrar verticalmente el contenido */
            padding-top: 20px; /* Espacio superior para el logo */
            padding-bottom: 20px; /* Espacio inferior */
        }
        header .container {
            background-color: rgba(255, 255, 255, 0.8); /* Fondo semitransparente para el contenido */
            border-radius: 8px;
        }

        /* Estilos para el menú móvil */
        #menu-mobile {
            display: none; /* Ocultar por defecto */
            position: fixed; /* Posicionamiento fijo para que se superponga al contenido */
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.9); /* Fondo oscuro semitransparente */
            z-index: 30; /* Asegurar que esté por encima de otros elementos */
        }

        #menu-mobile .menu-content {
            background-color: white;
            width: 80%; /* Ancho del menú */
            max-width: 320px; /* Ancho máximo */
            height: 100%;
            position: absolute; /* Posicionamiento absoluto dentro del contenedor #menu-mobile */
            right: 0; /* Pegar al lado derecho */
            padding: 20px;
            overflow-y: auto; /* Permitir scroll si el contenido es muy largo */
        }

        #menu-mobile .menu-header {
            display: flex;
            justify-content: flex-end; /* Alinear el botón de cierre a la derecha */
            margin-bottom: 20px;
        }

        #menu-mobile .menu-list {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        #menu-mobile .menu-list li {
            margin-bottom: 15px;
        }

        #menu-mobile .menu-list a {
            display: block;
            font-size: 1.2rem;
            color: #333;
            text-decoration: none;
            padding: 10px;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        #menu-mobile .menu-list a:hover {
            background-color: #f0f0f0;
        }

        /* Ajustes para pantallas pequeñas */
        @media (max-width: 768px) {
            header .container {
                flex-direction: column; /* Cambiar a columna en pantallas pequeñas */
                align-items: flex-start; /* Alinear al inicio */
            }
            header nav {
                display: none; /* Ocultar el menú de navegación en pantallas pequeñas */
            }
            #menu-toggle {
                display: block; /* Mostrar el botón de menú en pantallas pequeñas */
            }
            .section-title {
                font-size: 1.8rem; /* Reducir el tamaño del título en pantallas pequeñas */
            }
            .product-card {
                margin-bottom: 20px; /* Añadir margen inferior entre las tarjetas de producto en pantallas pequeñas */
            }
            .collection-card {
                margin-bottom: 20px; /* Añadir margen inferior entre las tarjetas de colección en pantallas pequeñas */
            }
            .grid-cols-1 {
                grid-template-columns: 1fr; /* Forzar una sola columna en pantallas muy pequeñas */
            }
            .md\:grid-cols-2 {
                grid-template-columns: 1fr; /* Forzar una sola columna en pantallas pequeñas */
            }
            .lg\:grid-cols-3 {
                grid-template-columns: 1fr; /* Forzar una sola columna en pantallas pequeñas */
            }
            .xl\:grid-cols-4{
                grid-template-columns: 1fr; /* Forzar una sola columna en pantallas pequeñas */
            }
            .footer-content {
                grid-template-columns: 1fr; /* Cambiar a una sola columna en el pie de página para móviles */
                text-align: center;
            }
            .footer-section {
                margin-bottom: 20px; /* Añadir margen entre las secciones del pie de página en móviles */
            }
        }
    </style>
</head>
<body class="bg-gray-100">
    <header class="bg-white shadow-md sticky top-0 z-10">
        <div class="container mx-auto px-4 py-2 flex justify-between items-center">
            <a href="/" class="flex items-center text-xl font-semibold text-gray-800">
                <img src="https://i.postimg.cc/Gt8X5Wdk/CLOSETT-25.png" alt="Closett 25 Logo" class="mr-2 h-8">
                Closett 25
            </a>
            <nav class="hidden md:block">
                <ul class="flex space-x-6">
                    <li><a href="/" class="hover:text-blue-600 transition duration-300">Inicio</a></li>
                    <li><a href="/productos.html" class="hover:text-blue-600 transition duration-300">Productos</a></li>
                    <li><a href="/colecciones.html" class="hover:text-blue-600 transition duration-300">Colecciones</a></li>
                    <li><a href="/nosotros.html" class="hover:text-blue-600 transition duration-300">Nosotros</a></li>
                    <li><a href="/contacto.html" class="hover:text-blue-600 transition duration-300">Contacto</a></li>
                </ul>
            </nav>
            <div class="flex items-center space-x-4">
                <a href="/carrito.html" class="hover:text-blue-600 transition duration-300">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-shopping-cart"><path d="M6 2L3 6v14a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2V6l-3-4z"></path><path d="M3 6h18"></path><path d="M16 10a4 4 0 0 1-8 0"></path></svg>
                </a>
                <a href="/cuenta.html" class="hover:text-blue-600 transition duration-300">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-user"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
                </a>
                <button id="menu-toggle" class="md:hidden text-gray-700 hover:text-blue-600 transition duration-300">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-menu"><line x1="4" x2="20" y1="12" y2="12"></line><line x1="4" x2="20" y1="6" y2="6"></line><line x1="4" x2="20" y1="18" y2="18"></line></svg>
                </button>
            </div>
        </div>
    </header>

    <div id="menu-mobile" class="hidden">
        <div class="menu-content">
            <div class="menu-header">
                <button id="menu-close" class="text-gray-700 hover:text-blue-600 transition duration-300">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-x"><line x1="18" x2="6" y1="6" y2="18"></line><line x1="6" x2="18" y1="6" y2="18"></line></svg>
                </button>
            </div>
            <nav class="menu-list">
                <ul>
                    <li><a href="/">Inicio</a></li>
                    <li><a href="/productos.html">Productos</a></li>
                    <li><a href="/colecciones.html">Colecciones</a></li>
                    <li><a href="/nosotros.html">Nosotros</a></li>
                    <li><a href="/contacto.html">Contacto</a></li>
                    <li><a href="/carrito.html">Carrito</a></li>
                    <li><a href="/cuenta.html">Mi Cuenta</a></li>
                </ul>
            </nav>
        </div>
    </div>

    <section class="bg-gradient-to-r from-blue-100 to-purple-100 text-gray-800 py-16 md:py-24">
        <div class="container mx-auto px-4 text-center">
            <h1 class="text-3xl md:text-5xl font-semibold mb-4">Las últimas tendencias en un solo lugar</h1>
            <p class="text-lg md:text-xl mb-8">
                Descubre tu estilo único con Closett 25.
                <span class="block text-blue-700 font-bold text-xl mt-2">"Viste tu esencia, define tu estilo."</span>
            </p>
            <a href="/productos.html" class="bg-blue-600 hover:bg-blue-700 text-white font-semibold py-3 px-6 rounded-full transition duration-300">Ver Productos</a>
        </div>
    </section>

    <section class="py-16">
        <div class="container mx-auto px-4">
            <h2 class="text-2xl font-semibold text-gray-800 text-center mb-8 section-title">Productos Destacados</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6">
                <div class="bg-white rounded-lg shadow-md overflow-hidden product-card">
                    <img src="https://i.postimg.cc/rwMx3B95/Imagen-de-Whats-App-2025-05-20-a-las-00-11-29-bc5382c4.jpg" alt="Vestido Elegante" class="w-full h-64 object-cover">
                    <div class="p-4">
                        <h3 class="text-lg font-semibold text-gray-800">Vestido Elegante</h3>
                        <p class="text-gray-600 mb-2">Perfecto para ocasiones especiales.</p>
                        <p class="text-xl font-bold text-blue-600">$99.99</p>
                        <a href="/producto1.html" class="mt-4 block bg-blue-600 hover:bg-blue-700 text-white font-semibold py-2 px-4 rounded-full text-center transition duration-300">Ver Detalles</a>
                    </div>
                </div>
                <div class="bg-white rounded-lg shadow-md overflow-hidden product-card">
                    <img src="https://cdn.pixabay.com/photo/2016/03/31/14/40/woman-1292792_1280.jpg" alt="Camisa de Hombre" class="w-full h-64 object-cover">
                    <div class="p-4">
                        <h3 class="text-lg font-semibold text-gray-800">Camisa Casual</h3>
                        <p class="text-gray-600 mb-2">Ideal para un look relajado.</p>
                        <p class="text-xl font-bold text-blue-600">$49.99</p>
                        <a href="/producto2.html" class="mt-4 block bg-blue-600 hover:bg-blue-700 text-white font-semibold py-2 px-4 rounded-full text-center transition duration-300">Ver Detalles</a>
                    </div>
                </div>
                <div class="bg-white rounded-lg shadow-md overflow-hidden product-card">
                    <img src="https://cdn.pixabay.com/photo/2016/11/19/16/01/audio-1840073_1280.jpg" alt="Pantalones Jeans" class="w-full h-64 object-cover">
                    <div class="p-4">
                        <h3 class="text-lg font-semibold text-gray-800">Jeans Clásicos</h3>
                        <p class="text-gray-600 mb-2">Un básico imprescindible en tu armario.</p>
                        <p class="text-xl font-bold text-blue-600">$69.99</p>
                        <a href="/producto3.html" class="mt-4 block bg-blue-600 hover:bg-blue-700 text-white font-semibold py-2 px-4 rounded-full text-center transition duration-300">Ver Detalles</a>
                    </div>
                </div>
                <div class="bg-white rounded-lg shadow-md overflow-hidden product-card">
                    <img src="https://cdn.pixabay.com/photo/2018/01/07/22/34/bag-3068441_1280.jpg" alt="Chaqueta de Cuero" class="w-full h-64 object-cover">
                    <div class="p-4">
                        <h3 class="text-lg font-semibold text-gray-800">Chaqueta de Cuero</h3>
                        <p class="text-gray-600 mb-2">Añade un toque de estilo a cualquier outfit.</p>
                        <p class="text-xl font-bold text-blue-600">$149.99</p>
                        <a href="/producto4.html" class="mt-4 block bg-blue-600 hover:bg-blue-700 text-white font-semibold py-2 px-4 rounded-full text-center transition duration-300">Ver Detalles</a>
                    </div>
                </div>
            </div>
            <div class="text-center mt-8">
                <a href="/productos.html" class="bg-gray-300 hover:bg-gray-400 text-gray-800 font-semibold py-3 px-6 rounded-full transition duration-300">Ver Todos los Productos</a>
            </div>
        </div>
    </section>

    <section class="bg-gray-100 py-16">
        <div class="container mx-auto px-4">
            <h2 class="text-2xl font-semibold text-gray-800 text-center mb-8 section-title">Nuestras Colecciones</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="bg-white rounded-lg shadow-md overflow-hidden collection-card">
                    <img src="https://cdn.pixabay.com/photo/2017/10/21/06/09/woman-2873913_1280.jpg" alt="Colección Primavera" class="w-full h-64 object-cover">
                    <div class="p-4">
                        <h3 class="text-lg font-semibold text-gray-800">Primavera 2024</h3>
                        <p class="text-gray-600 mb-2">Descubre los colores y estilos de la nueva temporada.</p>
                        <a href="/coleccion1.html" class="mt-4 block bg-purple-600 hover:bg-purple-700 text-white font-semibold py-2 px-4 rounded-full text-center transition duration-300">Ver Colección</a>
                    </div>
                </div>
                <div class="bg-white rounded-lg shadow-md overflow-hidden collection-card">
                    <img src="https://cdn.pixabay.com/photo/2019/07/29/11/11/woman-4370882_1280.jpg" alt="Colección Verano" class="w-full h-64 object-cover">
                    <div class="p-4">
                        <h3 class="text-lg font-semibold text-gray-800">Verano 2024</h3>
                        <p class="text-gray-600 mb-2">Frescura y estilo para tus días de sol.</p>
                        <a href="/coleccion2.html" class="mt-4 block bg-yellow-500 hover:bg-yellow-600 text-white font-semibold py-2 px-4 rounded-full text-center transition duration-300">Ver Colección</a>
                    </div>
                </div>
                <div class="bg-white rounded-lg shadow-md overflow-hidden collection-card">
                    <img src="https://cdn.pixabay.com/photo/2016/11/19/16/01/autumn-1840072_1280.jpg" alt="Colección Otoño" class="w-full h-64 object-cover">
                    <div class="p-4">
                        <h3 class="text-lg font-semibold text-gray-800">Otoño 2023</h3>
                        <p class="text-gray-600 mb-2">Colores cálidos y texturas suaves para la temporada.</p>
                        <a href="/coleccion3.html" class="mt-4 block bg-gray-700 hover:bg-gray-800 text-white font-semibold py-2 px-4 rounded-full text-center transition duration-300">Ver Colección</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-16">
        <div class="container mx-auto px-4 grid md:grid-cols-2 gap-8 items-center">
            <div>
                <h2 class="text-2xl font-semibold text-gray-800 mb-4 section-title">Sobre Nosotros</h2>
                <p class="text-gray-700 text-lg mb-4">
                    En Closett 25, nos apasiona la moda y creemos que el estilo es una forma de expresión personal.
                    Nos dedicamos a seleccionar las mejores prendas de vestir, calzado y accesorios para que encuentres
                    todo lo que necesitas para crear tu look perfecto.
                </p>
                <p class="text-gray-700 text-lg">
                    Trabajamos con diseñadores y marcas que comparten nuestra visión de calidad, estilo y
                    sostenibilidad.  Queremos que te sientas seguro y cómodo con tu ropa, y que encuentres en
                    Closett 25 tu tienda de confianza.
                </p>
                <a href="/nosotros.html" class="mt-6 bg-green-600 hover:bg-green-700 text-white font-semibold py-3 px-6 rounded-full transition duration-300">Conoce Nuestra Historia</a>
            </div>
            <div>
                <img src="https://cdn.pixabay.com/photo/2015/02/02/16/26/woman-621174_1280.jpg" alt="Sobre Nosotros" class="rounded-lg shadow-lg w-full">
            </div>
        </div>
    </section>

    <footer class="bg-gray-800 text-white py-6">
        <div class="container mx-auto px-4 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 footer-content">
            <div class="footer-section">
                <h4 class="text-lg font-semibold mb-4">Información de Contacto</h4>
                <p class="text-gray-300">Dirección: [Tu Dirección]</p>
                <p class="text-gray-300">Email: info@closett25.com.ar</p>
                <p class="text-gray-300">Teléfono: +54 9 123 4567890</p>
            </div>
            <div class="footer-section">
                <h4 class="text-lg font-semibold mb-4">Enlaces Útiles</h4>
                <ul class="space-y-2">
                    <li><a href="/preguntas-frecuentes.html" class="hover:text-blue-300 transition duration-300">Preguntas Frecuentes</a></li>
                    <li><a href="/terminos-y-condiciones.html" class="hover:text-blue-300 transition duration-300">Términos y Condiciones</a></li>
                    <li><a href="/politica-de-privacidad.html" class="hover:text-blue-300 transition duration-300">Política de Privacidad</a></li>
                    <li><a href="/envios-y-devoluciones.html" class="hover:text-blue-300 transition duration-300">Envíos y Devoluciones</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h4 class="text-lg font-semibold mb-4">Síguenos en Redes Sociales</h4>
                <div class="flex space-x-4">
                    <a href="#" class="hover:text-blue-300 transition duration-300">
                        <svg xmlns="http://www.w3.org/2000/svg" width=
