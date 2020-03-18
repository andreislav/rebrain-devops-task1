## **Данный репозиторий содержит дефолтный файл конфигурации Nginx**

### *Установка Nginx (Centos7):*
```
# yum update
# yum install nginx
```

### *Путь к конфигурационному файлу **nginx.conf***: `/etc/nginx/nginx.conf;`

### *После внесения изменений в **nginx.conf** рекомендуется выполнить проверку конфигурации командой* `nginx -t;`

## **Начало работы с репозиторием:**

* #### *Склонировать этот репозиторий:*
```
# git clone git@gitlab.rebrainme.com:andreywolfert_at_gmail_com/rebrain-devops-task1.git
```

* #### *Добавить удаленный репозиторий:*
```
# git remote add <name> git@gitlab.rebrainme.com:andreywolfert_at_gmail_com/rebrain-devops-task1.git
# git remote -v
```

* #### *Внести изменения в репозиторий:*
```
# git push -u <name> master
```

#### [Историю изменений в проекте можно посмотреть здесь](https://gitlab.rebrainme.com/andreywolfert_at_gmail_com/rebrain-devops-task1/commits/master)

#### [Документация Nginx приведена здесь](https://nginx.org/ru/docs/)
