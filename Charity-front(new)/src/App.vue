<script setup>
  </script>

<template>
  <!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <meta name="author" content="Mark Otto, Jacob Thornton, and Bootstrap contributors">
    <meta name="generator" content="Hugo 0.84.0">
    <title>Headers · Bootstrap v5.0</title>

    <link rel="canonical" href="https://getbootstrap.com/docs/5.0/examples/headers/">

    

    <!-- Bootstrap core CSS -->
<link href="../assets/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- <style>
      .bd-placeholder-img {
        font-size: 1.125rem;
        text-anchor: middle;
        -webkit-user-select: none;
        -moz-user-select: none;
        user-select: none;
      }

      @media (min-width: 768px) {
        .bd-placeholder-img-lg {
          font-size: 3.5rem;
        }
      }
    </style> -->

    
    <!-- Custom styles for this template -->
    <link href="headers.css" rel="stylesheet">
  </head>
  <body>
<!-- header -->
    <div class="rout">
      <div class="container" >
        <header class="d-flex flex-wrap justify-content-center py-3 mb-4 border-bottom">
          <a href="/" class="d-flex align-items-center mb-3 mb-md-0 me-md-auto text-dark text-decoration-none">
            <svg class="bi me-2" width="40" height="32"><use xlink:href="#bootstrap"/></svg>
            <span class="fs-4"></span>
          </a>

          <ul class="nav nav-pills">
            <router-link to="#" class="nav-link active" aria-current="page">Acceuil</router-link>
            <router-link class="nav-link" to="/categorie">Nos Catégories</router-link>
            <router-link class="nav-link" to="/projet">Nos Projets</router-link>
            <a class="nav-link" href="#">Faire un don</a>
            <router-link class="nav-link" to="/login">Connexion</router-link>
          </ul>
        </header>
      </div>
    </div>
  <div class="rout">
    <router-view></router-view>
  </div>

  
<main class="flex-shrink-0">
  <div class="container">
    <h1 class="mt-5">Sticky footer</h1>
    <p class="lead">Pin a footer to the bottom of the viewport in desktop browsers with this custom HTML and CSS.</p>
    <p>Use <a href="../examples/sticky-footer-navbar/">the sticky footer with a fixed navbar</a> if need be, too.</p>
  </div>
</main>
  
  <footer class="footer mt-auto py-3 bg-light">
    <div class="container">
      <span class="text-muted">Place sticky footer content here.</span>
    </div>
  </footer>

  </body>
  </html>


 
</template>

<style>
body{
  background-image: url("./assets/charity5.jpg");
}

.rout{
  background-color: antiquewhite;
}

.container {
  width: auto;
  max-width: 680px;
  padding: 0 15px;
}

</style>

