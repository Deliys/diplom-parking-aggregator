# diplom-parking-aggregator

В рамках проекта будет создано 5 отдельных модулей(частей сервиса). 

временно использую sqlite3 , потом заменю на postgres

# TODO
- [ ] Отслеживание свободных парковочных мест средствами компьютерного зрения
- [ ] android приложение
- [ ] web приложение
- [ ] api (папка api)
  * Взаимодействие с базой будет реализовано средствами api
- [ ] Агрегация данных со сторонних сервисов.(папка parser)
    * Это отдельный модуль ,который будет брать данные уже созданых "умных парковок".Реальзация средствами парсера для сайтов
      - [ ] https://krasparking.admkrsk.ru/#map (платная)
      - [ ] https://krasnoyarsk.spravker.ru/besplatnye-parkovki/raion-tsentralnyij/?page=3 (просто адреса)