Создать внешний репозиторий c названием JSON.
Клонировать репозиторий JSON на локальный компьютер. https://github.com/a-radonskaya/JSON.git 
Внутри локального JSON создать файл “new.json”. touch > new.json
Добавить файл под гит.  git add . ->  git status 
Закоммитить файл. git commit -m "new"
Отправить файл на внешний GitHub репозиторий. git push
Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.  cat > new.json 
Отправить изменения на внешний репозиторий. git add .   -> git commit -m "new" -> git push
Создать файл preferences.json   touch > prefences.json
В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, люби4)мое время года, сторона которую хотели бы посетить) в формате JSON.  cat > prefences.json
Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON  cat > skills.json
Отправить сразу 2 файла на внешний репозиторий.  git add . -> git status -> git commit -m "prefences,skills" -> git push
На веб интерфейсе создать файл bug_report.json.  1. Add file 2. bug_report.json. 3. commit new file 
Сделать Commit changes (сохранить) изменения на веб интерфейсе. 
На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON. 1. bug_report.json. 2. edit this file 
Сделать Commit changes (сохранить) изменения на веб интерфейсе. commit changes 
Синхронизировать внешний и локальный репозиторий JSON  git status -> git pull
