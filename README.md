# PracticaGit-Web
practica de git Bootcamp desarrollo web

- Respuestas:
1- ¿Qué comando o comandos utilizaste en el paso 11? ¿Por qué?
  git reset --hard HEAD~1. Asi elimino el paso anterior y volvemos a trabajar desde 0
2- ¿Que comando o comandos utilizaste en el paso 12 y por que?
  git restore <nombre> en este caso git restore git-nuestro.md. Volvemos al estadio inicial así.
3 El merge del paso 13 ¿creó algún conflicto? ¿Por qué?
  No se crearon conflicto pues el contenido de los archivos eran identicos.
4 El merge del paso 19 ¿creó algún conflicto? ¿Por qué?
  Debido a la diferencia entre el contenido del archivo en distintas ramas se creó un conflicto.
5 El merge del paso 21 ¿creó algún conflicto? ¿Por qué?
  No se crearon conflicto pues el contenido de los archivos eran identicos. Se "normalizaron" en los merges anteriores.
6 ¿Qúe comando o comandos utilizaste en el paso 25?
  git log --graph
7 El merge del paso 26 ¿Podría ser Fast Forward? ¿Por qué?
  No puesto que el resto de ramas no tendría acceso a ese commit.
8 ¿Qúe comando o comandos utilizaste en el paso 27?
  git reset --hard ~HEAD1
9 ¿Qúe comando o comandos utilizaste en el paso 28?
  git restore
10 ¿Qúe comando o comandos utilizaste en el paso 29?
  git branch -d title
11 ¿Qúe comando o comandos utilizaste en el paso 30?
  git reset --hard
12 ¿Qúe comando o comandos utilizaste en el paso 32?
  git reset --hard HEAD
13 ¿Qúe comando o comandos utilizaste en el paso 33?
  git reflog
  git checkout -d title <id del commit>
