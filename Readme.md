# Torneo de Fútbol - Repositorio


## Configuración de la Base de Datos

1. **Crear y utilizar la base de datos `torneoDeFutbol`:**
    use torneoDeFutbol

2. **Crear colecciones:**
    db.createCollection("equipos")
    db.createCollection("fases")
    db.createCollection("partidos")
    db.createCollection("arbitros")
    db.createCollection("posiciones")
    db.createCollection("resultados")

## Insertar Documentos en cada Colección

3. **Insertar documentos en la colección `equipos`:**
    ```
    db.equipos.insertMany([
      // Aquí van los documentos para la colección 'equipos', el archivo .json
    ])
    ```
 **Insertar documentos en la colección `fases`:**
    ```javascript
    db.fases.insertMany([
      // Aquí van los documentos para la colección 'fases', el archivo .json
    ])
    ```
 **Insertar documentos en la colección `partidos`:**
    ```javascript
    db.partidos.insertMany([
      // Aquí van los documentos para la colección 'partidos', el archivo .json
    ])
    ```
 **Insertar documentos en la colección `arbitros`:**
    ```
    db.arbitros.insertMany([
      // Aquí van los documentos para la colección 'arbitros', el archivo .json
    ])
    ```
 **Insertar documentos en la colección `posiciones`:**
    ```
    db.posiciones.insertMany([
      // Aquí van los documentos para la colección 'posiciones', el archivo .json
    ])
    ```
 **Insertar documentos en la colección `resultados`:**
    ```
    db.resultados.insertMany([
      // Aquí van los documentos para la colección 'resultados', el archivo .json
    ])
    ```
