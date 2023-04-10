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
<br>
## Manos a la Obra - Página 22:
### Actividad 5
<br> 
a) Hecho [creador_inserts.sql]
b) Hecho [personajes_inserts.sql]
<br>
a) Hecho [personajes_alters.sql]
b) Hecho [personajes_deletes.sql]

### Actividad Extra
Hecho - Cargado Ejecutado el script "nba".

## Manos a la Obra - Página 30:
### Actividad 6
a) 
b) Creo que el enunciado refiere a la tabla 'personajes'....
´´´
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
´´´
c)
´´´
mysql> SELECT nombre_real FROM personajes WHERE nombre_real LIKE 'B%';
+--------------+
| nombre_real  |
+--------------+
| Bruce Banner |
| Bobby Drake  |
| Burce Wayne  |
+--------------+
´´´
