# 📊 Análisis de Evasión de Clientes (Churn) – TelecomX

Este proyecto presenta un **Análisis Exploratorio de Datos (EDA)** sobre la evasión de clientes en la empresa Telecom. El objetivo es identificar patrones y factores que influyen en la cancelación del servicio.

---

## 📁 Dataset

El conjunto de datos contiene información sobre clientes, incluyendo:

- Información demográfica (género, dependientes, pareja)
- Servicios contratados (internet, soporte técnico, streaming)
- Tipo de contrato
- Método de pago
- Costos del servicio (mensual y total)
- Tiempo de permanencia del cliente
- Variable objetivo: **Churn (abandono del servicio)**
- etc...
---

## ⚙️ Proceso de análisis

El análisis se realizó en las siguientes etapas:

1. **Carga y exploración inicial de los datos**
2. **Limpieza de datos**
   - Eliminación de duplicados
   - Revisión de valores nulos
   - Corrección de inconsistencias
3. **Creación de nuevas variables**
   - Cálculo del costo diario promedio
4. **Análisis exploratorio de datos (EDA)**
   - Distribución del abandono de clientes
   - Comparación de churn con variables categóricas
   - Análisis de variables numéricas mediante gráficos

---

## 📊 Principales hallazgos

- Aproximadamente **26% de los clientes abandonan el servicio**.
- Los clientes con **contrato mensual** presentan mayor evasión.
- El **método de pago con cheque electrónico** muestra mayor tendencia al abandono.
- Muchos clientes cancelan **durante los primeros meses de servicio**.
- Los clientes con **costos mensuales y diarios más altos** presentan mayor probabilidad de abandono.

---

## 🛠️ Tecnologías utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📌 Objetivo del proyecto

Identificar patrones en el comportamiento de los clientes para comprender las causas del abandono y aportar información que ayude a mejorar las estrategias de **retención de clientes**.
#### Diccionario de datos

- `customerID`: número de identificación único de cada cliente
- `Churn`: si el cliente dejó o no la empresa
- `gender`: género (masculino y femenino)
- `SeniorCitizen`: información sobre si un cliente tiene o no una edad igual o mayor a 65 años
- `Partner`: si el cliente tiene o no una pareja
- `Dependents`: si el cliente tiene o no dependientes
- `tenure`: meses de contrato del cliente
- `PhoneService`: suscripción al servicio telefónico
- `MultipleLines`: suscripción a más de una línea telefónica
- `InternetService`: suscripción a un proveedor de internet
- `OnlineSecurity`: suscripción adicional de seguridad en línea
- `OnlineBackup`: suscripción adicional de respaldo en línea
- `DeviceProtection`: suscripción adicional de protección del dispositivo
- `TechSupport`: suscripción adicional de soporte técnico, menor tiempo de espera
- `StreamingTV`: suscripción de televisión por cable
- `StreamingMovies`: suscripción de streaming de películas
- `Contract`: tipo de contrato
- `PaperlessBilling`: si el cliente prefiere recibir la factura en línea
- `PaymentMethod`: forma de pago
- `Charges.Monthly`: total de todos los servicios del cliente por mes
- `Charges.Total`: total gastado por el cliente
