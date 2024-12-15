<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menú Elegante de Bebidas</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <!-- Custom CSS -->
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-image: url("imagenes/marfillounge.jpg");
        }

        .navbar {
            background-color: #343a40;
        }

        .navbar-brand, .nav-link {
            color: #ffffff !important;
            font-weight: 700;
        }

        .nav-link:hover {
            color: #ffc107 !important;
        }

        .menu-section {
            padding: 60px 0;
        }

        .menu-section h2 {
            text-align: center;
            margin-bottom: 40px;
            font-size: 2.5rem;
            color: #343a40;
        }

        .menu-item {
            background-color: #ffffff;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            overflow: hidden;
            transition: transform 0.3s, box-shadow 0.3s;
            cursor: pointer;
        }

        .menu-item:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 16px rgba(0,0,0,0.2);
        }

        .menu-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .menu-item-body {
            padding: 20px;
            text-align: center;
        }

        .menu-item-body h3 {
            margin-bottom: 15px;
            color: #007bff;
        }

        .menu-item-body p {
            color: #6c757d;
        }

        /* Modal Image Styling */
        .modal-img {
            width: 100%;
            height: auto;
        }

        /* Footer Styling */
        footer {
            background-color: #343a40;
            color: #ffffff;
            padding: 20px 0;
            text-align: center;
        }
    </style>
