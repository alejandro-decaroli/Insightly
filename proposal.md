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
Velzia es un mini ERP.

### Modelo
<img width="1341" height="1020" alt="BBD_Velzia drawio3" src="https://github.com/user-attachments/assets/050857b3-61ae-459e-a86f-8862ae9fb21f" />

## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Moneda<br>2. CRUD Cliente|
|CRUD dependiente|1. CRUD Caja {depende de} CRUD Moneda|
|Listado<br>+<br>detalle| 1. Listado de ventas "Pagas" filtrados por fecha=> detalle descripcion de venta<br> 2. Listado de costos fijos filtrados por fecha => detalle muestra detalle de cada costo|
|CUU/Epic|1. Efectuar una venta|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Caja<br>2. CRUD Cliente<br>3. CRUD Tasa<br>4. CRUD Venta<br>5. CRUD Pago<br>6. CRUD CostoVariable<br>7. CRUD CostoFijo<br>8. CRUD Transferencia<br>9. CRUD Ajuste<br>10. CRUD DividendoSocio<br>11. CRUD AporteSocio<br>12. CRUD Producto<br>13. CRUD Detalle<br>14. CRUD Moneda<br>15. CRUD Usuario |
|CUU/Epic||

### Alcance Adicional Voluntario
|Req|Detalle|
|:-|:-|
|Listado<br>+<br>detalle| 1. Calcular cuentas por gastar => muestra únicamente los detalles de los costos con estado 'Pendiente' por pagar y la sumatoria de los gastos<br>2. Calcular proyección => Muestra la sumatoria de los ingresos y los costos, tanto actuales como por cobrar, ademas el total de dinero en cajas<br>3. Calcular cuentas por cobrar => Muestra los detalles de las ventas que todavia no estan 'Pagas' y la sumatoria de los pagos pendientes de las mismas.<br>4. Reporte de ventas general => Muestra Producto mas vendido, mas rentable, ingreso actual, ingreso pendiente, porcentajes de ventas<br>5. Listado de costos variables por fecha y estado => muestra detalle de cada costo<br>6. Listado de transferencias por fecha => muestra detalle de cada transferencia<br>7. Listado de productos por fecha =>  muestra el detalle de cada producto<br>8. Listado de clientes por fecha => muestra el detalle de cada cliente |



