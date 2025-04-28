# Desafío - Ricomida

- Para realizar este desafío debes haber estudiado previamente todo el material disponible en el LMS correspondiente a la unidad.
- Una vez terminado el desafío, **comprime** la carpeta que contiene el desarrollo de los requerimientos solicitados y sube el `.zip` en el LMS.
- **Puntaje total:** 10 puntos.

## Desarrollo del desafío

- El desafío se debe desarrollar en **parejas**.
- Para la realización del desafío necesitarás apoyarte en el archivo **Apoyo Desafío - Ricomida**.

## Habilidades a evaluar

- Implementar adecuadamente la librería **jQuery** en un proyecto web, utilizando recursos locales y externos.
- Implementar componentes **JavaScript** de **Bootstrap**, para agregar elementos visuales a un sitio web.

## Descripción

El siguiente desafío permitirá al estudiante practicar las habilidades adquiridas hasta el momento en relación con **HTML**, **CSS**, **Bootstrap** y **jQuery**.  
Consiste en la construcción de una **página web** relacionada con la preparación de comidas y muestra de recetas, donde todo el sitio debe ser **responsivo**, partiendo de una **maqueta** con su guía de estilos.

Tareas a realizar:

- Desarrollar desde cero el **esqueleto** de la página web (**HTML**).
- Agregar los estilos indicados para mejorar la apariencia (**CSS**).
- Incorporar elementos y componentes de **Bootstrap** para mejorar aún más el estilo y permitir adaptabilidad a cualquier dispositivo (tablet, móvil, entre otros), incluyendo componentes especiales de **Bootstrap** que requieren **jQuery** (por ejemplo, **Tooltips**).

Finalmente, la página web debe tener **tres interacciones** activadas por eventos del usuario, utilizando:

- Eventos de `click` y `dblclick`
- Métodos como `toggle` y `on`
- Selectores de `id`, `etiquetas` y `clases`

Esto permitirá ejecutar **ventanas emergentes**, cambiar **estilos de texto** y hacer aparecer/desaparecer elementos mediante **animaciones**.

---

## Requerimientos

En grupos de **dos personas** se deben resolver los siguientes requerimientos:

### 1. Carousel

- Utilizar el **carousel** de **Bootstrap** con **2 ítems** de carousel, cada uno con **4 imágenes** en su interior.
- En tamaños `sm` y `xs` debe desaparecer.
- **(1 Punto)**

### 2. Tooltip

- Incluir un botón **"Enviar por correo"** con un **tooltip** aplicado.
- **(1 Punto)**

### 3. Evento

- Utilizar el evento `click` de **jQuery** para mostrar una alerta al hacer clic sobre el botón **"Enviar por Correo"**.
- Implementar el `id` a la etiqueta del botón con el nombre: `enviarCorreo`.
- El mensaje de la alerta debe ser: **"El correo fue enviado correctamente..."**
- **(2 Puntos)**

### 4. Selectores de etiqueta

- Utilizando **selectores de etiqueta** y el método de jQuery `on` con el evento `dblclick`, modificar el color del texto de los títulos **"INGREDIENTES"** y **"PREPARACIÓN"** a color rojo cuando se haga doble clic sobre cada uno de ellos de forma individual.
- **(3 Puntos)**

### 5. Selectores de clase

- Implementar **selectores de clases** y utilizar el método de jQuery `toggle` para hacer **desaparecer y aparecer** el contenido de todas las tarjetas **"card"** en la sección de **Recetas Relacionadas**.
- Esto debe suceder cuando el usuario haga clic sobre el título de cualquiera de las tres tarjetas.
- **(3 Puntos)**

> **Hint:** Guíate por la maqueta proporcionada.

---

## Guía de Estilos

### Tipografías

- **Cabin**
- **Lobster**  
(Disponibles en Google Fonts)

### Pesos de fuente

- Cabin Regular (400)
- Cabin Bold (700)
- Lobster Regular (400)

### Colores

- `#373a3c`
- `#dddddd`
- `#000` o `var(--black)`
- `#fff` o `var(--white)`
- `#dc3545` o `var(--danger)`

## Trabajo revisado y terminado por Richard Montoya @Richmontoya92