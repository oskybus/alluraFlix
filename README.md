1-¡Iniciemos el desafío de React! Configura tu proyecto base con React y asegúrate de tener todo listo para comenzar a construir las páginas.

Pasos a seguir:

Crea un proyecto React desde cero.
Configura la estructura básica de archivos y carpetas.
Asegúrate de tener todas las dependencias necesarias


2-Construcción de la Página Home en React
¡Hora de dar vida a la página principal! Construye la página Home con los componentes especificados.

Pasos a seguir:

Crea el componente Header con la logo y los botones para la Home y la página de Nuevo Video.
Desarrolla el componente Banner para mostrar imágenes de videos destacados.
Implementa las secciones de categorías: Frontend, Backend, Innovación y Gestión.
Diseña el componente Footer con el logo.



3-Cards de Videos y Funcionalidades en la Página Home
Agrega funcionalidades a la página Home, incluyendo cards de videos y botones de edición y borrado.

Pasos a seguir:

Crea las cards de videos para cada categoría.
Implementa los botones de borrar y editar en cada card.
Configura la apertura del modal al hacer clic en el botón de editar.


4-Desarrollo del Modal en React
Vamos a construir el modal para editar la información de los videos. Este modal debe tener todas las características especificadas.

Pasos a seguir:

Crea el componente Modal con el título "Editar Card".
Agrega un botón para cerrar el modal.
Diseña un formulario con los campos: título, categoría (select), imagen, video y descripción.
Incluye botones "Guardar" y "Limpiar".

5-Avanzamos a la página de Nuevo Video! Construye esta página siguiendo las especificaciones dadas.

Pasos a seguir:

Reutiliza el componente Header con el botón de la página actual seleccionado.
Reutiliza el componente Footer con el logo.
Diseña la sección principal con el título "Nuevo Video".
Implementa el formulario con los mismos campos que utilizaste en el modal.

6-Integración con json-server para Almacenamiento de Datos
Vamos a integrar nuestro proyecto con json-server para simular una API y almacenar datos de manera práctica. Sigue los pasos a continuación para asegurar una integración sin problemas:

Instalación de json-server:
Ejecuta npm install -g json-server para instalarlo globalmente.
Configuración de json-server:
Crea un archivo db.json con la estructura deseada para los datos.
Inicia el servidor con json-server --watch db.json.
Uso de la Fake API:
Ahora puedes realizar solicitudes HTTP a http://localhost:3000/ para interactuar con tus datos simulados.
Documentación:
Consulta la documentación oficial de json-server para obtener detalles adicionales: Enlace a la Documentación


7-Vamos implementar una solicitud 'GET' para leer datos en la página inicial. La lógica será separar los datos por categorías y listarlos de forma organizada.

Pasos a Seguir:

Crea una lógica para realizar una solicitud 'GET'.
Separa los datos por categorías: Frontend, Backend, Innovación y Gestión.
Lista los datos de forma organizada en la página inicial.



8-Implementa una solicitud 'POST' en la página de Nuevos Vídeos para crear nuevos cards que se mostrarán en la página inicial.

Pasos a Seguir:

Desarrolla la lógica para realizar una solicitud 'POST'.
Configura el formulario en la página de Nuevo Vídeo para recopilar información.
Al guardar, envía una solicitud 'POST' para crear un nuevo card.

9-Crea una solicitud 'DELETE' para quitar un card de la página inicial.
Pasos a Seguir:
Desarrolla la lógica para realizar una solicitud 'DELETE'.
Agrega un botón de eliminación en cada card en la página inicial.
Al hacer clic en el botón de eliminación, envía una solicitud 'DELETE' para quitar el card.

10 Publica tu página en la nube!
Utiliza lo que aprendiste sobre Git e GitHub y publica tu proyecto. De esta forma, podrás compartir el resultado de tu proyecto!

Artículos
Heroku, Vercel y otras opciones de cloud como plataforma | Alura Cursos Online