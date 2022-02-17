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
    
    ```xml
    <?xml version="1.0" encoding="UTF-8"?>
    <NEW>
        <NAME>Natalia Petyaeva</NAME>
        <AGE>43</AGE>
        <PETS>3</PETS>,
        <SALARY>1000</SALARY>
    </NEW>
    ```
28. Отправить изменения на внешний репозиторий. Использую команду `commit` с двумя параметрами: `-а` - проиндексирует отслеживаемые файлы (замена `git add`) и `-m` - написание комментария через командную строку:

       `git commit -am "Modified new.xml"`
       
       `git push`
29. Создать файл preferences.xml

    `touch preferences.xml`
    
    `git add preferences.xml`
30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
   
       ```xml
        <?xml version="1.0" encoding="UTF-8"?>
        <PREFERENCES>
            <FAVORITE_MOVIE>Flashbacks of a Fool</FAVORITE_MOVIE>
            <FAVORITE_SERIES>Любимый сериал</FAVORITE_SERIES>
            <FAVORITE_FOOD>Steak</FAVORITE_SERIES>
            <FAVORITE_SEASON>Autumn</FAVORITE_SEASON>
            <COUNTRY>Japan</COUNTRY>
        </PREFERENCES>
       ```
31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML

    `touch sklls.xml`
    
    `git add skills.xml`  
    
    `vim sklls.xml`
    
    ```xml
    <?xml version="1.0" encoding="UTF-8"?>
    <SKILLS>
        <SIX>What is JSON, XML. Their structure.</SIX>
        <SEVEN>API testing.</SEVEN>
        <EIGHT>How to view read logs.</EIGHT>
        <NINE>Postman, Fidler.</NINE>
        <ELEVEN>"Dev Tools of web browsers (Google Chrome, FireFox).</ELEVEN>
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
    
    ```xml
    <?xml version="1.0" encoding="UTF-8"?>
    <BUG_REPORT>
    <ID>0001</ID>
      <SUMMARY>Missing product images on the Product page</SUMMARY>
      <PRIORITY>High</PRIORITY>
      <SEVERITY>Major</SEVERITY>  
      <EXPECTED>Product images are displayed on the Product page</EXPECTED>  
      <ACTUAL>All product images are missing</ACTUAL>
      <STEPS>
        <STEP1>Open <a href="www.storeName.com">www.storeName.com</a></STEP1>
        <STEP2>Find and select a product on the Main page and make sure that the Product page has loaded</STEP2>
      </STEPS>
      <ENVIROMENT>
        <OS>Windows 10</OS>
        <BROWSER>Google Chrome 98.0.4758.102, (x86_64)</BROWSER>
      </ENVIROMENT>
      <ATTACHMENTS>
        <LINK1><a href="https://...">https://...</a></LINK1>
        <LINK2><a href="https://...">https://...</a></LINK2>
      </ATTACHMENTS>
    </BUG_REPORT>
    ```
36. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
37. Синхронизировать внешний и локальный репозиторий XML

    `git pull`
