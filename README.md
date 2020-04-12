# PDI-Tarea2-I2016
Materia: Procesamiento Digital de Imagenes

## Autores:
Nombre: Jose Francisco Iannini
C.I: 24.276.962

Nombre: Jeisson Ferreira
C.I: 18.003.702

## Materia:
Procesamiento Digital de Images

## Tarea 2
Operaciones a imagenes de formato .bmp

## Lenguajes Empleados:
1. JavaScript: Manipulacion de imagen
2. HTML: Interfaz grafica
3. CSS: Estilo interfaz grafica

## Descripcion
Manipulacion de imagenes en formato .bmp

1. Abrir una imagen en formato BMP sin compresion, de cualquier tipo
2. Calcular y mostrar informacion relevante de la imagen (e.g. dimensiones, profundidad de bits, Mb ocupados.)
3. Calcular y desplegar el histograma de la imagen. Si la imagen es a color, entonces un histograma por cada canal.
4. Realizar la ecualizacion de la imagen
5. Realizar las operaciones de espejo horizontal y vertical.
6. Calcular el negativo de la imagen
7. Modificar el brillo y contraste basado en modificaciones al histograma
8. Permitir la umbralizacioon de la imagen, dado un valor threshold o un rango (i.e. valor minimo y maximo)
9. Permitir el escalamiento y rotacion libre de la imagen
10. Ofrecer la opcion de interpolacion nearest o bilinear para las opciones que lo requieran
11. Aplicar acercamiento y alejamiento (zoom in/out)
12. Salvar la imagen resultante de las modificaciones realizadas

## Ejecucion
Abrir el documento index.html ubicado en la carpeta src. Este abrira un navegador web, en donde se encuentra una interfaz la cual tiene una serie de botones.

### Opciones a escoger 
1. Informacion: Despliega un modal con la informacion mas importante de la imagen.
2. Original: Muestra la imagen cargada originalmente.
3. Negativo: Calculo el negativo de la imagen actual y la muestra.
4. Gris: Convierte la imagen actual en escala de grises.
5. Espejo Horizontal/Vertical: Aplica el espejo a la imagen segun sea el caso.
6. Histograma: Despliega un modal con el histograma de la imagen actual, acompañado de la imagen.
7. Ecualizar: Ecualiza el histograma de la imagen aplicando ese efecto a la imagen. 
8. ZoomIN: Acerca la imagen 2X.
9. ZoomOUT: Aleja la imagen 2X.
10. Bilinear: Al presionar se selecciona el metodo de interplacion bilineal para el calculos en los que se requiera un interpolacion. Ese el metodo por defecto.
11. Neares Neighbor: Escoge el metodo de interpolacion de vecino mas cercano.
12. Grados: Cuadro de texto donde se introduce la cantidad de grados que se quiera rotar la imagen.
13. Izquierda/Derecha: Rota la imagen tantos grados ingresado hacia la izquierda o derecha segun sea el caso.
14. Brillo ("-","+"): Aumenta o disminuye el brillo a la imagen.
15. Contraste ("-","+"): Aumenta o disminuye el contraste a la imagen.
16. Ancho: Area de texto donde se ingresa una nueva medida en pixeles para el ancho de la imagen.
17. Alto: Area de texto donde se ingresa una nueva medida en pixeles para el de la imagen.
18. Escalar: Redimensiona la imagen segun el alto y ancho ingresado.
19. Threshold: Area de texto donde se ingresa el valor que se quiere aplicar para la umbralizacion.
20. Umbralizar: Umbraliza la imagen segun el threshold ingresado.

## Version
1.0

