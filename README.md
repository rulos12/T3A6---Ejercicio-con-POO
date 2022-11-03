# T3A6---Ejercicio-con-POO

## Etapa 1. Descripcion del problema
Una fábrica textil desea llevar el control de la nómina de sus empleados en la matriz ubicada en Teziutlán y dos sucursales más (sucursal cdmx, sucursal malecónVeracruz). Para calcular la nómina debe indicarse la cantidad de empleados, número de contrato, tipo de empleado, años de antigüedad, las horas laborales de contrato y el salario base, además de su información básica (nombre, apellidos, RFC, CURP, email y teléfono).

Además del sueldo base se debe agregar un bono por antigüedad bajo las siguientes condiciones:
~~~
De 0 a 2 años de antigüedad no se asigna bono.
de 3 a 5 años de antigüedad se asigna un bono del 3% y si el trabajador es administrativo entonces el bono será del 4%.
De 6 a 10 años de antigüedad recibe un bono adicional del 8% y si el trabajador es administrativo, entonces el bono será del 12%.
~~~
Realizar el cálculo respectivo del ISR sobre el sueldo bruto acorde a la siguiente imagen:
![](![image](https://user-images.githubusercontent.com/112425272/199610995-d2035e08-016e-4d39-a148-0e5865135459.png)
Por último, mostrar un reporte de los trabajadores con sus datos, su salario bruto, ISR, bono por antigüedad y salario neto a pagar.

## Etapa 2. Diseño de la solulión

- Entrada:
  - String nombre, apellidoP, apellidoM, rfc, curp, email, telefono
  - int noContrato, años, tipoEmpleado, empleados
  - float salarioBruto, salarioFinal, horas, isr, salario
- Proceso:
  - Registrar los datos del empleado
  - calcular el sueldo bruto del empleado
  - calcular el isr del empleado
  - calcular el sueldo final del empleado
- Salida:
~~~
+--------------------------------------------------------+
| Fabrica textil Maquiladora                             |
|                                                        |
| Sucursal Teziutlan                                     |
| Nombre: raul sanchez gacria                            |
| Rfc: sagro1                                            |
| Curp: sagro2                                           |
| Correo: raulsa@gmail.com                               |
| Numero de telefono: 2312050311                         |
| Numero de contrato: 121312                             |
| Le pagan 31.25 por hora                                |
| Su salario bruto al mes es de: 7000.0                  |
| ISR: 784.16113                                         |
| Salario final: 6215.839                                |
+--------------------------------------------------------+
~~~
## Etapa 3. Especificaciones 
![](https://github.com/rulos12/T3A6---Ejercicio-con-POO/blob/main/T3A6.png)
## Etapa 4. Solución
https://github.com/rulos12/T3A6---Ejercicio-con-POO/blob/main/T3A6.zip

