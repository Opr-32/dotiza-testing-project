**Окружение:** ОС Windows 11, Браузер: Google Chrome. Версия сайта: Release.

**Описание:** На странице создания нового пароля в тексте-подсказке над полем ввода отображается техническая инструкция для разработчика (development-логи). Это вводит обычного пользователя в заблуждение и раскрывает детали внутренней инфраструктуры проекта.

**Шаги к воспроизведению:**

1. Открыть сайт https://dotiza.ru/
2. Нажать кнопку "Войти" на главной странице
3. Нажать на ссылку "Восстановить пароль"
4. Ввести Эл.почту в поле ввода: testEML10@mail.ru; Нажать на кнопку "Создать ссылку сброса"
5. Перейти на Эл. почту: testEML10@mail.ru, открыть письмо с предложением сбросить пароль
6. В письме нажать на кнопку "Сбросить пароль"
7. После перенаправления на страницу сброса пароля обратить внимание на надпись "Введите токен из письма или development-логов и задайте новый пароль." над полем ввода токена сброса.

**Вложения:**
private-user-images.githubusercontent.com/297925481/702801876-f4a29398-571b-4724-bd0b-eb269083025d.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3OTQ0MzQ5OTYsIm5iZiI6MTc5NDQzNDY5NiwicGF0aCI6Ii8yOTc5MjU0ODEvNzAyODAxODc2LWY0YTI5Mzk4LTU3MWItNDcyNC1iZDBiLWViMjY5MDgzMDI1ZC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYxMTExJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MTExMVQyMjA0NTZaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT05MmM4NGJlYjFmOWM1NTJhMjgxNWE2YmEzMzA3YjEwMDg0MDIwOWI1ODFhZWI0NDgxMGE3NmM5NWI0YmZiZWExJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.adGeKxu7mNdEl9d4J3dqs8y3LZUlqS1GkVDjp1QG-XI


**Дополнительная информация:** Баг не мешает основному функционалу, (сброс пароля прошел исправно), но влияет на опыт пользователя (UX) и вводит его в замешательство
