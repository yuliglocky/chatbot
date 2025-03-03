# Chatbot para una empresa ecommerse

# 📌 Descripción General
Este chatbot está diseñado para interactuar con los usuarios y proporcionar respuestas automatizadas basadas en una lógica predefinida e integraciones con API.

# Características
1. Respuestas automatizadas
2. Integración con API
3. Interfaz fácil de usa
4. Flujos de trabajo personalizables


# 🛠️ Tecnologías Usadas

Este chatbot ha sido desarrollado utilizando las siguientes tecnologías:
1. Botmaker: Plataforma de automatización conversacional.
2. Google Sheets: Base de datos para almacenar y gestionar información.
3. Google Apps Script: Automatización de procesos y conexión con Google Sheets.
# Diagramas para la estructura del chatbot


<div style="display: flex; justify-content: space-between; border: 2px solid #000; padding: 20px; border-radius: 5px;">
  <div style="text-align: center;">
       <p><strong>Diagrama de Consulta de Opciones</strong></p>
    <img src="https://github.com/user-attachments/assets/0e615b24-2e73-418e-879c-8b4fbd7ad5ff" width="40%" style="margin-right: 10px;" />
 
  </div>
  <div style="text-align: center;">
    <p><strong>Diagrama de Consulta con la API</strong></p>
    <img src="https://github.com/user-attachments/assets/1e236074-80e6-4cb3-813d-1f640ad00783" width="40%" />
  
  </div>
</div>

## Codigo 
# No code
![image](https://github.com/user-attachments/assets/235a47e9-4fbf-48f3-9e19-c7eaff048c8b)
## Pasos para crear la sección del chatbot (No code) (BotMaker):
1. Mensaje de bienvenida para nuevos usuarios:
Crea un mensaje de bienvenida que se muestre cuando el usuario ingresa al chatbot por primera vez. Este mensaje debe ser amistoso y claro, invitando al usuario a interactuar.

2. Diseño del menú de opciones:
Desarrolla un menú de opciones con botones que permitan al usuario seleccionar la información que desea recibir. Cada botón debe tener una etiqueta clara y un propósito definido.

3. Condición para llamadas naturales:
Implementa una condición para manejar situaciones donde el usuario no selecciona una opción del menú. Esto permitirá consultar el menú de nuevo o salir del chatbot sin necesidad de repetir los botones.

4. Evitar botones repetitivos:
Para optimizar la experiencia del usuario y reducir la cantidad de botones visibles, utiliza un bloque de acción que programe una intención específica en lugar de mostrar botones redundantes.

 5. Uso de "Programar una intención":
Dentro del bloque de acción, utiliza la opción "Programar una intención" para gestionar las interacciones del usuario, lo que facilitará que el chatbot responda de forma adecuada a las acciones del usuario sin necesidad de botones adicionales.

# No code y javaScript
![image](https://github.com/user-attachments/assets/ccc11647-f40e-4dd8-9447-68341cd47c89)
## Pasos para crear la sección del chatbot (No code) (JavaScript) (BotMaker):
Pasos para crear el flujo de consulta del pedido:

1. Solicitar el ID del pedido:
Presenta un formulario donde el usuario ingrese el ID de su pedido. Este ID será utilizado para hacer la consulta a la API.

2. Consultar la API:
Con el ID proporcionado por el usuario, realiza una consulta a la API para verificar si el pedido existe.

3. Mostrar el estado del pedido:
Si la API devuelve un pedido válido, muestra el estado del pedido.
Si la API no encuentra el pedido, muestra un mensaje indicando que el pedido no existe.
 
4. Preguntar si desea realizar otra consulta:
Después de mostrar el estado del pedido, pregunta al usuario si desea volver a consultar otro pedido.
Si sí, repite el proceso desde el paso 1.
Si no, continúa al siguiente paso.

5. Regresar al menú principal o salir:
Si el usuario no desea consultar otro pedido, pregunta si desea regresar al menú de opciones o salir del programa.
Si elige regresar al menú, muestra el menú de opciones disponibles.
Si elige salir, termina el flujo del chatbot.


# Desarrollo de api en AppScript y GoogleSheets

Desarrollo de API en AppScript y Google Sheets

1. Crear el proyecto en Google Sheets:
Abre una hoja de cálculo en Google Sheets y crea un nuevo proyecto para almacenar los datos que serán utilizados en la API.

2. Seleccionar App Script:
En el menú de Google Sheets, selecciona "Extensiones" y luego "Apps Script". Esto abrirá el editor de App Script para empezar a escribir el código.

3. Crear el código para el manejo de datos:
En el editor de Apps Script, escribe el código necesario para manejar los datos que serán expuestos a través de la API. Asegúrate de que el código gestione las solicitudes correctamente, como obtener, agregar, o modificar datos en la hoja de cálculo.

4. Comprobar el funcionamiento de la API:
Para verificar que la API está funcionando correctamente, utiliza la opción "Implementar" en App Script.
Copia la URL proporcionada para la API y pruébala con el ID de un producto o algún dato de ejemplo. Asegúrate de que la respuesta de la API sea la esperada.






