# CommandEx - Command Executor

## Установка и запуск

````
git clone https://github.com/romannep/commandex.git
cd commandex
npm install
npm start
````

## Описание

Web приложение для удаленного запуска команд: 
запускается на сервере и предоставляет web интерфейс для выполнения
заранее определенного списка команд.

Возможные команды задаются в файле`commandex-data.json`, без возможности
редактирования через web интерфейс. Таким образом приложение не может быть
использовано как удаленный shell для запуска произвольных команд. 

Приложение запускается на порту, указанному в файле `env.json` (2002 по умолчанию).

Приложение имеет встроенную систему авторизации. 
В нем определено две роли пользователей:
- `admin` - полный доступ в систему, включая создание новых пользователей 
- `user` - только просмотр и запуск команд

Для первоначального доступа используйте следующие учетные данные (логин\пароль)
- admin\admin
- user\user

 
