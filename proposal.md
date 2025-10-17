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
<img width="1341" height="1020" alt="BBD_Velzia_2 drawio" src="https://github.com/user-attachments/assets/ff5f05d7-c341-4269-af9e-4afcff89947b" />


## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Moneda<br>2. CRUD Cliente|
|CRUD dependiente|1. CRUD Caja {depende de} CRUD Moneda|
|Listado<br>+<br>detalle| 1. Listado de ventas terminados filtrados por fecha=> detalle descripcion de venta<br> 2. Listado de costos fijos filtrados por fecha => detalle muestra detalle de cada costo|
|CUU/Epic|1. Efectuar una venta|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Caja<br>2. CRUD Cliente<br>3. CRUD Tasa<br>4. CRUD Venta<br>5. CRUD Pago<br>6. CRUD CostoVariable<br>7. CRUD CostoFijo<br>8. CRUD Transferencia<br>9. CRUD Ajuste<br>10. CRUD DividendoSocio<br>11. CRUD AporteSocio<br>12. CRUD Producto<br>13. CRUD Detalle |
|CUU/Epic||

### Alcance Adicional Voluntario
|Req|Detalle|
|:-|:-|
|Listado<br>+<br>detalle| 1. Calcular cuentas por gastar<br>2. Calcular proyección<br>3. Calcular cuentas por cobrar<br>4. Producto más vendido<br>5. Producto más rentable<br>6. Cliente más rentable|



