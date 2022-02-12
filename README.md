
# web11_modulo12_despliegue_servidor_practica

Práctica de configuración de servidores y despliegue de aplicaciones en AWS.

## Resumen enunciado
Cada alumno deberá desplegar en un servidor su desarrollo para la práctica del curso de
Programación Backend con Node y la Práctica de React.
La entrega de la práctica será a través del formulario de entrega de prácticas, indicando en el README.md la URL donde está desplegada la práctica.

**Ejercicio 1**
 - Utilizar node como servidor de aplicación utilizando PM2 o supervisor
 - Utilizar nginx como proxy inverso que se encargue de recibir las peticiones HTTP y derivárselas a node.
 - Los archivos estáticos de la aplicación (imágenes, css, etc.) deberán ser servidos por nginx (no por node). Se deberá añadir una cabecera HTTP cuando se sirvan estáticos cuyo valor sea: X-Owner.
 
**Ejercicio 2**
Si se accede al servidor web indicando la dirección IP del servidor en lugar del nombre de dominio, se deberá carga la práctica realizada en el módulo de React o React Avanzado (a elección del alumno).

**Extras opcionales**
Se puede utilizar Docker, pero el resultado deberá ser el mismo que se pide en los ejercicios anteriores

> Se puede descargar el enunciado completo [aquí](documentation/enunciado.pdf).


## Solución
Los repositorios de los proyectos utilizados para la práctica son:

**Backend con Node:**  https://gitkc.cloud/pablopsdigital/web11_modulo10_backend_avanzado_con_nodejs_practica

**Frontend con React:** 
https://gitkc.cloud/pablopsdigital/web11_modulo07_fundamentos_de_react_practica


Los enlaces a la aplicaciones desplegadas son:

**Ejercicio 1 (Node):**
 - Home: http://3.145.23.128/
 - Swagger: http://3.145.23.128/api/api-docs/
 - API: http://3.145.23.128/api/v1/advertisement

**Ejercicio 2 (React):** 
Home: http://ec2-3-145-23-128.us-east-2.compute.amazonaws.com/