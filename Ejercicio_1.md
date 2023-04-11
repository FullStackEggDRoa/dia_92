# EJERCICIOS DE APRENDIZAJE
## Ejercicio_1
### 1. Obtener los datos completos de los empleados
```
SELECT * FROM empleados;
+--------+----------------+---------+------------+-------------------+---------+--------------+-----------------+----------+
| id_emp | nombre         | sex_emp | fec_nac    | fec_incorporacion | sal_emp | comision_emp | cargo_emp       | id_depto |
+--------+----------------+---------+------------+-------------------+---------+--------------+-----------------+----------+
|     60 | Darío Casas    | M       | 1960-04-05 | 1992-11-01        | 4500000 |       500000 | Investigador    |     3000 |
|     99 | Diana Solarte  | F       | 1957-11-19 | 1990-05-16        | 1250000 |       500000 | Secretaria      |     1000 |
|    111 | Irene Díaz     | F       | 1979-09-28 | 2004-06-01        | 1050000 |       200000 | Mecánico        |     4200 |
|    144 | Rosa Angulo    | F       | 1957-03-15 | 1998-08-16        | 3250000 |      3500000 | Jefe Ventas     |     2000 |
|    219 | Melissa Roa    | F       | 1960-06-19 | 2001-03-16        | 2250000 |      2500000 | Vendedor        |     2100 |
|    221 | Carla López    | F       | 1975-05-11 | 2005-07-16        | 4500000 |       500000 | Jefe Mercadeo   |     3500 |
|    222 | José Giraldo   | M       | 1985-01-20 | 2000-11-01        | 1200000 |       400000 | Asesor          |     3500 |
|    269 | María Rojas    | F       | 1959-01-15 | 1990-05-16        | 6250000 |      1500000 | Gerente         |     1000 |
|    331 | Carlos Rozo    | M       | 1975-05-11 | 2001-09-16        |  750000 |       500000 | Vigilante       |     3500 |
|    333 | Pedro Blanco   | M       | 1987-10-28 | 2000-10-01        |  800000 |      3000000 | Vendedor        |     2000 |
|    334 | Marisol Pulido | F       | 1979-10-01 | 1990-05-16        | 3250000 |      1000000 | Investigador    |     3000 |
|    335 | Ana Moreno     | F       | 1992-01-05 | 2004-06-01        | 1200000 |       400000 | Secretaria      |     3000 |
|    336 | Carolina Ríos  | F       | 1992-02-15 | 2000-10-01        | 1250000 |       500000 | Secretaria      |     1500 |
|    337 | Edith Muñoz    | F       | 1992-03-31 | 2000-10-01        |  800000 |      3600000 | Vendedor        |     2100 |
|    338 | Abel Gómez     | M       | 1939-12-24 | 2000-10-01        | 1050000 |       200000 | Mecánico        |     4300 |
|    343 | Elisa Rojas    | F       | 1979-09-28 | 2004-06-01        | 3000000 |      1000000 | Jefe Mecánicos  |     4000 |
|    383 | Luis Pérez     | M       | 1956-02-25 | 2000-01-01        | 5050000 |            0 | Director        |     1500 |
|    444 | Jesús Alfonso  | M       | 1988-03-14 | 2000-10-01        |  800000 |      3500000 | Vendedor        |     2000 |
|    555 | Julián Mora    | M       | 1989-07-03 | 2000-10-01        |  800000 |      3100000 | Vendedor        |     2200 |
|    666 | Manuel Millán  | M       | 1990-12-08 | 2004-06-01        |  800000 |      3700000 | Vendedor        |     2300 |
|    689 | Mario Llano    | M       | 1945-08-30 | 1990-05-16        | 2250000 |      2500000 | Vendedor        |     2300 |
|    777 | Marcos Cortez  | M       | 1986-06-23 | 2000-04-16        | 2550000 |       500000 | Mecánico        |     4000 |
|    782 | Antonio Gil    | M       | 1980-01-23 | 2010-04-16        |  850000 |      1500000 | Técnico         |     1500 |
|    785 | Joaquín Rosas  | M       | 1947-07-07 | 1990-05-16        | 2250000 |      2500000 | Vendedor        |     2200 |
|    802 | William Daza   | M       | 1982-10-09 | 1999-12-16        | 2250000 |      1000000 | Investigador    |     3000 |
|    898 | Iván Duarte    | M       | 1955-08-12 | 1998-05-16        | 1050000 |       200000 | Mecánico        |     4100 |
+--------+----------------+---------+------------+-------------------+---------+--------------+-----------------+----------+
```
### 2. Obtener los datos completos de los departamentos.
```
SELECT * FROM departamentos;
+----------+----------------+-------------+-------------------+
| id_depto | nombre_depto   | ciudad      | nombre_jefe_depto |
+----------+----------------+-------------+-------------------+
|     1000 | GERENCIA       | CIUDAD REAL | Bruno Cebrian     |
|     1500 | PRODUCCIÓN     | CIUDAD REAL | Jesica Duran      |
|     2000 | VENTAS         | CIUDAD REAL | Alicia Andres     |
|     2100 | VENTAS         | BARCELONA   | Fabian Soto       |
|     2200 | VENTAS         | VALENCIA    | Mari Plaza        |
|     2300 | VENTAS         | MADRID      | Jonatan Acuña     |
|     3000 | INVESTIGACIÓN  | CIUDAD REAL | Valentina Sola    |
|     3500 | MERCADEO       | CIUDAD REAL | Abraham Diego     |
|     4000 | MANTENIMIENTO  | CIUDAD REAL | Raúl Carrero      |
|     4100 | MANTENIMIENTO  | BARCELONA   | Catalina Valdes   |
|     4200 | MANTENIMIENTO  | VALENCIA    | Adriana Rocha     |
|     4300 | MANTENIMIENTO  | MADRID      | German Luna       |
+----------+----------------+-------------+-------------------+
```
### 3. Listar el nombre de los departamentos.
```
SELECT nombre_depto  FROM departamentos;
+----------------+
| nombre_depto   |
+----------------+
| GERENCIA       |
| PRODUCCIÓN     |
| VENTAS         |
| VENTAS         |
| VENTAS         |
| VENTAS         |
| INVESTIGACIÓN  |
| MERCADEO       |
| MANTENIMIENTO  |
| MANTENIMIENTO  |
| MANTENIMIENTO  |
| MANTENIMIENTO  |
+----------------+
```
### 4. Obtener el nombre y salario de todos los empleados.
```
SELECT nombre,sal_emp FROM empleados;
+----------------+---------+
| nombre         | sal_emp |
+----------------+---------+
| Darío Casas    | 4500000 |
| Diana Solarte  | 1250000 |
| Irene Díaz     | 1050000 |
| Rosa Angulo    | 3250000 |
| Melissa Roa    | 2250000 |
| Carla López    | 4500000 |
| José Giraldo   | 1200000 |
| María Rojas    | 6250000 |
| Carlos Rozo    |  750000 |
| Pedro Blanco   |  800000 |
| Marisol Pulido | 3250000 |
| Ana Moreno     | 1200000 |
| Carolina Ríos  | 1250000 |
| Edith Muñoz    |  800000 |
| Abel Gómez     | 1050000 |
| Elisa Rojas    | 3000000 |
| Luis Pérez     | 5050000 |
| Jesús Alfonso  |  800000 |
| Julián Mora    |  800000 |
| Manuel Millán  |  800000 |
| Mario Llano    | 2250000 |
| Marcos Cortez  | 2550000 |
| Antonio Gil    |  850000 |
| Joaquín Rosas  | 2250000 |
| William Daza   | 2250000 |
| Iván Duarte    | 1050000 |
+----------------+---------+
```
5. Listar todas las comisiones.
```
SELECT comision_emp FROM empleados;
+--------------+
| comision_emp |
+--------------+
|       500000 |
|       500000 |
|       200000 |
|      3500000 |
|      2500000 |
|       500000 |
|       400000 |
|      1500000 |
|       500000 |
|      3000000 |
|      1000000 |
|       400000 |
|       500000 |
|      3600000 |
|       200000 |
|      1000000 |
|            0 |
|      3500000 |
|      3100000 |
|      3700000 |
|      2500000 |
|       500000 |
|      1500000 |
|      2500000 |
|      1000000 |
|       200000 |
+--------------+
```
### 6. Obtener los datos de los empleados cuyo cargo sea ‘Secretaria’.
```
SELECT * FROM empleados WHERE cargo_emp = "Secretaria";
+--------+----------------+---------+------------+-------------------+---------+--------------+------------+----------+
| id_emp | nombre         | sex_emp | fec_nac    | fec_incorporacion | sal_emp | comision_emp | cargo_emp  | id_depto |
+--------+----------------+---------+------------+-------------------+---------+--------------+------------+----------+
|     99 | Diana Solarte  | F       | 1957-11-19 | 1990-05-16        | 1250000 |       500000 | Secretaria |     1000 |
|    335 | Ana Moreno     | F       | 1992-01-05 | 2004-06-01        | 1200000 |       400000 | Secretaria |     3000 |
|    336 | Carolina Ríos  | F       | 1992-02-15 | 2000-10-01        | 1250000 |       500000 | Secretaria |     1500 |
+--------+----------------+---------+------------+-------------------+---------+--------------+------------+----------+
```
### 7. Obtener los datos de los empleados vendedores, ordenados por nombre alfabéticamente.
```
SELECT * FROM empleados WHERE cargo_emp = "Vendedor" ORDER BY nombre ASC;
+--------+----------------+---------+------------+-------------------+---------+--------------+-----------+----------+
| id_emp | nombre         | sex_emp | fec_nac    | fec_incorporacion | sal_emp | comision_emp | cargo_emp | id_depto |
+--------+----------------+---------+------------+-------------------+---------+--------------+-----------+----------+
|    337 | Edith Muñoz    | F       | 1992-03-31 | 2000-10-01        |  800000 |      3600000 | Vendedor  |     2100 |
|    444 | Jesús Alfonso  | M       | 1988-03-14 | 2000-10-01        |  800000 |      3500000 | Vendedor  |     2000 |
|    785 | Joaquín Rosas  | M       | 1947-07-07 | 1990-05-16        | 2250000 |      2500000 | Vendedor  |     2200 |
|    555 | Julián Mora    | M       | 1989-07-03 | 2000-10-01        |  800000 |      3100000 | Vendedor  |     2200 |
|    666 | Manuel Millán  | M       | 1990-12-08 | 2004-06-01        |  800000 |      3700000 | Vendedor  |     2300 |
|    689 | Mario Llano    | M       | 1945-08-30 | 1990-05-16        | 2250000 |      2500000 | Vendedor  |     2300 |
|    219 | Melissa Roa    | F       | 1960-06-19 | 2001-03-16        | 2250000 |      2500000 | Vendedor  |     2100 |
|    333 | Pedro Blanco   | M       | 1987-10-28 | 2000-10-01        |  800000 |      3000000 | Vendedor  |     2000 |
+--------+----------------+---------+------------+-------------------+---------+--------------+-----------+----------+
```
### 8. Obtener el nombre y cargo de todos los empleados, ordenados por salario de menor a mayor.
```
SELECT nombre, cargo_emp FROM empleados ORDER BY sal_emp  ASC;
+----------------+-----------------+
| nombre         | cargo_emp       |
+----------------+-----------------+
| Carlos Rozo    | Vigilante       |
| Manuel Millán  | Vendedor        |
| Julián Mora    | Vendedor        |
| Jesús Alfonso  | Vendedor        |
| Edith Muñoz    | Vendedor        |
| Pedro Blanco   | Vendedor        |
| Antonio Gil    | Técnico         |
| Iván Duarte    | Mecánico        |
| Abel Gómez     | Mecánico        |
| Irene Díaz     | Mecánico        |
| Ana Moreno     | Secretaria      |
| José Giraldo   | Asesor          |
| Carolina Ríos  | Secretaria      |
| Diana Solarte  | Secretaria      |
| William Daza   | Investigador    |
| Joaquín Rosas  | Vendedor        |
| Melissa Roa    | Vendedor        |
| Mario Llano    | Vendedor        |
| Marcos Cortez  | Mecánico        |
| Elisa Rojas    | Jefe Mecánicos  |
| Marisol Pulido | Investigador    |
| Rosa Angulo    | Jefe Ventas     |
| Carla López    | Jefe Mercadeo   |
| Darío Casas    | Investigador    |
| Luis Pérez     | Director        |
| María Rojas    | Gerente         |
+----------------+-----------------+
```
### 9. Obtener el nombre de o de los jefes que tengan su departamento situado en la ciudad de “Ciudad Real”
```
SELECT nombre_jefe_depto FROM departamentos WHERE ciudad = "CIUDAD REAL";
+-------------------+
| nombre_jefe_depto |
+-------------------+
| Bruno Cebrian     |
| Jesica Duran      |
| Alicia Andres     |
| Valentina Sola    |
| Abraham Diego     |
| Raúl Carrero      |
+-------------------+
```
### 10. Elabore un listado donde para cada fila, figure el alias ‘Nombre’ y ‘Cargo’ para las respectivas tablas de empleados.
```
SELECT nombre AS Nombre, cargo_emp AS Cargo FROM empleados;
+----------------+-----------------+
| Nombre         | Cargo           |
+----------------+-----------------+
| Darío Casas    | Investigador    |
| Diana Solarte  | Secretaria      |
| Irene Díaz     | Mecánico        |
| Rosa Angulo    | Jefe Ventas     |
| Melissa Roa    | Vendedor        |
| Carla López    | Jefe Mercadeo   |
| José Giraldo   | Asesor          |
| María Rojas    | Gerente         |
| Carlos Rozo    | Vigilante       |
| Pedro Blanco   | Vendedor        |
| Marisol Pulido | Investigador    |
| Ana Moreno     | Secretaria      |
| Carolina Ríos  | Secretaria      |
| Edith Muñoz    | Vendedor        |
| Abel Gómez     | Mecánico        |
| Elisa Rojas    | Jefe Mecánicos  |
| Luis Pérez     | Director        |
| Jesús Alfonso  | Vendedor        |
| Julián Mora    | Vendedor        |
| Manuel Millán  | Vendedor        |
| Mario Llano    | Vendedor        |
| Marcos Cortez  | Mecánico        |
| Antonio Gil    | Técnico         |
| Joaquín Rosas  | Vendedor        |
| William Daza   | Investigador    |
| Iván Duarte    | Mecánico        |
+----------------+-----------------+
```
11. Listar los salarios y comisiones de los empleados del departamento 2000, ordenado por comisión de menor a mayor.
```
SELECT sal_emp, comision_emp FROM empleados WHERE id_depto=2000 ORDER BY comision_emp ASC;
+---------+--------------+
| sal_emp | comision_emp |
+---------+--------------+
|  800000 |      3000000 |
| 3250000 |      3500000 |
|  800000 |      3500000 |
+---------+--------------+
```
12. Obtener el valor total a pagar a cada empleado del departamento 3000, que resulta de: sumar el salario y la comisión, más una bonificación de 500. Mostrar el nombre del empleado y el total a pagar, en orden alfabético.
```
SELECT nombre AS "Nombre Empleado", sal_emp+comision_emp+500 AS "Total a Pagar" FROM empleados WHERE id_depto=3000;
+-----------------+---------------+
| Nombre Empleado | Total a Pagar |
+-----------------+---------------+
| Darío Casas     |       5000500 |
| Marisol Pulido  |       4250500 |
| Ana Moreno      |       1600500 |
| William Daza    |       3250500 |
+-----------------+---------------+
```
