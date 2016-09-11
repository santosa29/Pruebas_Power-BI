# Proyectos Web/Mobile/Desktop Costa Rica
#####Un listado actualizado de proyectos de desarrollo (Web, aplicaciones nativas, aplicaciones desktop, entre otros) pendientes, información de contacto de los interesados y detalles sobre los requerimientos.

##Ejemplo
El formato que deberemos seguir será el siguiente:

###Aplicación empresarial: una aplicación empresarial basada en tecnologías Web

```javascript
  {
    categorías: ['api', 'mobile', 'app'],
    empresa: 'Tosty S.A.',
    nombre: 'Aplicación empresarial',
    descripción: 'Una aplicación móvil para mostrar eventos recientes de una nueva red social',
    requerimientos: ['Deberá correr vía Web', 'Deberá permitir el registro de usuarios']
    budget: '$5000',
    urgente: true,
    contacto: {
      nombre: 'Manuel Ro',
      email: 'some@email.com',
      telefono: '+506 8888 8888'
    },
    ejemplos: ['http://un-ejemplo.com', 'http://otro-ejemplo.com']
  }
  ```
##Cómo agregar información sobre mi proyecto
Los interesados en promocionar un proyecto pueden publicarlo en el grupo [Desarrolladores Web Costa Rica]: https://www.facebook.com/groups/DesarrolladoresWebCostarica con la informacion requerida.

En este mismo repositorio encontrarás tres archivos: `Web.md`, `Desktop.md` y `Mobile.md`, en cada uno de ellos se agregarán los proyectos que vayan surgiendo. Los documentos se actualizarán una vez por semana, con el fin de agregar proyectos nuevos constantemente.

###Heading
El heading estará compuesto por un nombre genérico para la aplicación que sintetice brevemente su naturaleza, seguido de dos puntos (:) y una descripción corta.

###Categorías
Las categorías representan clasificaciones dentro de las cuales la aplicación puede calzar, es decir, si es una aplicación para dispositivos móviles, o si está pensada para ser utilizada a través de Internet con un navegador. Este arreglo puede quedar vacío.

###Empresa
El nombre de la empresa, o en su defecto, la persona interesada en los servicios. Este string puede quedar vacío.

###Nombre
El nombre de la aplicación, por lo general un nombre genérico funcionará muy bien.

###Descripción
Una descripción para la aplicación. Una síntesis sobre las características y el funcionamiento esperado. Es recomendable que este string no quede vacío, ya que le dará al desarrollador una mejor idea sobre el tiempo requerido y los requerimientos.

###Requerimientos
Una arreglo con los requerimientos principales. Es recomendable agregar aquellos requerimientos que describen el funcionamiento de la aplicación de manera sencilla y breve.

###Budget
Un string con formato en dólares con la cantidad con la que dispone al momento de solicitar los servicios de desarrollo de un desarrollador, o en su defecto, el valor percibido de la aplicación que usted necesita.

###Urgente
Un booleano que indica el carácter de urgencia de la aplicación. De contar con tiempo suficiente, su valor deberá ser `false`.

###Contacto
La información de contacto de la persona o empresa interesada. Es recomendable que este objeto no se encuentre vacío.

####Nombre
El nombre del representante o la persona interesada en el proyecto.

####Email
Una dirección de correo electrónico a la cual enviarle información sobre posibles oferentes.

####Teléfono
Un número telefónico, únicamente si desea ser contactado por este medio.

###Ejemplos
Un arreglo con ejemplos de aplicaciones ya existentes que tienen similitud total o parcial con el proyecto que le interesa desarrollar.

