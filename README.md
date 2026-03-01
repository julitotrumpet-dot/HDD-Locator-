# HDD Professional Multi-Level Simulator v4.2

![HDD Simulator](https://images.unsplash.com/photo-1541888946425-d81bb19240f5?q=80&w=400&auto=format&fit=crop)

HDD Professional: Horizontal Directional Drilling Simulator v4.2

HDD Professional is a high-precision technical simulator developed for the web, designed for Horizontal Directional Drilling (HDD) operators and enthusiasts. The project combines gaming mechanics with real industrial safety protocols to offer a logical and challenging training experience.

🚀 Key Features

Absolute Horizon Logic: A navigation system where 0% Pitch represents the actual horizon, requiring the operator to calculate depths based on variable terrain topography.

20 Training Levels: Progressive difficulty curve introducing complex terrains, multiple underground utilities, and specific exit targets.

Integrated Safety Management:

811 Protocol: Identification of underground utilities (Gas, Water, Electric, Telecom).

Potholing: A star-based rating system requiring visual verification of utilities before crossing.

Snap Alert: Monitoring of rod bend radius to prevent mechanical failures due to excessive steering force.

Utility Strike: Realistic simulation of critical consequences in case of contact with underground services.

Dual Interface: Dynamic switching between Profile View (for depth and pitch control) and Plan View (for lateral deviation control within the safety corridor).

Mobile Optimized: Responsive design with enhanced touch controls, fullscreen support, and gesture-lock to prevent accidental scrolling.

🛠️ Technologies Used

Language: JavaScript (ES6+) for physics logic and rendering engine.

Rendering: HTML5 Canvas API for dynamic 2D graphics.

Styling: Tailwind CSS for a modern, adaptive user interface.

Architecture: Single-file code structure for maximum portability and ease of execution.

🎮 Operating Instructions

Tool Face (Clock): Orient the tool face to determine the steering direction.

Power: Adjust the steering/push intensity (Watch out for the Snap Alert).

Actions:

Drill: Advance with rotation (maintains a straight path).

Push: Advance without rotation (allows steering the drill head).

Back: Retract to correct errors by returning along the tracked path.

Objective: Reach the Exit Target while respecting depth and lateral tolerances.

⚠️ Legal Disclaimer

This application is a simulation tool for educational purposes only. In real-world environments, always follow local safety regulations, use professional locating equipment, and comply with current excavation laws.

Developed by Julio Sarracent Simulation engineering applied to underground infrastructure.

**HDD Professional** es un simulador técnico de perforación horizontal dirigida desarrollado por **Julio Sarracent**, profesional con experiencia directa en la industria de telecomunicaciones. El simulador está diseñado para educar sobre la lógica de navegación subterránea y los protocolos de seguridad críticos en el campo.

## 🛠 Características Técnicas

* **Lógica de Horizonte Absoluto:** El simulador utiliza cálculos precisos de inclinación (Pitch) donde 0% representa el nivel real.
* **Simulación de Curvatura (Snap Alert):** Incluye alertas de seguridad basadas en el radio de curvatura de las varillas (10ft), penalizando movimientos que comprometan la integridad mecánica.
* **Navegación en 2 Ejes:**
    * **Vista Principal (Perfil):** Control de profundidad y elevación absoluta.
    * **Vista Aérea (Planta):** Control de desviación lateral y mantenimiento del corredor de seguridad (*Runaway Safety Corridor*).
* **Protocolos de Seguridad Realistas:** Simulación de *Potholing* (verificación visual de servicios) y detección de servicios públicos (Gas, Agua, Eléctrico, Telecom).

## 🎮 Cómo Jugar

1.  **Ajuste de Inicio:** Define el ángulo de entrada inicial antes de colocar la primera varilla.
2.  **Modos de Avance:**
    * **Drill (Perforar):** Avance con rotación (mantiene la dirección actual).
    * **Push (Empujar):** Avance sin rotación para redireccionar la broca según la cara de la herramienta (*Tool Face*).
3.  **Tool Face (Reloj):** Utiliza la lógica de reloj (1-12) para orientar la dirección del empuje.
4.  **Objetivo:** Completar los 20 niveles alcanzando el punto de salida con precisión, verificando todos los servicios mediante *potholes* para obtener la máxima puntuación.

## ⚠️ Disclaimer Profesional

Este simulador tiene fines educativos y de entrenamiento lógico. En operaciones reales, siempre se deben seguir las regulaciones de **OSHA**, las leyes locales de servicios públicos y llamar al **811** antes de excavar.

---
Desarrollado con HTML5, Tailwind CSS y JavaScript.
