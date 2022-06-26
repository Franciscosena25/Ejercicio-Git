# Practica Git. 

## ¿Qué comando utilizaste en el paso 11? ¿Por qué?
*git reset --hard HEAD~1* para modificar el working copy y vaciar el staging area.

## ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
 *git reflog* para listar todas las acciones realizadas y a continuación se realizara un *git reset --hard* con el identificador del ultimo commit antes del reset.

## El merge del paso 13, ¿Causó algún conﬂicto? ¿Por qué?
No, ya que según el merge la rama style ya esta actualizada.

## El merge del paso 19, ¿Causó algún conﬂicto? ¿Por qué?
 
Si, ya que cada rama tenia el mismo archivo con diferentes contenido.
## El merge del paso 21, ¿Causó algún conﬂicto? ¿Por qué?
No, ya que se hizo un Fast-forward.

## ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph --decorate --pretty=oneline

## El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Si, ya que solamente avanzaríamos el puntero.

## ¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1

## ¿Qué comando o comandos utilizaste en el paso 28?
git checkout -- git-nuestro.md

## ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title

## ¿Qué comando o comandos utilizaste en el paso 30?
git reflog 
git checkout 
git branch title 
git checkout title

## ¿Qué comando o comandos usaste en el paso 32?
git reflog 
git checkout 

## ¿Qué comando o comandos usaste en el punto 33?
git reflog
git checkout
