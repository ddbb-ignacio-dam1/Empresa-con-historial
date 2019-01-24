# Empresa con historial
Se desea almacenar información de los empleados, puestos de trabajo que ocupan o han ocupado en la empresa, departamento, estudios, etc con las siguientes características:

De cada empleado se almacena DNI, NSS, Nombre, Domicilio (opcional), Sexo (almacenando los caracteres V para identificar un varón y M para identificar una mujer) y Edad.

Existen tres tipos de empleados en la empresa: Contables, Diseñadores y Desarrolladores.

Cada empleado trabaja obligatoriamente en un Dpto de la empresa. Los Dptos tienen estructura jerárquica y cada Dpto puede depender de otro o tener otro Dpto a su cargo. Cada Dpto puede tener más de uno a su cargo pero sólo dependerá de un Dpto 'padre' como máximo. De cada Dpto se almacena el nombre y el presupuesto que maneja actualmente y el número de empleados que tiene.

De cada empleado se almacenan sus estudios (centro en el que estudió, año de finalización, título y especialidad. De cada centro se guarda código, nombre y ciudad.

Los puestos de trabajo de la empresa se codifican con un número único de 3 cifras, el nombre del trabajo, el salario mínimo y el salario máximo de cada trabajo.

Interesa tener la información histórica (anterior) además de la actual, tanto de los puestos de trabajo como de los salarios percibidos por cada empleado.

Para lo cual se almacenan para los puestos de trabajo la fecha en que comenzó en un determinado puesto de trabajo y la que finalizó en dicho puesto (si ha finalizado ya) y el Dpto al que está o estaba asignado.

Para guardar las nóminas percibidas por cada trabajador se guarda el salario (la cantidad en nómina) y el mes y año.

Es preciso que cada vez que se genere una nómina se compruebe que el salario a percibir está entre los límites del puesto de trabajo desempañado en ese momento.

Para cada puesto de trabajo realizado cada empleado puede tener un supervisor.

Cada empleado tiene un solo salario en cada momento. También, cada empleado tendrá asignado un solo trabajo en cada momento.

## Modelo entidad relaccion

![alt_text](https://github.com/ddbb-ignacio-dam1/Empresa-con-historial/blob/master/Empresa%20con%20historial.jpg)

## Grafo realaccional

![alt_text](https://github.com/ddbb-ignacio-dam1/Empresa-con-historial/blob/master/Grafo%20realaccional%20empresa.jpg)
