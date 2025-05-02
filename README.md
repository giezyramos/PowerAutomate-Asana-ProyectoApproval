📄 Descripción del flujo: Aprobación de creación de proyectos en Asana
Este flujo automatiza la validación y aprobación de solicitudes de creación de nuevos proyectos en Asana, iniciadas a través de un formulario.

🔁 Paso a paso del flujo
Obtener respuestas del formulario (Get_response_details)

Se activa cuando un usuario envía una solicitud mediante un formulario (como Microsoft Forms).

El flujo recoge automáticamente los detalles del formulario: nombre del solicitante, tipo de proyecto, descripción, etc.

Iniciar y esperar una aprobación (Start_and_wait_for_an_approval_1)

El sistema envía una solicitud de aprobación (por ejemplo, vía correo o Microsoft Teams) al responsable de validar la creación del proyecto.

Este paso pausa la ejecución del flujo hasta que se emita una respuesta (aprobado o rechazado).

Condición (Condition)

Evalúa la respuesta de la aprobación:

Si se aprueba: (no mostrado en el resumen, pero probablemente se continúa con la creación del proyecto en Asana)

Si se rechaza: se puede enviar una notificación al solicitante informando la decisión.

![solicitud de creacion de proyectos en asana con form y power automate](https://github.com/user-attachments/assets/87a38303-949d-4fd6-8989-4632a710ac41)

![Resumen del flujo creacion de proyecto en asana](https://github.com/user-attachments/assets/31c3616d-ffa8-4c08-8024-20ae5554dc9e)


![image](https://github.com/user-attachments/assets/afde6ac6-aace-4057-b3ad-fdc519ae8ae6)

![image](https://github.com/user-attachments/assets/36d706e7-1ded-44ab-9399-32e4e6fd66c3)



