# Piedra, Papel o Tijera - Juego Multijugador

Proyecto final realizado para la materia de Desarrollo 3. Se desarrolló un juego multijugador de Piedra, Papel o Tijera mediante una arquitectura cliente-servidor.

La aplicación permite que dos jugadores se conecten al sistema, creen una cuenta o inicien sesión y participen en una partida. El cliente proporciona la interfaz gráfica para interactuar con el juego, mientras que el servidor administra las conexiones, coordina las partidas y consulta la base de datos para gestionar las cuentas y los resultados.

# Tecnologías utilizadas

C#

Windows Forms

.NET

Comunicación mediante TCP

Microsoft SQL Server

# Estructura del proyecto

El sistema está dividido en dos componentes:

Cliente: aplicación de escritorio que permite a los jugadores interactuar con el sistema, enviar sus jugadas y consultar los resultados.

Servidor: administra las conexiones de los jugadores, coordina las partidas y utiliza la base de datos para gestionar la información.

# Repositorios originales

Cliente: GitHub - Jimaxo2/PPT-Juego-Cliente

Servidor: GitHub - Jimaxo2/PPT-Juego-Servidor

# Configuración e instalación

Contar con un entorno compatible con C# y con los proyectos incluidos en los repositorios originales.

Preparar una base de datos en SQL Server para almacenar la información de los usuarios y las partidas.

Configurar la conexión del servidor con la base de datos.

Iniciar el servidor y verificar que esté escuchando en el puerto configurado, que en la implementación original es el 5000.

Configurar la dirección IP del servidor en el cliente. Si ambos se ejecutan en el mismo equipo, se puede utilizar 127.0.0.1.

Iniciar el cliente para conectarse al servidor y comenzar a jugar.

# Información adicional

Este repositorio reúne la descripción del proyecto y los enlaces a sus componentes originales. Para consultar o ejecutar el código fuente completo, es necesario acceder a los repositorios del cliente y del servidor.
