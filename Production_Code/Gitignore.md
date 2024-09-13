# Git игнорирование файлов

Git игнорирование файлов - удобная вещь, если вы не хотите отправлять какие то фалы на GitHub. Вы конечно можете вручную при каждом коммите выбирать файлы, которые не хотите добавлять в коммит, но неудобно. Особенно, если их много

Все очень просто: 
- Создаете в корне проекта файл с названием `.gitignore`
- Записываете в нем пути к файлам, которые не хотите отправлять на GitHub
- Если хотите игнорировать все файлы какого то расширения, то пишите `*.txt`, например

Пример файла `.gitignore`:
```
.env
.pycache
.DS_store
*.tmp
```