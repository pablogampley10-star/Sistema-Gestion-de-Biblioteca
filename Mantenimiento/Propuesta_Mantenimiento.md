# 📘 Propuesta de Mantenimiento

## 🛠️ Tema
**Mantenibilidad de productos de software**  
Caso de estudio: **Sistema de Gestión de Biblioteca**

---

## 🔎 Conceptos Teóricos de Mantenimiento de Software

### Tipos de Mantenimiento
- **Correctivo:** Corrige errores o fallos detectados después del lanzamiento.  
- **Adaptativo:** Ajusta el software a cambios en el entorno (SO, hardware, normativas).  
- **Perfectivo:** Añade nuevas funcionalidades, optimiza rendimiento y mejora usabilidad.  
- **Preventivo:** Acciones programadas para evitar fallos futuros y optimizar rendimiento.  

### Costos de Mantenimiento
- **Directos:** Mano de obra, materiales, repuestos, tiempo de inactividad.  
- **Indirectos:** Pérdida de producción, impactos operativos.  
- **Indicador clave:** CPMV (Costo Total de Mantenimiento como % del Valor de Reemplazo del Activo).  

---

## ⚠️ Problemáticas Identificadas
1. El sistema no permite llevar control del progreso de lectura de los libros.  
2. La interfaz es poco dinámica y requiere mejor adaptación visual.  

---

## 🧩 Tipos de Mantenimiento Aplicables

| Problemática | Tipo de Mantenimiento | Justificación |
|--------------|----------------------|---------------|
| No permite llevar control del progreso de lectura | **Perfectivo** | Añade nuevas funciones y mejora la experiencia del usuario. |
| Interfaz poco dinámica | **Adaptativo** | Se entrega una nueva versión de la interfaz para mayor comodidad de navegación. |

---

## ✨ Cambio Funcional Propuesto
**Funcionalidad nueva:** Registro del avance de lectura de los libros por usuario.  

### 📑 Descripción Técnica
- Campo de avance de lectura (%) o páginas leídas en el módulo de préstamos/libros adquiridos.  
- Actualización manual del progreso por parte del usuario.  
- Reportes e indicadores del avance total de lectura.  
- Panel visual con barra o gráfico de progreso.  

### 📈 Impacto del Cambio
- **Mantenibilidad:** Facilita futuras ampliaciones (recomendaciones, estadísticas).  
- **Calidad:** Mejora la interacción y satisfacción del usuario.  
- **Usabilidad:** Interfaz más intuitiva y atractiva.  

---

## 📝 Uso de Markdown en Proyectos de Software
- Lenguaje de marcado sencillo creado por John Gruber (2004).  
- Permite dar formato a texto plano y convertirlo fácilmente en HTML.  
- Ventajas en GitHub:  
  - Comunicación ágil.  
  - Documentación clara y legible.  
  - Colaboración eficiente en proyectos.  

---

## 📊 Evidencia Opcional del Cambio

### Diagrama de Caso de Uso (UML)
- **Actor:** Usuario  
- **Caso de Uso Existente:** Gestionar Préstamo/Libro Adquirido  
- **Nuevo Caso de Uso:** Registrar Avance de Lectura  
- **Relación:** Extiende de "Gestionar Préstamo/Libro Adquirido"  

---

## 💡 Reflexión Final
El mantenimiento propuesto amplía las capacidades del sistema y fortalece la relación entre usuario y aplicación.  
La nueva funcionalidad convierte al sistema en una herramienta más dinámica, moderna y centrada en el usuario.  

---
