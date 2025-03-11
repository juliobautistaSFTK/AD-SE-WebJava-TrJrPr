### Guía para el ejercicio AD-SE-WebJava-TrJrPr

En este ejercicio se utilizan 2 características de GITHUB, se llaman Actions y Codespaces.

Los Actions son flujos de trabajo que se activan al hacer un commit en el repositorio, la finalidad del Action en este ejercicio, es descargar el código en un área virtual propia de GITHUB.

De forma automática este Action compila el proyecto con Maven, crea una base de datos Mariadb, crea una tabla y posteriormente ejecuta los test del código con Maven.

![Descripción de la imagen](../Imagenes/imagenes/Img40.png)

Este Action viene precargado y no se debe modificar.

Si tienes como resultado algo parecido a esta pantalla, significa que algo salió mal entre la compilación, los test o tu código no apunta correctamente a la base de datos.

![Descripción de la imagen](../Imagenes/imagenes/Img41.png)

Para ver el detalle del error da clic en el resultado y te debe aparecer algo similar a esta imagen.

![Descripción de la imagen](../Imagenes/imagenes/Img42.png)

Este ejercicio utiliza otra herramienta que se llama Codespaces. Un codespace es un ambiente de desarrollo que se hospeda en la nube. 

Este ejercicio cuenta con un docker-compose.yml que crea 3 contenedores de docker.

=============================================================


![Descripción de la imagen](../Imagenes/imagenes/Img9.png)

Selecciona crear un nuevo fork.

![Descripción de la imagen](../Imagenes/imagenes/Img10.png)

Es recomendable dejar el nombre que se presenta default y selecciona el botón create fork.

![Descripción de la imagen](../Imagenes/imagenes/Img11.png)

Aparecerá este mensaje “forked from”.

![Descripción de la imagen](../Imagenes/imagenes/Img12.png)

Se verá así.

![Descripción de la imagen](../Imagenes/imagenes/Img13.png)

Para acceder a un Codespace selecciona Code una vez dentro de tu repositorio.

![Descripción de la imagen](../Imagenes/imagenes/Img14.png)

Tendremos esta ventana con 2 pestañas.

![Descripción de la imagen](../Imagenes/imagenes/Img15.png)

Selecciona Codespaces.

![Descripción de la imagen](../Imagenes/imagenes/Img16.png)

Tendrás esta pantalla, en este ejemplo el Codespace se generará con las instrucciones en la rama main. 

Espera hasta que presente una pantalla similar a esta:

![Descripción de la imagen](../Imagenes/imagenes/Img17.png)

Ya puedes utilizar este Codespace.

Si quieres utilizar el Codespace con Visual Studio Code, necesitas tener instalado previamente Visual Studio Code en tu computadora.

Tendrás una pantalla como la siguiente:

![Descripción de la imagen](../Imagenes/imagenes/Img18.png)

![Descripción de la imagen](../Imagenes/imagenes/Img19.png)

Espera unos minutos en lo que levanta el CodeSpace y tendrás una pantalla como esta:

![Descripción de la imagen](../Imagenes/imagenes/Img20.png)

Si no aparece la sección de la terminal presiona control-ñ.

![Descripción de la imagen](../Imagenes/imagenes/Img21.png)

Para entregar tu ejercicio, debes previamente hacer el push a tu rama en tu repositorio.


Una vez que tu solución esté en tu rama, deberás comparar tu rama local y la rama del fork, basta con agregar la palabra compare al link de tu repositorio como la siguiente imagen.

![Descripción de la imagen](../Imagenes/imagenes/Img27.png)


Te presentará la comparación de los cambios, donde podrás seleccionar tu rama de tu repositorio contra la rama del repositorio que previamente creaste con el fork, selecciona Create pull request.

![Descripción de la imagen](../Imagenes/imagenes/Img28.png)

![Descripción de la imagen](../Imagenes/imagenes/Img27_1.png)

Tendrás esta pantalla donde es muy importante escribir en campo Add a title la palabra Ejercicio_(el número del ejericio) y tu IS como se muestra en la imagen, puedes agregar alguna descripción adicional en el campo Add a description y selecciona Create pull request.

![Descripción de la imagen](../Imagenes/imagenes/Img29.png)

Ahora espera la evaluación de tu instructor.

**Recuerda borrar todos los Codespace abiertos.**










