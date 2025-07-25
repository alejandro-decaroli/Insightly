# Propuesta TP DSW

## Grupo
### Integrantes
* 46876 Zinni, Gonzalo
* 44963 Decaroli, Alejandro


### Repositorios
* [Backend app](https://github.com/alejandro-decaroli/Velzia_backend)
* [Frontend app](https://github.com/alejandro-decaroli/Velzia_frontend)


## Tema
### Descripción
Velzia es un sistema de gestion de ventas.

### Modelo
![BBD_Velzia](https://github.com/user-attachments/assets/6588509e-9ef4-4123-9b3b-4216662c988d)






## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Moneda<br>2. CRUD Cliente|
|CRUD dependiente|1. CRUD Tasa {depende de} CRUD Moneda|
|Listado<br>+<br>detalle| 1. Listado de ventas terminados filtrados por fecha=> detalle descripcion de venta<br> 2. Listado de costos fijos filtrados por fecha => detalle muestra detalle de cada costo|
|CUU/Epic|1. Efectuar una venta|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Caja<br>2. CRUD Cliente<br>3. CRUD Tasa<br>4. CRUD Venta<br>5. CRUD Pago<br>6. CRUD CostoVariable<br>7. CRUD CostoFijo<br>8. CRUD Transferencia<br>9. CRUD Ajuste<br>10. CRUD DividendoSocio<br>11. CRUD AporteSocio|
|CUU/Epic|1. Calcular ganancia marginal<br>2. Calcular proyección<br>3. Calcular cuentas por cobrar|

### Alcance Adicional Voluntario
|Req|Detalle|
|:-|:-|
|Listado<br>+<br>detalle| 3. Listado de ajustes de una caja<br> 4. Listado de ventas de un cliente<br> 5. Listado de transferencias de una caja<br> 6. Listado de aportes de socio por caja<br> 7. Listado de dividendos de socio caja|
|CUU/Epic|4. Calcular cuentas por gastar<br>5. Calcular punto de equilibrio<br>6. Mostrar movimientos de una caja|


