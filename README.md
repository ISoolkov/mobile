# mobile
[Документация](https://test-bc740.web.app/ )
## Развёртывание окружения
1. Клонировать репозиторий https://github.com/ISoolkov/mobile.git
2. Запустить код
```
npm install
ionic serve
если не открыл сайт, то ctrl+c и заново ionic serve
```
##  Двустороннее связывание 
```
Открываем tabs.page.html, в файле 12 строка (ngModel), и связываем с переменной, которая записана в tabs.page.ts (пример переменной с 8 по 13 строку)

<ion-input label="Ввод данных"  [(ngModel)]="Name"></ion-input>
 ```
       
##  Редактирование синей кнопки на главном экране            
```
 Заходим в tabs.page.html (13 строка)
</ion-item>
    <ion-button (click) = "changeBUTTON()">Добавить суффикс</ion-button>
</ion-item>
```
