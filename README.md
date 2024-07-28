# Repositorio de Proyectos - Alan L. Pérez

¡Bienvenidos a mi repositorio! Aquí encontrarás una selección de proyectos y dashboards que he desarrollado a lo largo de mi carrera. Aunque mi trabajo profesional es confidencial, he incluido una serie de proyectos representativos que realicé como pilotos, plantillas y durante diversos cursos. Estos proyectos ilustran mis habilidades en análisis y procesamiento de datos, automatización, modelos de Machine Learning, así como en la creación de tableros y visualización de datos.

## Tabla de Contenidos

1. [Predicción de Vencimiento de Facturas - Modelo de Machine Learning](#predicción-de-vencimiento-de-facturas---modelo-de-machine-learning)
2. [Netflix Titles - Dashboard](#netflix-titles---dashboard)
3. [Presupuesto Personal - Dashboard](#presupuesto-personal---dashboard)
4. [Netzuk - Dashboard](#netzuk---dashboard)

---

## Predicción de Vencimiento de Facturas - Machine Learning.
Este proyecto se enfoca en la predicción de vencimientos de facturas. El objetivo es predecir con precisión cuándo una factura está en riesgo de vencimiento, permitiendo una mejor planificación financiera y gestión de cobros.

Este es el modelo inicial, desarrollado como piloto, utilizó un conjunto de datos similar al caso de uso real por lo que puedo compartirlo. Este modelo logró clasificar con mucha precisión las facturas. Posteriormente, en colaboración con científicos de datos, perfeccionamos el modelo para mejorar aún más su precisión y aplicabilidad en escenarios reales.

### Resultado de los distintos modelos.
| Algoritmo                  | MSE Scores          | R2 Score |
|----------------------------|---------------------|----------|
| Linear Regression          | 3.195110e+11        | 0.324119 |
| Support Vector Regression   | 4.767176e+11        | -0.008430|
| Decision Tree Regression    | 1.970601e+11        | 0.583147 |
| Random Forest Regression    | 1.214346e+11        | 0.743122 |
| XGB Regressor               | 1.472704e+11        | 0.688470 |

## Estrategia de Segmentación
Con base en los resultados, se pueden aplicar las siguientes estrategias:

Segmentación por Riesgo: Clasificar las facturas en categorías de riesgo (bajo, medio, alto) para priorizar la gestión.
Perfilado de Clientes: Identificar características comunes en clientes con alto riesgo para ajustar estrategias de cobro.
Optimización de Cobranza: Implementar tácticas personalizadas según el riesgo de vencimiento, mejorando la eficiencia en la recuperación de pagos.
Actualmente, estoy trabajando en un dashboard operativo que permtia aplicar estas estrategias con una actualización diaria de las facturas/Clientes.


---


## Netflix Titles - Dashboard

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/4d037cb5-eea3-43e3-8d72-a5e714e71a4d" alt="Netflix Titles Dashboard 1" width="350"/></td>
    <td><img src="https://github.com/user-attachments/assets/26edfaed-a5ca-4ae4-a2c0-04c12d5786b4" alt="Netflix Titles Dashboard 2" width="350"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/20bd6be0-4695-4f47-a722-c1ceafe34b0b" alt="Netflix Titles Dashboard 3" width="350"/></td>
    <td><img src="https://github.com/user-attachments/assets/091c174a-54bc-47b6-a730-f968084ef058" alt="Netflix Titles Dashboard 4" width="350"/></td>
  </tr>
</table>

**Descripción:**
El dashboard de Netflix Titles proporciona una exploración detallada del dataset, destacando información relevante a través de gráficos diversos como mapas y WordClouds. Es una herramienta útil para entender patrones y tendencias en los datos de películas y series.

---

## Presupuesto Personal - Dashboard

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/aaac25a6-4a4b-4bba-8963-d9d6a237be68" alt="Presupuesto Personal Dashboard" width="550" height="auto"/></td>
  </tr>
</table>

**Descripción:**
Este dashboard de Presupuesto Personal es una plantilla de Excel diseñada para el seguimiento y gestión de gastos personales. Ofrece una visión clara de las finanzas personales y ayuda en la planificación del presupuesto.

---

## Dizteku - Dashboard

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/36933584-7ea5-4108-9a2d-c42b063cdfb9" alt="Netzuk Dashboard" width="550"/></td>
  </tr>
</table>

**Descripción:**
El dashboard Dizteku incluye una visión integral de los ingresos, gastos, márgenes y beneficios. Fue creado como un proyecto de curso para demostrar habilidades en la creación de dashboards funcionales. Aplica filtros simples y funciona como una versión piloto para desarrollos futuros.

---
