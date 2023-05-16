## TAREA06 - CD
1. **Casos de uso**.
El responsable de almacén tiene como única tarea servir los pedidos de los socios. Aparece en el caso de uso "``Cumplimentar pedidos``". Si bien es una tarea complicada que se corresponde con la siguiente descripción:

El responsable de almacén revisa a diario los pedidos almacenados en el sistema para cumplimentarlos y enviarlos. El proceso consta de varios pasos:
- El responsable recupera la lista de pedidos pendientes
- Selecciona el más antiguo
- Busca los artículos que lo componen en el almacén para genera el paquete y disminuye el stock de los artículos
- Cuando reúne todos los artículos los empaqueta para enviarlos al socio indicando al sistema que ya puede añadir el pedido a la ruta que le corresponde según la población del socio que ha hecho el pedido.
- Como con los artículos comprados se debe adjuntar un albarán con el resumen del pedido, se genera este albarán automáticamente.
- El sistema debe indicar al responsable de almacén en que zona tiene que almacenar el pedido mientras llega el día de hacer el reparto.
- Cambiar el estado del pedido a "almacén".
Contemplar como caso alternativo que no haya artículos disponibles en el almacén, en cuyo caso se realiza una petición a fábrica.

Tu tarea consiste en elaborar la documentación del caso de uso "``Cumplimentar pedidos``" rellenando los siguientes apartados: 
- **Nombre** → es el nombre del caso de uso. 
- **Actores** → aquellos que interactúan con el sistema a través del caso de uso. Representan un tipo de usuario del sistema. Se entiende como usuario cualquier cosa externa que interactúa con el sistema. 
- **Propósito** → breve descripción de lo que se espera que haga.
- **Precondiciones** → aquellas que deben cumplirse para que pueda llevarse a cabo el caso de uso. 
- **Flujo normal** → flujo normal de eventos que deben cumplirse para ejecutar el caso de uso exitosamente, desde el punto de vista del actor que participa y del sistema.
- **Flujo alternativo** → flujo de eventos que se llevan a cabo cuando se producen casos inesperados o poco frecuentes. No se deben incluir aquí errores como escribir un tipo de dato incorrecto o la omisión de un parámetro necesario.
- **Postcondiciones** → las que se cumplen una vez que se ha realizado el caso de uso.

2. Elabora el **diagrama de secuencia** para el caso de uso "``Cumplimentar pedidos``".

3. Elabora el **diagrama de colaboración** para el caso de uso "``Cumplimentar pedidos``".

4. Elaborar el **diagrama de actividad** para el caso de uso "Cumplimentar pedidos".

5. Describe a qué objeto puede corresponder el siguiente **diagrama de transición** de estados indicando cual es la funcionalidad que representa.

<div align = center><img src="https://github.com/AlbaGonzalezPereira/daw_cd/blob/main/Tarea06_comportamiento/img/diagrama.PNG" alt="diagrama de transición" style = "width: 60%"></div>