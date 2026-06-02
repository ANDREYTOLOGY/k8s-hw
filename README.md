# Домашнее задание занятию `«Базовые объекты K8S»` - `Чернышов Андрей`
 
## Задание 1. Создать Pod с именем hello-world.  

**Файл манифеста:** [`hello-world-pod.yaml`](/hello-world-pod.yaml)

![1]((https://github.com/ANDREYTOLOGY/k8s-hw/blob/main/img/k8s-1.png))   
![2]((https://github.com/ANDREYTOLOGY/k8s-hw/blob/main/img/k8s-2.png))  

При открытии http://localhost:8080 через curl отображается информация о запросе.  

## Задание 2. Создать Service и подключить его к Pod
![3]((https://github.com/ANDREYTOLOGY/k8s-hw/blob/main/img/k8s-3.png))     

![4]((https://github.com/ANDREYTOLOGY/k8s-hw/blob/main/img/k8s-4.png))  

При открытии http://localhost:8080 сервис успешно перенаправляет запрос на Pod.

