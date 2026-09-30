# jsClase7

Pre-Entrega: Interfaz dinámica con DOM y eventos
Objetivo de aprendizaje
Consolidar la capacidad de manipular el árbol jerárquico del HTML (DOM) y gestionar el flujo de eventos para crear una experiencia de usuario fluida y dinámica.

Qué construir
Debes desarrollar una interfaz interactiva para tu proyecto, pasando de los prompts, console y alert a un desarrollo integro mediante el DOM. Esta interfaz debe permitir al usuario:

Ver una colección de objetos renderizada en pantalla (no por consola), generada dinámicamente desde un array.
Agregar un nuevo ítem completando los inputs de un formulario y presionando un botón, sin recargar la página: la lista se actualiza sola.
Recibir feedback visual de cada acción (ej. un mensaje en pantalla o un resaltado al agregar/eliminar).
Interactuar con cada ítem (ej. botón "Eliminar" o "Logrado") y/o filtrar la lista con un evento de teclado.


Criterios de aceptación
Tu código debe cumplir con:

Selección Precisa: Uso de querySelector o getElementById/ClassName para referenciar elementos.
Renderizado Dinámico: Una función que recorra un array de objetos y genere elementos HTML (usando innerHTML junto con backticks) para mostrarlos en pantalla.
Feedback Visual: Uso de DOM para comunicarle al usuario cuando realiza una accion y su correspondiente consecuencia.
Uso de eventos: Acceso a eventos para plantear la interacción con el usuario (detectar un click, una tecla, etc.).
Estructura del proyecto: tres archivos —index.html en la raíz, style.css y main.js cada uno en su carpeta— correctamente enlazados.
Estilado básico: el proyecto no puede quedar en blanco y negro ni sin un layout claro.
Pasos sugeridos
Prepara tu HTML: Crea una estructura básica que tenga inputs claros y un <div> o <ul> vacío donde se inyectará el contenido.
Vincula tus Objetos: Toma los objetos que definiste en la pre-entrega anterior. Crea una función que limpie el contenedor y dibuje cada objeto.
Actualiza la Vista: Cada vez que el array cambie, llama de nuevo a tu función de renderizado.
Añade Interactividad: Agrega botones dentro de cada elemento renderizado (ej: un botón "Eliminar" o "Logrado") y asígnales eventos para que realicen acciones según lo que desee el usuario.