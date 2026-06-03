# Álgebra y Matemática Discreta aplicada a la Investigación Médica

Este repositorio constituye un entorno formal de desarrollo e investigación donde se intersectan las estructuras de la matemática pura con la analítica de datos avanzada. El objetivo principal es desmantelar la complejidad de los fundamentos algebraicos y discretos, no como abstracciones teóricas, sino como herramientas de software aplicadas a la modelización y optimización de variables clínicas.

## 🩺 El Caso de Estudio: Pima Indians Diabetes Dataset

Para dotar al repositorio de un propósito empírico y un impacto real en la salud pública, se ha seleccionado el dataset **Pima Indians Diabetes** (proveniente del *National Institute of Diabetes and Digestive and Kidney Diseases*). La elección de esta cohorte específica responde a criterios metodológicos rigurosos:

* **Naturaleza de los Datos**: El dataset presenta una estructura limpia pero compleja de variables predictoras continuas y discretas (niveles de glucosa en plasma, presión arterial, grosor del pliegue cutáneo del tríceps, insulina sérica, índice de masa corporal y una función de pedigrí de la diabetes) correlacionadas con una variable binaria de desenlace clínico.
* **Desafío Analítico**: Representa un escenario ideal para evaluar la estabilidad de algoritmos de optimización y clasificación ante la presencia de correlaciones no lineales, datos faltantes implícitos (ceros estructurales) y la necesidad de separar patrones predictivos claros en entornos de alta vulnerabilidad biológica.

## 🔬 Plan de Trabajo y Ópticas Matemáticas

La investigación se despliega a lo largo de diez módulos independientes. Cada unidad temática abordará el dataset Pima Indians desde una perspectiva matemática y computacional única, implementada en notebooks interactivos de Python:

1.  **Métodos de Prueba e Inducción Completa**: Formalización de hipótesis analíticas y validación de predicados lógicos sobre las reglas de consistencia de los datos biomédicos.
2.  **Teoría de Conjuntos**: Segmentación y álgebra de eventos basada en perfiles de riesgo. Mapeo de subpoblaciones clínicas combinando criterios de exclusión e inclusión funcional.
3.  **Teoría de Números**: Implementación de funciones de dispersión criptográfica (hashing) para la anonimización de registros médicos y optimización de índices a nivel de base de datos.
4.  **Operaciones con Matrices**: Álgebra lineal computacional aplicada a la transformación del espacio de características del dataset, calculando matrices de covarianza y transformaciones afines.
5.  **Relaciones**: Modelado de estructuras de orden y equivalencia entre pacientes, evaluando niveles de proximidad en función de sus perfiles sintomáticos mediante matrices de relación.
6.  **Eliminación Gaussiana**: Resolución de sistemas de ecuaciones lineales para determinar los coeficientes base y balance de sistemas de ponderación en modelos predictivos lineales.
7.  **Programación Lineal**: Modelado matemático de restricciones y fronteras metabólicas, estableciendo regiones factibles para la optimización de recursos analíticos.
8.  **Algoritmo Simplex**: Optimización lineal computacional orientada a la minimización de funciones de costo y maximización de la eficiencia en la clasificación multivariada de variables de riesgo.
9.  **Teoría de Grafos**: Construcción de redes de correlación donde las variables clínicas operan como nodos y las dependencias estadísticas determinan las aristas, analizando la topología de la enfermedad.
10. **Árboles**: Construcción e implementación desde cero de estructuras jerárquicas y árboles de decisión para el trazado de flujos diagnósticos y la clasificación lógica del estado de salud de los pacientes.

## 📁 Estructura del Proyecto

* **`data/`**: Almacenamiento local aislado del dataset Pima Indians y matrices de control.
* **`notebooks/`**: Cuadernos interactivos indexados donde se ejecuta el análisis paso a paso.
* **`src/` Módulos**: Scripts reutilizables y algoritmos core en Python puro para cada óptica matemática.

---

## 🎓 Certificaciones y Respaldo Académico

Este entorno de desarrollo y la rigurosidad aplicada en su diseño visual y conceptual se sustentan en una trayectoria de formación continua en tecnologías analíticas y comunicación visual:

* **Diseño Gráfico Certificado (Escuela de Diseño y Comunicación BIOS)**: Formación avanzada orientada a la síntesis visual, maquetación limpia de interfaces de datos y estructuración profesional de soportes digitales.

*(Nota: La documentación de soporte, el programa analítico de la certificación y las credenciales académicas se encuentran digitalizados y disponibles para su auditoría en la raíz del repositorio o mediante el control de versiones local).*

```bash
# Para clonar el entorno e instalar dependencias:
git clone [https://github.com/mvikips/algebra-matematica-discreta.git](https://github.com/mvikips/algebra-matematica-discreta.git)
pip install -r requirements.txt

