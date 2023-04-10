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
###2. Obtener los datos completos de los departamentos.
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
### 3. 
