# SOFTWARE ENGINEERING 2 MEETING #18
Reunión: R_18<br>
Date: 09/08/21<br>
Quarter: P_02<br>

<!-- ================================================== [CONTENIDO] ================================================= -->

## GENERAL 
1. Se mostró el avance de los modales y formularios.
    1. Se mostró el diseño a mostrar al cliente terminado.
    2. Se ayudó a debuggear un problema con la acaparación del click.
2. Tópicos que se discutieron:
    1. ¿Qué campos pueden o no ser nulls?
    2. Categorías sobre edad según lo que pidió el usuario.
    3. ¿Qué podemos hacer con el dato arenero?
3. Se arregla trabar con el formulario como esta actualmente en los endpoint (por ahora)


## FRONT-END WEB
1. Avances:
    1. Se termina de implementar el diseño del modal a presentar al cliente.
    2. Se termina de implementar el formato y diseño de formulario que se va a presentar al cliente.
        1. Se esperará a que el cliente dé retro-alimentación sobre los campos del formulario, pues la
           organización está en proceso de actualizarlo.
        2. En caso de que haya tiempo tendremos campos tentativos (basados en el antiguo formulario).
2. Metas: 
    1. Terminar de debuggear la acaparación de click en el modal.
    2. Poner íconos en caso de que no hayan imágenes recibidas por parte del back-end
    3. Y de ser posible llenar el catálogo con más animalitos.
    4. Implementar la lógica necesaria para la s validaciones cuando un animal venga con ciertos campos null.
    5. Arreglar el drop down de edad para que se acople a lo que dice el cliente.


## FRONT-END MOVIL
1. Avances:
    1. Testing de los casos de prueba.
    2. Se adelanta solicitudes y solicitudes de adopción.
    3. Generar lógica de gestión de solicitudes.
2. Metas:
    1. Terminar lo del formulario de adopción con los campos actuales.
    2. Visualizar solicitudes y propuestas de voluntarios.
    3. CRUD de usuarios.


## BACKEND
1. Avances:
    1. Se terminaron los endpoints acordados en la semana parsada.
    2. Se ha actualizado la documentación respectiva.
2. Metas:
    1. Colocar con asterisco cuando un campo puede venir null y hacer el filtrado respectivo.
    2. Endpoint solicitudes de adopción (GET)
    3. Hacer endpoint de los gatos adoptables.
        1. Y avisarle a Juan.
    4. Poner id para notificaciones.
    5. Poner el dato de arenero en la base
        1. is_usa_arenero (boolean)
