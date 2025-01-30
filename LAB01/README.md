# LABORATORIO 1- INTRODUCCIÓN GIT
ESCUELA COLOMBIANA DE INGENIERÍA - CICLOS DE VIDA DE DESARROLLO DE SOFTWARE
## Respuestas
# PARTE I (Trabajo Individual)
3. Averigua para qué sirve y como se usan estos comandos git add y git commit -m “mensaje” PARTE I

- git add: Este comando se usa para añadir cambios (archivos modificados, nuevos archivos o archivos eliminados)

- git commit -m “mensaje”: Una vez que se han añadido los cambios, el comando git commit se usa para guardar esos cambios en el
    historial de Git, creando un cambio con un mensaje que describe la modificacion o eliminacion realizada. 

# PARTE II (Trabajo en parejas)
1.	Se escogen los roles para trabajar en equipo, una persona debe escoger ser "Owner" o Propietario del repositorio y la otra "Collaborator" o Colaborador en el repositorio.

[![Imagen-de-Whats-App-2025-01-23-a-las-14-07-09-8ba2c198.jpg](https://i.postimg.cc/26HzyjL5/Imagen-de-Whats-App-2025-01-23-a-las-14-07-09-8ba2c198.jpg)](https://postimg.cc/JDkwdLqw)

[![Imagen-de-Whats-App-2025-01-23-a-las-14-07-16-c18d6bd7.jpg](https://i.postimg.cc/T1pTD8nJ/Imagen-de-Whats-App-2025-01-23-a-las-14-07-16-c18d6bd7.jpg)](https://postimg.cc/H8DqqhZr)

2.	El owner agrega al colaborador con permisos de escritura en el repositorio que creó en la parte 1

[![Imagen-de-Whats-App-2025-01-23-a-las-14-25-42-51a5e40a.jpg](https://i.postimg.cc/L5w2kyTK/Imagen-de-Whats-App-2025-01-23-a-las-14-25-42-51a5e40a.jpg)](https://postimg.cc/7J3Fwndm)

3.	El owner le comparte la url via Teams al colaborador
4.	El colaborador acepta la invitación al repositorio

[![Captura-de-pantalla-2025-01-29-210213.jpg](https://i.postimg.cc/g0g9qSzS/Captura-de-pantalla-2025-01-29-210213.jpg)](https://postimg.cc/qt6ZpGCy)

5.	Owner y Colaborador editan el archivo README.md al mismo tiempo e intentan subir los cambios al mismo tiempo.

[![sa.jpg](https://i.postimg.cc/7YSZMkpK/sa.jpg)](https://postimg.cc/8jPGNqkv)

6.	¿Que sucedió?
- Al intentar modificar el archivo **README.md** nos genero un error como se aprecia en la imagen adjunta en la parte superior, el error le sale al que mas se haya demorado en hacer **git push** que en este caso fue al colaborador.

7.	La persona que perdió la competencia de subir los cambios, tiene que resolver los conflictos, cúando haces pull de los cambios, los archivos tienen los símbolos `<<<` `===` y `>>>` (son normales en la resolución de conflictos), estos conflictos debes resolverlos manualmente.

    Elavoracion De Primeros Conflictos Git
- **Hola mundo (Owner) error - Sebastian Beltran** 
- **Error 2 - Salomon Baena**

    Cambio (Creacion Pull Request)
- <<<<<<< HEAD

    Creacion De Prueba Pull Request - Salomon
- =======


    Creacion pull request - Salomon Baena
- >>>>>>> Salomon

[![a.jpg](https://i.postimg.cc/KY6W56X5/a.jpg)](https://postimg.cc/kVywJhgV)

[![Imagen-de-Whats-App-2025-01-23-a-las-15-31-31-2e0ad2d3.jpg](https://i.postimg.cc/K8KQs0Dp/Imagen-de-Whats-App-2025-01-23-a-las-15-31-31-2e0ad2d3.jpg)](https://postimg.cc/VJ8jJBTX)

9.	Resuelvan el conflicto con IntelliJ si es posible,  [Resolver conflictos en IntelliJ]( https://www.jetbrains.com/help/idea/resolving-conflicts.html#distributed-version-control-systems)


## PARTE III (Trabajo de a parejas)
1. ¿Hay una mejor forma de trabajar con git para no tener conflictos? 
- Se podría crear ramas especificas para cada característica o tarea del proyecto
- Evitar trabajarr en ramas importantes o principales como main o develop, estas ramas se deberían usar ya cuando el proyecto está estable o se mande a producción.
- Realizar PR (Pull Request) para revisar el código antes de que se una con la rama principal.

2. ¿Qué es y como funciona el Pull Request?

* Es una solicitud para integrar los cambios de una rama a otra en un repositorio Git. Permite:
* Revisar los cambios antes de integrarlos.
* Discutir el código con el equipo.
* Detectar errores o inconsistencias mediante revisiones y pruebas.

3.	Creen una rama cada uno y suban sus cambios

[![fff.jpg](https://i.postimg.cc/G2RQtdw6/fff.jpg)](https://postimg.cc/KK9LsXY5)

4.	Tanto owner como colaborador hacen un cambio en el README.md y hacen un Pull Request (PR) a la rama main/master

[![Imagen-de-Whats-App-2025-01-26-a-las-21-13-36-892234e4.jpg](https://i.postimg.cc/Zn7FwNBh/Imagen-de-Whats-App-2025-01-26-a-las-21-13-36-892234e4.jpg)](https://postimg.cc/ZvNdRCxf)

[![Imagen-de-Whats-App-2025-01-26-a-las-21-11-10-9262d229.jpg](https://i.postimg.cc/XNQ8jR2D/Imagen-de-Whats-App-2025-01-26-a-las-21-11-10-9262d229.jpg)](https://postimg.cc/14V6Mj1p)

5.	Teniendo en cuenta la recomendación, mezclen los cambios a la rama main a través de PR con el check/review/approval del otro compañero (Cuando se hace merge se deberían borrar las ramas en github)

[![Imagen-de-Whats-App-2025-01-26-a-las-21-11-00-533ebee0.jpg](https://i.postimg.cc/6QrrDg2c/Imagen-de-Whats-App-2025-01-26-a-las-21-11-00-533ebee0.jpg)](https://postimg.cc/xkdNmsPN)

[![Screenshot-2025-01-29-at-22-34-31.png](https://i.postimg.cc/mk9THzfy/Screenshot-2025-01-29-at-22-34-31.png)](https://postimg.cc/D42VVzzS)

[![Screenshot-2025-01-29-at-22-38-10.png](https://i.postimg.cc/Yq1p2Wxp/Screenshot-2025-01-29-at-22-38-10.png)](https://postimg.cc/PP5G2Ncc)

# INTEGRANTES
- Juan Sebastian Beltran
- David Salomon Baena

