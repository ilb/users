#### 1. Проверка прав внутреннего пользователя ldap, с помощью posix групп
Реализовать класс LdapUser, который будет проверять доступ пользователя к конкретной группе posix

#### 2. Проверка прав внешнего пользователя
- Реализовать класс User. У пользователя имеется remoteUser:string (идентификатор учетной записи) и securityLevel:integer (уровень доступа).
- Создать метод в классе, который будет проверять, чтобы securityLevel пользователя был не ниже указанного.
- Реализовать метод, который который выдаст Exeption.
- Реализовать метод который в случае, если securityLevel < 40, отправит нас на авторизацию (/auth.php)
