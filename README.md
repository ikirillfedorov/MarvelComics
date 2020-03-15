# MarvelComics
Проект для работы с Marvel API - https://developer.marvel.com/

____

 * Стартовый экран UITabBarController, c 3 вкладками. 
 * При загрузку проекта отправляется GET запрос к Marvel API полученные данные декодируются в структурру данных и выводятся в UITableView где в каждой ячейке заполняется: 
 * Имя персонажа
 * Описание персонажа
 * Так же в структуре данных опционально приходит ссылка на фото персонажа, если фото есть фото заполняется в ячейку, если нет остается "заглушка" на фото. 
 * Во время загрузки данных, пользователю показывается Activity indicator
 * При клике на ячейку отправляется GET запрос с конкретным ID персонажа и полученные данные выводятся на экран деталей персонажа (имя, описание, комиксы где упоминается персонаж). К комиксам, где упоминается персонаж так же запрашиваются картинки и название, которые в свою очередь выводятся в tableView в нижней части экрана. 
 * Верхняя часть экрана деталей сделана градиентом, что бы визуально сделать красивый переход. 
 * При переключении на экраны комиксов и авторов происходят аналогичные запросы к Marvel API и отображение информации на экранах, ячейки так же кликабильны. 
 * На каждой вкладке реализован поиск по части названия персонажа/комикса/автора. 
 * Для активации поиска нужно нажать return/enter
 * При очистке строки поиска, отправляется дефолтный запрос. 
 * При не корректном вводе поиска, на экран показывается "заглушка" с текстом поиска и сообщением на UILabel для пользователя, что запрос не корректный. 

![Alt-текст](https://github.com/ikirillfedorov/MarvelComics/blob/master/MarvelHeroes/ScreenShots/Screenshot%202020-03-15%20at%2020.57.15.png)
![Alt-текст](https://github.com/ikirillfedorov/MarvelComics/blob/master/MarvelHeroes/ScreenShots/Screenshot%202020-03-15%20at%2020.54.23.png)
![Alt-текст](https://github.com/ikirillfedorov/MarvelComics/blob/master/MarvelHeroes/ScreenShots/Screenshot%202020-03-15%20at%2020.54.37.png)
![Alt-текст](https://github.com/ikirillfedorov/MarvelComics/blob/master/MarvelHeroes/ScreenShots/Screenshot%202020-03-15%20at%2020.55.27.png)
![Alt-текст](https://github.com/ikirillfedorov/MarvelComics/blob/master/MarvelHeroes/ScreenShots/Screenshot%202020-03-15%20at%2020.55.01.png)
![Alt-текст](https://github.com/ikirillfedorov/MarvelComics/blob/master/MarvelHeroes/ScreenShots/Screenshot%202020-03-15%20at%2020.55.38.png)
![Alt-текст](https://github.com/ikirillfedorov/MarvelComics/blob/master/MarvelHeroes/ScreenShots/Screenshot%202020-03-15%20at%2020.56.29.png)

