# gulp
Моя сборка для gulp

## Команды

```
gulp build 
gulp build:watch
gulp build:bitrix
gulp build:bitrix:watch
gulp server - запускает build + локально разварчивает сервер с livereload
```
## Перенос проекта на bitrix

- В папке local создать папку gulp и скопировать туда весь каталог с проектом
- Поменять переменную buildpath на путь к шаблону, например `../templates/templatename`
- После этого запустить одну из команд `build:bitrix` или `build:bitrix:watch`