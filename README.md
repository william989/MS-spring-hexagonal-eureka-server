### Construir Imágen Docker

```bash
docker build -t eurekaservice .
```

### Iniciar Contenedor 

```bash
docker run --name eurekaservice --restart always --detach -p 8761:8761
eurekaservice 
```

En caso el contenedor este iniciado, se tiene que detener y eliminar

```bash
docker stop eurekaservice
docker rm eurekaservice
```