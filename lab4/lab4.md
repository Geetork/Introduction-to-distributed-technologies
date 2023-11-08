University: [ITMO University](https://itmo.ru/ru/) <br/>
Faculty: [FICT](https://fict.itmo.ru) <br/>
Course: [Network programming](https://github.com/itmo-ict-faculty/network-programming) <br/>
Year: 2023/2024 <br/>
Group: K4110c <br/>
Author: Li Galina <br/>
Lab: Lab2 <br/>
Date of create: 08.11.2023 <br/>
Date of finished: x.x.2023 <br/>

# Лабораторная работа №4 "Сети связи в Minikube, CNI и CoreDNS"

## Описание
   Это последняя лабораторная работа в которой вы познакомитесь с сетями связи в Minikube. Особенность Kubernetes заключается в том, что у него одновременно работают underlay и overlay сети, а управление может быть организованно различными CNI.

## Цель работы:
   Познакомиться с CNI Calico и функцией IPAM Plugin, изучить особенности работы CNI и CoreDNS.

## Ход работы:
   В процессе выполнения лабораторной работы были выпонены следующие шаги:
   
   1. При запуске minikube установлен плагин CNI=calico и включен режим работы Multi-Node Clusters одновеременно

![image](https://github.com/Geetork/Introduction-to-distributed-technologies/assets/58363643/331eb734-0086-4546-b355-6a12bef2af22)

   2. Проверена настройка и количество нод

![image](https://github.com/Geetork/Introduction-to-distributed-technologies/assets/58363643/2409846c-f354-4ece-9887-eb42090c81bb)

   3. Для запущенных нод указаны лэйблы
      
![image](https://github.com/Geetork/Introduction-to-distributed-technologies/assets/58363643/e858d1cf-11a8-43f6-9379-54d3ea8e2a62)

   4. Разработан манифест, который назначает ip адреса нодам в зависимости от указанных лэйблов

![image](https://github.com/Geetork/Introduction-to-distributed-technologies/assets/58363643/349be74f-4a0e-467e-941a-2c32f3d3033e)
![image](https://github.com/Geetork/Introduction-to-distributed-technologies/assets/58363643/7a67a203-52d9-4471-ba11-c364538ec6bb)
![image](https://github.com/Geetork/Introduction-to-distributed-technologies/assets/58363643/a3f4cddd-ea6f-4e52-9e28-a819e1bf842a)

   5. Запущен режим проброса портов, затем было выполнение подключение к контейнерам через веб-браузер

![image](https://github.com/Geetork/Introduction-to-distributed-technologies/assets/58363643/965e7f3c-080f-42d4-a1ac-4f277eeeb4e5)

   6. Пропингованы контейнеры
      
![image](https://github.com/Geetork/Introduction-to-distributed-technologies/assets/58363643/ba6d0790-4f61-4a1d-8af4-fb0d659ac945)


## Вывод

Таким образом, ознакомились с CNI Calico и функцией IPAM Plugin, изучили особенности работы CNI и CoreDNS.



