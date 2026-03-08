# 📊 TelecomX: Análisis de Evasión de Clientes (Churn)

## 📝 Descripción del Proyecto
Este proyecto se centra en el Análisis Exploratorio de Datos (EDA) y la limpieza de una base de datos jerárquica de la empresa de telecomunicaciones TelecomX. El objetivo principal es identificar los factores clave que impulsan a los clientes a cancelar sus servicios (Churn) para proporcionar una base analítica sólida que permita diseñar estrategias de retención.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python
* **Librerías de manipulación de datos:** Pandas
* **Librerías de visualización:** Matplotlib, Seaborn
* **Entorno:** Google Colab / Jupyter Notebook

## 🧹 Procesamiento y Limpieza de Datos
* Aplanamiento de datos desde formato JSON a estructura tabular.
* Eliminación de registros duplicados y tratamiento de valores nulos en la variable objetivo.
* Transformación de tipos de datos (conversión de texto a variables numéricas binarias).
* **Ingeniería de características (Feature Engineering):** Creación de la métrica `Cuentas_Diarias` para evaluar el impacto psicológico del costo.
* Traducción y estandarización del dataset al español para facilitar la comunicación con *stakeholders*.

## 📈 Principales Descubrimientos (Insights)
Tras analizar visual y estadísticamente los datos de más de 7,000 clientes, descubrimos que el **26.5%** abandona la empresa. Los factores más críticos son:
1. **El Tipo de Contrato:** El 42.7% de los clientes con contratos "Mes a mes" abandona la empresa, mientras que la retención en contratos de "Dos años" es casi total (97.2%).
2. **Fricción en los Pagos:** Los clientes que utilizan "Cheque electrónico" tienen una tasa de abandono desproporcionadamente alta frente a los débitos automáticos.
3. **Falta de Valor Agregado:** La ausencia de servicios como "Soporte Técnico" y "Seguridad en Línea" está fuertemente correlacionada con la cancelación del servicio.
4. **Zona de Peligro:** La mayoría de los abandonos ocurren durante los primeros 10 meses de servicio, impulsados por facturas mensuales que superan el promedio de los usuarios retenidos.

## 🚀 Cómo ejecutar este proyecto
1. Clona este repositorio en tu máquina local:
   ```bash
   git clone [https://github.com/tu-usuario/TelecomX-Churn-Analysis.git](https://github.com/tu-usuario/TelecomX-Churn-Analysis.git)
   
