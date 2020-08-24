# 01-Simulacion-MVC-JAVA-SPRING-

## Web compuesta de: 
* Listado de montos por ciudades: se pide desplegar una tabla que muestre el listado de
ciudades, el tipo de ayuda y el monto total correspondiente a cada clasificación. 

* Formulario de creación de ayuda: debe crear un formulario que contenga un campo
selector de cliente, un campo para el monto y un motivo. Al procesarlo se debe crear un
nuevo registro en la tabla “Ayudas”. 

## Script de datos
```
INSERT INTO Ciudades VALUES (1,'Santiago');
INSERT INTO Ciudades VALUES (2,'Viña del Mar');
INSERT INTO Ciudades VALUES (3,'Concepción');
INSERT INTO Ciudades VALUES (4,'Rancagua');
INSERT INTO Ciudades VALUES (5,'Temuco');
INSERT INTO Beneficiarios VALUES (1,'Juan Perez',23,1);
INSERT INTO Beneficiarios VALUES (2,'Pedro López',30,3);
INSERT INTO Beneficiarios VALUES (3,'Diego González',18,2);
INSERT INTO Beneficiarios VALUES (4,'Martín Sánchez',45,1);
INSERT INTO Beneficiarios VALUES (5,'Samuel Reyes',30,4);
INSERT INTO Beneficiarios VALUES (6,'Matías Donoso',60,5);
INSERT INTO Ayudas (beneficiarioid, monto, motivo) VALUES
(3,250000,'Insumos');
INSERT INTO Ayudas (beneficiarioid, monto, motivo) VALUES
(2,50000,'Alimentación');
INSERT INTO Ayudas (beneficiarioid, monto, motivo) VALUES
(2,40000,'Cuentas');
INSERT INTO Ayudas (beneficiarioid, monto, motivo) VALUES
(4,240000,'Alimentación');
INSERT INTO Ayudas (beneficiarioid, monto, motivo) VALUES
(1,80000,'Cuentas');
INSERT INTO Ayudas (beneficiarioid, monto, motivo) VALUES
(2,150000,'Insumos');
INSERT INTO Ayudas (beneficiarioid, monto, motivo) VALUES
(4,100000,'Cuentas');
INSERT INTO Ayudas (beneficiarioid, monto, motivo) VALUES
(3,50000,'Cuentas');
INSERT INTO Ayudas (beneficiarioid, monto, motivo) VALUES
(3,50000,'Alimentación');
INSERT INTO Ayudas (beneficiarioid, monto, motivo) VALUES
(1,25000,'Insumos');
INSERT INTO Ayudas (beneficiarioid, monto, motivo) VALUES
(5,25000,'Alimentación');
INSERT INTO Ayudas (beneficiarioid, monto, motivo) VALUES
(6,38500,'Cuentas');
INSERT INTO Ayudas (beneficiarioid, monto, motivo) VALUES
(5,20000,'Insumos');
```





