
## DOCUMENTACIÓN GENERAL:

- platformio-ide-terminal

## CONFLICTOS GIT:

- problema:
* branch            master     -> FETCH_HEAD
fatal: refusing to merge unrelated histories

..* Solución al problema GIT:

... COMANDOS:

git checkout master
git merge origin/master --allow-unrelated-histories
Resolve conflict, then

git add -A .
git commit -m "Upload"
git push
