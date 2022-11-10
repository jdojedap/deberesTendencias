<h2>1.Crear el contenedor para administrador y su puerto</h2>

![image](https://user-images.githubusercontent.com/91167333/198837896-5c8bcde3-67a3-43e7-9624-064aabea0229.png)
<h2>2.crear el contenedor para postgtresql y el puerto que va a usar </h2>

![image](https://user-images.githubusercontent.com/91167333/198838792-9dee1048-6daf-44ea-960d-df575e18c49b.png)

<h2>3.se asigna el contenedor admin y contraseña con codigo (docker run -d --name dbpsql -e POSTGRES_PASSWORD=admin  -p 5432:5432 postgres)</h2>

![image](https://user-images.githubusercontent.com/91167333/198838847-54a69cdc-bd26-498e-90e1-50b8647a1535.png)

<h2>4.Crear la red que se va  a usar con (docker network create --attachable redJuanOjeda)</h2>

![image](https://user-images.githubusercontent.com/91167333/198838866-721c27fb-393d-41e0-b659-1fa821e96f41.png)

<h2>5.Conectar en la red JuanOjeda los contenedores entre si con (docker network connect redJuanOjeda pgadmin  y  (docker network connect redJuanOjeda postgresql)</h2>

![image](https://user-images.githubusercontent.com/91167333/198838922-403be276-eef8-48fa-8bff-b8d49908d3d4.png)

<h2>6.Usamos codigo (codigo inspect redJuanOjeda) para poder visualizar las redes que estan funcionando y conectados</h2>

![image](https://user-images.githubusercontent.com/91167333/198839007-278d3e2c-5d4f-4797-9c85-fdd1519a03a3.png)
![image](https://user-images.githubusercontent.com/91167333/198839065-22cb37d9-4312-4d87-a127-e675dd36039e.png)
![image](https://user-images.githubusercontent.com/91167333/198839193-b113e6b0-b465-4107-a16d-9abaafbcca51.png)
![image](https://user-images.githubusercontent.com/91167333/198839080-5cdf724d-faf0-47dc-9740-ea1d864f94d2.png)

