# Diagrama de casos de uso - Proyecto de red social académica

## Actores
- **Estudiante**: Usuario principal del sistema que interactúa con las funcionalidades.
- **Moderador**: Usuario encargado de moderar el contenido en los foros de discusión.

## Casos de Uso
1. **Registro e inicio de sesión**
   - **Actor**: Estudiante
   - **Descripción**: Permite al estudiante registrarse e iniciar sesión usando sus credenciales universitarias y recuperar la contraseña en caso de olvidarla.
   
2. **Aulas virtuales y grupos de Estudio**
   - **Actor**: Estudiante
   - **Descripción**: Permite al estudiante crear y acceder a aulas virtuales. Los estudiantes pueden unirse a través de invitaciones o códigos de acceso y asignar roles dentro del aula.

3. **Foros de discusión**
   - **Actores**: Estudiante, moderador
   - **Descripción**: Permite a los estudiantes crear y responder hilos en foros clasificados por materias. Los moderadores pueden reportar publicaciones inapropiadas.

4. **Videollamadas grupales**
   - **Actor**: Estudiante
   - **Descripción**: Permite a los estudiantes realizar videollamadas grupales para interacciones en tiempo real.

5. **Sistema de tutoría**
   - **Actor**: Estudiante
   - **Descripción**: Facilita la conexión entre estudiantes avanzados (tutores) y estudiantes de cursos iniciales, permitiendo la solicitud de tutorías en diversas materias.

6. **Notificaciones automáticas**
   - **Actor**: Estudiante
   - **Descripción**: El sistema enviará notificaciones automáticas sobre actividad en los foros, tutorías y otras interacciones académicas.

## Relaciones entre Actores y Casos de Uso
- **Estudiante**:
  - Registro e inicio de sesión
  - Aulas virtuales y grupos de estudio
  - Foros de discusión
  - Videollamadas grupales
  - Sistema de tutoría
  - Notificaciones automáticas

- **Moderador**:
  - Foros de discusión

## Relaciones entre casos de sso
- **Aulas virtuales y grupos de estudio** → **Foros de discusión**: Relación para permitir discusiones dentro de las aulas.
- **Sistema de tutoría** → **Notificaciones automáticas**: El sistema de tutoría enviará recordatorios y notificaciones automáticas sobre sesiones programadas.



![alt text.](/DOCUMENTACIÓN/Recursos%20graficos/Diseño%20del%20proyecto/diagrama%caso%de%uso%final.png)
