University: [ITMO University](https://itmo.ru/ru/) <br/>
Faculty: [FICT](https://fict.itmo.ru) <br/>
Course: [Network programming](https://github.com/itmo-ict-faculty/network-programming) <br/>
Year: 2023/2024 <br/>
Group: K4110c <br/>
Author: Li Galina <br/>
Lab: Lab2 <br/>
Date of create: 27.10.2023 <br/>
Date of finished: x.x.2023 <br/>

# Лабораторная работа №3 "Сертификаты и "секреты" в Minikube, безопасное хранение данных"

## Описание
   В данной лабораторной работе вы познакомитесь с сертификатами и "секретами" в Minikube, правилами безопасного хранения данных в Minikube.

## Цель работы:
   Познакомиться с сертификатами и "секретами" в Minikube, правилами безопасного хранения данных в Minikube.

## Ход работы:
   В процессе выполнения лабораторной работы были выпонены следующие шаги:
   
   1. Создан configMap.

![image](https://github.com/Geetork/Introduction-to-distributed-technologies/assets/58363643/b67f061e-a4f5-4db3-9616-5e202b8eeb1b)
![image](https://github.com/Geetork/Introduction-to-distributed-technologies/assets/58363643/38aded5e-7f54-40fa-b4a3-b0b138c48963)

   2. Сгенерирован сертификат
      
![image](https://github.com/Geetork/Introduction-to-distributed-technologies/assets/58363643/6f681d7f-bd14-417c-a10b-39a9c4b0136a)

   3. Включен, создан ingress

![image](https://github.com/Geetork/Introduction-to-distributed-technologies/assets/58363643/5e7f456e-7881-46a6-8908-0444e7c184df)
![image](https://github.com/Geetork/Introduction-to-distributed-technologies/assets/58363643/20ffdaa3-9731-48cf-9663-130113053d2b)

![image](https://github.com/Geetork/Introduction-to-distributed-technologies/assets/58363643/4e9393bf-858d-4090-ba02-201a1ad23b23)

   4. Отредактирован файл hosts

![image](https://github.com/Geetork/Introduction-to-distributed-technologies/assets/58363643/6da0291a-5f48-4516-8bcf-a2593e662361)

   5. Создан секрет, который затес добавлен в ingress
![image](https://github.com/Geetork/Introduction-to-distributed-technologies/assets/58363643/c2c2bb75-1af2-4d3b-bef6-001f1368a763)

   6. С помощью fqdn имени открыто веб-приложение

![image](https://github.com/Geetork/Introduction-to-distributed-technologies/assets/58363643/07893c5a-9196-4c67-b6d9-c196244731ca)

   7. Просметрены данные о сертификате
      
![image](https://github.com/Geetork/Introduction-to-distributed-technologies/assets/58363643/13962f01-6a98-403f-bab0-395c5afe8363)

## Вывод

Таким образом, ознакомились с объектоми Ingress, configMap, secret.


