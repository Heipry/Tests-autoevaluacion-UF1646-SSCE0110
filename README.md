<p align="center">
  <a href="https://heipry.github.io/Tests-autoevaluacion-UF1646-SSCE0110/evaluacion.html" target="_blank">
    <button style="background-color:black; color:white; padding:10px 20px; border:none; border-radius:8px; font-size:16px; cursor:pointer;">
      🔀 Ir directamente al test
    </button>
  </a>
</p>


# Repositorio de Tests UF1646

Este repositorio contiene la **colección de tests y evaluaciones** estructurados en archivos JavaScript, diseñados para reforzar y evaluar conocimientos sobre la **impartición de acciones formativas para el empleo**.  

Cada test incluye preguntas de **opción múltiple con justificaciones detalladas** para cada respuesta correcta.  

El repositorio contiene una **web basada en HTML y estilizada con Tailwind CSS**, lo que asegura un diseño moderno, responsivo y fácil de personalizar.  

Las preguntas se han elaborado específicamente para la **Unidad Formativa UF1646: "Impartición de acciones formativas para el empleo"**, sirviendo como herramienta de apoyo pedagógico.

---

## 📌 Características principales

- **Sistema modular y reutilizable:**  
  La estructura de los tests en archivos JavaScript separados hace que el sistema sea completamente modular y fácil de ampliar.  
  Puedes añadir nuevos tests de otros módulos o unidades formativas sin necesidad de modificar la lógica de la aplicación principal.  

- **Datos estructurados:**  
  Cada test está organizado en un archivo JavaScript (formato de módulo **ES6**) que exporta un array de objetos.  
  Esto facilita la importación e integración de los datos en cualquier proyecto web.  

- **Justificación detallada:**  
  Todas las preguntas incluyen una explicación que ayuda a comprender el razonamiento detrás de la respuesta correcta, potenciando el aprendizaje autónomo.  

- **Contenido pedagógico:**  
  Las preguntas cubren aspectos clave de la **formación de formadores y la docencia**, lo que los hace ideales para estudiantes, profesionales del sector o formadores que buscan material didáctico.  

---

## 📂 Estructura del Contenido

Los tests están organizados en distintos archivos JavaScript, cada uno correspondiente a un bloque o tema de la unidad formativa.  
Esto permite una navegación clara y una integración sencilla de los datos en la aplicación web.  

---

## 🚀 Uso

Para utilizar los tests de forma local, es necesario servir los archivos desde un **servidor web**, ya que los navegadores bloquean las importaciones de módulos ES6 al abrir directamente el archivo `index.html` con `file://`.

```bash
# Clona el repositorio
git clone https://github.com/Heipry/Tests-autoevaluacion-UF1646-SSCE0110.git

# Navega al directorio
cd Tests-autoevaluacion-UF1646-SSCE0110

# Abre el archivo en tu navegador preferido mediante servidor web
````

Puedes usar cualquiera de estas opciones:

### 🔹 Opción 1: Extensión de Visual Studio Code

Instala la extensión **Live Server** y haz clic en "Go Live" para lanzar un servidor local.
Esto abrirá el proyecto en tu navegador en una dirección como `http://127.0.0.1:5500`.

### 🔹 Opción 2: Servidor con Python

Si tienes Python instalado, puedes abrir un servidor local ejecutando en la raíz del repositorio:

```bash
# Para Python 3
python -m http.server 8000
```

Luego abre en tu navegador:
👉 [http://localhost:8000/evaluacion.html](http://localhost:8000/evaluacion.html)

### 🔹 Opción 3: Node.js con npx

Si tienes Node.js, puedes usar el paquete `serve`:

```bash
npx serve .
```

Esto iniciará un servidor y podrás acceder desde tu navegador en la URL que indique la consola, recuerda que el punto de entrada es `evaluacion.html`.

---

## 🌍 Versión en línea

Este proyecto también está disponible como **GitHub Pages**, por lo que puedes acceder a los tests directamente desde tu navegador sin necesidad de descargar nada:

👉 [Abrir la aplicación en GitHub Pages](https://heipry.github.io/Tests-autoevaluacion-UF1646-SSCE0110/evaluacion.html)

## 🔀 Versión randomizada

La aplicación selecciona preguntas de forma aleatoria y muestra únicamente 10 preguntas por intento, además de mezclar el orden de las respuestas en cada una.  
Esto permite practicar con preguntas diferentes cada vez y simular una experiencia de examen más realista.  

Si lo prefieres, también puedes elegir un **test o evaluación concreta** de 10 preguntas, que siempre serán las mismas. Para ello, utiliza el selector disponible en la aplicación.


---

## 🛠️ Tecnologías Utilizadas

El proyecto está desarrollado con tecnologías web estándar:

* **HTML5** → estructura de la página
* **CSS3** → estilos y diseño
* **JavaScript (ES6 Modules)** → lógica interactiva y modular de los tests
* **Tailwind CSS** → framework *utility-first* para maquetación y estilizado rápido

---

## 👤 Autoría y Contribuciones

Este proyecto es una herramienta de apoyo educativo creada por **Javier Díaz**.

Dada la naturaleza específica del contenido, las contribuciones externas **no son necesarias**.
Sin embargo, si deseas proponer mejoras o notificar un problema, puedes abrir un **issue** en este repositorio.
