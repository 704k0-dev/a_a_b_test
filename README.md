## Análisis del Embudo de Ventas y Test A/A/B para una Empresa Alimenticia

Este proyecto tiene como objetivo investigar el comportamiento de los usuarios y las usuarias en una aplicación de una empresa emergente que vende productos alimenticios. El análisis incluye dos fases principales: estudiar el embudo de ventas y analizar los resultados de un test A/A/B.

### Descripción del Proyecto

La empresa necesita entender mejor cómo sus usuarios interactúan con la aplicación, especialmente en el contexto del proceso de compra. El análisis aborda dos aspectos fundamentales:

1. **Embudo de ventas**: 
   - El objetivo es descubrir cómo los usuarios llegan a la etapa de compra dentro de la aplicación.
   - Preguntas clave:
     - ¿Cuántos usuarios realmente llegan a la etapa de compra?
     - ¿Cuántos usuarios se quedan atascados en etapas anteriores?
     - ¿Cuáles son las etapas específicas donde se observa mayor fricción?

2. **Análisis de Test A/A/B**:
   - El equipo de diseño está evaluando cambiar las fuentes tipográficas en toda la aplicación, pero existe la preocupación de que los cambios afecten negativamente la experiencia del usuario.
   - Para tomar una decisión basada en datos, se ha realizado un test A/A/B. Los usuarios se han dividido en tres grupos:
     - **Grupo A**: Control, con las fuentes antiguas.
     - **Grupo A (duplicado)**: Otro grupo de control con las mismas fuentes antiguas, para validar la consistencia de los resultados.
     - **Grupo B**: Grupo de prueba, que experimenta las nuevas fuentes.
   - El análisis busca responder:
     - ¿Qué conjunto de fuentes produce mejores resultados en términos de conversión y uso de la aplicación?
     - ¿Existen diferencias significativas entre los dos grupos A de control? Si es así, ¿qué factores están influyendo en estos resultados?

### Ventajas de dos grupos A

El uso de dos grupos de control tiene ciertas ventajas clave:
- Permite asegurar que los resultados sean fiables y precisos. Si hay diferencias significativas entre los dos grupos A, esto puede señalar problemas subyacentes en el experimento o factores que están afectando los resultados.
- Ayuda a estimar la cantidad de tiempo y datos necesarios para futuros tests, mejorando la planificación de experimentos posteriores.

### Dataset Utilizado

El dataset contiene información sobre el comportamiento de los usuarios en la aplicación y se utilizará tanto para el análisis del embudo de ventas como para el test A/A/B.

### Contenidos del Proyecto

- **`notebooks/`**: Contiene los notebooks donde se realiza el análisis completo del embudo de ventas y el test A/A/B.
- **`datasets/`**: Incluye los datos utilizados en el análisis (si es posible compartirlos).
- **`environment.yml`**: Archivo con las dependencias necesarias para reproducir el entorno.
- **`README.md`**: Este archivo con la descripción general del proyecto.

### Instalación y Uso

Para reproducir este análisis, sigue los siguientes pasos:

1. Clona este repositorio:
   ```bash
   git clone https://github.com/704k0-dev/a_a_b_test.git
   ```

2. Crea un entorno de Conda e instala las dependencias:
   ```bash
   conda env create -f environment.yml
   conda activate nombre_entorno
   ```

3. Abre Jupyter Notebook y explora los análisis:
   ```bash
   jupyter notebook
   ```

### Conclusiones del Proyecto

Los resultados de este análisis permiten a la empresa comprender mejor el comportamiento de sus usuarios en el embudo de ventas y tomar decisiones basadas en datos respecto a los cambios de diseño en la aplicación. En particular:
- Se identificaron puntos clave donde los usuarios tienden a quedarse atascados en el embudo de ventas, proporcionando áreas claras de mejora.
- Los resultados del test A/A/B demostraron que las nuevas fuentes tipográficas no tuvieron un impacto negativo en la tasa de conversión, lo que sugiere que es seguro implementar el nuevo diseño en toda la aplicación.

### Licencia

Este proyecto está licenciado bajo la MIT License - ver el archivo LICENSE para más detalles.