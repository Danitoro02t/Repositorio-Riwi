Parche Dev 2026

Hola. Esta es la pagina oficial del evento Parche Dev 2026. La arme usando puro HTML semantico para el reto individual del Modulo 1 (HTML y CSS) en RIWI

Puedes ver como quedo subido aqui: https://DanielToroTaborda.github.io/parche-dev/

Paginas del proyecto

Inicio: La portada del sitio

Agenda: El cronograma con los eventos y salas

Ponentes: La info de la gente que va a dar las charlas

Inscripcion y confirmacion: El formulario para registrarse

Codigo de conducta: Las reglas de convivencia del evento

Como verlo en tu compu

Clona este repositorio en tu maquina.

Abrelo con VS Code

Busca el archivo index.html, le das clic derecho y le das en Live Preview (y listo)

Decisiones que tome en el codigo

Etiqueta  en el footer: La use especificamente para el correo de contacto (hola@parchedev.example), porque estuve leyendo que en HTML5 esa es la forma correcta de poner los datos del autor o responsable de la pagina

Tablas organizadas con scope, colspan y rowspan: La agenda me dio algo de lidia, pero la saque con una sola tabla usando , , scope="col" y scope="row". Con esto me me asegure de que si alguien usa un lector de pantalla, entienda perfecto que charla va en cual hora y sala

Formularios con  y : En la pagina de inscripcion.html agrupe los campos por bloques tematicos. Asi el formulario no queda hecho un chorizo de campos sueltos y la navegacion por teclado o lector de pantalla queda super clara

Respuestas de la investigacion tecnica (Ticket 5):

¿Por que usar aria-current="page"? Sirve para avisarle a las herramientas de accesibilidad (como lectores de pantalla) exactamente en que pagina del menu esta parado el usuario

¿Diferencia entre method="get" y method="post"? Con GET los datos viajan visibles en la URL (sirve para busquedas o datos publicos), mientras que con POST viajan ocultos en la peticion (es el que toca usar si mandamos datos sensibles o de registro)

Lo que aprendi haciendolo

La importancia de la Accesibilidad Web (A11y): Descubri como los skip links, los atributos aria y la semantica hacen que una pagina sea incluyente y se pueda navegar solo con el teclado

Manejo de tablas HTML: Aprendi a cuadrar horarios que se ven complicados mezclando colspan y rowspan sin tirarme la estructura ni la accesibilidad

Codigo limpio con el validador W3C: Pase cada pagina por el validador oficial y corregi todo hasta que me quedo en cero errores y cero advertencias

Creado por

Daniel Toro Taborda · [GitHub](https://github.com/Danitoro02t) 