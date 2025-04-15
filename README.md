# ⚔️ CRUD + Programación Funcional - Shingeki no Kyojin

Este proyecto es una aplicación de consola desarrollada con **Java 23**, basada en el universo de *Shingeki no Kyojin (Attack on Titan)*. He implementado operaciones **CRUD** básicas sobre las entidades **Personajes** y **Batallas**.
En el Main.java incluye **ejercicios de programación funcional** usando **streams** y **expresiones lambda**.

El objetivo del proyecto es que puedas aprender y aplicar los principios de la programación funcional junto con un sistema CRUD sencillo conectado a una base de datos **MySQL**, y si te mola la temática pues mejor no?😁

Lo he diseñado con una arquitectura modular basada en:
- ✅ POJO (entidades)
- ✅ DAO (Data Access Object)
- ✅ Base de datos MySQL
- ✅ JSON con datos iniciales para insertar en la BD

---

### 🔁 CRUD
- ✅ **Listar** personajes y batallas
- 📝 **Actualizar** datos
- ❌ **Eliminar** por identificador

### 🧠 Ejercicios de Programación Funcional
- Uso de `streams` y `lambda`
- Filtrar y ordenar según las características de los personajes.
- Transformaciones con `map`
- Agrupaciones según las estadísticas en Map.

---

## 🛠 Tecnologías Usadas

- **Java 23**
- **Maven**
- **MySQL**
- **JDBC** para conexión con la base de datos
- **Gson (Google)** para manejo de JSON
- **Programación funcional** con Java Streams

## ⚙ Configuración y ejecución

### ⚠️ IMPORTANTE: Verifica las credenciales en la clase conexionDB.java y ajustalas según tu configuración.
Ejecuta el contenido del fichero shingeki.sql en tu servidor MySQL para generar la base de datos y tablas.

Al ejecutar el programa se insertarán algunos datos predeterminados en la base de datos, una vez ejecutado por primera vez asegurate de comentar las 2 lineas del Main.java que realizan esta función:

![image](https://github.com/user-attachments/assets/1ae30172-5e7b-4763-aece-2403b3eeb3aa)


