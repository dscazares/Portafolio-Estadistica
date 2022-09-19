# Portafolio Estadística

En este repositorio se pueden encontrar los 2 proyectos del módulo 1 de estadística para la ciencia de datos.

El entregable 1 "Los salarios" está enfocado en análisis exploratorio de datos y técnicas de preprocesamiento. Por otra parte, el entregable 2 "Los peces y el mercurio", además de incluir un análisis de los datos, se centra en la implementación de modelos estadisticos, así como de técnicas para verificar la validez de los mismos y  construir mejores modelos.


**Contenidos**
<!-- no toc -->
- [Portafolio Análisis: Los salarios](#portafolio-análisis-los-salarios)
- [Portafolio Implementación: Los peces y el mercurio](#portafolio-implementación-los-peces-y-el-mercurio)

## Portafolio Análisis: Los salarios

### Descripción
En este trabajo, por medio del uso del dataset [Data Science Job Salaries](#https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries) de Kaggle, se busco realizar un análisis exploratorio de los salarios de las personas que trabajan en el sector de Ciencia de datos. Para dicha tarea, se emplearon metodos para calcular medidas estadísticas, visualizar los datos e identificar problemas de calidad en la información.

Así mismo, se busco poner en práctica técnicas de preprocesamiento con el objetivo de mejorar la calidad de los datos que se tienen. Para esto, se utilizaron tecnicas de imputación, creación de atributos y detección de anomalías (outliers).

### Datos

Se tienen datos de personas que trabajan en Ciencia de datos en diferentes partes del mundo. Dataset obtenido de Kaggle.

**Variables presentes**

1. **work_year**: Año en que se pagó el salario.
2. **experience_level**: Nivel de experiencia: EN Entry-level/Junior, MI Mid-level/Intermediate, SE Senior-level/Experto, EX Executive-level/Director
3. **employment_type**: Tipo de empleo: PT Tiempo parcial, FT Tiempo completo, CT Contrato, FL Freelance
4. **job_title**: Rol trabajado durante el año
5. **salary**: Monto total del salario bruto pagado (antes de impuestos)
6. **salary_currency**: Moneda del salario pagado
7. **salaryinusd**: Salario en USD
8. **employee_residence**: País de residencia del empleado durante el año laboral
9. **remote_ratio**: Cantidad de trabajo realizado de forma remota: 0 Sin trabajo remoto (< 20 %), 50 Parcialmente remoto, 100 Totalmente remoto (> 80 %)
10. **company_location**: País dondse se ubica la oficina principal del empleador
11. **company_size**: Número promedio de personas que trabajaron para la empresa durante el año: S menos de 50 empleados (pequeño) M 50 a 250 empleados (mediano) L más de 250 empleados (grande)

## Portafolio Implementación: Los peces y el mercurio

### Descripción

En este trabajo, por medio del uso de datos de un estudio realizado en 53 lagos de Florida, se busco realizar un análisis de las variables que influyen en la concentración de mercurio en los peces. Para dicha tarea, se emplearon metodos para calcular medidas estadísticas y visualizar datos. Así mismo, se busco construir modelos estadisticos y validar su utilidad por medio del uso de supuestos e hipotesis. Esto, con el objetivo encontrar modelos que permitan entender el compartamiento actual de diferentes variables sobre la concentración de mercurio en peces, así como hacer predicciones a futuro del comportamiento de este fenomeno.

### Datos

Se tienen datos de un estudio realizado en 53 lagos de Florida que mide la concentración de mercurio en los peces.

**Variables presentes**

1. id = número de indentificación 
2. lago = nombre del lago 
3. alcalinidad = alcalinidad (mg/l de carbonato de calcio) 
4. PH = PH 
5. calcio = calcio (mg/l) 
6. clorofila = clorofila (mg/l) 
7. avg-mercurio = concentración media de mercurio (parte por millón) en el tejido muscualar del grupo de peces estudiados en cada lago
8. num-peces = número de peces estudiados en el lago 
9. min-mercurio = mínimo de la concentración de mercurio en cada grupo de peces 
10. max-mercurio = máximo de la concentración de mercurio en cada grupo de peces 
11. est-mercurio = estimación (mediante regresión) de la concentración de mercurio en el pez de 3 años (o promedio de mercurio cuando la edad no está disponible)
12. edad = indicador de la edad de los peces (0: jóvenes; 1: maduros)  