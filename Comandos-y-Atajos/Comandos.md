# Comandos en MacOS

## Comandos Básicos

1. Navegación:

- **pwd**: Muestra el directorio de trabajo actual.
- **ls**: Lista los archivos y carpetas en el directorio actual.
- **cd [ruta]**: Cambia al directorio especificado.
- **cd ~**: Cambia al directorio principal del usuario.

2. Gestión de Archivos y Directorios:

- **touch [nombre_archivo]**: Crea un archivo vacío con el nombre especificado.
- **mkdir [nombre_directorio]**: Crea un nuevo directorio.
- **rm [nombre_archivo]**: Elimina el archivo especificado.
- **rm -r [nombre_directorio]**: Elimina un directorio y su contenido de forma recursiva.
- **cp [origen] [destino]**: Copia un archivo o directorio de origen a destino.
- **mv [origen] [destino]**: Mueve o renombra un archivo o directorio.

3. Gestión de Permisos:

- **chmod [permiso] [archivo/directorio]**: Cambia los permisos de un archivo o directorio.
- **chown [usuario] [archivo/directorio]**: Cambia el propietario de un archivo o directorio

## Comandos Avanzados

1.	Manipulación de Archivos:
- **cat [archivo]**: Muestra el contenido de un archivo.
- **grep [patrón] [archivo]**: Busca un patrón de texto dentro de un archivo.
- **find [directorio] -name [nombre_archivo]**: Busca archivos y directorios por nombre.

2.	Gestión de Procesos:
- __ps -aux__: Muestra todos los procesos activos.
- **kill [PID]**: Termina un proceso específico usando su ID de proceso (PID).
- **top**: Muestra los procesos en tiempo real, similar al Administrador de Tareas.

3.	Redes:
- **ping [dirección_ip]**: Envía paquetes de red a una dirección IP para comprobar la conectividad.
- **ifconfig**: Muestra la configuración de red de las interfaces de red.
- **ssh [usuario]@[dirección_ip]**: Conéctate de forma remota a otra máquina a través de SSH.
	
4.	Automatización y Scripts:
- **alias [nombre]='[comando]'**: Crea un alias para un comando o secuencia de comandos.
- **crontab -e**: Edita las tareas programadas para ejecución automática.