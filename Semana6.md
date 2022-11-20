<h1>1.SE CREA UNA CARETA Y EN ESTE SE CREA UN ARCHI YML Y SE EJECUTA EL COMANDO docker-compose up -d</h1>
![image](https://user-images.githubusercontent.com/91167333/202927307-fbd25bb2-3c1f-41a4-acdf-e4eb3d18813d.png)

<h1>2.SE CLONA EL REPOSITORIO DE LA APP EN LA CARPETA</h1>

![image](https://user-images.githubusercontent.com/91167333/202927356-c6e184f5-efbd-4a9e-be48-d856321cd371.png)

<h1>3.GENERA EL ARCHIVO ARTEFACTO JAR CON EL CONTENEDOR MAVEN Y SE MODIFICA LA RED QUE USAMOS POR db_dafault</h1>

![image](https://user-images.githubusercontent.com/91167333/202927526-c4ede62b-7228-470a-b097-ceac1f373f70.png)

<h1>3.1 CREAMOS LA BASE DE DATOS EN PGADMIN </h1>


![image](https://user-images.githubusercontent.com/91167333/202927939-b4b6bf8a-f780-4a01-996a-cb4f3bb91c1c.png)


<h1>3.2 CAMBIAMOS EL NOMBRE DEL PROYECTO DE LA BASE DE DATOS EN EL DOCKER FILE </h1>

![image](https://user-images.githubusercontent.com/91167333/202927879-002baea3-53b3-49f7-ac9f-14ec97791c9a.png)


<h1>4.CREARCION DE IMAGEN DE SPRINGBOOT CON EL COMANDO  docker build -t myapp . </h1>

![image](https://user-images.githubusercontent.com/91167333/202927648-b8933985-2bc2-4d3e-9ddc-6267929c3882.png)

<h1>5.CORREMOS UN CONTENEDOR CON COMANDO docker run -d --network red_de_los_contenedores -p 8081:8081 myapp</h1>

![image](https://user-images.githubusercontent.com/91167333/202927674-2e9be122-acf4-453c-8104-e122ae6256c3.png)


<h1>6.PROBAMOS EL FUNCIONAMIENTO CEN EL LOCALHOST localhost:8081/users</h1>

![image](https://user-images.githubusercontent.com/91167333/202927749-2f9f12e5-557c-4dd1-8a3f-f075e438a154.png)











