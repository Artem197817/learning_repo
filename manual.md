# Руководтво
## Настройка Git
+ git config --global user.name "Your Name" - запись имени пользователя
+ git config --global user.email "your_email@whatever.com" - запись электронной почты пользователя
### Команды настройки сокращенного вида частоиспользуемых команд
+ git config --global alias.co checkout
+ git config --global alias.ci commit
+ git config --global alias.st status
+ git config --global alias.br branch
+ git config --global alias.hist "log --pretty=format:'%h %ad | %s%d [%an]' --graph --date=short"
## Команды инициализации и записи изменений
+ git init - инициализация реппозитария
+ git add name file - добавить файл к коммиту
+ git add . - добавить к отслеживанию все файлы
+ git commit -m "comment" - записать изменения
## Дополнительные команды
+ git log - история коммитов
+ git help command - помощь 
+ git diff - просмотр вносимых изменений
## Работа с удаленным репозиторием
+ git remote - связь с удаленным репозиторием
+ git push - отправка в удаленный репозитарий
+ git clone - получение удаленного репозитория
+ git fetch - получение изменений из удаленного репозитария/home/artem/Документы/learning_repo/
+ git pull - получение изменений из удаленного репозитария со слиянием
## Работа с ветками
+ git checkout - перемещение между узлами репозитория
+ git branch - создание новой ветки
+ git merge - слияние веток
+ git gtaph - графическое представление структуры репозитария
+ git checout - b name branch - создание новой ветки с одновременным переключением на нее
+ git branch -d name branch - удаление слитой ветки
