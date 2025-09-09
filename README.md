# primerexamen-cesar-prado

### Cesar prado Vallejo

### Univesidad Adventista

### Tecnologia en Internet


Este proyecto es una página HTML semántica para la tienda **MANACO**, con mejoras enfocadas en **Accesibilidad (a11y)**.

---

## 🔹 Mejoras de Accesibilidad (a11y) agregadas

- **Skip link**: Se añadió un enlace al inicio de la página para saltar directamente al contenido principal.  
- **Foco visible y navegación por teclado**: Se aplicaron estilos para que los elementos interactivos muestren un indicador de foco y la página sea totalmente navegable con teclado
- **Sustitución de imágenes por `div` accesibles**: Las imágenes de productos fueron reemplazadas por contenedores `<div>` con `aria-label` descriptivo, de modo que los lectores de pantalla reciban la información equivalente.  
- **Uso prudente de `aria-*`**: Se aplicó `aria-label` solo cuando fue necesario (logo y productos), evitando redundancia y manteniendo la semántica  


##  SEO

- **Título optimizado (`<meta name="title">`)**: Se utiliza un título atractivo y relevante — *MANACO - Calzado que impulsa tu paso* — que comunica el valor de la marca y mejora el CTR en resultados de búsqueda.
- **Descripción clara y persuasiva (`<meta name="description">`)**: Se define una descripción que resalta los atributos del producto (comodidad, estilo, calidad), diseñada para captar la atención de usuarios y motores de búsqueda.
- **Etiquetas Open Graph (`og:*`)**: Se implementan metadatos para mejorar la presentación del sitio al compartirse en redes sociales, incluyendo título, descripción e imagen destacada.
- **Imagen destacada (`og:image`)**: Se especifica una imagen representativa del producto para reforzar la identidad visual en plataformas como Facebook y WhatsApp.
- **Tipo de contenido (`og:type`)**: Se declara el tipo como `website` para asegurar una correcta interpretación por parte de los motores de renderizado social.

Estas decisiones contribuyen a una mejor indexación, mayor engagement en redes sociales y una experiencia más coherente para el usuario.
