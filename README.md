






# 🔪 Proyecto Power BI: Análisis de Asesinos en Serie


# 🇬🇧 English Version

> If you prefer to read this README in English, click here:  
- 🔗 **[View English version](#-power-bi-project-serial-killers-analysis)**





## 🕵️‍♀️ Autoras  
- Nuria Salas Vázquez  
- Cibele Busnello

---

## 🧠 Descripción del proyecto

Este proyecto explora el fenómeno de los asesinos en serie mediante visualizaciones basadas en dos datasets recopilados de Wikipedia:

- 🧷 **Dataset original en Kaggle: [Wikipedia Serial Killers Dataset](https://www.kaggle.com/datasets/dante890b/wikipedia-serial-killers-list)**



### Columnas del DataFrame 'victims'

Este DataFrame contiene información sobre asesinos en serie a nivel mundial. A continuación se describen las columnas disponibles:

| Nombre de la columna                           | Descripción                                                                |
|------------------------------------------------|----------------------------------------------------------------------------|
| **Name**                                       | Nombre del asesino en serie.                                               |
| **Killer Type**                                | Clasificación del tipo de asesino (mujer, hombre, grupo de hombres...).    |
| **Country**                                    | País donde cometió los crímenes.                                           |
| **Country Sorted**                             | Variante estandarizada del país para facilitar análisis.                   |
| **Continent**                                  | Continente correspondiente al país.                                        |
| **Start Year**                                 | Año en el que comenzó su actividad criminal.                               |
| **End Year**                                   | Año en el que terminó su actividad criminal.                               |
| **Median Year**                                | Año medio entre el inicio y el fin de su actividad.                        |
| **Years Active**                               | Duración (en años) durante los que estuvo activo.                          |
| **Decade**                                     | Década principal en la que cometió los crímenes.                           |
| **Total Victims (Unproven + Proven)**          | Total de víctimas, incluyendo casos no probados.                           |
| **Unproven Possible Victims**                  | Estimación de víctimas no confirmadas.                                     |
| **Proven Victims**                             | Número de víctimas confirmadas oficialmente.                               |
| **Notes**                                      | Notas adicionales o información relevante sobre el caso.                   |
          


### Columnas del DataFrame 'profile' 

Este documento describe el significado de cada columna en el dataset relacionado con asesinos en serie.

| Nombre de la Columna                           | Descripción                                                                 |
|------------------------------------------------|-----------------------------------------------------------------------------|
| **Name**                                       | Nombre completo del individuo.                                              |
| **Nicknames**                                  | Alias o apodos por los que es conocido el individuo.                        |
| **Age**                                        | Edad del individuo al momento de su muerte o actual si sigue vivo.          |
| **Born Date**                                  | Fecha de nacimiento del individuo.                                          |
| **Born Location**                              | Ciudad o región donde nació el individuo.                                   |
| **Born Country**                               | País de nacimiento del individuo.                                           |
| **Continent**                                  | Continente donde nació el individuo.                                        |
| **Died Date**                                  | Fecha de fallecimiento (si está muerto).                                    |
| **Died Location**                              | Lugar donde falleció el individuo.                                          |
| **Date Apprehended**                           | Fecha en la que fue arrestado el individuo.                                 |
| **Apprehended Age**                            | Edad al momento del arresto.                                                | 
| **Conviction**                                 | Delitos por los que fue condenado el individuo.                             |
| **Criminal Penalty**                           | Castigo o sentencia recibida (ej. cadena perpetua, pena de muerte).         |
| **Criminal Penalty Categories**                | Clasificación general de la condena (ej. Muerte, Cadena perpetua, Prisión). |
| **Zodiac Sign**                                | Signo del zodiaco según la fecha de nacimiento.                             |





---

## 🧹🔍 Proceso

1. 🗂️ Descarga de los datos desde Kaggle  
2. 🧼 Limpieza y análisis exploratorio (EDA) en Python con VS Code  
3. 📊 Visualización y diseño de dashboard en Power BI (incluyendo versión móvil)

---

## 🧾 Visualizaciones destacadas

- 🔢 Big Numbers: víctimas confirmadas y posibles, número de asesinos, países implicados  
- 🗺️ Mapas: lugar de nacimiento y país de actividad criminal  
- 📉 Gráficos:
  - Asesinatos por asesino
  - Asesinatos por país
  - Número de asesinos por país  
- 🩸 **Top 15 asesinos más sangrientos:** ficha técnica con apodo, crimen, pena y datos personales  
- 🚻 Clasificación: hombre, mujer, grupos de hombres, parejas

---

## 🧨 Principales conclusiones

- EE.UU. y Europa concentran la mayoría de los casos  
- Perfil predominante: hombre que actúa solo  
- Algunos casos registran décadas de actividad y decenas de víctimas
- Más de la mitad de las victimas sin confirmar. Un escalofriante recordatorio de todo lo que aún no sabemos y de cuántas     historias quizás nunca se cuenten.

---

## 📁 Enlaces

- 🔗 **[Ver informe en Power BI](https://github.com/CibiPB/project-da-promo-49-modulo-4/raw/main/Power%20BI/Final%20Project.pbix)**

- 🐙 **Repositorio en GitHub: [Ver proyecto en GitHub](https://github.com/CibiPB/project-da-promo-49-modulo-4)**




---

## 🎯 Público objetivo

- 🔍 Aficionados a la criminología  
- 🧑‍🏫 Estudiantes y analistas de datos  
- 🧪 Profesionales que evalúan competencias en Power BI

---

## 🧰 Herramientas

- 🐍 Python  
- 💻 Visual Studio Code  
- 📊 Power BI (desktop y mobile)

---


# 🔪 Power BI Project: Serial Killers Analysis

## 🕵️‍♀️ Authors  
- Nuria Salas Vázquez  
- Cibele Busnello

---

## 🧠 Project Description

This project explores the phenomenon of serial killers using data visualization based on two Wikipedia datasets:

- 🧷 **Original dataset on Kaggle: [Wikipedia Serial Killers Dataset](https://www.kaggle.com/datasets/dante890b/wikipedia-serial-killers-list)**


### 'victims' DataFrame Columns

This DataFrame contains information about serial killers around the world. The following are the columns included:

| Column Name                                    | Description                                                                |
|------------------------------------------------|----------------------------------------------------------------------------|
| **Name**                                       | Name of the serial killer.                                                 |
| **Killer Type**                                | Classification of killer type (male, female, male-grouos....).             |
| **Country**                                    | Country where the crimes were committed.                                   |
| **Country Sorted**                             | Standardized version of country name for sorting/analysis.                 |
| **Continent**                                  | Continent where the country is located.                                    |
| **Start Year**                                 | Year when the criminal activity started.                                   |
| **End Year**                                   | Year when the criminal activity ended.                                     |
| **Median Year**                                | Median year between start and end of activity.                             |
| **Years Active**                               | Number of years the killer was active.                                     |
| **Decade**                                     | Main decade in which the crimes took place.                                |
| **Total Victims (Unproven + Proven)**          | Total number of victims (including unproven cases).                        |
| **Unproven Possible Victims**                  | Estimated number of unconfirmed victims.                                   |
| **Proven Victims**                             | Number of officially confirmed victims.                                    |
| **Notes**                                      | Additional notes or relevant case details.                                 |




### 'profile' DataFrame columns

This document describes the meaning of each column in the dataset related to serial killers.

| Column Name                                     | Description                                                                 |
|-------------------------------------------------|-----------------------------------------------------------------------------|
| **Name**                                        | Full name of the individual.                                                |
| **Nicknames**                                   | Aliases or nicknames the individual is known by.                            |
| **Age**                                         | The age of the individual at the time of death or currently, if still alive.|
| **Born Date**                                   | The birth date of the individual.                                           |
| **Born Location**                               | The city or region where the individual was born.                           |
| **Born Country**                                | The country where the individual was born.                                  |
| **Continent**                                   | The continent where the individual was born.                                |
| **Died Date**                                   | The date of death of the individual (if deceased).                          | 
| **Died Location**                               | The location where the individual died.                                     |
| **Date Apprehended**                            | The date when the individual was arrested.                                  |
| **Apprehended Age**                             | Age of the individual at the time of apprehension.                          |
| **Conviction**                                  | Crimes or charges the individual was convicted of.                          |
| **Criminal Penalty**                            | The punishment or sentence received (e.g., life imprisonment, death penalty)|
| **Criminal Penalty Categories**                 | General classification of the penalty (e.g., Death, Life, Prison).          |
| **Zodiac Sign**                                 | Astrological sign based on the date of birth.                               |


---

## 🧹🔍 Process

1. 🗂️ Download data from Kaggle  
2. 🧼 Clean and explore (EDA) with Python in VS Code  
3. 📊 Create Power BI dashboard (with mobile view)

---

## 🧾 Highlighted Visuals

- 🔢 Big Numbers: confirmed/possible victims, number of killers, countries  
- 🗺️ Maps: birthplaces and countries of activity  
- 📉 Charts:
  - Murders per killer
  - Murders per country
  - Killers per country  
- 🩸 **Top 15 deadliest killers:** nickname, crime type, sentence, and personal facts  
- 🚻 Classification: male, female, male groups, couples

---

## 🧨 Main Insights

- Most cases are in the U.S. and Europe  
- Male solo killers dominate  
- Some have dozens of victims over decades
- More than half of the victims remain unconfirmed — a chilling reminder of how much we still don't know, and how many stories may never be told.
---

## 📁 Links

- 🔗 **[View Power BI Report](https://github.com/CibiPB/project-da-promo-49-modulo-4/raw/main/Power%20BI/Final%20Project.pbix)**

- 🐙 **GitHub Repository: [View project on GitHub](https://github.com/CibiPB/project-da-promo-49-modulo-4)**

---

## 🎯 Target Audience

- 🔍 Criminology enthusiasts  
- 📊 Data students and professionals  
- 🧪 Power BI recruiters/trainers

---

## 🧰 Tools Used

- 🐍 Python  
- 💻 Visual Studio Code  
- 📊 Power BI
"""