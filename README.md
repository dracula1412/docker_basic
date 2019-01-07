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
  Attach Image later
