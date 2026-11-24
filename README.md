# Иванова Елизавета, ФИТ-1-2025. П07. Docker basics

## 1. Устанавливаем докер

```
sudo apt update
sudo apt install docker.io 
```

Проверяем работу 

<img width="785" height="243" alt="image" src="https://github.com/user-attachments/assets/a83ec4a5-edcb-4980-bc27-a0b9702798d9" />

<img width="675" height="201" alt="image" src="https://github.com/user-attachments/assets/a0f64d11-7025-487a-ae17-4797021bb4f4" />

## 2. Создаем структуру проекта 

<img width="440" height="181" alt="image" src="https://github.com/user-attachments/assets/40878667-ef80-4c36-9b02-48aba75e9b14" />

## 3. Заполняем файлы 

nginx/dockerfile

<img width="494" height="226" alt="image" src="https://github.com/user-attachments/assets/88f9f69b-2354-4703-9fbc-d8d24a1f8a39" />

---

nginx/index.html

<img width="499" height="254" alt="image" src="https://github.com/user-attachments/assets/c05226d7-078f-4113-aecd-4c4d03a49f7d" />

---

nginx/nginx-conf/nginx.conf

<img width="510" height="309" alt="image" src="https://github.com/user-attachments/assets/dd3d3496-e88f-4a60-8f2f-e29c9d76f3fa" />

## 4. Сборка и запуск 

Выполняем с помощью команды

```
sudo docker build -t nginx-server ./nginx

```
Проверяем 

<img width="992" height="252" alt="image" src="https://github.com/user-attachments/assets/fd72b0a4-7c3e-4472-bffc-7617f57e1d04" />

## 5. Создаем скрипт 

<img width="494" height="389" alt="image" src="https://github.com/user-attachments/assets/9f672b15-7319-4df4-90de-bec5c50cf77c" />

Делаем файл исполняемым и запускаем 

<img width="1492" height="722" alt="image" src="https://github.com/user-attachments/assets/69f962f6-40ba-422c-96a0-c009e20aacfe" />

<img width="1433" height="400" alt="image" src="https://github.com/user-attachments/assets/acdc61ae-6f41-4670-8e30-5344f944f961" />

