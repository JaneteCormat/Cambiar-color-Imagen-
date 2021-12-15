# Cambiar-color-Imagen-

## Clase ProcesaImg
#### En esta clase nos servirá para cargar la imagen la cual queremos cambiarle el color. 
#### En la clase cargarImagen se declara las variables, se declara una variable llamada selector el cual nos permite mostrar fácilmente una ventana para la selección de un fichero, también se declara una variable filtroImagen el cual nos ayudara a filtrar solo los archivos que sean en formato imagen. Después se carga el filtro al selector para que solo se puede visualizar los formatos de imagen que contiene la filtración, después dentro de un try se selecciona la imagen y después se lee la imagen y se guarda en la variable bmp. Por último se retorna la imagen guardada en la variable bmp.

![1](https://user-images.githubusercontent.com/95993275/146121587-5d46f32d-2dde-4d79-8e70-541621f090ba.png)


#### En el siguiente método nos sirve para cambiar el color de la imagen. Dentro de dos for anidados recorremos cada pixel de la imagen cargada e iremos obteniendo los colores de ese pixel de los colores rgb y luego se van cambiando los colores de cada pixel. Y al final se retorna la imagen cambiada su color.
![2](https://user-images.githubusercontent.com/95993275/146121588-95f1e775-5943-4c25-a883-a5ec0303f96d.png)


#### En la clase Principal tenemos un Frame el cual nos ayuda a mostrar la imagen en el Label. Y tenemos dos botones uno para cargar una imagen desde nuestra computadora, el otro  botón nos ayuda para cambiarle el color de dicha imagen cargada.
![3](https://user-images.githubusercontent.com/95993275/146121589-012f9759-bf4d-4d14-89a4-c2e1d483a4d3.png)


#### El código de esta clase se tiene solo los eventos de los botones, el botón de cargar imagen llamará el método que nos ayuda para cargar la imagen, el botón de cambiar el color también llama el método el cual cambia el color y por último al ejecutar ponemos cadena vacia al label para que no se muestre la información al cargar una imagen.
![4](https://user-images.githubusercontent.com/95993275/146121562-c9c7581f-962d-4152-abd5-a1a97acf5226.png)



# Resultados
#### Ventana principal al ejecutar el programa, para cargar una imagen presionamo el boton de cargar imagen. 

![5](https://user-images.githubusercontent.com/95993275/146121565-eac5e017-abfe-40bf-9050-d873ae0f1ca4.png)

#### Luego nos muestra esta pequea ventana el cual nos ayudara para seleccionar la imagen que deseamos cambiarle el color. Ahora buscaremos la imagen y presionamos el boton Abrir para cargar la imagen en el programa.
![6](https://user-images.githubusercontent.com/95993275/146121566-e1a0f6bd-ec7a-4143-ba1b-05cfad4cb346.png)


#### Posteriormente podemos visualizar la imagen en la ventana. Para cambiar de color dicha imagen presionamos el botón “Cambiar Color”.
![7](https://user-images.githubusercontent.com/95993275/146121568-43cc6a2c-de9e-4614-af87-3d2ec49b7088.png)
#### Imagen cambiada de color.
![8](https://user-images.githubusercontent.com/95993275/146121577-7f38d91c-a375-45fe-8a45-4d02f2729f7c.png)
