# Reconocedor-de-Patentes
Guía de desarrollo del Reconocedor de Patentes
	Esta guía fue desarrollada en Google Colab el cual permite editar y ejecutar archivos .ipynb en los servidores de Google, obteniendo así gran capacidad de cómputo, lo cual permite entrenar de manera rápida modelos de aprendizaje profundo. También sirve para cualquier usuario que quiera probar el reconocedor de patentes desarrollado en este proyecto sin tener que instalar programas y librerías en su propia computadora.
	Descargar el siguiente archivo comprimido, el cual contiene el Reconocedor de Patentes, un script de soporte, las imágenes de entrenamiento y pruebas y el modelo finalizado con todos los checkpoints obtenidos del primer entrenamiento.
 
 https://drive.google.com/file/d/1vd7EZrH0atovymUvGdCMIu5IdBk8NKv2/view?usp=sharing

	Descomprimir el archivo .zip. Iniciar sesión en Google Drive y cargar la carpeta “Esbiza_Proyecto_de_Grado” en su directorio principal de Drive.
	Abrir desde Google Drive el archivo “Reconocedor_de_Patentes.ipynb” con Google Colab. Para esto debemos seguir los siguientes pasos:
1.	Dar doble clic sobre Reconocedor_de_Patentes.ipynb.
2.	Clicar en “Abrir con”, y luego en “Conectar más aplicaciones”.
3.	En “Buscar aplicaciones” colocamos “Colaboratory”.
4.	Elegir Colaboratory.
5.	Clicar en “Instalar” y dar los permisos necesarios.

	Ir ejecutando las celdas una a una siguiendo las instrucciones que se detallan el notebook.	
Si quiere solamente probar el reconocedor de patentes, ejecutar únicamente las secciones:
•	Iniciando ubicaciones de arhivos y directorios para el espacio de trabajo.
•	Instalando Tensorflow y modelo pre-entrenado.
•	Preparación de los datos.
•	Cargar modelo entrenado desde un checkpoint.
•	Detectando desde una imagen.
•	Aplicando Tesseract-OCR.
