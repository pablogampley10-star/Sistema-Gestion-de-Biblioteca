# 📚 Sistema de Gestión de Biblioteca

## 📖 Descripción del Caso
El sistema de gestión de biblioteca tiene como finalidad optimizar el registro de libros, usuarios y préstamos.  
Actualmente presenta limitaciones como la falta de control del progreso de lectura y una interfaz poco dinámica.  
El proyecto busca mejorar la experiencia del usuario y garantizar la mantenibilidad del software.

---

## 🎯 Objetivos
- Facilitar el registro y consulta de libros y usuarios.
- Permitir el control de préstamos y devoluciones.
- Incorporar nuevas funcionalidades que mejoren la interacción (ej. avance de lectura).
- Asegurar la usabilidad, seguridad y disponibilidad del sistema.
- Validar el cumplimiento de requerimientos mediante pruebas unitarias y de validación.

---

## ✅ Requerimientos

### Requerimientos Funcionales
- **RF1:** Registrar libros y equipos con código único de inventario.  
- **RF2:** Buscar recursos por palabra clave o tipo de material.  
- **RF3:** Enviar recordatorios de devolución a profesores.  
- **RF4:** Reservar salas de estudio en horarios específicos.  
- **RF5:** Mostrar estado detallado de cada recurso (disponible, prestado, reservado, en reparación).

### Requerimientos No Funcionales
- **RNF1:** Disponibilidad del sistema ≥ 99%.  
- **RNF2:** Interfaz de reserva usable sin ayuda en menos de 5 clics.  
- **RNF3:** Privacidad: solo el bibliotecario puede acceder al historial de préstamos de estudiantes.

---

## 🧪 Tabla de Pruebas

| ID   | Tipo       | Requerimiento Asociado | Datos de Entrada | Resultado Esperado | Resultado Obtenido |
|------|------------|-------------------------|------------------|--------------------|--------------------|
| PU1  | Unitaria   | RF1                     | Proyector EPSON, Código EQ-P05 | Registro correcto | Correcto |
| PU2  | Unitaria   | RF2                     | Búsqueda: "Proyector" | Listado de equipos disponibles | Correcto |
| PU3  | Unitaria   | RF3                     | ID Profesor con préstamo vencido | Envío de recordatorio | Correcto |
| PV1  | Validación | RNF2                    | Profesor nuevo reserva sala | Reserva en <5 clics | Correcto |
| PV2  | Validación | RNF3                    | Profesor intenta ver historial | Acceso denegado | Correcto |

---

## 🔧 Tipo de Mantenimiento Propuesto
- **Perfectivo:** Añadir la funcionalidad de registrar el avance de lectura de los libros por usuario.  
- **Adaptativo:** Mejorar la interfaz gráfica para una experiencia más dinámica y moderna.  

**Impacto:**  
- Mejora la usabilidad y satisfacción del usuario.  
- Facilita futuras ampliaciones del sistema (ej. estadísticas de lectura).  
- Incrementa la calidad y mantenibilidad del software.

---

## 🔄 Reflexión sobre el Control de Versiones
El uso de **control de versiones (ej. GitHub)** es esencial para proyectos de software:  
- Permite llevar un historial claro de cambios y mejoras.  
- Facilita la colaboración entre varios desarrolladores.  
- Garantiza trazabilidad entre requerimientos, pruebas y versiones liberadas.  
- Reduce riesgos al poder revertir cambios en caso de errores.  
- Favorece la documentación continua mediante archivos como `README.md`.

El control de versiones convierte el desarrollo en un proceso ordenado, transparente y confiable, asegurando que cada mejora del sistema quede registrada y disponible para futuras iteraciones.

---
