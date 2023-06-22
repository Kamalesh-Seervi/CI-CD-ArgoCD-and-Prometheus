# K8-ArgoCD
 
# Part 1 : Dockerized the Node app

- Build the image using the below command.

```
docker build -t <DockerHub_username>/<image_name> .
```

-  Push this image to the docker hub by using the below command.

```
docker push <DockerHub_username>/<image_name>
```

<img width="1344" alt="image" src="https://github.com/Kamalesh-Seervi/CI-CD-ArgoCD-and-Prometheus/assets/107933310/f015c6db-4122-4214-969d-752d18c644e5">

- Docker image pushed successfully .

- <img width="1379" alt="image" src="https://github.com/Kamalesh-Seervi/CI-CD-ArgoCD-and-Prometheus/assets/107933310/d287436c-9f38-4eb3-9d7f-3d3842b6bbaf">




# Part 2 : Configuring Kubernetes cluster using terraform


- Navigate into k8-terraform

```
cd k8-teraform
```

- Now type the following command

```
terraform init
```