</head>
<body>

    <!-- Barra de Navegación -->
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#"><img src="imagenes/logomarfil.png" style="width: 70%; height: 70%; margin-top: -100px; margin-bottom: -40px; margin-left: 60px;"></a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" 
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" href="#cachimbas">Cachimbas</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#refrescos">Refrescos</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#cocteles">Cócteles</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#batidos">Batidos</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#cervezas">Cervezas</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#vinos">Vinos</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#vinos">Copas</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Secciones del Menú -->
    <div class="container menu-section" id="cachimbas" style="margin-top: 230px;">
        <h2>Cachimbas</h2>
        <div class="row g-4">
            <!-- Item 1 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Cachimba+Menta" data-title="Blond Blend">
                    <img src="https://via.placeholder.com/400x300?text=Cachimba+Blond+Blend" alt="Blond Blend">
                    <div class="menu-item-body">
                        <h3>CACHIMBA BLOND BLEND</h3>
                        <p>Una combinacion de hoja virginia.</p>
                    </div>
                </div>
            </div>
            <!-- Item 2 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Cachimba+Frutas" data-title="Fusion Blend">
                    <img src="https://via.placeholder.com/400x300?text=Cachimba+Fusion+Blend" alt="Fusion Blend">
                    <div class="menu-item-body">
                        <h3>CACHIMBA FUSION BLEND</h3>
                        <p>Una combinacion de hoja virginia y burley.</p>
                    </div>
                </div>
            </div>
            <!-- Item 3 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Cachimba+Uva" data-title="Full Black">
                    <img src="https://via.placeholder.com/400x300?text=Cachimba+Full+Black" alt="Full Black">
                    <div class="menu-item-body">
                        <h3>CACHIMBA FULL BLACK</h3>
                        <p>Una combinacion de hoja burley.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Refrescos -->
    <div class="container menu-section" id="refrescos">
        <h2>Refrescos</h2>
        <div class="row g-4">
            <!-- Item 1 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Coca-Cola" data-title="Coca-Cola">
                    <img src="imagenes/cocacola.jpg" alt="Coca-Cola">
                    <div class="menu-item-body">
                        <h3>Coca-Cola</h3>
                        <p>La bebida refrescante por excelencia.</p>
                    </div>
                </div>
            </div>
            <!-- Item 2 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Coca-Cola" data-title="Coca-Cola">
                    <img src="imagenes/cocacolazero.jpg" alt="Coca-Cola">
                    <div class="menu-item-body">
                        <h3>Coca-Cola Zero</h3>
                        <p>La bebida refrescante por excelencia en su version cero.</p>
                    </div>
                </div>
            </div>
            <!-- Item 3 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Fanta+Naranja" data-title="Fanta Naranja">
                    <img src="imagenes/fantanaranja.png" alt="Fanta Naranja">
                    <div class="menu-item-body">
                        <h3>Fanta Naranja</h3>
                        <p>Fanta sabor a naranja fresca.</p>
                    </div>
                </div>
            </div>
            <!-- Item 4 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Fanta+Naranja" data-title="Fanta Limon">
                    <img src="imagenes/fantalimon.png" alt="Fanta Limon">
                    <div class="menu-item-body">
                        <h3>Fanta Limon</h3>
                        <p>Fanta sabor a naranja fresca.</p>
                    </div>
                </div>
            </div>
            <!-- Item 5 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Sprite" data-title="Sprite">
                    <img src="imagenes/Nestea.png" alt="Nestea">
                    <div class="menu-item-body">
                        <h3>Nestea</h3>
                        <p>Bebida refrescante de té.</p>
                    </div>
                </div>
            </div>
            <!-- Item 6 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Sprite" data-title="Sprite">
                    <img src="imagenes/Nesteamaracuya.png" alt="Nestea Maracuya">
                    <div class="menu-item-body">
                        <h3>Nestea Maracuya</h3>
                        <p>Bebida refrescante de té de maracuya.</p>
                    </div>
                </div>
            </div>
            <!-- Item 7 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Sprite" data-title="Sprite">
                    <img src="imagenes/sprite.png" alt="Sprite">
                    <div class="menu-item-body">
                        <h3>Sprite</h3>
                        <p>Limonada gaseosa refrescante.</p>
                    </div>
                </div>
            </div>
            <!-- Item 8 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Sprite" data-title="Sprite">
                    <img src="imagenes/Royalbliss.png" alt="Royal Bliss">
                    <div class="menu-item-body">
                        <h3>Royal Bliss</h3>
                        <p>Tonica</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Cócteles -->
    <div class="container menu-section" id="cocteles">
        <h2>Cócteles</h2>
        <div class="row g-4">
            <!-- Item 1 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Mojito" data-title="Mojito">
                    <img src="https://via.placeholder.com/400x300?text=Mojito" alt="Mojito">
                    <div class="menu-item-body">
                        <h3>Mojito</h3>
                        <p>Ron, menta y lima para una sensación refrescante.</p>
                    </div>
                </div>
            </div>
            <!-- Item 2 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Margarita" data-title="Margarita">
                    <img src="https://via.placeholder.com/400x300?text=Margarita" alt="Margarita">
                    <div class="menu-item-body">
                        <h3>Margarita</h3>
                        <p>Tequila, triple sec y lima con sal en el borde.</p>
                    </div>
                </div>
            </div>
            <!-- Item 3 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Piña+Colada" data-title="Piña Colada">
                    <img src="https://via.placeholder.com/400x300?text=Piña+Colada" alt="Piña Colada">
                    <div class="menu-item-body">
                        <h3>Piña Colada</h3>
                        <p>Piña, coco y ron para un cóctel tropical.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Batidos -->
    <div class="container menu-section" id="batidos">
        <h2>Batidos</h2>
        <div class="row g-4">
            <!-- Item 1 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Batido+Fresa" data-title="Batido de Fresa">
                    <img src="https://via.placeholder.com/400x300?text=Batido+Fresa" alt="Batido de Fresa">
                    <div class="menu-item-body">
                        <h3>Batido de Pantera Rosa</h3>
                        <p>Batido cremoso con fresas frescas.</p>
                    </div>
                </div>
            </div>
            <!-- Item 2 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Batido+Chocolate" data-title="Batido de Chocolate">
                    <img src="https://via.placeholder.com/400x300?text=Batido+Chocolate" alt="Batido de Chocolate">
                    <div class="menu-item-body">
                        <h3>Batido de Oreo</h3>
                        <p>Una delicia para los amantes del chocolate.</p>
                    </div>
                </div>
            </div>
            <!-- Item 3 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Batido+Vainilla" data-title="Batido de Vainilla">
                    <img src="https://via.placeholder.com/400x300?text=Batido+Vainilla" alt="Batido de Vainilla">
                    <div class="menu-item-body">
                        <h3>Batido de Kitkat</h3>
                        <p>Un clásico batido de vainilla.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Cervezas -->
    <div class="container menu-section" id="cervezas">
        <h2>Cervezas</h2>
        <div class="row g-4">
            <!-- Item 1 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Cerveza+Lager" data-title="Cerveza Lager">
                    <img src="https://via.placeholder.com/400x300?text=Cerveza+Lager" alt="Cerveza Lager">
                    <div class="menu-item-body">
                        <h3>Doble Alhambra Especial</h3>
                        <p>Refrescante y ligera, perfecta para cualquier ocasión.</p>
                    </div>
                </div>
            </div>
            <!-- Item 2 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Cerveza+IPA" data-title="Cerveza IPA">
                    <img src="https://via.placeholder.com/400x300?text=Cerveza+IPA" alt="Cerveza IPA">
                    <div class="menu-item-body">
                        <h3>Tercio Mahou</h3>
                        <p>Cerveza con carácter y un toque amargo.</p>
                    </div>
                </div>
            </div>
            <!-- Item 3 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Cerveza+Stout" data-title="Cerveza Stout">
                    <img src="https://via.placeholder.com/400x300?text=Cerveza+Stout" alt="Cerveza Stout">
                    <div class="menu-item-body">
                        <h3>Tercio Alhambra 1925</h3>
                        <p>Cerveza oscura con toques de café y chocolate.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Cerveza+Stout" data-title="Cerveza Stout">
                    <img src="https://via.placeholder.com/400x300?text=Cerveza+Stout" alt="Cerveza Stout">
                    <div class="menu-item-body">
                        <h3>Tercio Corona</h3>
                        <p>Cerveza oscura con toques de café y chocolate.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Cerveza+Stout" data-title="Cerveza Stout">
                    <img src="https://via.placeholder.com/400x300?text=Cerveza+Stout" alt="Cerveza Stout">
                    <div class="menu-item-body">
                        <h3>Tercio Mohou 0.0 Tostada</h3>
                        <p>Cerveza oscura con toques de café y chocolate.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Cerveza+Stout" data-title="Cerveza Stout">
                    <img src="https://via.placeholder.com/400x300?text=Cerveza+Stout" alt="Cerveza Stout">
                    <div class="menu-item-body">
                        <h3>Salitos Blue</h3>
                        <p>Cerveza oscura con toques de café y chocolate.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Cerveza+Stout" data-title="Cerveza Stout">
                    <img src="https://via.placeholder.com/400x300?text=Cerveza+Stout" alt="Cerveza Stout">
                    <div class="menu-item-body">
                        <h3>Salitos Pink</h3>
                        <p>Cerveza oscura con toques de café y chocolate.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Cerveza+Stout" data-title="Cerveza Stout">
                    <img src="https://via.placeholder.com/400x300?text=Cerveza+Stout" alt="Cerveza Stout">
                    <div class="menu-item-body">
                        <h3>Salitos Tequila</h3>
                        <p>Cerveza oscura con toques de café y chocolate.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Vinos -->
    <div class="container menu-section" id="vinos">
        <h2>Vinos</h2>
        <div class="row g-4">
            <!-- Item 1 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Vino+Tinto" data-title="Vino Tinto">
                    <img src="https://via.placeholder.com/400x300?text=Vino+Tinto" alt="Vino Tinto">
                    <div class="menu-item-body">
                        <h3>Vino Tinto</h3>
                        <p>Un vino robusto con toques de frutas rojas.</p>
                    </div>
                </div>
            </div>
            <!-- Item 2 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Vino+Blanco" data-title="Vino Blanco">
                    <img src="https://via.placeholder.com/400x300?text=Vino+Blanco" alt="Vino Blanco">
                    <div class="menu-item-body">
                        <h3>Vino Blanco</h3>
                        <p>Ligero y refrescante, con un final suave.</p>
                    </div>
                </div>
            </div>
            <!-- Item 3 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Vino+Rosado" data-title="Vino Rosado">
                    <img src="https://via.placeholder.com/400x300?text=Vino+Rosado" alt="Vino Rosado">
                    <div class="menu-item-body">
                        <h3>Vino Rosado</h3>
                        <p>Refrescante y afrutado, ideal para el verano.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
     <!-- Copas -->
    <div class="container menu-section" id="vinos">
        <h2>Copas</h2>
        <div class="row g-4">
            <!-- Item 1 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Vino+Tinto" data-title="Vino Tinto">
                    <img src="https://via.placeholder.com/400x300?text=Vino+Tinto" alt="Vino Tinto">
                    <div class="menu-item-body">
                        <h3>Vino Tinto</h3>
                        <p>Un vino robusto con toques de frutas rojas.</p>
                    </div>
                </div>
            </div>
            <!-- Item 2 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Vino+Blanco" data-title="Vino Blanco">
                    <img src="https://via.placeholder.com/400x300?text=Vino+Blanco" alt="Vino Blanco">
                    <div class="menu-item-body">
                        <h3>Vino Blanco</h3>
                        <p>Ligero y refrescante, con un final suave.</p>
                    </div>
                </div>
            </div>
            <!-- Item 3 -->
            <div class="col-md-4">
                <div class="menu-item" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="https://via.placeholder.com/400x300?text=Vino+Rosado" data-title="Vino Rosado">
                    <img src="https://via.placeholder.com/400x300?text=Vino+Rosado" alt="Vino Rosado">
                    <div class="menu-item-body">
                        <h3>Vino Rosado</h3>
                        <p>Refrescante y afrutado, ideal para el verano.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Modal para Imágenes -->
    <div class="modal fade" id="imageModal" tabindex="-1" aria-labelledby="imageModalLabel" aria-hidden="true">
      <div class="modal-dialog modal-lg modal-dialog-centered">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title" id="imageModalLabel">Título</h5>
            <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Cerrar"></button>
          </div>
          <div class="modal-body">
            <img src="#" alt="Imagen" class="modal-img">
          </div>
        </div>
      </div>
    </div>

    <!-- Pie de Página -->
    <footer>
        <div class="container">
            <p>&copy; 2024 Menú de Bebidas. Todos los derechos reservados.</p>
        </div>
    </footer>

    <!-- Bootstrap JS y Dependencias -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <!-- Custom JavaScript -->
    <script>
        // Código para manejar el modal de imágenes
        const imageModal = document.getElementById('imageModal');
        imageModal.addEventListener('show.bs.modal', function (event) {
            // Elemento que activó el modal
            const triggerElement = event.relatedTarget;
            // Extraer información de los atributos de datos
            const imgSrc = triggerElement.getAttribute('data-img');
            const title = triggerElement.getAttribute('data-title');
            // Actualizar el contenido del modal
            const modalTitle = imageModal.querySelector('.modal-title');
            const modalImg = imageModal.querySelector('.modal-img');
            modalTitle.textContent = title;
            modalImg.src = imgSrc;
            modalImg.alt = title;
        });
    </script>
</body>
</html>
