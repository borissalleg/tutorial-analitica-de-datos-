#**Semana 1: Conceptos Fundamentales del Análisis de Datos**


---

> 🎯 **Resultado de Aprendizaje de la Unidad:**  
> Identifica las etapas del proceso de análisis de datos, las fuentes y tipos de datos, y los métodos adecuados para su análisis.

> 📌 **Objetivos Específicos de la Semana 1:**
> 1. Comprender el concepto y la importancia del análisis de datos en la toma de decisiones.


???+ info "Conceptos Fundamentales"
    === "Que es el análisis de datos?"
        El **análisis de datos** es el proceso de inspeccionar, limpiar, transformar y modelar datos con el objetivo de descubrir información útil, llegar a conclusiones y apoyar la toma de decisiones.

        ```mermaid
        graph LR
            A[Datos Crudos] --> B[Procesamiento]
            B --> C[Análisis]
            C --> D[Insights]
            D --> E[Decisiones]
        ```
        === "Importancia en el Contexto Empresarial"

            | Beneficio | Descripción |
            | :--- | :--- |
            | **Toma de decisiones basada en evidencia** | Reduce la incertidumbre y el sesgo intuitivo, permitiendo fundamentar las estrategias en datos reales y verificables. |
            | **Identificación de oportunidades** | Detecta tendencias, patrones de mercado y nichos no explorados que pueden generar ventajas competitivas. |
            | **Optimización de procesos** | Mejora la eficiencia operativa al identificar cuellos de botella, desperdicios y áreas de mejora en los flujos de trabajo. |
            | **Predicción de escenarios** | Anticipa comportamientos futuros del mercado, clientes o variables económicas mediante modelos predictivos. |
            | **Reducción de riesgos** | Permite evaluar probabilidades de fracaso y diseñar planes de contingencia basados en evidencia histórica. |
            | **Personalización de la experiencia** | Facilita la segmentación de clientes para ofrecer productos, servicios y comunicaciones más relevantes. |
        
        === "Etapas del Proceso de Análisis de Datos"

            ```mermaid

                graph TD
                    A[1. Definición del Problema] --> B[2. Recolección de Datos]
                    B --> C[3. Limpieza y Preparación]
                    C --> D[4. Análisis Exploratorio]
                    D --> E[5. Modelado y Análisis]
                    E --> F[6. Visualización e Interpretación]
                    F --> G[7. Comunicación de Resultados]
                    G --> A


            ```
    === "Relación de la Analítica de Datos con la Estadística, la Econometría y el Machine Learning"
        Para un profesional en Negocios Internacionales, la analítica de datos no es una disciplina aislada, sino la integración de varias herramientas poderosas. Comprender la diferencia y sinergia entre ellas es clave para liderar proyectos de inteligencia comercial o expansión global.

        === "La Estadística"
            La estadística es la base de todo. Permite recolectar, organizar y resumir datos para entender qué está pasando en un mercado.

            **¿Qué hace?** Describe la realidad actual y pasada mediante promedios, varianzas y distribuciones.

            **Enfoque:** Rigor matemático para asegurar que los datos no mientan (muestreo, intervalos de confianza).

            **Ejemplo en Negocios Internacionales:** Analizar el promedio de exportaciones de café hacia la Unión Europea en los últimos 5 años e identificar los meses con mayor demanda (estacionalidad).

        === "La Econometría"
            La econometría aplica modelos estadísticos y matemáticos a datos económicos para probar teorías y medir el impacto de una variable sobre otra.

            **¿Qué hace?** Busca relaciones de causa y efecto. No solo dice qué pasa, sino por qué pasa y en qué medida.

            **Enfoque:** Control de variables macroeconómicas y microeconómicas para la toma de decisiones estratégicas.

        === "El Machine Learning"
            Es una rama de la Inteligencia Artificial donde los algoritmos aprenden de los datos históricos para identificar patrones complejos y automatizar decisiones sin ser programados explícitamente.

            **¿Qué hace?** Maximiza la precisión de las predicciones y la clasificación a gran escala (Big Data).

            **Enfoque:** Eficiencia predictiva y adaptabilidad del algoritmo ante nuevos datos.

            **Ejemplo en Negocios Internacionales:** Crear un modelo predictivo que analice en tiempo real el comportamiento de los consumidores en una plataforma de e-commerce global para recomendar productos específicos según su país de origen, o predecir el riesgo de impago de un cliente internacional.

        ## Cuadro Comparativo 

        | Disciplina | Pregunta Clave | Enfoque Principal | Aplicación Típica en Negocios Internacionales |
        | :--- | :--- | :--- | :--- |
        | **Estadística** | ¿Qué dicen los datos de nuestro histórico de ventas? | Resumen, descripción y validación de la muestra del mercado. | Reportes de exportaciones/importaciones, cálculo de participación de mercado y medias de consumo. |
        | **Econometría** | ¿El tipo de cambio causó la caída de las exportaciones? | Identificación de relaciones causales y validación de teorías económicas. | Análisis de riesgo país, evaluación del impacto de tratados comerciales y aranceles. |
        | **Machine Learning** | ¿Cuánto nos va a comprar este cliente el próximo mes? | Predicción a futuro, automatización y detección de patrones complejos en Big Data. | Optimización de la cadena de suministro global, detección de fraudes en aduanas y segmentación de clientes internacionales. |


