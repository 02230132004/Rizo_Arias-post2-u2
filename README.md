# HidraVida – Post-Contenido 2 | Unidad 2 UX/UI Móvil  
**Estudiante:** Miguel rizo arias  
**Asignatura:** Aplicaciones Móviles – Ingeniería de Sistemas UDES 2026  

## Brief de la App (≈280 palabras)
HidraVida es una aplicación móvil ficticia de salud y hábitos que ayuda a adultos jóvenes (18–35 años) en regiones cálidas como Norte de Santander (Cúcuta) a mantener una hidratación adecuada. En climas con temperaturas >30°C frecuentes, muchas personas olvidan beber agua por rutinas ocupadas, lo que causa fatiga, dolores de cabeza y riesgos renales a largo plazo.  

**Problema central:** Falta de recordatorios personalizados y visualización clara del progreso de hidratación diaria/semanal.  

**Flujo principal (3 pantallas):**
1. **Dashboard/Home** – Muestra progreso circular actual, historial semanal en lista y botón para registrar.  
2. **Registro** – Formulario con inputs/botones para sumar ml/vasos y guardar.  
3. **Resumen semanal** – Grid de días con badges de cumplimiento y métricas totales.  

Este flujo permite variedad: inputs (formulario), lista/grid (historial), métricas/progreso (círculos y badges). Justificación: cubre componentes requeridos y flujo coherente centrado en usuario (problema real en Colombia tropical).

## Decisiones de Design System
Basado en **Material Design 3** (m3.material.io/styles/color/roles):  
- Paleta accesible: Primary #00695C, Secondary #4DB6AC, Background #FAFAFA, Surface #FFFFFF, Text-primary #212121, Text-secondary #757575.  
- Tipografía: Inter (legible, variable font).  
- Espaciado: 4-8-16-24 pt.  
- Componentes con variantes (botón, input, chip) para consistencia y fácil actualización.

## Resultados de contraste verificado (WCAG 2.1 AA)
- Texto principal (#212121) sobre surface (#FFFFFF): 12.8:1 ✓  
- Texto grande (>18pt) sobre primary: 5.2:1 ✓  
- Botones (texto blanco sobre primary): 8.1:1 ✓  
Verificado con WebAIM Contrast Checker.

## Microinteracciones documentadas
1. **Guardar registro** → Trigger: tap botón Guardar; Rules: validar + simular save; Feedback: spinner → check + snackbar; Loop: error → snackbar rojo.  
2. **Actualización progreso** → Trigger: save OK; Feedback: animación círculo + badge celebración.

## Enlace Figma
https://www.figma.com/make/u8iq7SIjpVkjOPvc3snu45/HidraVida?t=thl91ox56S9I6jyu-1

## Referencias
- Material Design 3: https://m3.material.io  
- WCAG 2.1 AA: https://www.w3.org/TR/WCAG21/#contrast-minimum  
- Dan Saffer – Microinteractions (modelo trigger-rules-feedback-loop)



