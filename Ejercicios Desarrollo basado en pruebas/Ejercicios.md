# Ejercicios - Desarrollo basado en pruebas
---

### 1. Descargar y ejecutar las pruebas de alguno de los proyectos anteriores, y si sale todo bien, hacer un pull request a alguno de esos proyectos con tests adicionales, si es que faltan (en el momento que se lea este tema).

![Ejercicio1](https://github.com/iMiguel10/Ejercicios-IV/blob/master/Ejercicios%20Desarrollo%20basado%20en%20pruebas/Ejercicio1.PNG)

---

### 2. Para la aplicación que se está haciendo, escribir una serie de aserciones y probar que efectivamente no fallan. Añadir tests para una nueva funcionalidad, probar que falla y escribir el código para que no lo haga (vamos, lo que viene siendo TDD).

En mi proyecto ya tenemos una serie de test hechos con unittest, [TEST](https://github.com/iMiguel10/Proyecto-IV-Porra-Deportiva-/blob/master/test/test.py).

---

### 3. Crear algún conjunto de scripts de tests, usando tu lenguaje favorito, y ejecutarlos desde el marco de test más adecuado (o el que más te guste) para ese lenguaje.

En mi proyecto tenemos una serie de test hechos para pytest, [TEST](https://github.com/iMiguel10/Proyecto-IV-Porra-Deportiva-/blob/master/test/test_porra-dep-app.py).

---

### 4. Instalar alguno de los entornos virtuales de node.js (o de cualquier otro lenguaje con el que se esté familiarizado) y, con ellos, instalar la última versión existente, la versión minor más actual de la 4.x y lo mismo para la 0.11 o alguna impar (de desarrollo).
---

### 5. Como ejercicio, algo ligeramente diferente: una web para calificar las empresas en las que hacen prácticas los alumnos. 
Las acciones serían:  

* Crear empresa
* Listar calificaciones para cada empresa
* crear calificación y añadirla (comprobando que la persona no la haya añadido ya)
* borrar calificación (si se arrepiente o te denuncia la empresa o algo)
* Hacer un ránking de empresas por calificación, por ejemplo
* Crear un repositorio en GitHub para la librería y crear un pequeño programa que use algunas de sus funcionalidades.

Si se quiere hacer con cualquier otra aplicación, también es válido.
Se trata de hacer una aplicación simple que se pueda hacer rápidamente con un generador de aplicaciones como los que incluyen diferentes marcos MVC. Si cuesta mucho trabajo, simplemente prepara una aplicación que puedas usar más adelante en el resto de los ejercicios.

En mi proyecto tenemos una aplicación basada en apuestas y jornadas de partidos de fútbol, [Microservicio](https://github.com/iMiguel10/Proyecto-IV-Porra-Deportiva-/blob/master/src/funcionesbasicasDB.py).

---

### 6. Ejecutar el programa en diferentes versiones del lenguaje. ¿Funciona en todas ellas? 

Por ejemplo para mi proyecto estoy utilizando Python 3, y si intento ejecutar en Python 2 me sale algún fallo que es posible solucionar, pero en principio el código que tenemos no es compatible con la versión 2 de Python. 

---

### 7. Crear una descripción del módulo usando package.json. En caso de que se trate de otro lenguaje, usar el método correspondiente.
---

### 8. Automatizar con grunt, gulp u otra herramienta de gestión de tareas en Node la generación de documentación de la librería que se cree usando docco u otro sistema similar de generación de documentación. Previamente, por supuesto, habrá que documentar tal librería.
---

### 9. Añadiendo integración continua

Para mi proyecto se ha añadido integración contínua con Travis, asi que aquí dejo la [documentación](https://github.com/iMiguel10/Proyecto-IV-Porra-Deportiva-/blob/master/doc/Integ-Cont-Conf.md).

---

