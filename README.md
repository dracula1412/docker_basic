# Docker Tutorial
---
- Build command:
  ```
  sudo docker build -t ubuntu-nginx .
  ```
- See docker image was created:
  ```
  sudo docker images
  ```
- Run command:
  ```
  sudo docker run -v /home/hungkm/docker/docker_basic/public:/var/www/html -p 9000:80 -it ubuntu-nginx /bin/bash
  ```
- Result:

  ![image](https://user-images.githubusercontent.com/1135048/50764079-3aaf1500-12a4-11e9-9e63-044a839574da.png)
- Docker Auto Build after link with Github:
  - [Link](https://cloud.docker.com/repository/docker/hungkm/docker_basic/builds)
  - Screenshot:
  ![image](https://user-images.githubusercontent.com/1135048/50764179-81047400-12a4-11e9-9e8a-04d06243d482.png)

