# Dia_92
Encuentro Día 92 de MySQL 
<br>
<br>
Para su ejecución, es necesario incluir la librería que se detalla a continuación, en ella se encuentra todos las Entidades (Objetos), Servicios y 
Utilidades, relacionados con los ejercicios de todas las guías.
<br>
<br>
Link Librería: https://github.com/FullStackEggDRoa/libreria_comun.git
<br>
<br>
# Desde Netbeans: 
Propiedades de Proyecto / Librerías / Class Path / Adicionar Proyecto (Add Project) / (Ubicar Directorio Librería)
# Respuestas:
## Manos a la Obra - Página 19:

### Actividad 4
1) Se crearon las bases de datos y sus respectivas tablas.
2) 2.1.[c] 2.2.[?] 2.3.[d] 2.4[c] 
3) Hecho.

## Manos a la Obra - Página 22:
### Actividad 5
 
a) Hecho [creador_inserts.sql]
<br>
b) Hecho [personajes_inserts.sql]
<br>
a) Hecho [personajes_alters.sql]
<br>
b) Hecho [personajes_deletes.sql]
<br>

### Actividad Extra
Hecho - Cargado Ejecutado el script "nba".

## Manos a la Obra - Página 30:
### Actividad 6
a) Ok. Checked!!
<br>
b) Creo que el enunciado refiere a la tabla 'personajes'....
```
mysql> SELECT nombre_real FROM personajes;
+----------------+
| nombre_real    |
+----------------+
| Bruce Banner   |
| Diana Prince   |
| Tony Stark     |
| Thor Odinson   |
| Wanda Maximoff |
| Carol Danvers  |
| Thanos         |
| Peter Parker   |
| Steve Rogers   |
| Bobby Drake    |
| Burce Wayne    |
| Clark Kent     |
+----------------+
```
c)
```
mysql> SELECT nombre_real FROM personajes WHERE nombre_real LIKE 'B%';
+--------------+
| nombre_real  |
+--------------+
| Bruce Banner |
| Bobby Drake  |
| Burce Wayne  |
+--------------+
```
## Manos a la Obra - Página 31:
### Actividad 7
```
SELECT * FROM personajes ORDER BY inteligencia ASC;
+--------------+----------------+------------------+--------------+----------+-----------+-------+-----------+-------------------------+------------+
| id_personaje | nombre_real    | personaje        | inteligencia | fuerza   | velocidad | poder | aparicion | ocupacion               | id_creador |
+--------------+----------------+------------------+--------------+----------+-----------+-------+-----------+-------------------------+------------+
|           10 | Bobby Drake    | Ice Man          |          140 | 2 mil    |        64 |   122 |      1963 | Contador                |          1 |
|            4 | Thor Odinson   | Thor             |          145 | infinita |       100 |   235 |      1962 | Rey de Asgard           |          1 |
|            9 | Steve Rogers   | Capitan America  |          145 | 600      |        45 |    60 |      1941 | Oficial Federeal        |          1 |
|            6 | Carol Danvers  | Capitana Marvel  |          157 | 250 mil  |        85 |   128 |      1968 | Oficial de Intelegencia |          1 |
|            1 | Bruce Banner   | Hulk             |          160 | 600 mil  |        75 |    98 |      1962 | Fisico Nuclear          |          1 |
|            2 | Diana Prince   | Mujer Maravilla  |          160 | infinita |        95 |   127 |      1949 | Princesa Guerrera       |          2 |
|            8 | Peter Parker   | Spider Man       |          165 | 25 mil   |        80 |    74 |      1962 | Fotógrafo               |          1 |
|           13 | Clark Kent     | Superman         |          165 | infinita |       120 |   182 |      1938 | Reportero               |          2 |
|            3 | Tony Stark     | Iron Man         |          170 | 200 mil  |        70 |   123 |      1963 | Inventor Industrial     |          1 |
|            5 | Wanda Maximoff | Bruja <Escarlata |          170 | 100 mil  |        90 |   345 |      1964 | Bruja                   |          1 |
|            7 | Thanos         | Thanos           |          170 | infinita |        40 |   306 |      1973 | Adorador de la Muerte   |          1 |
|           12 | Burce Wayne    | Batman           |          170 | 500      |        32 |    47 |      1939 | Hombre de Negocios      |          2 |
+--------------+----------------+------------------+--------------+----------+-----------+-------+-----------+-------------------------+------------+
```
## Ejercicio 1
Link: https://github.com/FullStackEggDRoa/dia_92/blob/main/Ejercicio_1.md
