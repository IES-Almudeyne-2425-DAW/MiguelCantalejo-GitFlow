# Página de Prueba con Bootstrap
Este proyecto es una página web de ejemplo creada con **HTML**, **CSS** y el framework **Bootstrap**. La página incluye una galería de imágenes, una sección de descripción y un diseño responsivo para ajustarse a diferentes tamaños de pantalla.

---

## Características

- **Diseño Responsivo:** Adaptable a dispositivos móviles, tabletas y ordenadores de escritorio.
- **Bootstrap 5:** Uso del framework para una estructura y diseño modernos.
- **Efectos Visuales:** Incluye un efecto de ampliación al pasar el ratón sobre las imágenes.
- **Archivos Organizativos:** Separación del estilo en un archivo CSS dedicado.

---
## Contenido del Proyecto

### 1. `index.html`
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página de Prueba</title>
    <!-- Enlace a Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="bg-primary text-white text-center py-4">
        <h1>Bienvenido a la Página de Prueba</h1>
    </header>

    <main class="container mt-4">
        <section>
            <h2 class="text-center mb-4">Galería de Imágenes</h2>
            <div class="row">
                <div class="col-md-4">
                    <img src="images/imagen1.jpg" alt="Imagen 1" class="img-fluid rounded shadow">
                </div>
                <div class="col-md-4">
                    <img src="images/imagen2.jpg" alt="Imagen 2" class="img-fluid rounded shadow">
                </div>
                <div class="col-md-4">
                    <img src="images/imagen3.jpg" alt="Imagen 3" class="img-fluid rounded shadow">
                </div>
            </div>
        </section>

        <section class="mt-5 text-center">
            <h2>Descripción</h2>
            <p class="text-muted">
                Esta es una página de prueba utilizando Bootstrap para una presentación limpia y responsiva.
            </p>
        </section>
    </main>

    <footer class="bg-dark text-white text-center py-3 mt-5">
        <p>&copy; 2024 Página de Prueba</p>
    </footer>
    <!-- Enlace a Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
---

## Estructura del Proyectos

```bash
El proyecto sigue la siguiente estructura de carpetas:
Proyecto/
│
├── index.html         # Archivo principal HTML
├── styles.css         # Archivo CSS para los estilos personalizados
├── /images/           # Carpeta que contiene las imágenes de la galería
│   ├── imagen1.jpg
│   ├── imagen2.jpg
│   ├── imagen3.jpg
```