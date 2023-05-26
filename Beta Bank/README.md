## Data:



- *RowNumber*: índice de cadena de datos
- *CustomerId*: identificador de cliente único
- *Surname*: apellido
- *CreditScore*: valor de crédito
- *Geography*: país de residencia
- *Gender*: sexo
- *Age*: edad
- *Tenure*: período durante el cual ha madurado el depósito a plazo fijo de un cliente (años)
- *Balance*: saldo de la cuenta
- *NumOfProducts*: número de productos bancarios utilizados por el cliente
- *HasCrCard*: el cliente tiene una tarjeta de crédito (1 - sí; 0 - no)
- *IsActiveMember*: actividad del cliente (1 - sí; 0 - no)
- *EstimatedSalary*: salario estimado

## Goal:

Necesitamos predecir si un cliente dejará el banco pronto. Se tiene los datos sobre el comportamiento pasado de los clientes y la terminación de contratos con el banco.
Crear un modelo con el máximo valor F1 posible. Se necesita un valor F1 de al menos 0.59. Verificar F1 para el conjunto de prueba.
Además, debes medir la métrica AUC-ROC y compararla con el valor F1.

## Libraries used:

pandas

matplotlib.pyplot

sklearn.utils

sklearn.model_selection 

sklearn.preprocessing 

sklearn.tree

sklearn.metrics

sklearn.linear_model

sklearn.metrics

sklearn.ensemble

sklearn.metrics

seaborn

numpy