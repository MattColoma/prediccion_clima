# Análisis Meteorológico para Constructora Andes

### Contexto del Proyecto
La empresa Constructora Andes, especializada en proyectos de infraestructura, enfrenta desafíos relacionados con las condiciones meteorológicas en sus obras. Factores como la temperatura, la lluvia y el viento pueden afectar la seguridad y planificación de las construcciones. Con este análisis de datos meteorológicos, buscamos proporcionar información clave para la toma de decisiones, minimizando riesgos y optimizando los tiempos de ejecución de los proyectos.

## Comprensión del Negocio (Business Understanding)
Objetivos Claves y KPIs Relevantes
###Objetivos del Negocio:
- Minimizar los riesgos asociados a condiciones meteorológicas adversas en las obras de construcción.
- Optimizar la planificación de proyectos considerando factores climáticos.
- Reducir tiempos de inactividad por condiciones climáticas desfavorables.
- Mejorar la seguridad de los trabajadores en condiciones meteorológicas variables.

### Cómo se utiliza la solución:
- La solución analizará patrones meteorológicos históricos para predecir condiciones adversas.
- Permitirá planificar actividades críticas en períodos con menor probabilidad de eventos climáticos extremos.
- Servirá como base para desarrollar protocolos de seguridad específicos para diferentes condiciones climáticas.

### Soluciones alternativas actuales:
- Consultar pronósticos meteorológicos generales sin análisis específico para construcción.
- Tomar decisiones basadas en experiencia empírica sin soporte de datos históricos.

### Enfoque del problema:
- Problema supervisado (podemos predecir condiciones basadas en datos históricos).
- Análisis offline (datos históricos).
- Podría extenderse a componentes online para pronósticos en tiempo real.
###Métricas de rendimiento:
- Precisión en la predicción de lluvias (RainTomorrow).
- Error medio en la predicción de temperaturas.
- Sensibilidad en la detección de condiciones extremas.
###Hipótesis iniciales:
- Las precipitaciones (Rainfall) están correlacionadas con mayores retrasos en proyectos.
- Las temperaturas extremas (MinTemp, MaxTemp) afectan la productividad del personal.
- La velocidad del viento (WindGustSpeed) está relacionada con incidentes de seguridad.
- Existen patrones estacionales en las condiciones meteorológicas que pueden predecirse.
 
# python -m venv venv
venv\Scripts\activate  # en Windows

# Luego instala los paquetes
pip install -r requirements.txt
