1. Включаем ingress в minikube
![alt text](image.png)

2. Проверяем запустился ли ingress controller
![alt text](image-1.png)

3. Запускаем hello-world
![alt text](image-2.png)

4. Создаем сервис типа NodePort
![alt text](image-3.png)

5. Создаем ingress-resource
![alt text](image-4.png)

6. Проверяем, что ingress-resource появился
![alt text](image-5.png)

7. (для всех остальных) Делаем ingress доступным на хостовой машине, это связано с особенностями minikube. Не закрываем данное окно!!!
![alt text](image-6.png)

8. Ingress на входе ожидает хост hello-world.local, поэтому нужно добавить мапинг на хостовой машине в файл /etc/hosts для UNIX-based систем.
![alt text](image-7.png)

ИТОГ:
![alt text](image-8.png)
