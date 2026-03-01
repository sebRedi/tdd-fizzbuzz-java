# TDD FizzBuzz en Java

## Descripción del Proyecto
Este repositorio contiene el desarrollo de un laboratorio académico cuyo objetivo es aplicar la metodología de **Desarrollo Guiado por Pruebas (Test Driven Development – TDD)** mediante la implementación del ejercicio clásico **FizzBuzz** en el lenguaje de programación **Java**, utilizando **JUnit 5**, **Maven** y **GitHub Codespaces** como entorno de desarrollo.

El laboratorio sigue el ciclo fundamental de TDD:  
**Red → Green → Refactor**, priorizando la escritura de pruebas antes de la implementación del código funcional.

---

## Objetivo del Laboratorio
- Comprender y aplicar la metodología **TDD**.
- Implementar pruebas unitarias usando **JUnit 5**.
- Desarrollar código incremental y validado mediante pruebas automatizadas.
- Familiarizarse con la estructura de un proyecto Java basado en **Maven**.
- Utilizar **GitHub Codespaces** como entorno de desarrollo en la nube.

---

## Metodología TDD Aplicada
El desarrollo del laboratorio se realizó siguiendo los siguientes pasos:

1. **Escritura de la primera prueba**  
   Se creó una prueba unitaria para verificar que, al ingresar un número que no sea múltiplo de 3 ni de 5, el método retorna el mismo número como cadena.

2. **Implementación mínima**  
   Se implementó la funcionalidad mínima necesaria para que la prueba pasara correctamente.

3. **Adición progresiva de pruebas**  
   Se agregaron pruebas para validar los siguientes casos:
   - Múltiplos de 3 → `"Fizz"`
   - Múltiplos de 5 → `"Buzz"`
   - Múltiplos de 3 y 5 → `"FizzBuzz"`

4. **Ajuste de la lógica**  
   Se modificó la implementación del método `fizzbuzz` hasta que todas las pruebas pasaran exitosamente.

5. **Validación continua**  
   Después de cada cambio se ejecutaron las pruebas utilizando Maven para garantizar la estabilidad del código.

---

## Estructura del Proyecto
```
tdd-fizzbuzz-java
├── pom.xml
├── README.md
└── src
    ├── main
    │   └── java
    │       └── FizzBuzz.java
    └── test
        └── java
            └── FizzBuzzTest.java
```

---

## Tecnologías Utilizadas
- **Java**
- **JUnit 5**
- **Apache Maven**
- **GitHub Codespaces**

---

## Ejecución del Proyecto
Para ejecutar las pruebas del proyecto, utilice el siguiente comando en la raíz del repositorio:

```bash
mvn test
```

---

## Resultados
- Todas las pruebas unitarias pasan exitosamente.
- La funcionalidad FizzBuzz cumple con los requisitos definidos.
- El desarrollo sigue correctamente los principios de TDD.

---

## Conclusiones
La metodología TDD permite construir software más confiable y mantenible, ya que cada cambio en el código es validado inmediatamente mediante pruebas automatizadas. Este laboratorio demuestra cómo una implementación incremental, guiada por pruebas, reduce errores y mejora la calidad del código.

---

## Trabajo Futuro
- Agregar más pruebas unitarias para casos límite.
- Refactorizar el código para mejorar su legibilidad.
- Integrar el proyecto con un pipeline de **CI/CD** utilizando **GitHub Actions**.
- Ampliar el ejercicio a otros problemas clásicos usando TDD.

---

## Autor
**Sebastian Galvis Briceño**

Laboratorio académico – Desarrollo Guiado por Pruebas (TDD)
