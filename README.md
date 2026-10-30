# Sistema de Gestión de Inventarios — Centro «Una Familia de Familias» (Quito)
**Actividad Práctico-Experimental M1S4 (RA1 y RA2 — Programación Orientada a Objetos)**

## 1. Contenido del Proyecto (Sin carpetas `build`, `target`, `out`, `bin` ni `node_modules`)
- `src/GestionBodegaDonaciones.java`: **Programa Iterativo/Condicional Principal**. Implementa las reglas de negocio **RN-01 a RN-06** (arreglos paralelos para 5 productos donados, menú `do-while` + `switch`, listado tabular con `for` y `printf`, validaciones `do-while` en ingreso y despacho, alertas de caducidad con `switch` mejorado `->` y resumen estadístico de cierre).
- `src/ClasificadorPrioridadDonacion.java`: **Programa Condicional 1 (`if / else if / else`)**. Clasifica lotes entrantes según días de vigencia e integridad del envase.
- `src/AsignadorRacionesFamiliares.java`: **Programa Condicional 2 (`switch` + `if`)**. Calcula el kit alimentario y peso en kilogramos asignado a cada familia beneficiaria en Quito según su categoría (`A`, `B`, `C`, `D`) y número de integrantes.
- `src/ControlTemperaturaCamaraFria.java`: **Programa Iterativo 2 (`while` + `for`)**. Registra las lecturas térmicas de la cámara fría de lácteos (2 °C a 8 °C), calcula el promedio y detecta alertas.
- `src/PrototipoBodegaGUI.java`: **Módulo Cocreativo POO + Persistencia CSV + GUI Swing**. Demuestra la encapsulación en la clase `ProductoDonado`, la generación del archivo `inventario_quito.csv` (Cero Papel) y la estructura de eventos en `JFrame`.

## 2. Cómo Compilar y Ejecutar en Consola o IDE (NetBeans / IntelliJ / VS Code / Eclipse)
Desde la carpeta raíz del proyecto, puedes ejecutar directamente cualquiera de los programas con Java 17+:
```bash
java src/GestionBodegaDonaciones.java
java src/ClasificadorPrioridadDonacion.java
java src/AsignadorRacionesFamiliares.java
java src/ControlTemperaturaCamaraFria.java
java src/PrototipoBodegaGUI.java
```
O compilando de forma tradicional:
```bash
javac src/*.java
java -cp src GestionBodegaDonaciones
```
