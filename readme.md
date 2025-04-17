# Инструкция по установке, запуску и работе с приложением аутентификации

## Установка и запуск

### 1. Клонирование репозитория
```bash
git clone https://github.com/Santatann/FrontBack6.git
cd <папка-проекта>
```
### 2. Установка зависимостей
```bash
npm init -y
npm install express express-session bcrypt cookie-parser
```
### 3. Запуск приложения
```bash
cd <папка-проекта>
node server.js
```
### 4. Сервер будет доступен по адресу: http://localhost:3000
## Использование
### Доступные страницы:
- Главная: http://localhost:3000
- Профиль: http://localhost:3000/profile.html
### Основные функции
#### 1. Регистрация
- Перейдите на главную страницу
- Нажмите "Зарегистрироваться"
- Введите логин и пароль
- После успешной регистрации вы автоматически войдёте в систему
#### 2. Вход
- На главной странице введите свои учётные данные
- Нажмите "Войти"
#### 3. Личный кабинет
- После входа вы будете перенаправлены в личный кабинет
##### Здесь можно
- Просматривать свои данные
- Обновлять кэшированные данные (кнопка "Обновить данные")
- Выйти из системы
#### 4. Смена темы
- На главной странице или в личном кабинете
- Нажмите кнопку "Переключить тему"
- Тема сохранится автоматически