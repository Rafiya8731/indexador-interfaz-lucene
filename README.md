# Indexador de Productos y Reseñas con Apache Lucene
Este proyecto es un indexador en Java que utiliza Apache Lucene para buscar y organizar productos y reseñas almacenados en archivos JSON.

Características Principales
- Indexación de productos y reseñas desde archivos JSON.
- Búsqueda rápida y eficiente utilizando Apache Lucene.
- Interfaz sencilla para realizar consultas.

Tecnologías Utilizadas
- **Lenguaje**: Java
- **Biblioteca**: Apache Lucene
- **Formato de datos**: JSON
- **Herramientas**: Maven (gestión de dependencias), Git (control de versiones)

## Uso

### 1. Ejecutar el Indexador (Crear índices Metadata, Metadata Analizado y Reviews Agrupadas)
```bash
java -jar Indexar.jar
```
Saldra por terminal un menú en el que hay que crear como mínimo los índices metadata, metadata analizado y reviews agrupadas (que son los índices que se usan en la interfaz).
### 2. Ejercutar la interfaz
```bash
java -jar Interfaz.jar
```
