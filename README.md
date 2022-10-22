<h1># deberesTendencias</h1>
<h1>informes semanales para tendencias tecnologicas</h1>

<h2>1.Crear una cuenta en Docker Hub</h2>

<img src="crear cuenta.JPG" />

<h2>2. Iniciar play with docker desde el navegador e iniciar sesion</h2>

![image](https://user-images.githubusercontent.com/91167333/195993050-60cf5b17-adec-4373-8e8d-80255af69a62.png)

<h2>4. click en añadir nueva instancia</h2>

![image](https://user-images.githubusercontent.com/91167333/195993186-27a9b09d-e133-490f-a993-6cf6cf407ce6.png)

<h2>6. En la pantalla consola añadir el contenedor con el comando "docker run --name serverweb -p 80:80 -d nginx" especificanco el puerto con el que se trabajará</h2>

![image](https://user-images.githubusercontent.com/91167333/195993148-51736c48-26b1-4046-81e3-35e6adf82a42.png)

<h2>8. Revisar el contenedor que esta corriendo con comando "docker ps"</h2>

<img src="1.JPG" />
<h2>9.obtener un archivo html desde un repositorio en github con el comando "wget" seguido del url del repositorio</h2>

![image](https://user-images.githubusercontent.com/91167333/197315434-9b17d20c-6113-43d2-bdd6-66e7665fa28f.png)

<h2>10.se puede observar que se cargo correctamente</h2>

![image](https://user-images.githubusercontent.com/91167333/197315456-41102b74-a9e8-4d4b-8b57-6edd2b247206.png)

<h2>11.seguido se clona el repositorio con "git clone" seguido del url del html</h2>


![image](https://user-images.githubusercontent.com/91167333/197315526-22499386-3590-4492-8e79-2ac4c25003a1.png)

<h2>12.se ingresa al directorio del html con "cd"</h2>


![image](https://user-images.githubusercontent.com/91167333/197315540-5d6436aa-a9e8-410b-be02-1456442160b1.png)

<h2>13.revisamos con un "ls" si esta el archivo html </h2>


![image](https://user-images.githubusercontent.com/91167333/197315559-c8b4f1f6-42f2-4f07-9ac3-9cf9bb7fa297.png)

<h2>14.se extrae el archivo html con el comando "docker cp index2.html serverweb/usr/share/nginx/html/index2.html</h2>


![image](https://user-images.githubusercontent.com/91167333/197315578-3827b236-5f3a-4e40-b272-cc6d940c20fb.png)

<h2>15.presionamos en el boton port para ingresar al puerto cargado anteriormente</h2>


![image](https://user-images.githubusercontent.com/91167333/197315597-a8ed21c9-8141-4db0-8c1e-6fd3d4973bd7.png)

<h2>16.Ingresamos el puerto utilizado en el contenedor</h2>

  ![image](https://user-images.githubusercontent.com/91167333/197315602-f7edba1c-39ac-4856-afeb-3138e9a49bd0.png)

<h2>17. esta funcionando nginx y en la url se agrega un slash seguido del nombre del html al que vamos a ingresar </h2>

![image](https://user-images.githubusercontent.com/91167333/197344965-9b36cd11-2c9f-456a-9ab6-939986bff95a.png)



<h2>18. Se puede observar que la pagina web se cargo correctamente y se visualiza el html anteriormente cargado desde github </h2>

![image](https://user-images.githubusercontent.com/91167333/197315624-6dd4f180-431e-41f6-aac7-a8d365c80d4a.png)





