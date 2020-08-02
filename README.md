# Vision-Artificial-RNA
Visión Artificial con aplicación de una RNACosas a tener en cuenta para ejecutar el proyecto
Se debe saber cómo crear entornos virtuales con Conda a partir de un fichero yml
OpenCV puede dar problemas a la hora de instalar desde Conda (sobre todo con la integración de la web-cam). Se debe buscar el repositorio que corresponda a nuestro SO, siempre teniendo en cuenta la versión de Python especificada en el fichero yml.
Cómo lanzar el proyecto
Clonar en tu máquina el repositorio

Instalar conda (gestor de paquetes cientificos de Python). Con la instalación de Conda vendrá Jupyter también.

Instalar con Conda el entorno virtual de Python extraído en el fichero fa-workshop01.yml. Se han detectado algunos issues con algunas versiones de OS. Está extraido de un MacOS. La instalación en otros OS no debería ser problema instalando una a una las dependencias antes de correr el notebook.

Establecer Tensorflow como el backend de Keras con el siguiente comando.

set KERAS_BACKEND=tensorflow para Windows KERAS_BACKEND=tensorflow para Limux/MacOS

Para comprobar que todo está configurado correctamente: python -c "from keras import backend"

Activar el entorno de desarrollo y hacer disponible este entorno virtual para que pueda ser ejecutado desde Jupyter. Se puede encontrar cómo hacerlo en este enlace.

Descomprimir los dos archivos .zip que se encuentran en el directorio data

Ejecutar el siguiente comando desde el directorio raíz del proyecto jupyter notebook

Seleccionar nuestro entorno virtual para que el kernel de Jupyter ejecute el código usando nuestras librerías.

Autores
Juan Aguilar - AguilarGuisado

Udacity attribution as the original creators of this project in their full AI Nanodegree program.

Todo el código es libre de ser distribuido y modificado bajo la licencia Apache v2.0
