# TWK - Moda Circular para Niños

"Pequeñas prendas, grandes sonrisas"

## 🌟 Descripción

Plan de negocios interactivo para TWK, una empresa de moda circular especializada en ropa infantil. A través de un modelo de consignación sostenible, ofrecemos segundas oportunidades a prendas de alta calidad, promoviendo el consumo consciente y apoyando a las familias.

## 🚀 Ver en Vivo

Este sitio está desplegado en GitHub Pages: [Tu URL aquí una vez configurado]

## 📋 Características

- **Diseño Responsivo**: Optimizado para móviles y desktop
- **Navegación Suave**: Scrolling fluido entre secciones
- **Contenido Interactivo**: Tabs, gráficos y elementos clickeables
- **Gráficos Financieros**: Visualización de datos con Chart.js
- **Diseño Moderno**: Interfaz limpia con Tailwind CSS

## 🛠️ Tecnologías Utilizadas

- HTML5 semántico
- CSS3 con Tailwind CSS
- JavaScript vanilla
- Chart.js para visualizaciones
- Google Fonts (Inter)

## 📁 Estructura del Proyecto

```
TWK/
├── index.html              # Página de redirección
├── main.html              # Página principal del plan de negocios
├── src/
│   └── img/
│       └── logo.png       # Logo de TWK
├── .pre-commit-config.yaml # Configuración de pre-commit hooks
├── .gitignore
└── README.md
```

## 🔧 Desarrollo Local

1. Clona el repositorio:

   ```bash
   git clone [tu-repo-url]
   cd TWK
   ```

2. Abre `main.html` en tu navegador preferido

3. Para desarrollo, puedes usar un servidor local:
   ```bash
   python -m http.server 8000
   # o
   npx serve .
   ```

## 📦 Configuración de GitHub Pages

### Pasos para activar GitHub Pages:

1. **Ve a tu repositorio en GitHub**
2. **Clica en "Settings"** (Configuración)
3. **Scroll hacia abajo hasta "Pages"** en el menú lateral
4. **En "Source"**, selecciona "Deploy from a branch"
5. **Selecciona la rama "main"** y carpeta "/ (root)"
6. **Clica "Save"**

Tu sitio estará disponible en: `https://[tu-usuario].github.io/TWK`

### Solución de Problemas Comunes:

- **404 Error**: Asegúrate de que `index.html` esté en la raíz
- **Imágenes no cargan**: Verifica que las rutas sean relativas
- **CDN Issues**: Los CDNs funcionan en GitHub Pages, pero considera versiones locales

## 🎨 Personalización

### Colores del Tema:

- **Primario**: `#A7C7E7` (Azul suave)
- **Secundario**: `#3b82f6` (Azul vibrante)
- **Fondo**: `#f8f7f4` (Beige claro)
- **Texto**: `#333` (Gris oscuro)

### Secciones del Plan:

1. **Fundamentos** - Resumen, ADN, Equipo, Condiciones
2. **Problema/Solución** - Desafío del fast fashion vs. oportunidad circular
3. **Modelo de Negocio** - Círculo virtuoso de consignación
4. **Marketing** - Estrategia de valor y merchandising
5. **Estrategia** - Análisis FODA y Porter's 5 Forces
6. **Inversión** - Distribución del capital inicial
7. **Impacto** - Compromiso ambiental y social

## 📈 Pre-commit Hooks

Este proyecto incluye hooks de pre-commit para mantener la calidad del código:

- Validación de estructura HTML
- Formateo con Prettier
- Detección de secretos hardcodeados
- Verificación de uso de CDNs
- Limpieza de espacios en blanco

Para instalar: `pre-commit install`

## 📞 Contacto

**TWK - TheWallKids**

- Instagram: @thewallkids
- Propósito: Revolucionar la moda infantil hacia un futuro más sostenible

---

💚 **Únete a la revolución de la moda circular**
