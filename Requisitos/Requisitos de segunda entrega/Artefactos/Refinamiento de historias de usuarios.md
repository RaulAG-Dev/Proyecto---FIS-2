# Refinamiento storias de Usuario

# Historias de Usuario y Criterios de Aceptación

## Registro y Autenticación de Usuarios

**Como**: estudiante  
**Quiero**: registrarme e iniciar sesión usando mis credenciales universitarias.  
**Para**: acceder al sistema y recuperar mi contraseña en caso de olvidarla.

### Criterios de Aceptación:
- Validación de correos electrónicos universitarios.
- Recuperación de contraseñas mediante correo.
- Bloqueo de cuentas tras múltiples intentos fallidos de inicio de sesión.

---

## Aulas Virtuales y Grupos de Estudio

**Como**: estudiante  
**Quiero**: crear y unirme a aulas virtuales mediante códigos o invitaciones.  
**Para**: colaborar en grupos de estudio.

### Criterios de Aceptación:
- Generación de códigos únicos para cada aula.
- Invitaciones directas vía correo institucional.
- Restricción de acceso a usuarios no autorizados.

---

## Foros de Discusión

**Como**: estudiante  
**Quiero**: crear hilos en foros y reportar publicaciones inapropiadas.  
**Para**: mantener un espacio de discusión seguro y académico.

### Criterios de Aceptación:
- Clasificación de foros por materias o temas.
- Botón de "reportar" para publicaciones inapropiadas.
- Moderación con alertas automatizadas.

---

## Videoconferencias

**Como**: estudiante  
**Quiero**: realizar videollamadas grupales desde la plataforma.  
**Para**: colaborar en tiempo real.

### Criterios de Aceptación:
- Capacidad para al menos 10 participantes por videollamada.
- Notificaciones previas al inicio de una sesión programada.

---

## Sistema de Tutoría

**Como**: estudiante  
**Quiero**: conectar con tutores avanzados en materias específicas.  
**Para**: mejorar mi rendimiento académico.

### Criterios de Aceptación:
- Búsqueda de tutores por materia o tema.
- Sistema de calificación para tutores tras cada sesión.

---

## Notificaciones Automáticas

**Como**: usuario  
**Quiero**: recibir alertas sobre actividad en la plataforma.  
**Para**: estar al tanto de eventos relevantes.

### Criterios de Aceptación:
- Notificaciones sobre mensajes nuevos en foros.
- Alertas de próximas sesiones de tutoría o videollamadas.

---

# Casos de Uso con Excepciones Consideradas

## Caso de Uso: Registro de Usuarios

**Flujo Principal**: El usuario completa su registro, el sistema valida sus credenciales y envía un correo de confirmación.

### Excepciones:
- Correo no institucional → Muestra error.
- Correo ya registrado → Indica duplicado.

---

## Caso de Uso: Creación de Aulas Virtuales

**Flujo Principal**: Un usuario crea un aula, el sistema genera un código y permite a otros unirse.

### Excepciones:
- Código duplicado → Genera un nuevo código.
- Usuario no autorizado → Bloquea el acceso.
