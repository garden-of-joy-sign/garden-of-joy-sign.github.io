## Программа специального назначения для специального клиента

GitHub - клиентская часть (броузер клиент), для использования GitHub Page

## В случае возникновения ошибки невозможности конвертирования image

1. Скопировать таблицу с другим именем (например, **SignOld_yyyymmdd**) 
2. Выполнить меню: File/Make a Copy - и сохранить с именем **Sign**
3. Меню: Extetnsion/App Script
4. Открыть файл "Code.js"
5. Запустить (Run) функцию "**initialSetup**"


|![Initial Setup](DocImage/InitialSetup.png)|
|-|

6. Сделать DoPostTrigger
- function - **doPost**
- eventType - **On form submit**
![DoPost Trigger](DocImage/DoPostTrigger.png)

7. Сделать Deploy Script

|![Deploy1](DocImage/Deploy1.png)|
|-|


|![Deploy2](DocImage/Deploy2.png)|
|-|

Скопировать DeployId и использовать ее как параметр

|![Deploy3](DocImage/Deploy3.png)|
|-|


    
 