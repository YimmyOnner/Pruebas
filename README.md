<style>
/* Estilo académico */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: #f5f6fa;
    color: #1a1a1a;
    margin: 0;
    padding: 0;
}

.card {
    background: #fff;
    border-radius: 15px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    padding: 25px;
    margin: 20px auto;
    max-width: 800px;
    transition: transform 0.3s ease;
}
.card:hover { transform: translateY(-5px); }

.concepto { border-left: 6px solid #1E88E5; }
.ejemplos { border-left: 6px solid #6A1B9A; }
.evaluaciones { border-left: 6px solid #F57C00; }
.reflexion { border-left: 6px solid #43A047; }
.bibliografia { border-left: 6px solid #546E7A; }
.tareas { border-left: 6px solid #1E88E5; }
.declaracion { border-left: 6px solid #607D8B; }

h1, h2 { margin-bottom: 15px; }

pre {
    background: #f7f7f7;
    padding: 10px;
    border-radius: 10px;
    font-size: 14px;
    overflow-x: auto;
}

a.button {
    display: inline-block;
    padding: 10px 20px;
    margin: 10px 0;
    background-color: #1E88E5;
    color: white;
    text-decoration: none;
    border-radius: 8px;
    transition: background 0.3s;
}
a.button:hover { background-color: #1565C0; }
</style>

<!-- Portada -->
<div class="card">
<h1>Portafolio Académico – Teoría de la Programación</h1>
<p><strong>Institución:</strong> Nombre de la institución</p>
<p><strong>Carrera:</strong> Nombre de la carrera</p>
<p><strong>Asignatura:</strong> Teoría de la Programación</p>
<p><strong>Ciclo / Período académico:</strong> Información</p>
<p><strong>Docente:</strong> Nombre del docente</p>
<p><strong>Estudiante:</strong> Yimmy Angulo</p>

<a class="button" href="#contenidos">Ir a Contenidos de la Unidad 1</a>
<a class="button" href="#tareas">Ver Tareas Entregadas</a>
<a class="button" href="#evaluaciones">Ver Evaluaciones Tomadas</a>
<a class="button" href="#bibliografia">Bibliografía</a>
<a class="button" href="#ia">Declaración de IA</a>
</div>

<!-- Contenidos -->
<div class="card concepto" id="contenidos">
<h2>🧠 Concepto: Estructuras Secuenciales</h2>
<p>
Las <strong>estructuras secuenciales</strong> son aquellas en las que las instrucciones se ejecutan una tras otra,
siguiendo un orden lógico y lineal, sin condiciones ni repeticiones.  
Son la base de cualquier programa, ya que permiten realizar pasos definidos de forma ordenada.
</p>
</div>

<div class="card ejemplos">
<h2>📋 Ejemplos</h2>
<ol>
<li>
<strong>Ejemplo 1:</strong> Calcular el área de un rectángulo.
<pre><code>Leer base y altura
Calcular área = base * altura
Mostrar área</code></pre>
</li>
<li>
<strong>Ejemplo 2:</strong> Mostrar un mensaje de bienvenida.
<pre><code>Imprimir "Bienvenido al sistema"</code></pre>
</li>
<li>
<strong>Ejemplo 3:</strong> Sumar dos números.
<pre><code>Leer A, B
Calcular S = A + B
Mostrar S</code></pre>
</li>
</ol>
</div>

<div class="card reflexion">
<h2>💭 Reflexión Personal</h2>
<p>
La programación no solo consiste en escribir código, sino en
<strong>pensar de forma estructurada y lógica</strong>.  
Aprender a programar mejora nuestra capacidad para resolver problemas, planificar tareas y comprender la tecnología que usamos día a día.
</p>
<p>
En un mundo dominado por la automatización y los datos, la programación se convierte en una
<strong>herramienta esencial para la innovación y el pensamiento crítico</strong>.
</p>
<a class="button" href="#contenidos">🔙 Volver a Contenidos</a>
</div>

<!-- Tareas -->
<div class="card tareas" id="tareas">
<h2>📝 Tareas Entregadas</h2>
<ul>
<li><a href="pdfs/aa882c27-6395-4434-adb7-d3da322a704d.pdf">📘 Aprendizaje Autónomo (AA) – Unidad 1</a></li>
</ul>
<a class="button" href="#contenidos">🔙 Volver a Contenidos</a>
</div>

<!-- Evaluaciones -->
<div class="card evaluaciones" id="evaluaciones">
<h2>🧾 Evaluaciones Tomadas</h2>
<ul>
<li><a href="pdfs/304dd43c-da11-48ab-83e3-7a97755be15a.pdf">📗 Aprendizaje Práctico Experimental (APE) – Unidad 1</a></li>
</ul>
<a class="button" href="#contenidos">🔙 Volver a Contenidos</a>
</div>

<!-- Bibliografía -->
<div class="card bibliografia" id="bibliografia">
<h2>📚 Bibliografía (Formato IEEE)</h2>
<p>
[1] D. Knuth, <em>The Art of Computer Programming</em>, 3rd ed., Addison-Wesley, 1997.<br>
[2] B. W. Kernighan and D. M. Ritchie, <em>The C Programming Language</em>, 2nd ed., Prentice Hall, 1988.<br>
[3] S. McConnell, <em>Code Complete</em>, 2nd ed., Microsoft Press, 2004.<br>
[4] IEEE Computer Society, “Software Engineering Body of Knowledge,” <em>IEEE SWEBOK V3.0</em>, 2014.
</p>
<a class="button" href="#contenidos">🔙 Volver a Contenidos</a>
</div>

<!-- Declaración de IA -->
<div class="card declaracion" id="ia">
<h2>🤖 Declaración de Uso de IA Generativa</h2>
<p>
El estudiante declara que para la elaboración de este portafolio se ha utilizado IA generativa únicamente como herramienta de apoyo para mejorar la presentación, organización y redacción de los contenidos, manteniendo la autoría y análisis crítico en todos los trabajos presentados.
</p>
<a class="button" href="#contenidos">🔙 Volver a Contenidos</a>
</div>

