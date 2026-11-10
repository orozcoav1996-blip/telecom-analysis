# Análisis de uso de clientes – ConnectaTel

Proyecto del Sprint 7: análisis estadístico del comportamiento de uso (llamadas y mensajes) de los clientes de ConnectaTel, empresa de telecomunicaciones con operaciones en México y Colombia.

## 🎯 Objetivo del proyecto

Identificar patrones de uso, detectar comportamientos atípicos y crear segmentos de clientes para apoyar el diseño de planes, estrategias de retención y mejoras en la oferta comercial.

## 📂 Datasets utilizados

- `plans.csv`: planes actuales (precio, minutos, mensajes y GB incluidos, costo por excedente).
- `users_latam.csv`: información de clientes (edad, ciudad, fecha de registro, plan, fecha de cancelación).
- `usage.csv`: detalle de uso real (llamadas con duración y mensajes con longitud).

## 🔄 Etapas del análisis

1. Carga y exploración de los datasets.
2. Identificación de problemas de calidad: nulos, sentinels (-999, "?") y fechas fuera de rango.
3. Limpieza básica: reemplazo de sentinels, conversión de fechas y verificación de nulos MAR.
4. Estadísticas de uso por usuario (mensajes, llamadas y minutos).
5. Visualización de distribuciones e identificación de outliers con boxplots y método IQR.
6. Segmentación de clientes por nivel de uso y por edad.
7. Insight ejecutivo con conclusiones y recomendaciones comerciales.

## 📘 Contenido del repositorio

- `S7 Version-Estudiante-Project-ConnectaTel.ipynb`: notebook con el análisis completo.
- `README.md`: descripción del proyecto.

## 🛠️ Herramientas

Python: pandas, numpy, seaborn y matplotlib.
