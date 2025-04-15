# ⚔️ CRUD + Programación Funcional - Shingeki no Kyojin

Este proyecto es una aplicación de consola desarrollada con **Java 23**, basada en el universo de *Shingeki no Kyojin (Attack on Titan)*. He implementado operaciones **CRUD** básicas sobre las entidades **Personajes** y **Batallas**.
En el Main.java incluye **ejercicios de programación funcional** usando **streams** y **expresiones lambda**.

---

## 📚 Descripción General

El objetivo del proyecto es que puedas aprender y aplicar los principios de la programación funcional junto con un sistema CRUD sencillo conectado a una base de datos **MySQL**, y si te mola la temática pues mejor no?😁

---

## 🧩 Funcionalidades

### 🔁 CRUD Completo
- ✅ **Listar** personajes y batallas
- 📝 **Actualizar** datos
- ❌ **Eliminar** por identificador

### 🧠 Ejercicios de Programación Funcional
- Uso de `streams` y `lambda`
- Filtrar y ordenar según las características de los personajes.
- Transformaciones con `map`
- Agrupaciones según las estadísticas en Map.

---

## ⚙ Tecnologías Usadas

- **Java 23**
- **Maven**
- **MySQL**
- **JDBC** para conexión con la base de datos
- **Programación funcional** con Java Streams

## Configuración y ejecución

- ⚠️ IMPORTANTE: Verifica las credenciales en la clase conexionDB.java y ajustalas según tu configuración.
Ejecuta el contenido del fichero hospital.sql en tu servidor MySQL para generar la base de datos y tablas. Ejecuta el Main.java para poner la aplicación en funcionamiento. 😁

Al ejecutar el programa se insertarán algunos datos predeterminados en la base de datos, una vez ejecutado por primera vez asegurate de comentar las 2 lineas que realizan esta función:
