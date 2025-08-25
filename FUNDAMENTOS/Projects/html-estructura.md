# Estrucuta de HTML GENERAL

``` html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi Sitio Web</title>
</head>
<body>

  <!-- ================= HEADER ================= -->
  <header class="header">
    <!-- ===== NAVBAR ===== -->
    <nav class="navbar">
      <div class="navbar__brand">Mi Empresa</div>
      <ul class="navbar__links">
        <li><a href="#productos">Productos</a></li>
        <li><a href="#servicios">Servicios</a></li>
        <li><a href="#recursos">Recursos</a></li>
        <li><a href="#contacto">Contacto</a></li>
      </ul>
    </nav>
  
    <!-- ===== HERO ===== -->
    <section class="hero">
      <h1 class="hero__title">Bienvenido a Mi Sitio</h1>
      <p class="hero__subtitle">La mejor solución para tu negocio</p>
      <div class="hero__actions">
        <a href="#empezar" class="btn">Comenzar</a>
        <a href="#demo" class="btn btn--secondary">Ver demo</a>
      </div>
    </section>
  </header>

  <!-- ================= MAIN / CUERPO DE PÁGINA ================= -->
  <main class="main" id="contenido">
    <div class="layout">
      <!-- Contenido principal -->
      <article class="content">
        <section id="productos" class="section">
          <h2>Productos</h2>
          <p>Descripción de productos...</p>
        </section>

        <section id="servicios" class="section">
          <h2>Servicios</h2>
          <p>Descripción de servicios...</p>
        </section>

        <section id="recursos" class="section">
          <h2>Recursos</h2>
          <p>Materiales de apoyo...</p>
        </section>
      </article>

      <!-- Sidebar -->
      <aside class="sidebar">
        <h2>Sidebar</h2>
        <ul class="sidebar__menu">
          <li><a href="#productos">Productos</a></li>
