<div align="center">

# Hola, soy Diego Trascasa García 👋

### Analista de datos · Ingeniero de la Salud

Convierto datos sanitarios en información útil: desde la señal de un sensor o un Excel oficial desordenado hasta un panel interactivo que cualquiera puede entender.

**Busco mi primer puesto como analista de datos, idealmente en el sector sanitario.**

[![Web](https://img.shields.io/badge/Web-diegotraski.github.io-B3223D?style=for-the-badge&logo=googlechrome&logoColor=white)](https://diegotraski.github.io)
[![CV](https://img.shields.io/badge/CV-PDF-16202E?style=for-the-badge&logo=readdotcv&logoColor=white)](https://diegotraski.github.io/cv-diego-trascasa.pdf)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Diego_Trascasa_García-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/diego-trascasa-garc%C3%ADa-b171382b2/)
![Ubicación](https://img.shields.io/badge/Burgos,_España-555555?style=for-the-badge&logo=googlemaps&logoColor=white)

<sub>🇬🇧 Health Engineering graduate and IBM-certified Data Analyst. I turn healthcare data into clear, usable insight with Python, SQL and interactive dashboards. Looking for my first data analyst role, ideally in healthcare.</sub>

</div>

---

## 📊 Proyectos de datos y salud

### 🏥 [Observatorio de la Sanidad en Castilla y León](https://github.com/diegotraski/observatorio-sanidad-cyl) · [Demo](https://observatorio-sanidad-cyl-tmj3fejzr594gvoczadj5x.streamlit.app/)

Análisis de las listas de espera de los 14 hospitales públicos de Castilla y León con datos oficiales de Sacyl y del INE (2018-2026).

- **Pipeline reproducible:** descarga 56 Excel trimestrales, los limpia con controles de calidad y los carga en una base de datos SQL con un solo comando.
- **Hallazgos:** la lista quirúrgica ha crecido un **33 % en el primer semestre de 2026**, y Burgos tiene un **29 % más de espera por habitante** que la media.
- **Previsión y dashboard:** previsión a 12 meses validada frente a modelos simples, y un dashboard con mapa y un **asistente de IA que responde preguntas convirtiéndolas en SQL** de solo lectura.

`Python` `pandas` `SQL (SQLite)` `Jupyter` `Plotly` `Streamlit` `statsmodels` `IA generativa` `pytest`

### 💓 [Monitor cardíaco con clasificación de latidos](https://github.com/diegotraski/ecg-monitor-tfg) · *Trabajo Fin de Grado*

Monitor de ECG de bajo coste: un Arduino capta la señal y una app web la muestra en tiempo real y clasifica los latidos con **Random Forest (97,5 % de exactitud en MIT-BIH)**. Las sesiones se guardan en SQLite y se exportan a CSV.

`Python` `scikit-learn` `Streamlit` `SQLite` `Arduino` `Procesado de señales`

### 🦵 [MotionClin](https://github.com/diegotraski/motionclin) · [Demo](https://diegotraski.github.io/motionclin/)

Del vídeo del móvil a un informe clínico, en el navegador y sin que el vídeo salga del dispositivo: marcha, sentadilla, levantarse de la silla y equilibrio.

- **De la señal al dato:** 33 puntos del cuerpo por fotograma con visión artificial, filtrado de fase cero, detección de eventos y métricas por ciclo con su **media ± DE, n y fiabilidad**.
- **Estadística con criterio clínico:** compara sesiones con **t de Welch y d de Cohen**, y solo habla de mejora si supera el cambio mínimo relevante. Referencias de laboratorio de **235 personas sanas** según edad y velocidad.
- **Verificado y listo para validar:** error medio de **0,24 pasos/min** en cadencia con 30 sujetos simulados por prueba; protocolo de validación con Bland-Altman e ICC; 25 pruebas automáticas.
- **Informes:** PDF técnico para el fisioterapeuta y de una página, con semáforo, para el paciente. App en español e inglés.

`JavaScript` `MediaPipe` `Visión artificial` `Procesado de señales` `Estadística` `PWA`

---

## 🛠️ Aplicaciones con datos (de principio a fin)

| Proyecto | Qué hace | Tecnologías |
|---|---|---|
| ⛽ **[GasolinaNeta](https://github.com/diegotraski/gasolinaneta)** · [Demo](https://gasolinaneta.vercel.app) | Compara gasolineras y puntos de recarga por **ahorro neto** con los precios oficiales del Ministerio (11.000+ estaciones) y rutas reales. | Next.js · TypeScript · Supabase · MapLibre |
| ⚔️ **[Elektro Scout](https://github.com/diegotraski/elektro-scout)** · [Demo](https://elektro-scouting-new-xovn.vercel.app) | Convierte cientos de ataques de torneos de Clash of Clans en estadísticas de rendimiento por ejército, jugador y equipo. | Next.js · Supabase · Recharts |
| 🐠 **[Acuario NFC](https://github.com/diegotraski/acuario-nfc)** · [Demo](https://acuario-nfc.vercel.app/?demo=1) | Registra el mantenimiento del acuario tocando etiquetas NFC con el móvil. | Next.js · Supabase · PWA |

---

## 🧰 Herramientas

**Análisis de datos**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

**Visualización y dashboards**

![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Recharts](https://img.shields.io/badge/Recharts-22B5BF?style=flat-square)
![IBM Cognos](https://img.shields.io/badge/IBM_Cognos-052FAD?style=flat-square&logo=ibm&logoColor=white)

**Estadística y Machine Learning**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-4051B5?style=flat-square)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![IA generativa](https://img.shields.io/badge/IA_generativa-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

**Bases de datos y desarrollo**

![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)

---

## 🎓 Formación

- **IBM Data Analyst Professional Certificate** (2026): Python, pandas, SQL, visualización, dashboards, Excel/Cognos e IA generativa.
- **Grado en Ingeniería de la Salud**, Universidad de Burgos (2020-2025). TFG: monitor cardíaco con clasificación de latidos mediante Machine Learning.

---

<div align="center">

📫 **¿Hablamos?** Escríbeme por [LinkedIn](https://www.linkedin.com/in/diego-trascasa-garc%C3%ADa-b171382b2/) o a diego.tragar@gmail.com · Todo mi trabajo en [diegotraski.github.io](https://diegotraski.github.io)

</div>
