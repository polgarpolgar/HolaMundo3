# HolaMundo3
1- Queremos definir las clases necesarias para poder gestionar los empleados de
una empresa. Existen cuatro categorías de empleados: Jefes de Sección,
Trabajadores por Horas, Trabajadores por Piezas y Vendedores a Comisión.

2- Los miembros que deben incorporar todas las clases son (manteniendo el
nombre que se indica):
i. nombre
ii. apellidos
iii. salario (devuelve el salario semanal calculado según se indica
más adelante)
iv. toString (devuelve un texto compuesto por: texto indicador del
tipo de empleado, apellidos y nombre)

3- Los salarios se calcularán de la siguiente forma:
a. Jefes de Sección: cantidad fija pero puede ser distinta para cada jefe.
b. Trabajadores por horas: nº de horas trabajadas multiplicadas por el
salario de una hora. El salario por hora puede variar de un empleado
a otro.
c. Trabajadores por piezas: nº de piezas fabricadas multiplicadas por el
importe (salario) que se paga por pieza. Este importe puede variar de
un empleado a otro.
d. Vendedores a comisión: salario base más nº de piezas vendidas por
importe de comisión por pieza.

4- Crea un paquete de clases con el nombre ‘Empleados’. Declara una clase base
‘Empleado’. Declara cuatro clases derivadas, una para cada categoría de
empleado. En ellas debes declarar las propiedades de lectura y escritura
necesarias para calcular el salario; por ejemplo, en la clase Jefe se incluirá
una propiedad ‘SalarioSemanal’, en la clase TrabajadorPorPiezas una
propiedad ‘Cantidad’ para el número de piezas fabricadas y otra propiedad
‘SalarioPorPieza’ ... Las propiedades ‘nombre’ y ‘apellidos’ serán de solo
lectura. Los valores para las propiedades se inicializarán a través de los
constructores.

5- Para comprobar el funcionamiento crea un Array de empleados y visualiza sus
datos y ganancias en la consola de sistema.

6- Modifica la clase para que los nuevos objetos se añadan automáticamente a
una colección.
