# Políticas 2050 - Microdesafío Semana 8

Este proyecto consiste en la manipulación, anonimización y carga de datos relacionados con las políticas de reducción de CO2 para el año 2050. El desafío incluye la transformación de un archivo CSV, la anonimización de ciertos campos sensibles, y la carga de los datos anonimizados en una base de datos Amazon Redshift.

## Estructura del Proyecto

- **Datos_Microdesafio_Semana8_DE.csv**: El archivo CSV original que contiene los datos de entrada.
- **temp_data.csv**: El archivo CSV generado que contiene los datos anonimizados y listos para ser cargados en Redshift.
- **env.example**: Un ejemplo del archivo `.env` necesario para almacenar las credenciales de la base de datos.
- **scripts**: Contiene los scripts de Python que se utilizan en el proyecto.

## Requisitos

Para ejecutar este proyecto, necesitarás lo siguiente:

- Python 3.7+
- Librerías de Python: `pandas`, `psycopg2`, `python-dotenv`
- Amazon Redshift para la base de datos

## Configuración

1. **Clonar el repositorio**:

   ```bash
   git clone https://github.com/kevsanmm/Data.Engineering.git
   cd Data.Engineering/Microdesafios/Semana8
