from pathlib import Path

md = r"""# SlideForge IA

## Descripción

**SlideForge IA** es una aplicación web que permite generar presentaciones profesionales mediante inteligencia artificial. El usuario proporciona un tema, configura algunos parámetros opcionales y, si lo desea, carga una imagen de referencia para que la IA adopte un estilo visual similar.

La aplicación utiliza servicios de **Pollinations AI** para:

- Analizar imágenes de referencia.
- Generar el contenido de las diapositivas.
- Crear imágenes ilustrativas.
- Exportar presentaciones en formatos visuales.

---

## Características principales

### 1. Generación automática de presentaciones

El usuario introduce:

- Tema de la presentación.
- Contexto adicional.
- Idioma.
- Cantidad de diapositivas.

La IA construye automáticamente la estructura completa de la presentación.

### 2. Análisis de estilo visual

El usuario puede cargar una imagen de referencia.

La IA identifica:

- Paleta de colores.
- Tipografía predominante.
- Estilo de composición.
- Tipo de diseño.
- Estado de ánimo visual.

Estos elementos se aplican a toda la presentación.

### 3. Tipos de diapositivas

El sistema genera distintos formatos:

- Portada.
- Índice.
- Contenido.
- Datos y estadísticas.
- Citas destacadas.
- Cierre.

### 4. Generación de imágenes

Cada diapositiva puede incorporar imágenes generadas automáticamente a partir de prompts creados por la IA.

### 5. Vista previa interactiva

La aplicación ofrece:

- Miniaturas de todas las diapositivas.
- Visualización en pantalla completa.
- Navegación entre diapositivas mediante botones o teclado.

### 6. Exportación

Las presentaciones pueden exportarse en:

- PDF.
- PPTX (PowerPoint).

---

## Flujo de trabajo

```text
Usuario
   │
   ├── Tema
   ├── Contexto
   ├── Idioma
   └── Imagen opcional
            │
            ▼
 Análisis visual de referencia
            │
            ▼
 Generación de contenido IA
            │
            ▼
 Creación de diapositivas
            │
            ▼
 Generación de imágenes
            │
            ▼
 Vista previa
            │
            ├── PDF
            └── PPTX
