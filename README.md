<h1 align="center">
  <font color="red">
 BRAVUS
  </font>
</h1>
<center>
  <img src="https://posbrava.com/wp-content/uploads/2023/05/Logo-Horizontal-blanco.png">
</center>

Bravus POS es un conjunto de aplicaciones diseñadas para restaurantes y establecimientos de venta de alimentos. Funciona como un sistema de punto de venta (POS) completo, que tiene como objetivo agilizar y optimizar las operaciones diarias de ventas y gestión de pedidos. Tanto los empleados como los clientes se benefician de una experiencia eficiente y satisfactoria al utilizar este sistema. 

## **1. POS (Puntos de Venta)**

La sección POS de la aplicación es el núcleo del sistema, donde se gestionan todas las transacciones de venta y pedidos. Permite a los usuarios crear órdenes para los clientes, seleccionando productos del menú y personalizando las órdenes según las preferencias específicas de cada cliente. Esta funcionalidad garantiza que se puedan satisfacer las necesidades individuales de los clientes y brindarles una experiencia personalizada.

### Funcionalidades Principales

- Creación de órdenes para diferentes tipos de servicio **(servicio rápido, para mesa, para recoger, para llevar)**.

- Personalización de órdenes con extras, modificadores y adiciones.

- Ajuste de cantidades de productos.

- Procesamiento de pagos con efectivo y tarjeta a través de un procesador de pagos integrado **(Clover)**.
  
## **2. KDS (Sistema de Visualización de Cocina)**

El KDS (Kitchen Display System) es una herramienta diseñada para optimizar las operaciones en la cocina. Permite a los cocineros visualizar y gestionar las órdenes pendientes de preparación de manera eficiente. Además de mostrar las órdenes pendientes, esta sección utiliza un sistema de colores para indicar el estado temporal de cada orden. Esto facilita una gestión más efectiva del tiempo y permite una respuesta proactiva a las necesidades del servicio. Con el KDS, los cocineros pueden coordinar mejor el flujo de trabajo en la cocina y garantizar una preparación oportuna de los platos.


### Funcionalidades Principales

- Selección de la impresora o pantalla de visualización de la cocina.

- Visualización de las órdenes pendientes con detalles como productos incluidos y tiempo de preparación estimado.

- Visualización de órdenes con colores codificados por tiempo:
    * Las órdenes que están dentro del tiempo configurado se muestran en verde, indicando que están en tiempo.
    * Las órdenes que están próximas a exceder el tiempo configurado se muestran en amarillo, advirtiendo al personal de cocina que deben acelerar el proceso de preparación.
    * Las órdenes que han excedido el tiempo configurado se muestran en rojo, alertando al equipo de cocina que se ha sobrepasado el tiempo límite y requiere atención inmediata.

- Marcar productos como listos una vez preparados.

## **3. Table Map (Mapa de Mesas)**

La sección Table Map (Mapa de Mesas) es una funcionalidad que esta próxima a desarrollarse y ofrecerá una representación visual del espacio del restaurante, lo que facilitará la gestión de las mesas y las reservas. Con esta función, los usuarios podrán tener una vista clara y organizada de todas las mesas disponibles en el restaurante. Esto les permitirá gestionar de manera eficiente las reservas, asignar mesas a los clientes y optimizar la capacidad del establecimiento. La representación visual del espacio del restaurante en table map será una herramienta útil para mejorar la experiencia tanto de los clientes como del personal.

### Funcionalidades Principales

- Visualización del diseño del restaurante con todas las mesas disponibles.

- Gestión de reservas y asignación de mesas a clientes.

- Seguimiento en tiempo real del estado de las mesas (ocupadas, disponibles, reservadas).

- Integración con el POS para sincronizar la disponibilidad de las mesas con las órdenes en proceso.


## **4. SELFKIOS**

SELFKIOS es una aplicación que ofrece a los usuarios una experiencia de autoservicio en la compra de productos asociados a una sucursal específica. Con una interfaz intuitiva y amigable, esta aplicación permite a los clientes navegar por el menú, personalizar sus pedidos y realizar pagos , sin necesidad de interactuar directamente con el personal del establecimiento. Con SELFKIOS, los clientes pueden disfrutar de una experiencia de compra rápida y conveniente, adaptada a sus preferencias individuales.

## Funcionalidades Principales

1. Creación de Órdenes:

    * La aplicación ofrece tres opciones de orden: Restaurante, Para llevar y Para recoger.
    
    * Para el tipo de orden "Restaurante", se solicita al usuario su nombre para
    asociar su pedido.

    * En el caso de órdenes "Para llevar", se requiere únicamente el nombre del cliente
    para identificar su órden.

    * Para las órdenes "Para recoger", se solicitan el nombre del cliente, su número de 
    teléfono, correo electrónico y la hora estimada de recogida para una coordinación
    eficiente.

2. Personalización de Órdenes:

    * Los usuarios tienen la libertad de personalizar sus pedidos según sus preferencias individuales.

    * Pueden seleccionar entre una variedad de opciones adicionales, como bebidas, postres, adiciones, extras e ingredientes adicionales, para adaptar su pedido a sus gustos específicos.

3. Gestión de Pagos:

    * La aplicación ofrece dos métodos de pago: en efectivo y con tarjeta.

    * Para los pagos en efectivo, la aplicación genera un recibo que el cliente puede llevar a la caja para realizar el pago correspondiente. De esta manera, se brinda flexibilidad al cliente al permitirle elegir el método de pago que prefiera, ya sea en efectivo o con tarjeta.

## 

<h2>POS, KDS y Table Map trabajan en conjunto para proporcionar una experiencia integral de gestión de ventas y servicios en el entorno de un restaurante o establecimiento de servicios de alimentos. Cada una de estas secciones cumple un papel específico para optimizar las operaciones y mejorar la experiencia tanto para el personal como para los clientes. Desde la creación y personalización de órdenes en la sección POS, hasta la visualización y gestión de las órdenes pendientes en el KDS, y la gestión de mesas y reservas en la sección Table Map, todas estas funciones se complementan entre sí para garantizar una gestión eficiente y una experiencia satisfactoria para todos los involucrados.</h2>

## **Beneficios para los Usuarios**

- **Convivencia:** Los usuarios pueden realizar pedidos y pagos de forma rápida y sencilla, evitando largas filas y la necesidad de interactuar directamente con el personal del establecimiento.

- **Personalización:** La opción de personalizar los pedidos según las preferencias individuales de cada cliente garantiza una experiencia de compra más satisfactoria y adaptada a sus necesidades.

- **Flexibilidad de Pago:** SELFKIOS permite a los usuarios elegir entre pagar en efectivo o con tarjeta, brindándoles la libertad de utilizar el método de pago.

# Tecnologias

## Este proyecto esta creado con [React](https://github.com/facebook/create-react-app).
![My Skills](https://skillicons.dev/icons?i=react,javascript)

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

