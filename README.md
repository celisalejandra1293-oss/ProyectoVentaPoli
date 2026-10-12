# ProyectoVentaPoli
## Generación y clasificación de datos

Proyecto académico desarrollado en Java para generar archivos de prueba de vendedores, productos y ventas, procesar la información y producir reportes ordenados.

### Requisitos
- Java instalado.
- Terminal de macOS o un entorno de desarrollo compatible con Java.

### Archivos principales
- `src/GenerateInfoFiles.java`: genera los archivos de prueba.
- `src/main.java`: procesa las ventas y genera los reportes.
- `products_info.txt`: información de productos.
- `salesmen_info.txt`: información de vendedores.
- `salesmen_report.csv`: recaudo por vendedor, ordenado de mayor a menor.
- `products_report.csv`: productos ordenados por cantidad vendida.
- `conslusion.txt`: conclusiones del proyecto.

### Cómo ejecutar el proyecto

Desde la carpeta principal del proyecto, compilar las clases:

```bash
javac -d bin src/GenerateInfoFiles.java src/main.java
```

Generar los archivos de prueba:

```bash
java -cp bin GenerateInfoFiles
```

Procesar las ventas y generar los reportes:

```bash
java -cp bin main
```

Los programas no solicitan datos por teclado. Al finalizar, muestran un mensaje de éxito o un mensaje de error.

### Autoría
Proyecto académico del módulo Conceptos Fundamentales de Programación.
Politécnico Grancolombiano.
