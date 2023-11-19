# Torneo de Fútbol - Repositorio

Este repositorio contiene el código fuente de un proyecto de torneo de fútbol que utiliza MongoDB como su base de datos. A continuación, se describen los pasos necesarios para crear la base de datos, las colecciones y los documentos requeridos.

## Configuración de la Base de Datos

1. **Crear y utilizar la base de datos `torneoDeFutbol`:**
    ```
    use torneoDeFutbol
    ```

2. **Crear colecciones:**
    ```
    db.createCollection("equipos")
    db.createCollection("fases")
    db.createCollection("partidos")
    db.createCollection("arbitros")
    db.createCollection("posiciones")
    db.createCollection("resultados")
    ```

## Insertar Documentos en cada Colección

3. **Insertar documentos en la colección `equipos`:**
    ```
    db.equipos.insertMany([
      // Aquí van los documentos para la colección 'equipos', alojados en el archivo .json
    ])
    ```

4. **Insertar documentos en la colección `fases`:**
    ```
    db.fases.insertMany([
      // Aquí van los documentos para la colección 'fases', alojados en el archivo .json
    ])
    ```

5. **Insertar documentos en la colección `partidos`:**
    ```
    db.partidos.insertMany([
      // Aquí van los documentos para la colección 'partidos', alojados en el archivo .json
    ])
    ```

6. **Insertar documentos en la colección `arbitros`:**
    ```
    db.arbitros.insertMany([
      // Aquí van los documentos para la colección 'arbitros', alojados en el archivo .json
    ])
    ```

7. **Insertar documentos en la colección `posiciones`:**
    ```
    db.posiciones.insertMany([
      // Aquí van los documentos para la colección 'posiciones', alojados en el archivo .json
    ])
    ```

8. **Insertar documentos en la colección `resultados`:**
    ```
    db.resultados.insertMany([
      // Aquí van los documentos para la colección 'resultados', alojados en el archivo .json
    ])
    ```