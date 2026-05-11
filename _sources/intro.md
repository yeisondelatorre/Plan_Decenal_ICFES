![Logo Plan Decenal](plandecenal.png)
# Análisis de Trayectorias Educativas: Plan Decenal Santa Marta

Bienvenido al repositorio de análisis de datos para el **Plan Decenal de Educación de Santa Marta**. Este libro interactivo utiliza microdatos históricos del ICFES (2008-2024) para diagnosticar el estado actual de la educación y proponer rutas basadas en evidencia científica y estadística.

##  Objetivo del Proyecto
El propósito de este análisis es identificar cómo las variables socioeconómicas y las políticas públicas han moldeado la trayectoria de los estudiantes en el Distrito. Buscamos responder:
* ¿Cómo ha evolucionado la brecha entre el sector oficial y privado?
* ¿Qué tanto influye el entorno familiar en el éxito académico en Santa Marta?
* ¿En qué competencias específicas (Matemáticas, Inglés, Lectura) se concentran los mayores desafíos de política pública?

##  Hallazgos Clave (Vista Previa)

A través del procesamiento de datos en formato **Parquet** y la consolidación de más de 15 años de historia evaluativa, hemos identificado tres pilares críticos:

### 1. El Fenómeno del "Techo de Cristal"
Los datos de dispersión muestran que el desempeño de los estudiantes de estratos 1 y 2 en Santa Marta está fuertemente anclado a la formación académica de los padres. Existe una correlación directa: a mayor nivel educativo de la madre, mayor es la probabilidad de que el estudiante rompa la barrera de los 250 puntos.

### 2. Rezago Competitivo en Bilingüismo
El análisis de radar de competencias revela que el sector oficial presenta su mayor debilidad en el área de **Inglés**. Dado el perfil turístico de Santa Marta, esto representa un cuello de botella para la inserción laboral de los jóvenes samarios.

### 3. Persistencia de la Brecha de Naturaleza
A pesar de las inversiones públicas, la distancia entre colegios oficiales y no oficiales se ha mantenido constante en la última década. El sector privado supera sistemáticamente al oficial en todas las dimensiones del examen Saber 11.

##  Metodología
Este libro fue construido utilizando herramientas de Ciencia de Datos de vanguardia:
* **Lenguaje:** Python (Pandas, Seaborn, Matplotlib).
* **Almacenamiento:** Formato Parquet para alta eficiencia en grandes volúmenes de datos.
* **Fuente:** Microdatos del ICFES (Estandarizados a metodología Saber 11 post-2014).

---
*Este es un documento vivo. Los análisis aquí presentados sirven como base técnica para la formulación de metas del Plan Decenal de Educación del Distrito.*