???+ info "## 🛠️ Actividades Prácticas en Clase (Semana 1)"

    Para aplicar los conceptos fundamentales y entender cómo interactúan la estadística, la econometría y el machine learning en el comercio global, se realizarán las siguientes dos actividades interactivas.



    === "Actividad 1: El Tablero de Decisiones de Expansión Global (Taller en Equipo)"

        * **⏱️ Duración:** 60 minutos.
        * **👥 Formato:** Equipos de 3 a 4 estudiantes.
        * **🎯 Objetivo:** Aprender a identificar qué herramientas analíticas (Estadística, Econometría o Machine Learning) se requieren para resolver problemas específicos de una empresa que busca internacionalizarse.

        #### 📝 Descripción del Reto
        Los equipos asumirán el rol de **Consultores de Inteligencia Comercial** para una empresa multilatina de moda sostenible que desea expandirse a nuevos mercados (Europa o Asia). El profesor entregará o proyectará 3 "Preguntas de Negocio" críticas que la junta directiva necesita resolver. 

        Cada equipo deberá estructurar una propuesta en una hoja o pizarra respondiendo la siguiente matriz por cada pregunta:

        1.  **Pregunta 1:** ¿Cuál ha sido el volumen de importación de ropa orgánica en Alemania y Japón en los últimos 3 años y qué competidores dominan el mercado?
        2.  **Pregunta 2:** ¿Una reducción del 5% en los aranceles debido al nuevo Tratado de Libre Comercio aumentará nuestras exportaciones, o el impacto será absorbido por los costos del transporte marítimo?
        3.  **Pregunta 3:** ¿Cómo podemos personalizar automáticamente los productos que ven los usuarios en nuestra plataforma web global según el país desde donde se conectan y sus clics anteriores?

        #### 📊 Formato de Entrega en Clase
        Cada equipo dibujará y completará la siguiente tabla para sustentar sus respuestas ante el grupo:

        | Pregunta de Negocio | Disciplina Analítica Requerida | Justificación Estratégica | Tipo de Acción / Decisión a Tomar |
        | :--- | :--- | :--- | :--- |
        | **Pregunta 1** | *[Estadística / Econometría / ML]* | *¿Por qué esta herramienta?* | *¿Qué decisión se toma con esto?* |
        | **Pregunta 2** | *[Estadística / Econometría / ML]* | *¿Por qué esta herramienta?* | *¿Qué decisión se toma con esto?* |
        | **Pregunta 3** | *[Estadística / Econometría / ML]* | *¿Por qué esta herramienta?* | *¿Qué decisión se toma con esto?* |

        > 🗣️ **Plenaria (15 min):** El profesor seleccionará tres equipos al azar para que defiendan su elección de disciplina ante la junta directiva (el resto de la clase).

        ---

    === "Actividad 2: "Del Caos al Insight" - Mapeo del Proceso Analítico (Caso de Estudio Express)"

        * **⏱️ Duración:** 45 minutos.
        * **👥 Formato:** Parejas.
        * **🎯 Objetivo:** Rastrear y ordenar las **Etapas del Proceso de Análisis de Datos** utilizando un escenario real de la cadena de suministro internacional.

        #### 📝 Descripción del Reto
        Se le presentará a los estudiantes la historia de **"ExportFresh"**, una empresa exportadora de frutas que sufrió pérdidas millonarias el mes pasado porque un contenedor de aguacates (paltas) llegó descompuesto a su destino en Róterdam debido a fallas en la cadena de frío.

        El profesor entregará los siguientes 7 hitos del caso desordenados. Las parejas deberán asociar cada hito con la **Etapa del Proceso de Análisis de Datos** correcta y ordenarlos cronológicamente:

        * **Hito A:** El analista crea un gráfico de líneas interactivo donde se muestra claramente el momento exacto en que la temperatura del contenedor subió de los 6°C óptimos.
        * **Hito B:** El Director de Logística define la pregunta central: ¿Por qué se perdió la cadena de frío y cómo evitamos que vuelva a pasar en los próximos envíos?
        * **Hito C:** Se descargan los archivos CSV con los registros automáticos de los sensores de temperatura del contenedor, facturas de la naviera y reportes de aduanas.
        * **Hito D:** El equipo de datos presenta un informe ejecutivo a la gerencia general recomendando cambiar de proveedor logístico marítimo por alta variabilidad de temperatura.
        * **Hito E:** Se eliminan los registros duplicados, se corrigen las fechas mal formateadas por el huso horario internacional y se rellenan los datos vacíos donde el sensor perdió señal por 10 minutos.
        * **Hito F:** Se ejecuta un cálculo estadístico rápido para ver la temperatura mínima, máxima y el promedio del viaje, notando anomalías en el día 4 del trayecto.
        * **Hito G:** Se corre un modelo predictivo para evaluar la probabilidad de fallo de los contenedores de la naviera actual frente a una nueva opción en el mercado.

        #### 🔑 Guía de Solución (Para el Profesor / Autoevaluación)
        Los estudiantes deberán presentar su solución en este formato (aquí el orden correcto):

        | Orden | Etapa del Proceso | Hito del Caso |
        | :---: | :--- | :---: |
        | **1** | 1. Definición del Problema | **Hito B** |
        | **2** | 2. Recolección de Datos | **Hito C** |
        | **3** | 3. Limpieza y Preparación | **Hito E** |
        | **4** | 4. Análisis Exploratorio | **Hito F** |
        | **5** | 5. Modelado y Análisis | **Hito G** |
        | **6** | 6. Visualización e Interpretación | **Hito A** |
        | **7** | 7. Comunicación de Resultados | **Hito D** |