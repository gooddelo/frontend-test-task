# Тестовое задание на позицию Frontend

![Normal](https://github.com/gooddelo/frontend-test-task/assets/39239196/0d862657-a5f4-4b7a-8a9d-38389f9f056a)

У нас есть устройство, которое замеряет значения CO2 и температуры в офисе, мы ласково зовём его Душнила.

У Душнилы можно спрашивать текущие значения через API по адресу http://dushnila.gooddelo.com/data
> Если вы хотите захостить сайта на Github Pages нужно проксировать адрес: https://api.allorigins.win/get?url=http://dushnila.gooddelo.com/data

Ваши задачи:
- Сверстать сайт по [**макету из Figma**](https://www.figma.com/file/2ZN3BIJGaLjKomcIRIlIy0/Dushnila?type=design&node-id=0%3A1&mode=design&t=Vfeu9ZcWw2n1bnb1-1 "макету из Figma") на **React по компонентам**
- Получать и выводить значения Душнилы **каждую минуту**
- Если **CO2 больше 800** или **температура больше 27** изменять **статус в Redux** с нормального на превышение, от статуса зависит цвет заднего фона и текст как на макете.

### Задание не будет оценено, если проект не запустится с
`npm install`
`npm run start`
