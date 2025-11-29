# Social Media Addiction
### Exploración del impacto del uso de redes sociales en estudiantes

---

## Descripción

Este proyecto analiza cómo los hábitos de uso de redes sociales influyen en el bienestar emocional, social y académico de estudiantes.  
Utiliza el dataset *Students’ Social Media Addiction vs Relationships* (Kaggle) para identificar patrones, validar hipótesis y construir modelos predictivos de adicción y afectación académica.

El objetivo es ofrecer información útil para docentes, estudiantes y cualquier persona interesada en comprender cómo las redes afectan la vida cotidiana.

---

## Fuente de datos

- Dataset proveniente de **Kaggle**: *Students’ Social Media Addiction vs Relationships*.
- El archivo CSV está incluido en este repositorio dentro de la carpeta `/data` para facilitar la reproducción del análisis.
- El notebook utiliza este archivo directamente sin necesidad de descargarlo manualmente.

---

## Objetivos del análisis

- Identificar patrones de uso de redes sociales según horas diarias, edad, género y país.  
- Analizar el impacto en relaciones, sueño, salud mental y rendimiento académico.  
- Validar hipótesis sobre dependencia y efectos asociados.  
- Clasificar niveles de adicción mediante machine learning.  
- Detectar subgrupos de estudiantes con comportamientos similares.

---

## Tecnologías utilizadas

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**
- **Google Colab**

---

## Contenido del repositorio
- /notebooks → Notebook completo del análisis (.ipynb)
- /presentation → Presentación del informe (PDF)
- /requirements.txt → Librerías necesarias para reproducir el proyecto
- /data → Base de datos utilizados

---

## Principales hallazgos

- Los estudiantes que utilizan redes sociales más de **6 horas por día** muestran mayores niveles de conflictos interpersonales, peor salud mental y menos horas de sueño.

- El tiempo de uso diario es el **factor más determinante** para explicar la adicción: a partir de 4 horas de uso, los niveles de dependencia aumentan significativamente.

- La **edad y el género** influyen muy poco en el nivel de adicción; el patrón principal se explica casi exclusivamente por la cantidad de horas conectados.

- A partir de las **5–6 horas diarias**, la probabilidad de que el rendimiento académico se vea afectado se vuelve muy alta, llegando casi al 100% en los niveles de uso más intensos.

- Se identificaron dos grupos claros de estudiantes:
  - **Grupo no afectado:** menor uso, más horas de sueño y mejor salud mental.
  - **Grupo afectado:** mayor uso, menos descanso, peor salud mental y más conflictos.

- Las variables analizadas forman un ciclo consistente:  
  **más horas en redes → menos sueño → peor salud mental → más conflictos → mayor impacto académico.**
  
  ---

## Cómo reproducir el análisis

1. **Clonar o descargar** este repositorio.  
2. Instalar dependencias:  
   ```bash
   pip install -r requirements.txt
   
3. Ejecutar el notebook:

bash
/notebooks/Social_Media_Addiction.ipynb
