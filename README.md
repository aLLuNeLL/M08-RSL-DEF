Pasos a seguir para el funcionamiento:

**ANTES DE EMPEZAR**
Tener instalado: docker

```
apt update && apt install docker docker-compose git -y
```

1. GIT CLONE:

  Se hace un git clone del repositorio entero: 
  ```
  git clone https://github.com/aLLuNeLL/M08-WEB-APP.git
  ```

2. RUTA DEL DOCKER-COMPOSE.YAML

  ```
  cd M08-RSL_DEF/
  ``` 
  --> Aquí dentro encontrarás el docker-compose.yaml

3. EJECUCIÓN:

  Para inicializarlo y montarlo, simplemente haces un: 
  ```
  docker-compose up --build
  ```

4. VISUALIZACIÓN:

  Para que se visualice,  
   ```
  docker-compose up
  ```
  De manera silenciosa:
  ```
  docker-compose up -d
  ```
  Vas a 
  ```
  localhost:8080
  ```
SI TODO HA IDO BIEN, DEBERÍA FUNCIONAR.

En caso de hacerlo por reenvio de puertos en Oracle Virtual Box:

![image](https://github.com/user-attachments/assets/e515e688-0f26-40a5-b5d2-5663a3e24e1a)

![image](https://github.com/user-attachments/assets/f2fc42d5-5e05-44c9-8ca0-ccfaafbdc50b)



