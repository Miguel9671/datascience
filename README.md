# datascience
repositorio inicial de datascience

## Resumen
- En el dataset 
#### Descripción de columnas
- StudentID: Identificador único de estudiantes
#### Detalles demograficos
- Age: La edad de los estudiantes entre los rangos de 15 a 18 años.
- Gender: Genero de los estudiantes, donde 0 representa masculino y 1 representa femenino.
- Ethnicity: La etnia de los estudiantes, codificados como:
    - 0: Caucasico
    - 1: Afroamericano
    - 2: Asiatico
    - 3: Otro
- ParentalEducation: Nivel Educacional de los padres, codificados como:
    - 0: Ninguno
    - 1: High School
    - 2: Some College
    - 3: Bachelor's
    - 4: Higher
#### Hábitos de Estudio
- StudyTimeWeekly: Estudio semanal de tiempo en horas, entre 0 a 20.
- Absences: Numero de ausencias durante el año escolar, rango de 0 a 30.
- Tutoring: Estado de tutorias, donde 0 indica no y 1 si.
- Participación de los padres
- ParentalSupport: Nivel de apoyo de los padres, codificado como:
    - 0: Ninguno
    - 1: Bajo
    - 2: Moderado
    - 3: Alto
    - 4: Muy alto
#### Actividades extracurriculares
- Extracurricular: Participación en actividades extracurriculares, donde 0 indica no y 1 indica si.
- Sports: Participacion en deportes, donde 0 indica no y 1 indica si.
- Music: Participacion en actividades musicales, donde 0 indica no y 1 indica si.
- Volunteering: Participacion en voluntariado, donde 0 indica no y 1 indica si.
#### Rendimiento academico
- GPA: Promedio de calificaciones en una escala de 2.0 a 4.0 , influenciado por los habitos de estudio, participacion de los padres y actividades extracurriculares.
- GradeClass: Clasificacion de los estudiantes basados en su calificaciones de la columna GPA:
    - 0: 'A' (GPA >= 3.5)
    - 1: 'B' (3.0 <= GPA < 3.5)
    - 2: 'C' (2.5 <= GPA < 3.0)
    - 3: 'D' (2.0 <= GPA < 2.5)
    - 4: 'F' (GPA < 2.0)

### Hipótesis

Mediante el estudio de los distintos datos entregados por el dataset, se espera definir puntos claves para el exito academico de los estudiantes, como por ejemplo:
    -Si realiza actividades extracurriculares, estas afectaran de manera positiva al rendimiento académico.
    -Al dedicar mas tiempo al estudio se aumentan las calificaciones de los estudiantes.
    -Mientras mas se ausentan los estudiantes estos disminuyen sus calificaciones.
    -Dependiendo de su etnia tendran mayor o menor calificaciones.
    -Si el apoyo de los padres se relaciona con las calificaciones y si su nivel educacional se relaciona.
    
### Objetivos

Se busca obtener conclusiones respecto a la hipótesis planteada y realizar un análisis de los datos en relación a la misma gracias al uso 
de gráficos utilizando las librerias de matplotlib y seaborn.
