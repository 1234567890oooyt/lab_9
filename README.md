# lab 9

# Запуск інстансу:


Для запуску викристовуйте файл "lab_9.bat"

Нище наведені команди для підключення і запуску демона на докері:

 
ssh -i "C:\Users\Yehen\Downloads\citroen.pem" -L 5566:127.0.0.1:2375 ubuntu@52.23.231.48


docker -H localhost:5566 build -t nginx .

docker -H localhost:5566 run -d -p 80:80 nginx

docker -H localhost:5566 images

docker -H localhost:5566 ps

для перевірки використовуйте "http://52.23.231.48"

