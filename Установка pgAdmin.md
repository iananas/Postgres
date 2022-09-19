# Установка pgAdmin
>Перед установкой gAdmin4 на Ubuntu 16.04 нужно убедиться, что сервер PostgreSQL работает. Версия PostgreSQL должна быть выше, чем 9.6. Для того чтобы проверить состояние службы Postgresql выполним такую команду:
>
![avatar](https://sun9-32.userapi.com/impg/lDHBMAYll8557-CxwGdCDFoCia3wkvBkQOueVg/RRTzGDsy7OU.jpg?size=580x389&quality=96&sign=8605bbb6d46be4ac444913b57863ed08&type=album)
>В поле status должно быть слово ative, выделенное зеленым цветом. 
>
>Первый этап установки pgAdmin — добавление репозитория разработчиков программы в систему. Для того чтобы сделать это, сначала установим публичный ключ при помощи команды: 
sudo wget https://www.pgadmin.org/static/packages_pgadmin_org.pub | sudo apt-key add packages_pgadmin_org.pub
>
![avatar](https://sun9-81.userapi.com/impg/xHd1OUlE-26uHCDUaLbsz8PDoTN7XVuQY0lMjg/OAlbpgoexe8.jpg?size=517x378&quality=96&sign=5f31e6c42233b8b417bf70ec33d230d7&type=album)
>После этого добавим запись о репозотории pgAdmin в файл /etc/apt/sources.list.d/pgadmin4.list
И обновим список пакетов
>
>Теперь приступаем к установке
>
  ![avatar](https://sun9-10.userapi.com/impg/wplYaZ761eKV265wyv114dHRTuqFc9_SG5XW7Q/ry-NKmj5OeI.jpg?size=559x367&quality=96&sign=401bdc2f7a6b61baf19497559ca28684&type=album)
>После установки программа pgAdmin4 появится в главном меню операционной системы Ubuntu.Запускаем его.При первой загрузке программа просит установить мастер-пароль для pgAdmin, придумаем секретное слово и нажимаем кнопку Ок.
>
 ![avatar](https://sun9-29.userapi.com/impg/HJld7_GFIi-dwOeaF1o_OGQp54BUjvCTugFjwg/loojH32Koas.jpg?size=831x691&quality=96&sign=a5e508788912bf3771d9f957f605f973&type=album)
 >Готово
 >
  ![avatar](https://sun9-77.userapi.com/impg/karJRN85oFTo5WCwgQAN0HgN5dJN9ggqRCgJmA/QS2KYR3NDjI.jpg?size=731x547&quality=96&sign=b03b97b08b102eeacd8486b87c387309&type=album)




