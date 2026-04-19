# 📦 Inventario Pro

> **Gestión de inventario moderna, 100% offline y sin dependencias.**  
> Diseñado para emprendedores, revendedores y pequeños negocios que necesitan control total de su stock, ventas y finanzas sin servidores ni suscripciones.

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Offline First](https://img.shields.io/badge/Offline--First-✅-brightgreen)](#)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-None-brightgreen)](#)
[![Single File](https://img.shields.io/badge/Format-Single%20HTML-orange)](#)

---

## 🌟 Características Principales

### 📊 Panel de Control en Tiempo Real
- Métricas clave: productos activos, unidades vendidas, ganancia bruta/neta y valor del inventario.
- Gráfico de ventas de los últimos 7 días con animaciones suaves.
- Ranking dinámico de los **Top 5 productos más vendidos**.

### 📦 Gestión de Productos
- **CRUD completo**: agregar, editar y eliminar productos.
- Búsqueda instantánea por nombre.
- Filtros inteligentes: `En Stock`, `Stock Bajo`, `Sin Stock`.
- Cálculo automático de costo por unidad y seguimiento de ventas.

### 🛒 Registro de Ventas & Movimientos
- Registro rápido con validación de stock y cálculo automático de ganancias.
- Historial completo de transacciones (`Ventas`, `Ajustes de Stock`, `Inversiones`).
- Filtros por tipo de movimiento y timestamps detallados.

### 📒 Sistema de Apuntes Inteligente
- Crear notas, tareas, ideas y recordatorios importantes.
- **Fijar** apuntes críticos en la parte superior.
- Categorías con etiquetas visuales y búsqueda por contenido.
- Exportación a formato `.txt`.

### 💾 100% Offline & Privado
- **Sin servidores, sin nube, sin rastreo.** Toda la información se guarda localmente en tu navegador mediante `localStorage`.
- Funciona sin conexión a internet después de la primera carga.
- Ideal para entornos con conectividad limitada o para quienes priorizan la privacidad.

### 🔄 Portabilidad de Datos
- 📤 **Exportar Backup**: descarga completa en formato `.json`.
- 📥 **Importar Backup**: restaura tus datos desde un archivo.
- 📊 **Exportar CSV**: genera reportes compatibles con Excel/Sheets.
- 📤 **Compartir Productos**: transferencia peer-to-peer mediante códigos codificados en Base64.
- ➖ **Ajuste de Ganancia Neta**: resta gastos externos (envíos, comisiones, etc.) sin alterar el registro de ventas.

### 🎨 Interfaz Moderna & Responsive
- Diseño **Glassmorphism** con modo Claro/Oscuro.
- Navegación inferior optimizada para móviles.
- Animaciones fluidas, transiciones suaves y microinteracciones.
- Adaptable a escritorio, tablet y smartphone.

---

## 🚀 Cómo Usarlo

1. **Descarga** el archivo `QWEN3.6_INVENTARIO_V2.html` o clona el repositorio.
2. **Abre el archivo** en cualquier navegador moderno (Chrome, Firefox, Edge, Safari, etc.).
3. **Empieza a gestionar** tu inventario. Los datos se guardan automáticamente.
4. *(Opcional)* Realiza copias de seguridad periódicas desde `⚙️ Ajustes > Exportar Backup`.

> 💡 **Nota:** No requiere instalación, ni servidor web, ni Node.js, ni paquetes externos. Es un archivo HTML autónomo.

---

## 🛠️ Stack Tecnológico

| Tecnología | Uso |
|------------|-----|
| `HTML5` | Estructura semántica y accesible |
| `CSS3` | Variables CSS, Glassmorphism, Grid/Flexbox, Animaciones |
| `JavaScript (ES6+)` | Lógica de negocio, manipulación del DOM, persistencia local |
| `localStorage` | Almacenamiento persistente en el navegador |
| `Canvas/SVG` | Iconos ligeros sin dependencias externas |

---

## 🔐 Privacidad & Seguridad

- ✅ **Sin telemetría:** No se envía ningún dato a servidores externos.
- ✅ **Cifrado local opcional:** Los datos residen únicamente en tu dispositivo.
- ⚠️ **Limitación de `localStorage`:** Recomendado para inventarios de hasta ~5MB (~5,000 productos). Para volúmenes mayores, utiliza la función de exportación periódica o contacta para soporte empresarial.

---

## 📈 Hoja de Ruta (Roadmap)

- [ ] 📱 Conversión a **PWA** (instalable en escritorio/móvil)
- [ ] 📸 Integración de **lector de códigos de barras/QR**
- [ ] 📊 Gráficos avanzados y exportación a PDF
- [ ] 🌍 Soporte multi-moneda y multi-idioma
- [ ] ☁️ Sincronización opcional en la nube (cifrado E2E)
- [ ] 👥 Perfiles multi-usuario con roles

---

## 🤝 Contribuir

Las contribuciones son bienvenidas. Si deseas mejorar la interfaz, optimizar el rendimiento o añadir funciones:

1. Haz un Fork del repositorio
2. Crea una rama (`git checkout -b feature/nueva-funcion`)
3. Realiza commits descriptivos
4. Abre un Pull Request

---

## 📜 Licencia

Distribuido bajo la licencia **MIT**. Consulta `LICENSE` para más información.

---

## 🙌 Créditos

Desarrollado con ❤️ por la comunidad open-source.  
Si este proyecto te resulta útil, considera dejar una ⭐ en el repositorio.

> 📩 ¿Problemas, sugerencias o soporte personalizado? Abre un **Issue** o contacta directamente.
