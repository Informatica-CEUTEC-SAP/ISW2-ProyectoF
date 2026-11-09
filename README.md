LEARN-CAP-849BCF83

Descripción del Proyecto: 
Patitas es un sitio web de cuidado de mascotas que centraliza en un solo lugar la información que un dueño necesita: el perfil de cada mascota, el carné de vacunas con alertas de vencimiento, la agenda de citas con veterinarios, un directorio de profesionales por especialidad, recordatorios de cuidados y consejos por especie. Su objetivo es que los dueños no olviden vacunas ni controles, que encuentren y reserven con un veterinario en pocos pasos y que cuiden mejor a sus animales con información clara y accesible desde el celular o la computadora.

Aspectos técnicos: 
Arquitectura: aplicación de una sola página (SPA) en un único archivo HTML con CSS y JavaScript propios, sin librerías ni recursos externos.
Datos simulados (mock): mascotas, veterinarios, citas, vacunas, recordatorios y consejos están definidos como objetos JavaScript. Las fechas se calculan relativas a hoy, así que las alertas siempre tienen sentido.
Estado y renderizado: un objeto de estado único y funciones que generan cada vista; la navegación usa el hash de la URL (#citas, #salud, etc.).
Seguridad: todo texto escrito por el usuario pasa por una función de escape antes de mostrarse.
Diseño: CSS con variables, adaptable a móvil y escritorio, modo claro y oscuro automático, foco visible y respeto a la preferencia de movimiento reducido.
Limitación: al recargar la página los datos vuelven a su estado inicial. Para un proyecto real habría que conectar un backend con base de datos, autenticación de usuarios y notificaciones por correo o SMS.
