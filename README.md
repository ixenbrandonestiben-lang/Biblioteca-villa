# 📚 Sistema de Gestión de Préstamos Bibliotecarios

## 📖 Descripción
Aplicación web frontend para la administración, seguimiento y archivado de préstamos de libros en una biblioteca. Diseñada para funcionar **100% en el navegador**, sin dependencias externas ni configuración de servidor. Utiliza `localStorage` para persistencia de datos y genera reportes auditables en formato JSON.

## ✨ Características Principales
- 🆕 **Registro Rápido:** Formulario con autocompletado de fechas y validación nativa.
- 📊 **Doble Vista Separada:** Tabla de `Préstamos Activos` y tabla de `Historial Archivado`.
- 🗃️ **Sistema de Archivado Seguro:** El botón `Archivar` no elimina datos. Los traslada al historial conservando toda la trazabilidad (fecha de préstamo, entrega y marca de tiempo de archivo).
- 🔍 **Búsqueda en Tiempo Real:** Filtrado instantáneo por nombre o carnet sin recargar la página ni re-renderizar el DOM.
- 💾 **Persistencia Local:** Los datos sobreviven a recargas y cierres del navegador mediante `localStorage`.
- 📥 **Exportación JSON:** Descarga completa de activos + historial en un solo archivo estructurado.
- 🎨 **UI Moderna & Responsive:** CSS puro con Custom Properties, Grid/Flexbox y diseño adaptable a móviles.

## 🛠️ Stack Tecnológico
| Capa | Tecnología |
|------|------------|
| Estructura | HTML5 Semántico |
| Estilos | CSS3 (Variables, Grid, Flexbox) |
| Lógica | JavaScript ES6+ (Vanilla) |
| Almacenamiento | `localStorage` API |
| Exportación | `Blob` API + `URL.createObjectURL` |

## 🚀 Instalación y Ejecución
Este proyecto es **autocontenido**. No requiere instalación de paquetes ni pasos de compilación.

1. Clona o descarga el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/biblioteca-gestion.git
   cd biblioteca-gestion
