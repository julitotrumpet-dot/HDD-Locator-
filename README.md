# HDD Professional Multi-Level Simulator v2.9

![HDD Simulator](https://images.unsplash.com/photo-1541888946425-d81bb19240f5?q=80&w=400&auto=format&fit=crop)

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
