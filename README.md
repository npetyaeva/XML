# XML

21. Создать внешний репозиторий c названием XML.

    `https://github.com/npetyaeva/XML.git`
22. Клонировать репозиторий XML на локальный компьютер.

    `git clone https://github.com/npetyaeva/XML.git`
    
    `cd XML`
23. Внутри локального XML создать файл “new.xml”.

    `touch new.xml`
24. Добавить файл под гит.

    `git add new.xml`
25. Закоммитить файл.

    `git commit -m "Added new.xml"`
26. Отправить файл на внешний GitHub репозиторий.

    `git push`
27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
    ```
    <?xml version="1.0" encoding="UTF-8"?>
    <NEW>
        <NAME>Петяева Наталья</NAME>
        <AGE>43</AGE>
        <PETS>3</PETS>,
        <SALARY>1000</SALARY>
    </NEW>
    ```
28. Отправить изменения на внешний репозиторий.

       `git commit -am "Modified new.xml"`
       
       `git push`
29. Создать файл preferences.xml

    `touch preferences.xml`
    
    `git add preferences.xml`
30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
    ```
    <?xml version="1.0" encoding="UTF-8"?>
    <PREFERENCES>
        <FAVORITE_MOVIE>Flashbacks of a Fool</FAVORITE_MOVIE>
        <FAVORITE_SERIES>Любимый сериал</FAVORITE_SERIES>
        <FAVORITE_FOOD>Стейк</FAVORITE_SERIES>
        <FAVORITE_SEASON>Oень</FAVORITE_SEASON>
        <COUNTRY>Япония</COUNTRY>
    </PREFERENCES>
    ```
31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML

    `touch sklls.xml`
    
    `git add skills.xml`  
    
    `vim sklls.xml`
    ```
    <?xml version="1.0" encoding="UTF-8"?>
    <SKILLS>
        <SIX>Что такое JSON, XML. Их структура.</SIX>
        <SEVEN>Тестирование API.</SEVEN>
        <EIGHT>Снятие и чтение логов.</EIGHT>
        <NINE>Postman, Fidler.</NINE>
        <ELEVEN>"Dev Tools веб браузеров (Google Chrome, FireFox).</ELEVEN>
    </SKILLS>
    ```

32. Сделать коммит в одну строку.

       `git commit -am "Added preferences.xml & sklls.xml"`

33. Отправить сразу 2 файла на внешний репозиторий.

    `git push`
34. На веб интерфейсе создать файл bug_report.xml.
35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

       `https://github.com/npetyaeva/XML/blob/main/bug_report.xml`
35. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
    ```
    <?xml version="1.0" encoding="UTF-8"?>
    <BUG_REPORT>
    <ID>BR000</ID>
      <SUMMARY>Заголовок</SUMMARY>
      <DESCRIPTION>
        <STEP>1. ...</STEP>
        <STEP>2. ...</STEP>
      </DESCRIPTION>
      <ACTUAL>Фактический результат</ACTUAL>
      <EXPECTED>Ожидаемый результат</EXPECTED>
      <ENVIROMENT>
        <VALUE>ОС</VALUE>
        <VALUE>Браузер</VALUE>
      </ENVIROMENT>
      <SEVERITY>Серьезность</SEVERITY>
      <PRIORITY>Приоритет</PRIORITY>
      <AUTHOR>Автор</AUTHOR>
      <ASSIGN>Назначено на</ASSIGN>
      <ATTACHMENTS>Вложения</ATTACHMENTS>
    </BUG_REPORT>
    ```
36. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
37. Синхронизировать внешний и локальный репозиторий XML

    `git pull`
