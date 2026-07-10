# Organización modular y creación de una librería
# 🌄 LlanquihueTourApp5

## 📌 Descripción

**LlanquihueTourApp5** es una aplicación desarrollada en Java como parte de la actividad "Organización modular y creación de una librería personalizada".

El sistema permite gestionar servicios turísticos de la agencia **Llanquihue Tour**, cargando la información desde un archivo de texto (`tours.txt`), almacenándola en una colección dinámica (`ArrayList`) y permitiendo realizar búsquedas por nombre desde la consola.

---

## 🎯 Objetivos

- Aplicar programación orientada a objetos.
- Organizar el proyecto en paquetes.
- Utilizar colecciones (`ArrayList`).
- Leer información desde un archivo `.txt`.
- Implementar búsqueda de registros.
- Manejar excepciones con `try-catch`.

---

## 📂 Estructura del proyecto

```text
LlanquihueTourApp5
│
├── src
│   ├── app
│   │   └── Main.java
│   │
│   ├── model
│   │   ├── ServicioTuristico.java
│   │   ├── RutaGastronomica.java
│   │   ├── PaseoLacustre.java
│   │   └── ExcursionCultural.java
│   │
│   ├── service
│   │   └── GestorServicios.java
│   │
│   └── util
│       └── LectorArchivo.java
│
├── tours.txt
├── README.md
├── build.xml
└── manifest.mf
```

---

## 📦 Paquetes utilizados

### 📁 app
Contiene la clase principal del programa.

- Main.java

### 📁 model
Contiene las clases del modelo.

- ServicioTuristico
- RutaGastronomica
- PaseoLacustre
- ExcursionCultural

### 📁 service
Contiene la lógica para administrar los servicios turísticos.

- GestorServicios

### 📁 util
Contiene la clase encargada de leer el archivo de texto.

- LectorArchivo

---

## ⚙️ Funcionalidades

- Leer servicios turísticos desde un archivo `tours.txt`.
- Guardar los servicios en un `ArrayList`.
- Mostrar todos los servicios registrados.
- Buscar un servicio por nombre.
- Manejar errores mediante `try-catch`.

---

## 🛠 Tecnologías utilizadas

- Java
- Apache NetBeans
- Programación Orientada a Objetos (POO)
- ArrayList
- BufferedReader
- FileReader
- GitHub

---

## ▶️ Cómo ejecutar el proyecto

1. Abrir el proyecto en Apache NetBeans.
2. Verificar que el archivo `tours.txt` esté disponible.
3. Ejecutar la clase **Main.java**.
4. Ingresar el nombre del servicio que desea buscar.
5. Visualizar los resultados en la consola.

---

## 👨‍💻 Autor

**Vicente Estrada**

Asignatura: **Desarrollo Orientado a Objetos I**

Año: **10/07/2026**

---

## ✅ Resultado esperado

Al ejecutar el programa se mostrarán los servicios cargados desde el archivo y el usuario podrá buscar cualquiera de ellos por nombre desde la consola.
