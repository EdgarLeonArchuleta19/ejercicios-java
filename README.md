<div align="center">

# ☕ Ejercicios de Java

### Colección Universitaria de Prácticas, Algoritmos, Estructuras de Datos, Interfaces Gráficas y Desarrollo Web

[![Java](https://img.shields.io/badge/Java-8%2B%20%7C%2017%2B-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![Swing GUI](https://img.shields.io/badge/GUI-Java%20Swing%20%2F%20AWT-5382A1?style=for-the-badge&logo=java&logoColor=white)](https://docs.oracle.com/javase/tutorial/uiswing/)
[![Data Structures](https://img.shields.io/badge/Estructuras-Datos%20y%20Algoritmos-success?style=for-the-badge)](./ED)
[![Concurrency](https://img.shields.io/badge/Concurrencia-Hilos%20y%20Sockets-blueviolet?style=for-the-badge)](./SO)
[![Web](https://img.shields.io/badge/M%C3%B3dulo%20Web-HTML5%20%7C%20CSS3%20%7C%20Node.js-E34F26?style=for-the-badge&logo=html5&logoColor=white)](./practicas-web)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](./LICENSE)

<br/>

**ejercicios-java** es un repositorio que unifica y preserva la colección de proyectos, ejercicios y prácticas académicas desarrolladas a lo largo de la formación universitaria en Ciencias de la Computación e Ingeniería de Software.

Abarca desde fundamentos de programación orientada a objetos (POO), estructuras de datos lineales y no lineales, sistemas concurrentes y clientes/servidores con sockets TCP/IP, hasta aplicaciones gráficas completas con Swing/AWT, inteligencia artificial con búsqueda en espacios de estados, y un módulo integral de maquetación y desarrollo web.

[Módulos y Materias](#-módulos-y-materias-incluidas) •
[Estructura del Repositorio](#-estructura-del-repositorio) •
[Módulo Web](#-módulo-web-practicas-web) •
[Requisitos y Ejecución](#-requisitos-y-ejecución) •
[Autor](#-autor)

</div>

---

## 🗂️ Módulos y Materias Incluidas

| Módulo / Materia | Directorio | Descripción y Temas Clave |
| :--- | :--- | :--- |
| **Estructuras de Datos** | [`/ED`](./ED) | Implementación de estructuras fundamentales: Árboles Binarios (`Arbol`), Pilas (`Pila`), Colas (`Cola`, `ColaManual`), Listas Enlazadas (`iLISTA`) y evaluador/conversor de expresiones aritméticas (infijas y postfijas). |
| **Sistemas Operativos** | [`/SO`](./SO) | Redes y comunicación Cliente-Servidor mediante Sockets TCP/IP (`Cliente.java`, `Servidor.java`), concurrencia con hilos (`Threads`), sincronización y paso de mensajes. |
| **Concurrencia y Sincronización** | [`/clinica`](./clinica) | Resolución clásica del problema **Productor-Consumidor** empleando un `BufferCircular`, monitores sincronizados y control de concurrencia en Java. |
| **Inteligencia Artificial** | [`/puzzle8`](./puzzle8) | Resolución del rompecabezas clásico **8-Puzzle** mediante representación de espacio de estados, heurísticas y algoritmos de búsqueda ciega e informada. |
| **Graficación por Computadora** | [`/GRAFICACION`](./GRAFICACION) | Renderizado de primitivas 2D/3D, algoritmos raster de trazado de líneas y transformaciones geométricas. |
| **Lenguajes y Autómatas** | [`/LENGUAJES`](./LENGUAJES) | Compiladores: Analizador léxico (`Scanner.java`), analizador sintáctico (`Parser.java`) y evaluación de reglas gramaticales. |
| **Métodos Numéricos** | [`/MN`](./MN) | Algoritmos de cálculo computacional, aproximaciones numéricas, raíces de ecuaciones y resolución matricial. |
| **Interfaces Gráficas (MVC & Swing)** | [`/proyectocatalogo`](./proyectocatalogo)<br>[`/Dibujo`](./Dibujo)<br>[`/BARAJA`](./BARAJA) | • **Lienzo de Dibujo:** Aplicación gráfica interactiva tipo Paint con arquitectura MVC y `Graphics2D`.<br>• **Baraja Española:** Simulación interactiva con barajado dinámico e interfaz Swing.<br>• **Catálogo Comercial:** Catálogo de productos con separación desacoplada Modelo-Vista-Controlador. |
| **Bases de Datos & JDBC** | [`/BD`](./BD)<br>[`/SQL`](./SQL)<br>[`/SQL2`](./SQL2)<br>[`/EQUIPO`](./EQUIPO) | Conexión a bases de datos relacionales (Microsoft SQL Server / MySQL) mediante JDBC (`mssql-jdbc`), procedimientos almacenados (`CallableStatement`), transacciones y consultas CRUD. |
| **Sistemas Integrales** | [`/MoviTec`](./MoviTec) | Sistema de transporte y movilidad escolar con interfaz Swing, autenticación con roles diferenciados (Alumno / Empleado) y persistencia relacional. |
| **Simulación y Probabilidad** | [`/BORRACHO`](./BORRACHO) | Modelado estocástico de la caminata aleatoria (*Random Walk* / Problema del Borracho) en 2D. |
| **Laboratorio de Algoritmos** | [`/PRUEBAS`](./PRUEBAS) | Banco de ejercicios variados: Simulación de física (`caidaparacaidista.java`), cajero automático interactivo (`CajeroATM.java`), visualización de gráficas estadísticas (`CombinedXYPlotDemo.java`) y lógica algorítmica. |
| **Desarrollo Web (Unificado)** | [`/practicas-web`](./practicas-web) | Módulo unificado de prácticas web: Maquetación responsive moderna con HTML5 y CSS3, examen práctico, y proyecto full-stack con backend Node.js/Express y frontend Vue.js. |

---

## 📁 Estructura del Repositorio

```text
ejercicios-java/
├── BARAJA/                 # Juego y simulación gráfica de baraja española (Swing + AWT)
├── BD/                     # Conexión JDBC a base de datos, procedimientos almacenados y CRUD
├── BORRACHO/               # Algoritmo de caminata aleatoria (Random Walk)
├── clinica/                # Concurrencia: Problema Productor-Consumidor con Buffer Circular
├── Dibujo/                 # Aplicación tipo Paint con arquitectura MVC y Java Graphics2D
├── ED/                     # Estructuras de Datos (Árboles binarios, Pilas, Colas, Listas)
├── EQUIPO/                 # Sistema de gestión de equipos con consultas SQL e impresiones
├── GRAFICACION/            # Graficación por computadora (algoritmos 2D/3D y primitivas)
├── LENGUAJES/              # Compiladores: Scanner léxico, Parser sintáctico y tokens
├── MN/                     # Métodos Numéricos y cálculo computacional
├── MoviTec/                # Sistema integral de movilidad escolar con interfaz Swing y BD
├── proyectocatalogo/       # Catálogo de productos con patrón MVC
├── PRUEBAS/                # Ejercicios variados (Física, Cajero ATM, Gráficas XY, POO)
├── puzzle8/                # Búsqueda en espacio de estados e IA para el 8-Puzzle
├── SO/                     # Sistemas Operativos: Sockets Cliente-Servidor TCP/IP y Threads
├── SQL/ & SQL2/            # Scripts de bases de datos, esquemas relacionales y librerías JDBC
├── practicas-web/          # Módulo unificado de prácticas web (HTML5, CSS3, JS, Node, Vue)
│   ├── practica01css/ .. practica07_/  # Prácticas progresivas de maquetación CSS
│   ├── practica10_examen/              # Evaluación práctica de maquetación web
│   └── proyecto/                       # Proyecto Full-Stack: Backend Express + Frontend Vue
├── .gitignore              # Exclusiones estándar para Java, Node y entornos
├── LICENSE                 # Licencia de código abierto MIT
└── README.md               # Documentación general del repositorio
```

---

## 🚀 Requisitos y Ejecución

### Prerrequisitos
- **Java Development Kit (JDK):** Versión 8 o superior (recomendado JDK 17 o 21 LTS).
- **Node.js (opcional, para módulo web):** Versión 18+ y npm.

### Compilar y Ejecutar un Módulo Java
Para compilar y ejecutar cualquier clase principal desde la terminal:

```bash
# Ejemplo 1: Ejecutar el algoritmo del 8-Puzzle
cd puzzle8
javac *.java
java MenuBusqueda

# Ejemplo 2: Ejecutar el problema del Productor-Consumidor
cd clinica/src
javac *.java
java PruebaBuferCircular

# Ejemplo 3: Ejecutar la aplicación de Dibujo (Paint MVC)
cd Dibujo
javac *.java
java Dibujo
```

### Ejecutar Módulos con Dependencias JDBC
Algunos proyectos (`BD`, `MoviTec`, `SQL`) incluyen controladores JDBC en su carpeta `lib/` o `librerias/`:

```bash
# Compilar con el classpath apuntando a la librería
javac -cp ".;lib/*" *.java

# Ejecutar incluyendo dependencias
java -cp ".;lib/*" Main
```

*(En sistemas basados en Unix como Linux o macOS, sustituir el separador `;` por `:`)*.

---

## 🌐 Módulo Web (`/practicas-web`)

Para visualizar las prácticas de HTML5 y CSS3:
- Abre cualquier archivo `index.html` directamente en tu navegador web preferido o mediante la extensión *Live Server* de VS Code.

Para ejecutar el proyecto Full-Stack (`/practicas-web/proyecto`):

```bash
# 1. Iniciar Backend (Node.js + Express)
cd practicas-web/proyecto/backend
npm install
node app.js

# 2. Iniciar Frontend (Vue.js + Vite)
cd ../frontend/tienda
npm install
npm run dev
```

---

## ⚖️ Licencia

Distribuido bajo la Licencia **MIT**. Consulta el archivo [LICENSE](LICENSE) para más detalles.

---

## 👨‍💻 Autor

**Edgar León Archuleta**
- 📍 Culiacán, Sinaloa, México
- 🌐 Portafolio: [edgarleonarchuleta19.github.io/portafolio](https://edgarleonarchuleta19.github.io/portafolio/)
- 🐙 GitHub: [@EdgarLeonArchuleta19](https://github.com/EdgarLeonArchuleta19)
- 💼 LinkedIn: [Edgar León Archuleta](https://www.linkedin.com/in/edgar-le%C3%B3n-archuleta-51b57128a/)
- ✉️ Correo: [leonedgar190@gmail.com](mailto:leonedgar190@gmail.com)