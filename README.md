# 📊 Proyecto CRISP-DM: Prevención de Fuga de Clientes (Telco Churn)

**Autor:** Benjamín Naveas  
**Institución:** Instituto Profesional Santo Tomás, Sede Arica  
**Asignatura:** IEI-097 Minería de Datos (Unidad I)  

## 📝 Descripción del Proyecto
Este repositorio contiene el análisis exploratorio y modelado de datos para identificar patrones de abandono de clientes (Churn) en una empresa de telecomunicaciones. El desarrollo sigue estrictamente las fases de la metodología **CRISP-DM** (Cross-Industry Standard Process for Data Mining). 

A través del procesamiento de datos, se aplicaron dos técnicas de representación del conocimiento: **Reglas de Asociación** (algoritmo Apriori) y un **Árbol de Decisión**, con el fin de traducir relaciones matemáticas complejas en reglas de negocio claras y aplicables para la retención de clientes.

## 🛠️ Tecnologías y Librerías Utilizadas
* **Entorno de desarrollo:** Google Colab / Python 3
* **Manipulación de datos:** `pandas`
* **Visualización:** `matplotlib`, `seaborn`
* **Modelado y Minería:** `scikit-learn` (Árboles de Decisión), `mlxtend` (Reglas de Asociación)

## 🚀 Instrucciones de Ejecución (Google Colab)

1. Abre `EvaluacionU1_Naveas_Benjaminn.ipynb` en [Google Colab](https://colab.research.google.com/) con el botón **Open in Colab** del notebook (o desde *Archivo → Abrir cuaderno → GitHub*).
2. Selecciona **Entorno de ejecución → Ejecutar todo**.

El notebook usa el archivo `WA_Fn-UseC_-Telco-Customer-Churn.csv` si está en la sesión y, si no, lo descarga automáticamente desde este repositorio, por lo que no es necesario subirlo a mano.

*Nota: cada salida de código va seguida de una celda de texto con su interpretación.*
