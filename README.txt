// txt
//  1. Создать внешний репозиторий c названием txt.
            // Repositories - New - txt - Create repository
//  2. Клонировать репозиторий txt на локальный компьютер.
            // Code - HTTPS - Copy link
            git clone (ctrl + V)
//  3. Внутри локального txt создать файл “new.txt”.
            cd txt/
            touch new.txt
//  4. Добавить файл под гит.
            git add new.txt 
//  5. Закоммитить файл.
            git commit -m "add new file"
//  6. Отправить файл на внешний GitHub репозиторий.
            git push
//  7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате txt.
        vim new.txt

            Name - John
            Age - 33
            Animals - 1
            Salary - 1$

//  8. Отправить изменения на внешний репозиторий.
        git add new.txt
        git commit -m "add text"
        git push
//  9. Создать файл preferences.txt
        touch preferences.txt
//  10. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате txt.
        vim preferences.txt
        
            Movie - Matrix
            Series - Simpsons
            Food - Ice-cream
            Season - Summer
            Country - Italy
        
//  11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате txt
        touch skills.txt       
        vim skills.txt
        
            skill1 - 1
            skill2 - 2
            skill3 - 3
            skill4 - 4

//  12. Сделать коммит в одну строку.
        git add preferences.txt skills.txt && git commit -m "add 2 new files"
//  13. Отправить сразу 2 файла на внешний репозиторий.
        git push
//  14. На веб интерфейсе создать файл bug_report.txt.
        // Add file - Create new file - bug_report.txt
//  15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
        // Commit new file
//  16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате txt.
        // Edit file - modify bug_report.txt
//  17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
        // Commit changes
//  18. Синхронизировать внешний и локальный репозиторий txt
        git pull
