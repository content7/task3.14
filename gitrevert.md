[< К содержанию](./readme.md)
___
## Исправление коммита. Команда "git revert".
___
Команда ***"git revert"*** используется для отката изменений в истории коммитов репозитория. В отличие от других команд отмены она не перемещает указатель.

При использовании команды ***"git revert"*** совершается переход к указанному коммиту, обращаются его изменения и создаётся новый коммит.

Для того, чтобы изменить последний коммит, нужно использовать команду:
```
git revert HEAD
```
В данном случае в качестве ссылки на изменяемый коммит использована ссылка **"HEAD"**, что позволяет обратить изменения последнего коммита.
<br><br>

___
