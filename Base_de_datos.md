## Estructura de la Base de Datos
### Publicaciones
 - id: Identificador único (entero)
 - img: Ruta de la imagen (cadena de texto)
 - titulo: Título de la publicación (cadena de texto)
 - descripcion: Descripción de la publicación (cadena de texto)
### Eventos
 - id: Identificador único (entero)
 - nombre: Nombre del evento (cadena de texto)
 - fecha: Fecha del evento (fecha)
 - horainicio: Hora de inicio del evento (hora)
 - horafin: Hora de finalización del evento (hora)
 - temporada: Temporada del evento (cadena de texto)
 - idestadios: Identificador del estadio asociado (entero)
 - idliga: Identificador de la liga asociada (entero)
### Jugadores
 - id: Identificador único (entero)
 - nombre: Nombre del jugador (cadena de texto)
 - apellido: Apellido del jugador (cadena de texto)
 - fechanacim: Fecha de nacimiento del jugador (fecha)
 - equipoid: Identificador del equipo asociado (entero)
 - altura: Altura del jugador (cadena de texto)
 - peso: Peso del jugador (cadena de texto)
 - numero: Número del jugador (entero)
### Usuarios
 - id: Identificador único (entero)
 - nombre: Nombre del usuario (cadena de texto)
 - contrasena: Contraseña del usuario (cadena de texto)
 - correo: Correo electrónico del usuario (cadena de texto)
 - admin: Indicador de administrador (booleano)
### Ligas
 - id: Identificador único (entero)
 - nombre: Nombre de la liga (cadena de texto)
 - logo: Ruta del logo de la liga (cadena de texto)
 - temporadaactual: Temporada actual de la liga (entero)
 - youtube: Enlace de YouTube de la liga (cadena de texto)
 - web: Sitio web de la liga (cadena de texto)
### Estadios
 - id: Identificador único (entero)
 - localizacion: Localización del estadio (cadena de texto)
 - capacidad: Capacidad del estadio (entero)
### Equipos
 - id: Identificador único (entero)
 - nombre: Nombre del equipo (cadena de texto)
 - ciudad: Ciudad del equipo (cadena de texto)
 - logo: Ruta del logo del equipo (cadena de texto)
 - id_liga: Identificador de la liga asociada (entero)
### Likes
 - id: Identificador único (entero)
 - publicacionid: Identificador de la publicación asociada (entero)
 - usuarioid: Identificador del usuario asociado (entero)
 - likecount: Conteo de likes (entero)
### Registros
 - id: Identificador único (entero)
 - eventoid: Identificador del evento asociado (entero)
 - jugadorid: Identificador del jugador asociado (entero)
 - accion: Acción registrada (cadena de texto)
 - minuto: Minuto en que ocurrió la acción (entero)
### Comentarios
 - id: Identificador único (entero)
 - idusuario: Identificador del usuario que comentó (entero)
 - publicacionid: Identificador de la publicación asociada (entero)
 - descripcion: Descripción del comentario (cadena de texto)