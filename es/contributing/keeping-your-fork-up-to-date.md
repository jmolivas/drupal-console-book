# Mantener su fork actualizado

Con el paso del tiempo su repositorio forkeado y el original (llamado upstream) se desincronizarán y usted se quedará con una versión del código antigua y no soportada.

Para sincronizar los cambios que haya hecho en un fork local con el repositorio original, usted debería:

## Configurar un fork remoto:
Especifique y configure un nuevo repositorio remoto upstream que apunte al repositorio upstream en Git.
```
git remote add upstream https://github.com/hechoendrupal/DrupalConsole.git
```
Para mayor y más detallada información, por favor visite la guía de Github
[Configurar un fork remoto](https://help.github.com/articles/configuring-a-remote-for-a-fork/)  

## Sincronizando su fork
Sincronize su fork para mantenerse actualizado con el repositorio upstream.
```
git fetch upstream
git merge upstream/master
```
Para más y mayor información, por favor visite la guía de Github
[Sincronizando un fork](https://help.github.com/articles/syncing-a-fork/)
