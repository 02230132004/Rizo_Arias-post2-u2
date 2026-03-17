# Rizo_Arias-post2-u2
# HydrateFlow - Post-Contenido 2  
**Unidad 2: UX/UI Móvil y Diseño Centrado en Usuario**  
Ingeniería de Sistemas – Universidad de Santander (UDES) – 2026

## Brief de la aplicación móvil ficticia

**Nombre de la app:** HydrateFlow  
**Categoría:** Salud y Bienestar / Hábitos diarios  

**Usuario objetivo principal:**  
Jóvenes adultos entre 20 y 35 años, principalmente estudiantes universitarios y profesionales que trabajan de forma remota o en oficinas en Colombia (especialmente en ciudades como Cúcuta, Bucaramanga o Bogotá). Estas personas llevan estilos de vida acelerados con horarios irregulares, mucho tiempo frente a pantallas y alto nivel de estrés académico o laboral, lo que les hace descuidar la hidratación diaria. Necesitan recordatorios simples, seguimiento visual motivador y registro rápido sin fricciones.

**Problema que resuelve:**  
Muchos jóvenes olvidan beber suficiente agua durante el día debido a la concentración en estudios, trabajo o redes sociales, lo que genera fatiga crónica, dolores de cabeza, disminución de la concentración y problemas de salud a mediano plazo. HydrateFlow soluciona esto ofreciendo un seguimiento intuitivo, recordatorios personalizados y visualización de progreso que motiva a mantener el hábito de forma sostenible.

**Flujo de usuario seleccionado (3 pantallas interconectadas):**

1. **Pantalla 1 – Dashboard / Home**  
   Muestra el progreso actual del día (ejemplo: 1.2 L de 2 L recomendados), un anillo circular de progreso con porcentaje, contador de racha (“streak” de días consecutivos), y botones rápidos para agregar cantidades comunes (+250 ml, +500 ml). Incluye métricas motivacionales como “60% del objetivo” y “5 días seguidos”.  
   **Acción principal del usuario:** Ver estado general y agregar consumo rápido sin salir de la pantalla principal.

2. **Pantalla 2 – Registro de consumo**  
   Formulario sencillo para registrar un nuevo consumo: selector de cantidad (con stepper o botones), chips/toggles para tipo de bebida (agua, infusión, jugo, etc.), campo opcional de nota y botón principal “Guardar”.  
   **Acción principal del usuario:** Registrar manualmente un vaso o botella tomada.  
   **Conexión:** Al guardar, regresa al Dashboard actualizando automáticamente el progreso y el anillo.

3. **Pantalla 3 – Historial**  
   Lista cronológica de todos los registros del día (cards con hora, cantidad, tipo de bebida y nota si existe), resumen total del día y un gráfico simple de barras o línea mostrando la distribución horaria o semanal.  
   **Acción principal del usuario:** Revisar detalle de lo consumido y analizar patrones.  
   **Conexión:** Accesible desde la navegación inferior del Dashboard.

**Justificación del flujo elegido:**  
Este flujo es coherente y realista para una app de hábitos: el usuario inicia en el Dashboard (visión general), registra consumos cuando toma agua (input/formulario), y consulta el historial para reflexionar o ajustar (lista + métricas). Cumple con los requisitos de variedad de componentes:  
- Dashboard → métricas y estado de progreso (círculo, porcentaje, streak).  
- Registro → formulario con inputs, selecciones y botón de acción.  
- Historial → lista/grid de información con elementos repetitivos.  

El diseño permite aplicar un Design System propio (tokens de color azulados para evocar frescura y confianza, tipografía legible, espaciado consistente), verificar accesibilidad WCAG 2.1 AA (contraste ≥4.5:1 en texto normal, ≥3:1 en componentes gráficos, targets táctiles ≥44×44 pt), documentar microinteracciones (ej. animación de llenado del progreso al guardar, feedback de éxito en botón Guardar) y realizar un handoff completo en GitHub con capturas y enlace a Figma.


Enlace al archivo Figma (vista):  
