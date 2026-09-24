# Glosario Técnico Final - Fundamentos de Programación

Este documento integra las 40 definiciones correspondientes a la Actividad 2 y la Actividad 4 de la materia de Fundamentos de Programación del Tecnológico de Software.

---

## Parte 1: Conceptos Fundamentales (Actividad 2)

### 1. Algoritmo
* **Definición:** Es una serie de pasos ordenados y finitos que se siguen para resolver un problema o cumplir una tarea específica.
* **Ejemplo:** Una receta para hacer un café: 1. Hervir agua, 2. Servir el café en la taza, 3. Verter el agua, 4. Mezclar.
* **Fuente:** [Joyanes Aguilar, L. (2008). Fundamentos de programación: Algoritmos, estructura de datos y objetos (4.ª ed.). McGraw-Hill](https://dn720004.ca.archive.org/0/items/fundamentos-de-programacion-4ta-edicion-luis-joyanes-aguilar/Fundamentos%20de%20programaci%C3%B3n%2C%204ta%20Edici%C3%B3n%20-%20Luis%20Joyanes%20Aguilar-FREELIBROS.ORG.pdf).

### 2. Programa
* **Definición:** Es un conjunto de instrucciones escritas en un lenguaje que la computadora entiende para ejecutar una tarea o resolver un problema específico de forma automática.
* **Ejemplo:** La aplicación de la calculadora en tu teléfono móvil.
* **Fuente:** [Tanenbaum, A. S. (2013). Sistemas operativos modernos (4.ª ed.). Pearson](https://gc.scalahed.com/recursos/files/r161r/w21040w/Sistemas%20operativos%20modernos.pdf).

### 3. Código fuente
* **Definición:** Es el texto estructurado escrito por un programador usando un lenguaje de programación específico, el cual contiene las instrucciones que luego serán traducidas para que la máquina las ejecute.
* **Ejemplo:** Las líneas de código en Python que escribes en tu editor de texto como `print("Hola Mundo")`.
* **Fuente:** [Stallings, W. (2012). Organización y arquitectura de computadores (9.ª ed.). Pearson](https://ellibrodepython.com/hola-mundo-python).

### 4. Lenguaje de programación
* **Definición:** Es un idioma artificial estructurado con reglas gramaticales y palabras clave que permite a un ser humano darle instrucciones precisas a una computadora.
* **Ejemplo:** Python, C++, Java o JavaScript.
* **Fuente:** [Sebesta, R. W. (2012). Concepts of Programming Languages (10.ª ed.). Pearson](https://www.kiv.zcu.cz/~jezek_ka/vyuka/PGS/Pro%20studenty/PGSSebesta10/concepts-of-programming-languages-10th-sebesta.pdf).

### 5. Sintaxis
* **Definición:** Es el conjunto de reglas que definen cómo deben escribirse los símbolos, palabras y estructuras dentro de un lenguaje de programación para que sea válido.
* **Ejemplo:** Colocar un punto y coma `;` al final de una línea de código en C++ o Java.
* **Fuente:** [Aho, A. V., Lam, M. S., Sethi, R., & Ullman, J. D. (2008). Compiladores: Principios, técnicas y herramientas (2.ª ed.). Pearson](https://books.google.com.gt/books?id=yG6qJBAnE9UC&printsec=frontcover#v=onepage&q&f=false).

### 6. Variable
* **Definición:** Es un espacio reservado en la memoria de la computadora cuyo valor puede cambiar a lo largo de la ejecución del programa.
* **Ejemplo:** `edad = 25`, donde más adelante en el código puede cambiar a `edad = 26`.
* **Fuente:** [Joyanes Aguilar, L. (2008). Fundamentos de programación. McGraw-Hill](https://dn720004.ca.archive.org/0/items/fundamentos-de-programacion-4ta-edicion-luis-joyanes-aguilar/Fundamentos%20de%20programaci%C3%B3n%2C%204ta%20Edici%C3%B3n%20-%20Luis%20Joyanes%20Aguilar-FREELIBROS.ORG.pdf).

### 7. Constante
* **Definición:** Es un valor o dato fijo guardado en memoria que no cambia ni puede ser modificado durante la ejecución del programa.
* **Ejemplo:** El valor de Pi (`PI = 3.1416`).
* **Fuente:** [Joyanes Aguilar, L. (2008). Fundamentos de programación. McGraw-Hill](https://dn720004.ca.archive.org/0/items/fundamentos-de-programacion-4ta-edicion-luis-joyanes-aguilar/Fundamentos%20de%20programaci%C3%B3n%2C%204ta%20Edici%C3%B3n%20-%20Luis%20Joyanes%20Aguilar-FREELIBROS.ORG.pdf).

### 8. Tipo de dato
* **Definición:** Es la clasificación que se le da a un valor para indicarle a la computadora qué tipo de información maneja y qué operaciones puede realizar con ella.
* **Ejemplo:** Números enteros (`int`), texto (`String`), decimales (`float`) o booleanos (`true/false`).
* **Fuente:** [Schildt, H. (2019). Java: The Complete Reference (11.ª ed.). McGraw-Hill](https://www.gandhicollegekada.org/department/Computer/E-Resources/Java-%20The%20Complete%20Reference,%20Eleventh%20Edition%20(%20PDFDrive.com%20).pdf).

### 9. Operador
* **Definición:** Es un símbolo especial que indica a la computadora que debe realizar una acción matemática, lógica o de comparación entre uno o más valores.
* **Ejemplo:** El signo `+` para sumar, `*` para multiplicar o `==` para comparar igualdad.
* **Fuente:** [Deitel, P., & Deitel, H. (2016). C++ How to Program (10.ª ed.). Pearson](https://es.slideshare.net/slideshow/ebook-pdf-c-how-to-program-10th-edition-by-paul-j-deitel/277491258).

### 10. Expresión
* **Definición:** Es una combinación de variables, constantes, operadores y funciones que la computadora evalúa para obtener un único valor final.
* **Ejemplo:** `resultado = (5 + 3) * 2` (se evalúa a 16).
* **Fuente:** [Joyanes Aguilar, L. (2008). Fundamentos de programación. McGraw-Hill](https://dn720004.ca.archive.org/0/items/fundamentos-de-programacion-4ta-edicion-luis-joyanes-aguilar/Fundamentos%20de%20programaci%C3%B3n%2C%204ta%20Edici%C3%B3n%20-%20Luis%20Joyanes%20Aguilar-FREELIBROS.ORG.pdf).

### 11. Condicional
* **Definición:** Es una estructura de control que permite al programa tomar decisiones y ejecutar un bloque de código u otro dependiendo de si una condición se cumple o no.
* **Ejemplo:** `if (edad >= 18)` imprime "Mayor de edad", `else` imprime "Menor de edad".
* **Fuente:** [Deitel, P., & Deitel, H. (2018). Java How to Program (11.ª ed.). Pearson](https://deitel.com/java-how-to-program-11-e-early-objects-version/).

### 12. Bucle (Loop / Ciclo)
* **Definición:** Es una estructura de control que repite un bloque de código de forma automática varias veces hasta que se cumpla una condición de parada.
* **Ejemplo:** Un ciclo `while` o `for` que imprime los números del 1 al 100.
* **Fuente:** [Joyanes Aguilar, L. (2008). Fundamentos de programación. McGraw-Hill](https://dn720004.ca.archive.org/0/items/fundamentos-de-programacion-4ta-edicion-luis-joyanes-aguilar/Fundamentos%20de%20programaci%C3%B3n%2C%204ta%20Edici%C3%B3n%20-%20Luis%20Joyanes%20Aguilar-FREELIBROS.ORG.pdf).

### 13. Función
* **Definición:** Es un bloque de código reutilizable diseñado para realizar una tarea específica cuando es invocado o llamado dentro del programa.
* **Ejemplo:** Una función llamada `calcularPromedio()` que toma calificaciones y devuelve la nota final.
* **Fuente:** [Cormen, T. H., Leiserson, C. E., Rivest, R. L., & Stein, C. (2009). Introduction to Algorithms (3.ª ed.). MIT Press](https://computo.fismat.umich.mx/~htejeda/books/algoritmos/Introduction_to_algorithms_Third_Edition_Cormen_Leiserson_Rivest_Stein.pdf).

### 14. Parámetro
* **Definición:** Es la variable declarada en la definición de una función que especifica el tipo de dato que la función espera recibir para trabajar.
* **Ejemplo:** En la firma `function sumar(a, b)`, `a` y `b` son los parámetros.
* **Fuente:** [Sebesta, R. W. (2012). Concepts of Programming Languages. Pearson](https://www.kiv.zcu.cz/~jezek_ka/vyuka/PGS/Pro%20studenty/PGSSebesta10/concepts-of-programming-languages-10th-sebesta.pdf).

### 15. Argumento
* **Definición:** Es el valor real y concreto que se le envía a una función cuando es llamada o ejecutada en el código.
* **Ejemplo:** Al ejecutar `sumar(10, 5)`, los números `10` y `5` son los argumentos.
* **Fuente:** [Sebesta, R. W. (2012). Concepts of Programming Languages. Pearson](https://www.kiv.zcu.cz/~jezek_ka/vyuka/PGS/Pro%20studenty/PGSSebesta10/concepts-of-programming-languages-10th-sebesta.pdf).

### 16. Retorno
* **Definición:** Es el valor final o resultado que una función procesa y envía de regreso al lugar donde fue llamada dentro del programa.
* **Ejemplo:** La instrucción `return a + b;` al final de una función de suma.
* **Fuente:** [Deitel, P., & Deitel, H. (2016). C++ How to Program. Pearson](https://faculty.ksu.edu.sa/sites/default/files/c_how_to_program_with_an_introduction_to_c_global_edition_8th_edition.pdf).

### 17. Arreglo (Array / Vector)
* **Definición:** Es una estructura de datos que permite almacenar múltiples elementos del mismo tipo de forma ordenada bajo una sola variable, accesibles mediante índices.
* **Ejemplo:** Una lista de compras: `compras = ["Manzanas", "Leche", "Pan"]`.
* **Fuente:** [Joyanes Aguilar, L. (2008). Fundamentos de programación. McGraw-Hill](https://dn720004.ca.archive.org/0/items/fundamentos-de-programacion-4ta-edicion-luis-joyanes-aguilar/Fundamentos%20de%20programaci%C3%B3n%2C%204ta%20Edici%C3%B3n%20-%20Luis%20Joyanes%20Aguilar-FREELIBROS.ORG.pdf).

### 18. Objeto
* **Definición:** Es una entidad dentro de la programación orientada a objetos que combina características (atributos) y comportamientos (métodos) para representar algo de la vida real o del sistema.
* **Ejemplo:** Un objeto `Auto` que tiene atributos como `color = "Rojo"` y `velocidad = 80`.
* **Fuente:** [Booch, G., Maksimchuk, R. A., Engel, M. W., Young, B. J., Conallen, J., & Houston, K. A. (2007). Object-Oriented Analysis and Design with Applications (3.ª ed.). Addison-Wesley](https://www.auhd.edu.ye/upfiles/elibrary/Azal2020-01-22-01-00-32-27635.pdf).

### 19. Método
* **Definición:** Es una función o acción asociada exclusivamente a un objeto o clase que define lo que dicho objeto puede hacer.
* **Ejemplo:** El método `frenar()` o `acelerar()` perteneciente al objeto `Auto`.
* **Fuente:** [Booch, G., et al. (2007). Object-Oriented Analysis and Design with Applications. Addison-Wesley](https://www.auhd.edu.ye/upfiles/elibrary/Azal2020-01-22-01-00-32-27635.pdf).

### 20. Evento
* **Definición:** Es una acción o acontecimiento detectado por el programa (provocado por el usuario o por el sistema) ante el cual el código debe reaccionar.
* **Ejemplo:** Hacer clic en un botón con el ratón (`onClick`) o presionar una tecla.
* **Fuente:** [Flanagan, D. (2020). JavaScript: The Definitive Guide (7.ª ed.). O'Reilly Media](https://forum.freemdict.com/uploads/short-url/l179nDbeiEq7d3M6TUUfZGEP6zc.pdf).

---

## Parte 2: Herramientas, Entornos y Control de Versiones (Actividad 4)

### 21. Compilador
* **Definición:** Programa especializado que traduce la totalidad del código fuente escrito en un lenguaje de alto nivel a código máquina o binario ejecutable antes de que el programa sea ejecutado.
* **Ejemplo:** Al compilar un programa en C++ con GCC (`g++ main.cpp -o programa`), se genera un archivo binario independiente.
* **Fuente:** [GNU Compiler Collection Docs](https://gcc.gnu.org/onlinedocs/).

### 22. Intérprete
* **Definición:** Motor de ejecución que lee, analiza y procesa el código fuente instrucción por instrucción en tiempo real, sin generar un archivo ejecutable previo.
* **Ejemplo:** El motor de Python o V8 de Node.js interpretan `print('Hola Mundo')` inmediatamente en la terminal.
* **Fuente:** [Python Interpreter Guide](https://docs.python.org/3/tutorial/interpreter.html).

### 23. Depurador (Debugger)
* **Definición:** Herramienta de desarrollo que permite inspeccionar la ejecución interna de un programa paso a paso mediante puntos de interrupción (`breakpoints`).
* **Ejemplo:** Usar el depurador de VS Code para pausar un programa en `if (usuario == null)` y verificar variables en memoria.
* **Fuente:** [VS Code Debugging Docs](https://code.visualstudio.com/docs/editor/debugging).

### 24. IDE (Entorno de Desarrollo Integrado)
* **Definición:** Aplicación de software integral que reúne editor de código avanzado, compilador, depurador y gestor de dependencias en una sola interfaz.
* **Ejemplo:** Visual Studio, IntelliJ IDEA o Eclipse para sistemas empresariales.
* **Fuente:** [JetBrains IntelliJ Guide](https://www.jetbrains.com/idea/).

### 25. Editor de Código
* **Definición:** Aplicación ligera optimizada para escribir y modificar archivos de texto plano con código fuente, destacando por su extensibilidad.
* **Ejemplo:** Visual Studio Code o Sublime Text para escribir HTML, CSS o Python.
* **Fuente:** [Visual Studio Code Docs](https://code.visualstudio.com/).

### 26. Biblioteca (Library)
* **Definición:** Conjunto de funciones, módulos y clases reutilizables prediseñadas que los desarrolladores invocan para realizar tareas específicas sin programar desde cero.
* **Ejemplo:** Importar `axios` en JavaScript para realizar peticiones HTTP mediante `axios.get('/api/datos')`.
* **Fuente:** [MDN JavaScript Guide](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide).

### 27. Framework
* **Definición:** Estructura o plantilla de trabajo estandarizada que proporciona la arquitectura base y aplica el principio de Inversión de Control.
* **Ejemplo:** Angular, React, Django o Laravel para construir aplicaciones web estructuradas.
* **Fuente:** [Angular Official Docs](https://angular.dev/).

### 28. API (Interfaz de Programación de Aplicaciones)
* **Definición:** Conjunto de protocolos y reglas que permite que dos sistemas informáticos o componentes de software se comuniquen e intercambien datos.
* **Ejemplo:** Google Maps API para consultar coordenadas y mapas desde una aplicación móvil.
* **Fuente:** [AWS API Reference](https://aws.amazon.com/es/what-is/api/).

### 29. Repositorio
* **Definición:** Almacén o depósito digital estructurado donde se guardan todos los archivos de código fuente y su historial de revisiones.
* **Ejemplo:** Un repositorio en Git con el código fuente de una aplicación y su bitácora de cambios.
* **Fuente:** [GitHub Repositories Docs](https://docs.github.com/es/repositories).

### 30. Control de Versiones
* **Definición:** Sistema que registra de manera cronológica e incremental los cambios sobre un conjunto de archivos para auditar modificaciones y revertir estados.
* **Ejemplo:** Gestionar versiones `v1.0`, `v1.1` y revertir cambios si un error afecta producción.
* **Fuente:** [Git Book (Control de Versiones)](https://git-scm.com/book/es/v2/).

### 31. Git
* **Definición:** Sistema distribuido de control de versiones de código abierto que opera localmente mediante comandos de consola.
* **Ejemplo:** Ejecutar `git init` para iniciar seguimiento y `git status` para revisar archivos.
* **Fuente:** [Git Official Documentation](https://git-scm.com/doc).

### 32. GitHub
* **Definición:** Plataforma en la nube basada en la web que aloja repositorios de Git y facilita la colaboración mediante Pull Requests e Issues.
* **Ejemplo:** Publicar un proyecto en `github.com/usuario/proyecto` para recibir contribuciones.
* **Fuente:** [GitHub Documentation](https://docs.github.com/).

### 33. Rama (Branch)
* **Definición:** Línea de desarrollo independiente dentro de un repositorio de Git para trabajar en funciones sin alterar la rama principal (`main`).
* **Ejemplo:** Crear la rama `git checkout -b feature/login` para programar el inicio de sesión.
* **Fuente:** [Git Branching Reference](https://git-scm.com/book/es/v2/).

### 34. Commit
* **Definición:** Captura instantánea (`snapshot`) permanente de los cambios confirmados dentro del historial del repositorio, con un hash único.
* **Ejemplo:** Ejecutar `git commit -m 'Agregar validación al formulario'` para guardar los cambios.
* **Fuente:** [Git Commit Reference](https://git-scm.com/docs/git-commit).

### 35. Merge
* **Definición:** Operación de fusión que unifica el historial y los cambios de una rama secundaria dentro de otra rama destino.
* **Ejemplo:** Ejecutar `git merge feature/login` sobre la rama `main`.
* **Fuente:** [Git Merge Reference](https://git-scm.com/docs/git-merge).

### 36. Callback
* **Definición:** Función que se pasa como argumento a otra función para ser invocada posteriormente al completarse una tarea.
* **Ejemplo:** `boton.addEventListener('click', () => { alert('¡Clic!'); })`.
* **Fuente:** [MDN Callback Glossary](https://developer.mozilla.org/es/docs/Glossary/Callback_function).

### 37. Programación Síncrona
* **Definición:** Modelo de ejecución secuencial y bloqueante donde cada instrucción debe finalizar antes de que el procesador pase a la siguiente.
* **Ejemplo:** Instrucciones consecutivas donde la lectura síncrona de un archivo pesado congela el hilo principal.
* **Fuente:** [MDN Asynchronous JS Guide](https://developer.mozilla.org/es/docs/Learn/JavaScript/Asynchronous/).

### 38. Programación Asíncrona
* **Definición:** Modelo de ejecución no bloqueante que permite iniciar tareas de larga duración y continuar ejecutando otras instrucciones mientras se espera la respuesta.
* **Ejemplo:** Usar `async/await` o `fetch()` para solicitar datos a un servidor sin congelar la interfaz.
* **Fuente:** [MDN Async Function Reference](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/).

### 39. JavaScript
* **Definición:** Lenguaje de programación interpretado, dinámico y orientado a objetos y eventos, estándar para web y servidores mediante Node.js.
* **Ejemplo:** Scripts que modifican dinámicamente el contenido de un sitio web.
* **Fuente:** [MDN JavaScript Portal](https://developer.mozilla.org/es/docs/Web/JavaScript).

### 40. TypeScript
* **Definición:** Superconjunto de JavaScript desarrollado por Microsoft que añade tipado estático y se transpila a JavaScript estándar.
* **Ejemplo:** Declarar `let edad: number = 25` para alertar errores de asignación de tipos.
* **Fuente:** [TypeScript Official Docs](https://www.typescriptlang.org/docs/).

---

## Referencias Bibliográficas Generales
* Joyanes Aguilar, L. (2008). *Fundamentos de programación: Algoritmos, estructura de datos y objetos* (4.ª ed.). McGraw-Hill.
* Pressman, R. S. (2010). *Ingeniería del Software: Un Enfoque Práctico* (7.ª ed.). McGraw-Hill.
* Sommerville, I. (2011). *Ingeniería de Software* (9.ª ed.). Pearson.
* Piattini, M. G. (2017). *Calidad de Sistemas Informáticos*. Alfaomega.
* Git Documentation (2026). *Official Git Reference and Book*.

---
*Elaborado individualmente por Geovanny Serralta para la materia de Fundamentos de Programación - Tecnológico de Software.*
