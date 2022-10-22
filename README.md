# deberesTendencias
informes semanales para tendencias tecnologicas

1.Crear una cuenta en Docker Hub 

<img src="crear cuenta.JPG" />

2. Iniciar play with docker desde el navegador e iniciar sesion

![image](https://user-images.githubusercontent.com/91167333/195993050-60cf5b17-adec-4373-8e8d-80255af69a62.png)

4. click en añadir nueva instancia

![image](https://user-images.githubusercontent.com/91167333/195993186-27a9b09d-e133-490f-a993-6cf6cf407ce6.png)

6. En la pantalla consola añadir el contenedor con el comando "docker run --name serverweb -p 80:80 -d nginx" especificanco el puerto con el que se trabajará

![image](https://user-images.githubusercontent.com/91167333/195993148-51736c48-26b1-4046-81e3-35e6adf82a42.png)

8. Revisar el contenedor que esta corriendo con comando "docker ps"

<img src="1.JPG" />
9.obtener un archivo html desde un repositorio en github con el comando "wget" seguido del url del repositorio

![image](https://user-images.githubusercontent.com/91167333/197315434-9b17d20c-6113-43d2-bdd6-66e7665fa28f.png)

10.se puede observar que se cargo correctamente

![image](https://user-images.githubusercontent.com/91167333/197315456-41102b74-a9e8-4d4b-8b57-6edd2b247206.png)

11.seguido se clona el repositorio con "git clone" seguido del url del html


![image](https://user-images.githubusercontent.com/91167333/197315526-22499386-3590-4492-8e79-2ac4c25003a1.png)

12.se ingresa al directorio del html con "cd"


![image](https://user-images.githubusercontent.com/91167333/197315540-5d6436aa-a9e8-410b-be02-1456442160b1.png)

13.revisamos con un "ls" si esta el archivo html 


![image](https://user-images.githubusercontent.com/91167333/197315559-c8b4f1f6-42f2-4f07-9ac3-9cf9bb7fa297.png)

14.se extrae el archivo html con el comando "docker cp index2.html serverweb/usr/share/nginx/html/index2.html


![image](https://user-images.githubusercontent.com/91167333/197315578-3827b236-5f3a-4e40-b272-cc6d940c20fb.png)

15.presionamos en el boton port para ingresar al puerto cargado anteriormente


![image](https://user-images.githubusercontent.com/91167333/197315597-a8ed21c9-8141-4db0-8c1e-6fd3d4973bd7.png)

16.Ingresamos el puerto utilizado en el contenedor

![image](https://user-images.githubusercontent.com/91167333/197315602-f7edba1c-39ac-4856-afeb-3138e9a49bd0.png)

17. Se puede observar que la pagina web se cargo correctamente y se visualiza el html anteriormente cargado desde github 

![image](https://user-images.githubusercontent.com/91167333/197315624-6dd4f180-431e-41f6-aac7-a8d365c80d4a.png)





