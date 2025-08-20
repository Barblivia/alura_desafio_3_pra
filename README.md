# alura_desafio_3_pra
Desafío Telecom X - 2 - Desarrollar modelos predictivos para prever qué clientes tienen mayor probabilidad de cancelar sus servicios.

**Challenge ONE Data Science – Telecom X 2**

**Propósito del análisis realizado**
En este proyecto se busca desarrollar modelos predictivos capaces de prever qué clientes tienen mayor probabilidad de cancelar sus servicios. La empresa quiere anticiparse al problema de la cancelación, y se busca detectar las características de los clientes pasibles de cancelar el servicio para implementar acciones que lo eviten. 

**Estructura del proyecto y organización de los archivos.**
1. El proyecto se basa en los datos de clientes ya trabajados en la etapa anterior, de modo que mantengan la consistencia en el análisis, en formato csv.
Enlace de archivos: https://raw.githubusercontent.com/Barblivia/alura_desafio_3_pra/main/datos_limpios.csv
2. Los campos que componen la base se presentan en el siguiente “Diccionario de datos”. 

**Diccionario de datos**
•	Churn: si el cliente dejó o no la empresa
•	gender: género (masculino y femenino)
•	SeniorCitizen: información sobre si un cliente tiene o no una edad igual o mayor a 65 años
•	Partner: si el cliente tiene o no una pareja
•	Dependents: si el cliente tiene o no dependientes
•	tenure: meses de contrato del cliente
•	PhoneService: suscripción al servicio telefónico
•	MultipleLines: suscripción a más de una línea telefónica
•	InternetService: suscripción a un proveedor de internet
•	OnlineSecurity: suscripción adicional de seguridad en línea
•	OnlineBackup: suscripción adicional de respaldo en línea
•	DeviceProtection: suscripción adicional de protección del dispositivo
•	TechSupport: suscripción adicional de soporte técnico, menor tiempo de espera
•	StreamingTV: suscripción de televisión por cable
•	StreamingMovies: suscripción de streaming de películas
•	Contract: tipo de contrato
•	PaperlessBilling: si el cliente prefiere recibir la factura en línea
•	PaymentMethod: forma de pago
•	Charges.Monthly: total de todos los servicios del cliente por mes
•	Charges.Total: total gastado por el cliente
•	Churn_bin: conversión de churn

3. Los análisis realizados se presentan en el archivo ‘alura_desafio_3_pra’ con el código para ejecutar en Colab. 
   
**Tecnologías Utilizadas**
•	Python 
•	Librerias Pandas / Matplotlib.pyplot / Seaborn / numpy   / sklearn
•	Google Colab 

**Guía de Instalación y Ejecución**

La notebook puede ejecutarse en Google Colab. Las librerías utilizadas están incluidas en el código. 
Para ejecutar seguir los siguientes pasos:
1. Abrir el archivo ‘alura_desafio_3_pra’ en Google Colab.
2. Ejecutar las celdas de código desde la primera a la última. Es importante seguir la secuencia pues deben instalarse librerías e importarse los datos de la base. Además se realizan transformaciones necesarias en pasos subsiguientes. 
3. En el Colab se puede visualizar el código y los resultados como tablas y gráficos.
4. El apartado “Conclusiones” del mismo archivo se presentan los resultados el análisis y las recomendaciones.
