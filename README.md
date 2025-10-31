# DS-FE-TP2
Desarrollo Software - Frontend - Trabajo Práctico 2

## 📋 Ejercicio Práctico: Perfil de Usuario

Este proyecto implementa una página HTML de perfil de usuario utilizando elementos semánticos y buenas prácticas de desarrollo web.

## 🎯 Objetivos del Ejercicio

Crear una página HTML completa que incluya:
- Estructura semántica con `<header>`, `<main>` y `<footer>`
- Sección de biografía usando `<article>`
- Tabla de contactos con `<thead>` y `<tbody>`
- Formulario de actualización de perfil
- Imagen de perfil con `<img>`
- Meta etiquetas para SEO y responsive design

## 🏗️ Estructura HTML Semántica

### Elementos Principales Utilizados

#### 1. **Estructura Básica**
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="...">
    <title>Perfil de Usuario</title>
</head>
```

#### 2. **Header (`<header>`)**
- Contiene el encabezado principal de la página
- Incluye el título, subtítulo y la imagen de perfil
- Proporciona contexto sobre el contenido de la página

#### 3. **Main (`<main>`)**
- Contenedor del contenido principal
- Agrupa las secciones más importantes: biografía, contacto y formulario
- Debe ser único en el documento

#### 4. **Article (`<article>`)**
- Utilizado para la biografía del usuario
- Representa contenido independiente y auto-contenido
- Ideal para contenido que podría distribuirse de forma independiente

#### 5. **Section (`<section>`)**
- Agrupa contenido temático relacionado
- Usado para la sección de contacto y el formulario
- Cada sección tiene su propio encabezado

#### 6. **Footer (`<footer>`)**
- Pie de página con información de copyright
- Enlaces adicionales y créditos

## 📊 Tabla de Contactos

### Estructura de la Tabla

```html
<table>
    <thead>
        <tr>
            <th>Tipo de Contacto</th>
            <th>Información</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Email Personal</td>
            <td>maria.gonzalez@email.com</td>
        </tr>
        <!-- Más filas... -->
    </tbody>
</table>
```

### Elementos Clave:
- **`<thead>`**: Encabezado de la tabla con títulos de columnas
- **`<tbody>`**: Cuerpo de la tabla con los datos
- **`<tr>`**: Filas de la tabla
- **`<th>`**: Celdas de encabezado (en thead)
- **`<td>`**: Celdas de datos (en tbody)

## 📝 Formulario de Actualización

### Campos del Formulario

1. **Input tipo text**: Para nombre completo
2. **Input tipo email**: Para correo electrónico (con validación automática)
3. **Input tipo text**: Para teléfono
4. **Textarea**: Para biografía (campo de texto multilínea)

### Atributos Importantes:
- `id`: Identificador único del campo
- `name`: Nombre del campo para envío de datos
- `placeholder`: Texto de ayuda dentro del campo
- `required`: Hace el campo obligatorio
- `type`: Define el tipo de input y validación

```html
<input type="email" 
       id="email" 
       name="email" 
       placeholder="ejemplo@email.com"
       required>
```

## 🖼️ Imagen de Perfil

```html
<img src="URL_DE_LA_IMAGEN" 
     alt="Foto de perfil de María González" 
     class="profile-image">
```

### Atributos Esenciales:
- **`src`**: URL de la imagen
- **`alt`**: Texto alternativo (accesibilidad y SEO)
- **`class`**: Clase CSS para estilos

## 🔍 Meta Etiquetas

### Meta Etiquetas Implementadas:

1. **Charset**: Define la codificación de caracteres
   ```html
   <meta charset="UTF-8">
   ```

2. **Viewport**: Hace la página responsive
   ```html
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   ```

3. **Description**: Descripción para motores de búsqueda
   ```html
   <meta name="description" content="Perfil de usuario - Ejercicio práctico...">
   ```

## 🎨 Características Adicionales

### Estilos CSS Integrados
- Diseño moderno y responsive
- Gradientes y sombras para mejor apariencia
- Efectos hover en elementos interactivos
- Media queries para dispositivos móviles

### Accesibilidad
- Etiquetas semánticas correctas
- Atributos `alt` en imágenes
- Labels asociados a inputs mediante `for` e `id`
- Estructura lógica y navegable

### Responsive Design
- Media query para pantallas menores a 768px
- Ajuste de tamaños de fuente y espaciados
- Imagen de perfil adaptable

## 📚 Conceptos Aprendidos

### 1. **HTML Semántico**
El uso de etiquetas semánticas mejora:
- **SEO**: Los motores de búsqueda entienden mejor el contenido
- **Accesibilidad**: Los lectores de pantalla navegan mejor
- **Mantenibilidad**: El código es más legible y organizado

### 2. **Estructura de Tablas**
- Separación clara entre encabezado (`<thead>`) y cuerpo (`<tbody>`)
- Mejora la accesibilidad y permite estilos diferenciados
- Facilita el procesamiento de datos

### 3. **Formularios HTML5**
- Validación nativa del navegador
- Tipos de input específicos (email, text, etc.)
- Atributos de accesibilidad (labels, placeholders)

### 4. **Meta Etiquetas**
- Esenciales para SEO y compartir en redes sociales
- Viewport crítico para diseño responsive
- Description mejora el CTR en buscadores

### 5. **Buenas Prácticas**
- Comentarios descriptivos en el código
- Indentación consistente
- Nombres de clases descriptivos
- Separación de preocupaciones (estructura, presentación, comportamiento)

## 🚀 Cómo Visualizar

1. Abrir el archivo `index.html` en cualquier navegador web moderno
2. La página es completamente funcional y responsive
3. Probar el formulario y ver las validaciones HTML5

## 📖 Recursos Adicionales

- [MDN Web Docs - HTML](https://developer.mozilla.org/es/docs/Web/HTML)
- [HTML5 Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)
- [Web Accessibility](https://www.w3.org/WAI/)

---

**Autor**: Ejercicio práctico para Desarrollo Software - Frontend  
**Fecha**: 2024  
**Tecnologías**: HTML5, CSS3
