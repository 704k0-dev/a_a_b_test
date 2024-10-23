## An�lisis del Embudo de Ventas y Test A/A/B para una Empresa Alimenticia

Este proyecto tiene como objetivo investigar el comportamiento de los usuarios y las usuarias en una aplicaci�n de una empresa emergente que vende productos alimenticios. El an�lisis incluye dos fases principales: estudiar el embudo de ventas y analizar los resultados de un test A/A/B.

### Descripci�n del Proyecto

La empresa necesita entender mejor c�mo sus usuarios interact�an con la aplicaci�n, especialmente en el contexto del proceso de compra. El an�lisis aborda dos aspectos fundamentales:

1. **Embudo de ventas**: 
   - El objetivo es descubrir c�mo los usuarios llegan a la etapa de compra dentro de la aplicaci�n.
   - Preguntas clave:
     - �Cu�ntos usuarios realmente llegan a la etapa de compra?
     - �Cu�ntos usuarios se quedan atascados en etapas anteriores?
     - �Cu�les son las etapas espec�ficas donde se observa mayor fricci�n?

2. **An�lisis de Test A/A/B**:
   - El equipo de dise�o est� evaluando cambiar las fuentes tipogr�ficas en toda la aplicaci�n, pero existe la preocupaci�n de que los cambios afecten negativamente la experiencia del usuario.
   - Para tomar una decisi�n basada en datos, se ha realizado un test A/A/B. Los usuarios se han dividido en tres grupos:
     - **Grupo A**: Control, con las fuentes antiguas.
     - **Grupo A (duplicado)**: Otro grupo de control con las mismas fuentes antiguas, para validar la consistencia de los resultados.
     - **Grupo B**: Grupo de prueba, que experimenta las nuevas fuentes.
   - El an�lisis busca responder:
     - �Qu� conjunto de fuentes produce mejores resultados en t�rminos de conversi�n y uso de la aplicaci�n?
     - �Existen diferencias significativas entre los dos grupos A de control? Si es as�, �qu� factores est�n influyendo en estos resultados?

### Ventajas de dos grupos A

El uso de dos grupos de control tiene ciertas ventajas clave:
- Permite asegurar que los resultados sean fiables y precisos. Si hay diferencias significativas entre los dos grupos A, esto puede se�alar problemas subyacentes en el experimento o factores que est�n afectando los resultados.
- Ayuda a estimar la cantidad de tiempo y datos necesarios para futuros tests, mejorando la planificaci�n de experimentos posteriores.

### Dataset Utilizado

El dataset contiene informaci�n sobre el comportamiento de los usuarios en la aplicaci�n y se utilizar� tanto para el an�lisis del embudo de ventas como para el test A/A/B.

### Contenidos del Proyecto

- **`notebooks/`**: Contiene los notebooks donde se realiza el an�lisis completo del embudo de ventas y el test A/A/B.
- **`datasets/`**: Incluye los datos utilizados en el an�lisis (si es posible compartirlos).
- **`environment.yml`**: Archivo con las dependencias necesarias para reproducir el entorno.
- **`README.md`**: Este archivo con la descripci�n general del proyecto.

### Instalaci�n y Uso

Para reproducir este an�lisis, sigue los siguientes pasos:

1. Clona este repositorio:
   ```bash
   git clone https://github.com/704k0-dev/a_a_b_test.git
   ```

2. Crea un entorno de Conda e instala las dependencias:
   ```bash
   conda env create -f environment.yml
   conda activate nombre_entorno
   ```

3. Abre Jupyter Notebook y explora los an�lisis:
   ```bash
   jupyter notebook
   ```

### Conclusiones del Proyecto

Los resultados de este an�lisis permiten a la empresa comprender mejor el comportamiento de sus usuarios en el embudo de ventas y tomar decisiones basadas en datos respecto a los cambios de dise�o en la aplicaci�n. En particular:
- Se identificaron puntos clave donde los usuarios tienden a quedarse atascados en el embudo de ventas, proporcionando �reas claras de mejora.
- Los resultados del test A/A/B demostraron que las nuevas fuentes tipogr�ficas no tuvieron un impacto negativo en la tasa de conversi�n, lo que sugiere que es seguro implementar el nuevo dise�o en toda la aplicaci�n.

### Licencia

Este proyecto est� licenciado bajo la MIT License - ver el archivo LICENSE para m�s detalles.