# Ejercicio
Configurar SonarQube utilizando Docker Compose, para esto necesitas dos servicios:
- Servicio: SonarQube
- Desde el host es necesario acceder a SonarQube por lo que necesitas mapear el puerto correspondiente.
- Servicio: PostgreSQL (existen otras opciones: Microsoft SQL Server, Oracle)
- Coloca un healtcheck para cada uno de los servicios.
- Los dos servicios deben pertenecer a una red de tipo bridge
- Investiga cuáles son los volúmenes necesarios para cada servicio
- Investiga cuáles son las variables de entorno para que los servicios funcionen de manera adecuada.
  
# Una vez creado tu archivo .yaml realiza la respectiva prueba   

<img width="1402" height="2382" alt="docker compose" src="https://github.com/user-attachments/assets/b6ff1d9d-cf88-4e6c-b9a5-7838018e9a99" />

```
docker compose up -d
```

<img width="1139" height="659" alt="docker compose up -d" src="https://github.com/user-attachments/assets/057160c0-9c81-4b4d-a4e3-983beb81af1d" />  


**localhost:9000**     
<img width="1144" height="659" alt="sonarqube login" src="https://github.com/user-attachments/assets/9c6ae187-1c3c-4c5a-a7d1-59dde5944b2f" />  
<img width="1866" height="663" alt="sonarqube panel" src="https://github.com/user-attachments/assets/b5367ca5-0e33-4dd9-8b2d-79c32fc94678" />



