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

### 1. Ejecutar el Indexador
```bash
  java -jar Indexar.jar
```
Ejecutar el indexador: java -jar Indexar.jar
Saldra por terminal un menu en el que hay que crear como minimo los indices metadata, metadata analizado y reviews agrupadas (que son los índices que se usan en la interfaz).
Ejercutar la interfaz: java -jar Interfaz.jar
