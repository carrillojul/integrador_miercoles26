# integrador_miercoles26
proyecto integrador 2026-1 - analisis de datos

##Integrantes
Julio Carrillo
Camila Ortiz
Isaac Castañeda
Felipe Valencia

# 🧠💰 Zent - Análisis de Gastos Hormiga con Python

Zent es un proyecto educativo enfocado en el análisis de datos personales para la **gestión y control de gastos hormiga** 🪙.
Este repositorio contiene el módulo de análisis desarrollado en **Python**, utilizando herramientas de ciencia de datos para transformar información financiera en insights accionables.

---

## 📌 Descripción

En el día a día, pequeños gastos pueden pasar desapercibidos pero tener un gran impacto en las finanzas personales.
Zent busca ayudarte a:

* 📊 Identificar patrones de gasto
* 🔍 Detectar gastos innecesarios
* 📈 Generar reportes claros y útiles
* 💡 Tomar decisiones financieras más inteligentes

Este módulo forma parte de una solución completa que integra:

* 🐍 Python → Análisis de datos
* ⚛️ React → Frontend interactivo
* ☕ Spring Boot → Backend robusto

---

## ⚙️ Tecnologías utilizadas

* 🐍 Python 3.x
* 📊 Pandas
* 📈 NumPy (opcional)
* 📉 Matplotlib
* 🎨 Seaborn

---

## 🚀 Instalación

Sigue estos pasos para configurar el entorno:

```bash
# 1. Clonar el repositorio
git clone https://github.com/tu-usuario/zent-python.git

# 2. Entrar al directorio
cd zent-python

# 3. Crear entorno virtual (opcional pero recomendado)
python -m venv venv

# 4. Activar entorno virtual
# En Windows:
venv\Scripts\activate
# En macOS/Linux:
source venv/bin/activate

# 5. Instalar dependencias
pip install pandas numpy matplotlib seaborn
```

---

## 📂 Estructura del proyecto

```
zent-python/
│
├── data/              # 📁 Datos de entrada (CSV, Excel, etc.)
├── notebooks/         # 📓 Análisis exploratorio
├── src/               # 🧩 Código fuente
│   ├── cleaning.py
│   ├── analysis.py
│   └── visualization.py
├── outputs/           # 📊 Resultados y reportes
└── README.md
```

---

## 📊 Ejemplo de uso

```python
import pandas as pd

# Cargar datos
df = pd.read_csv("data/gastos.csv")

# Ver resumen
print(df.describe())

# Agrupar gastos por categoría
gastos_categoria = df.groupby("categoria")["monto"].sum()

print(gastos_categoria)
```

---

## 🎯 Objetivo educativo

Este proyecto busca fortalecer habilidades en:

* 🧠 Análisis de datos
* 🐍 Programación en Python
* 📊 Visualización de información
* 🏗️ Arquitectura de aplicaciones modernas

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! 🚀
Puedes abrir issues o enviar pull requests para mejorar el proyecto.

---

## 📜 Licencia

Este proyecto es de uso educativo 📚.

---

## ✨ Autor

Desarrollado como parte de un proyecto integral de aprendizaje en análisis de datos y desarrollo full stack.

---

💡 *"Lo que no se mide, no se puede mejorar."*
