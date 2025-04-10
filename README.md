# Catador a la Carta 🍽️✨

Bienvenido/a al repositorio de **Catador a la Carta**. Este proyecto de carácter práctico tiene como objetivo facilitar la información sobre restaurantes de alto nivel y brindar recomendaciones basadas en reseñas, detalles y análisis de la oferta gastronómica actual.

---

## Índice 📑

- Bloque 1 - Requisitos
- Bloque 2 - Análisis
  - 1. Reseñas de Restaurantes
  - 2. Recomendaciones de Restaurantes
  - 3. Detalles de Restaurantes
- Bloque 4 - Implementación
- Bloque 5 - Pruebas
  - Casos de Prueba Funcionales
  - Errores Posibles Anticipados
- Bloque 6 - Despliegue y Mantenimiento
- Mejoras Futuras

---

## Bloque 1 - Requisitos 📝

**Problema a resolver:**  
Facilitar la información sobre restaurantes de alto nivel y brindar recomendaciones.

**Público objetivo:**  
Todas las personas interesadas en vivir experiencias nuevas.

**3 Features Claves:**
- ⭐ **Reseñas completas:** Brindar reseñas que acrediten las cualidades de cada restaurante (positivas y negativas).
- ⭐ **Recomendaciones:** Seleccionar y recomendar restaurantes por su buena calidad.
- ⭐ **Detalles precisos:** Proporcionar información del restaurante (ubicación, precios, productos, etc.).

---

## Bloque 2 - Análisis 🔍

### 1. Reseñas de Restaurantes

**Tareas:**
- Visitar el restaurante, evaluar comida, servicio y ambiente.
- Redactar reseñas claras, resaltando lo positivo y lo negativo.
- Incluir fotos en cada reseña.
- Publicar reseñas y permitir que los usuarios también comenten y califiquen.

**Dificultad:** Alta  
**Restricciones Técnicas:**  
Requiere sistema de usuarios, moderación de contenido e infraestructura para imágenes.  
**Restricciones de Negocio:**  
Riesgo legal por reseñas negativas y necesidad de una comunidad activa.

---

### 2. Recomendaciones de Restaurantes

**Tareas:**
- Recomendar restaurantes de buena calidad.
- Clasificar recomendaciones según tipo de comida.
- Actualizar de forma regular la lista de recomendaciones.

**Dificultad:** Media  
**Restricciones Técnicas:**  
Se requiere lógica de recomendación y un sistema para categorizar y personalizar sugerencias.  
**Restricciones de Negocio:**  
Debe garantizar transparencia y escalabilidad.

---

### 3. Detalles de Restaurantes

**Tareas:**
- Recopilar información (ubicación, horarios, menú, precios, etc.).
- Verificar la actualización y validez de los datos.
- Incluir enlaces a redes sociales y páginas web de los restaurantes.

**Dificultad:** Baja  
**Restricciones Técnicas:**  
Depende de una base de datos robusta y un sistema de verificación periódico.  
**Restricciones de Negocio:**  
La información puede desactualizarse rápidamente y depende de fuentes externas.

---

## Bloque 4 - Implementación 🚀

- **Mostrar el Top 5 de Restaurantes:**  
  Se ordena una lista de restaurantes basada en parámetros definidos (por ejemplo, reseñas) y se retorna el top 5.

  ![Image](https://github.com/user-attachments/assets/e52a8d37-a3da-45e4-aaec-9e1a99ee2280)

---

## Bloque 5 - Pruebas 🧪

### Casos de Prueba Funcionales

1. **Publicar una reseña como usuario**  
   - **Objetivo:** Verificar que un usuario registrado pueda publicar una reseña con texto e imagen.  
   - **Pasos:**
     1. Iniciar sesión.
     2. Seleccionar un restaurante.
     3. Redactar la reseña y subir una imagen.
     4. Publicar la reseña.
   - **Resultado esperado:** La reseña se muestra correctamente, con la imagen incluida.

2. **Ver lista de restaurantes recomendados**  
   - **Objetivo:** Asegurar que la sección de recomendaciones muestre una lista actualizada.  
   - **Pasos:**
     1. Navegar a la sección de recomendaciones.
   - **Resultado esperado:** Se visualiza una lista ordenada por tipo de comida (nombre, ubicación y breve descripción).

3. **Visualización de detalles del restaurante**  
   - **Objetivo:** Verificar que se muestran los datos del restaurante (ubicación, menú, horarios, precios).  
   - **Pasos:**
     1. Seleccionar un restaurante.
   - **Resultado esperado:** Se muestran correctamente todos los detalles, incluyendo enlaces a redes o sitios externos.

### Errores Posibles Anticipados ⚠️

- **Reseñas:**
  - Problemas en la carga de imágenes.
  - Fallos en la moderación de comentarios ofensivos.
  - Error 500 en el servidor de imágenes.

- **Recomendaciones:**
  - Listas que no se actualizan o aparecen vacías.
  - Recomendaciones irrelevantes debido a errores en el sistema de filtrado.

- **Detalles:**
  - Información desactualizada (menú, horarios, etc.).
  - Enlaces rotos.
  - Problemas de visualización en dispositivos móviles.

- **Carga de Contenido:**
  - Tiempos de carga lentos por exceso de imágenes.
  - Errores al cargar la galería de fotos.

---

## Bloque 6 - Despliegue y Mantenimiento 🔧

**Servidores:**  
Utilización de servicios en la nube (AWS, Google Cloud, Azure) con balanceadores de carga para garantizar la alta disponibilidad.

**Tiendas de Aplicaciones:**  
Publicar en Google Play Store y Apple App Store, cumpliendo con las directrices de cada plataforma.

**Procesos de CI/CD:**  
Automatización del despliegue para lograr actualizaciones rápidas y eficientes.

**Gestión y Monitoreo:**  
Implementar herramientas de monitoreo que permitan rastrear el rendimiento y analizar el comportamiento de los usuarios.

![Image](https://github.com/user-attachments/assets/d59545d3-f71b-47b7-81e6-c2c63b4c42c9)

---

## Mejoras Futuras 🌟

- **Experiencia del Usuario:**  
  Integrar personalización basada en aprendizaje automático para adaptar el contenido a las preferencias del usuario.

- **Ampliación de Canales:**  
  Explorar el despliegue en plataformas adicionales, como Huawei App Gallery o implementar una Progressive Web App (PWA).

- **Optimización de Rendimiento:**  
  Mejorar el rendimiento gráfico de la galería de imágenes y optimizar la carga del contenido.

---

¡Gracias por visitar el repositorio de **Catador a la Carta**! 🎉  
Si deseas contribuir o tienes sugerencias, no dudes en abrir un _issue_ o enviar un _pull request_.
