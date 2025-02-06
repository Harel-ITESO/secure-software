### Linux:

 - Sistema operativo open source basado en UNIX, cuenta con varias distribuciones que dependerán del propósito del proyecto su uso: 
 - Debian, CentOS,  Kali, Parrot son algunos de los ejemplos.

- Unix fue desarrollado en 1969 en los laboratorios Bell de AT&T. Pasó de lenguaje ensamblador a C

#### Estructura de Linux común: 

![Linux](https://i.imgur.com/fHGdRoX.png)

### Comandos básicos de linux:
- **ls** listar
-  **pwd** validar donde estoy parado
- **cd** cambio de directorio
-  **man** información de un comando
-  **exit** salir de la shell
-  **which**  muestra el path de un comando
- **echo** imprimir archivo
-  **grep** filtrar salida
-  **touch** creación de archivo
-  **mkdir**  creación de carpeta
- **vi/nano** edición de archivo
-  **cat** imprimir
-  **rm** borrar

### Git: 

`Git es un proyecto abierto, que nos permite controlar las versiones del producto (código) que estemos creando. Git se presenta como un sistema de control de versiones distribuido. Git se ha diseñado con la principal prioridad de conservar la integridad del código fuente que se está gestionado. Para ello utiliza el algoritmo SHA1.`

##### Jerarquía de instrucciones usando GIT:

![Git](https://i.imgur.com/5m65JuA.png)

##### Principales puntos de seguridad al momento de usar GIT

- No hacer commit de datos sensibles: Estos datos pueden ser Service Accounts Usuarios Contraseñas.

- Cuidar los accesos a los repositorios La carpeta .git contiene todo el historial del repositorio Uso de SSH y MFA.

- Git permite firmar tu trabajo con llaves GPG: Git commits, tags y los push requests se pueden firmar, sin embargo, el que más importa es el Git Tag.

- Mantener Git actualizado.

##### Readme / Markdown MD

- Permite agregar mas estilos para poder agregar a un texto añadido al código, da formato y simbologías para hacer mucho mas sencillo el entendimiento del código dentro del equipo.

![Markdown](https://i.imgur.com/tPCVe7J.png)

### Escalar de cero a un millón:

1) Los usuarios suelen acceder a los dominios 

2) Existe una resolución de nombre

3) Se genera un HTTP Request

4) El servidor puede regresar páginas HTML o JSON

5) Adicionamos Bases de datos para separar capaz Existen dif tipos de DBs

6) Para escalar servidores y mantener un punto de acceso o unos cuantos más sin sobrepasar con base en los servers . Load balancers.

7) Replicación de la base de datos (Master - Slave)

8) Integramos las bases de datos replicadas


### Hipervisores: 
Un hipervisor es una tecnología que nos permite crear Computadoras de forma virtual, por lo que un servidor puede contar con múltiples máquinas segmentando sistemas operativos y reglas de red Hipervisores como:

- Vmware 
- Hyper-V

### Contenedores: 
Tecnología que permite ejecutar aplicaciones de manera segmentada en un mismo sistema operativo (Linux), evitando así crear VM’s para cada aplicación.

### Cloud: 

Estructura de desarrollo ubicada en plataformas en la nube en la cual se ofrecen distintas herramientas como servicios para realizar el desarrollo y despliegue de sistemas o aplicaciones.

![Cloud](https://i.imgur.com/7XQwvHD.png)

### Arquitectura robusta de despliegue de una aplicación:

![Arqui](https://i.imgur.com/ZI4Dx3X.png)

