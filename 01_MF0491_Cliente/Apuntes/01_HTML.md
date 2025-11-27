# HTML — estructura y semántica

- `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`
- Etiquetas semánticas: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <title>Mi Página</title>
  </head>
  <body>
    <header class="site-header">
      <h1>Hola CIFO</h1>
      <div class="logo-area">
        <img src="img/logo.png" alt="Logo Cifo" class="logo" />
        <span class="brand-name"> CIFO web 2025</span>
      </div>
      <a href="#Contacto" class="cta-button"> Apúntate ahora </a>
      <!--  -->
      <nav class="main-nav">
        <ul>
          <li><a href="#">Inicio</a></li>
          <li><a href="#">Cursos</a></li>
          <li><a href="#">Recursos</a></li>
          <li><a href="#">Contacto</a></li>
        </ul>
      </nav>
    </header>
    <main><p>Contenido...</p></main>
  </body>
</html>
```
