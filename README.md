# Preparacion-para-entrevistas-como-DevOps<p align="center">


This site was built using [GitHub Pages](https://pages.github.com/).

# AWS    - Amazon Web Services
-------------------------------------------------------------------------------------------------------------------

## S3
•	Como se asignan permisos  [AWS](https://docs.aws.amazon.com/AmazonS3/latest/user-guide/set-permissions.html)

•	Diferencia entre los distintos tipos de S3  [Clases](https://aws.amazon.com/s3/storage-classes/)

•	Que es "Objeto Storage" y sus casos de uso

•	Diferencia entre "Object Storage" y "Block Storage"  

  Object Storage

      Object storage es un tipo de almacenamiento de datos en el que cada unidad de datos (llamada “objeto”) se almacena como una unidad discreta. Estos objetos pueden ser prácticamente cualquier tipo de datos: pdf, video, audio, texto, datos de sitios web o cualquier otro tipo de archivo. 
      A diferencia del file storage, estos objetos se almacenan en una estructura única y plana sin una jerarquía de carpetas. En el object storage, todos los objetos se almacenan en un espacio de direcciones planas a diferencia de la estructura jerárquica anidada utilizada por el file storage. Además, todos los metadatos predeterminados y personalizados se almacenan con el objeto en sí (no como parte de una tabla o índice de sistema de archivos separado), en un espacio de direcciones plano con un identificador único, y de esa manera es más fácil de indexar y acceder. 
      El object storage es bastante común en escenarios de almacenamiento basados en la nube y se puede utilizar para administrar, procesar y distribuir contenido con una escalabilidad y confiabilidad muy altas. El esquema de direccionamiento plano significa que el acceso a objetos individuales es rápido y fácil: los nombres de objetos pueden servir como “claves” en una tabla de búsqueda. Los sistemas de object storage simplemente necesitan conocer la clave (nombre) del objeto que está buscando y luego pueden devolvérselo rápida y fácilmente utilizando una tabla de búsqueda.

  
  Block Storage

    Object Storage y el File Storage tratan los archivos como una sola “unidad” de datos. Block Storage, como su nombre indica, trata los datos como una secuencia de     “trozos” o “bloques” de tamaño fijo en los que cada archivo u objeto podría distribuirse a través de múltiples bloques. Estos bloques no necesitan ser almacenados    contiguamente. Cada vez que el usuario solicita estos datos, el sistema de almacenamiento subyacente vuelve a combinar los bloques de datos y atiende la solicitud    del usuario.
  
  
  


•	Se puede usar para dar de alta un sitio web estático

•	Cómo funcionan los triggers y sus casos de uso

      Un trigger o disparador es un script que se usa en lenguaje de programación SQL, en especial en bases de datos como MySQL o PostgreSQL.
      Consiste en una serie de reglas predefinidas que se asocian a una tabla. Estas reglas se aplican a la base de datos cuando se realizan determinadas operaciones en la tabla, por ejemplo, al añadir, actualizar o eliminar registros.
      Dicho de otra manera, el trigger desencadena determinadas acciones de forma automática en las tablas de la base de datos cuando se insertan, modifican y se añaden nuevos datos.
  
  ¿Para qué sirve?
  
    La principal función de los trigger es contribuir a mejorar la gestión de la base de datos. Gracias a ellos muchas operaciones se pueden realizar de forma automática, sin necesidad de intervención humana, lo que permite ahorrar mucho tiempo. 
    Otra de sus funciones es aumentar la seguridad e integridad de la información. Esto lo consiguen gracias a la programación de restricciones o requerimientos de verificación que permiten minimizar los errores y sincronizar la información. 
    Por otra parte, entre sus principales ventajas es que todas estas funciones se pueden realizar desde la propia base de datos, es decir, no es necesario recurrir a lenguajes externos de programación.
  



