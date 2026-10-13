# proyecto-<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi página web</title>
    <link rel="stylesheet" href="css/estilos.css">
</head>
<body>

    <!-- Cabecera -->
    <header>
        <div class="top-bar">
            <span class="colores">🔵🟡🔴</span>
            <h1>Mi página web</h1>
            <button class="btn-oscuro">Cambiar tema</button>
        </div>
        <nav class="menu-principal">
            <a href="#texto">Texto</a>
            <a href="#listas">Listas</a>
            <a href="#tabla">Tabla</a>
            <a href="#multimedia">Multimedia</a>
            <a href="#formulario">Formulario</a>
            <a href="contacto.html">Contacto</a>
        </nav>
    </header>

    <div class="contenedor">
        <!-- Contenido Principal -->
        <main class="contenido-principal">

            <!-- Sección Texto -->
            <section id="texto" class="seccion">
                <h2>Elementos de texto</h2>
                <hr>
                <p>Aquí va negrita, cursiva y resaltado. Cita destacada. Enlace externo.</p>
                <p><strong>Texto en negrita</strong>, <em>texto en cursiva</em>, <mark>texto resaltado</mark>.</p>
                <blockquote>"Este es un texto de cita destacada."</blockquote>
                <p>Visita <a href="https://www.w3schools.com" target="_blank">este enlace externo</a> (se abre en pestaña nueva).</p>
                <hr>
            </section>

            <!-- Sección Listas -->
            <section id="listas" class="seccion">
                <h2>Listas</h2>
                <h3>Lista con viñetas</h3>
                <ul>
                    <li>HTML</li>
                    <li>CSS</li>
                    <li>JavaScript</li>
                </ul>

                <h3>Lista numerada</h3>
                <ol>
                    <li>Crear estructura</li>
                    <li>Dar estilo</li>
                    <li>Agregar interactividad</li>
                </ol>

                <h3>Lista de definiciones</h3>
                <dl>
                    <dt>HTML</dt>
                    <dd>Estructura del contenido web</dd>
                    <dt>CSS</dt>
                    <dd>Estilo y diseño visual</dd>
                    <dt>JavaScript</dt>
                    <dd>Comportamiento e interacción</dd>
                </dl>
            </section>

            <!-- Sección Tabla -->
            <section id="tabla" class="seccion">
                <h2>Tabla</h2>
                <table>
                    <thead>
                        <tr>
                            <th>Etiqueta</th>
                            <th>Función</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>&lt;h1&gt; ... &lt;/h1&gt;</td>
                            <td>Título principal</td>
                        </tr>
                        <tr>
                            <td>&lt;p&gt; ... &lt;/p&gt;</td>
                            <td>Párrafo de texto</td>
                        </tr>
                        <tr>
                            <td>&lt;a&gt; ... &lt;/a&gt;</td>
                            <td>Enlace o hipervínculo</td>
                        </tr>
                    </tbody>
                </table>
            </section>

            <!-- Sección Multimedia -->
            <section id="multimedia" class="seccion">
                <h2>Multimedia</h2>
                <div class="multimedia-fila">
                    <div class="caja-foto">
                        <img src="img/foto.jpg" alt="Imagen de ejemplo">
                        <p>FOTO</p>
                    </div>
                    <div class="caja-video">
                        <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Video de ejemplo" allowfullscreen></iframe>
                        <p>VIDEO</p>
                    </div>
                </div>
            </section>

            <!-- Sección Formulario -->
            <section id="formulario" class="seccion">
                <h2>Formulario</h2>
                <form id="miFormulario">
                    <div class="form-grupo">
                        <label for="nombre">Nombre:</label>
                        <input type="text" id="nombre" name="nombre">
                    </div>
                    <div class="form-grupo">
                        <label for="correo">Correo:</label>
                        <input type="email" id="correo" name="correo">
                    </div>
                    <div class="form-grupo">
                        <label for="mensaje">Mensaje:</label>
                        <textarea id="mensaje" name="mensaje" rows="3"></textarea>
                    </div>
                    <button type="submit" class="btn-enviar">Enviar</button>
                </form>
            </section>

        </main>

        <!-- Barra Lateral -->
        <aside class="barra-lateral">
            <h3>Barra lateral</h3>
            <p>Contenido relacionado</p>
            
            <div class="desplegable">
                <button class="btn-desplegable">Desplegable ▼</button>
                <div class="contenido-desplegable">
                    <p>Ver más contenido</p>
                </div>
            </div>
        </aside>
    </div>

    <!-- Pie de página -->
    <footer>
        <p>© 2026 Tu Nombre. Hecho con HTML, CSS y JavaScript.</p>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
