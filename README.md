<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Mi Página Web</title>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Estilos personalizados -->
<style>
  h1, h2, h3, h4 {
    color: #f8c6d8; /* rosa pastel */
  }
</style>

</head>
<body>

<!-- Navbar con imagen en el encabezado -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <!-- Imagen en el encabezado -->
    <a class="navbar-brand d-flex align-items-center" href="#">
      <img src="https://i.pinimg.com/736x/ba/8d/77/ba8d77790bb0955984fefed175e8d0ee.jpg" 
           alt="Mi Foto" 
           width="50" 
           height="50" 
           class="rounded-circle me-2">
      Mi Sitio
    </a>

    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#menu">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="menu">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#inicio">Inicio</a></li>
        <li class="nav-item"><a class="nav-link" href="#sobre-mi">Sobre mí</a></li>
        <li class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Encabezado de bienvenida -->
<div class="container mt-5">
  <h1 class="text-center">¡Bienvenido a mi página web!</h1>
</div>

<!-- Sección Inicio sin imagen -->
<section id="inicio" class="row mt-4">
  <div class="col-md-12 text-center">
    <h2>Sofia Mérida</h2>
    <p>Estudiante de 4to Bachillerato con interés en la programación web</p>
  </div>
</section>

<!-- Sección Sobre Mí -->
<section id="sobre-mi" class="mt-5">
  <div class="card">
    <div class="card-body">
      <h3 class="card-title">Sobre Mí</h3>
      <p class="card-text">
        Me apasiona la tecnología, los proyectos creativos y el aprendizaje constante. Además disfruto del arte y la lectura.
      </p>
    </div>
  </div>
</section>

<!-- Habilidades -->
<section class="mt-5">
  <h4>Habilidades</h4>
  <ul class="list-group">
    <li class="list-group-item">HTML5 y CSS3</li>
    <li class="list-group-item">Uso básico de Bootstrap 5</li>
    <li class="list-group-item">Trabajo en equipo</li>
  </ul>
</section>

<!-- Formación Académica -->
<section class="mt-4">
  <h4>Formación Académica</h4>
  <table class="table">
    <thead>
      <tr><th>Año</th><th>Institución</th><th>Grado</th></tr>
    </thead>
    <tbody>
      <tr><td>2025 - 2026</td><td>Sagrado Corazón de Jesus</td><td>4to Bachillerato</td></tr>
    </tbody>
  </table>
</section>

<!-- Contacto -->
<section id="contacto" class="mt-4">
  <h4>Contacto</h4>
  <p>Email: sofiamerida406@gmail.com</p>
</section>

<!-- Footer -->
<footer class="bg-dark text-light text-center p-3 mt-5">
  <p>© 2025 Sofia Mérida | Sitio web creado con Bootstrap 5</p>
</footer>

<!-- Script Bootstrap -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
