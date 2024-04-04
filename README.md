#### Git Fetch:

- загружает изменения из удалённого репозитория и сохраняет их в каталог локального репозитария refs/remotes/.  
- не сливает их с текущей версией.  
- не влияет на локальные ветки и текущие изменения.  
- позволяет просмотреть изменения перед их интеграцией.  
- требует написания вручную команды git merge для слияния всех полученных новых изменений с текущей веткой,<br>
в которой происходит работа.

![Git Fetch Schema](C:/Users/HP/Downloads/gitFetch.png)


#### Git Pull:

- это комбинация команд git fetch и git merge.
- выполняет git fetch автоматически и сразу же сливает изменения в текущую ветку.
- может привести к конфликтам, если вы не следите за изменениями в ветках.
- хорошо для применения, если есть ветка, настроенная на отслеживание удалённой ветки 

![Git Pull Schema](C:/Users/HP/Downloads/gitPull.png)

