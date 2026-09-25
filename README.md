# Terminal 24 sep

nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git --version
git version 2.43.0
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ ls
index.html
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ ls -la
total 12
drwxrwxr-x  2 nitro nitro 4096 sep 24 20:42 .
drwxrwxr-x 19 nitro nitro 4096 sep 24 20:41 ..
-rw-rw-r--  1 nitro nitro  241 sep 24 20:43 index.html
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git init
ayuda: Usando 'master' como el nombre de la rama inicial. Estenombre de rama predeterminado
ayuda: está sujeto a cambios. Para configurar el nombre de la rama inicial para usar en todos
ayuda: de sus nuevos repositorios, reprimiendo esta advertencia, llama a:
ayuda: 
ayuda:  git config --global init.defaultBranch <nombre>
ayuda: 
ayuda: Los nombres comúnmente elegidos en lugar de 'master' son 'main', 'trunk' y
ayuda: 'development'. Se puede cambiar el nombre de la rama recién creada mediante este comando:
ayuda: 
ayuda:  git branch -m <nombre>
Inicializado repositorio Git vacío en /home/nitro/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep/.git/
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git status
En la rama master

No hay commits todavía

Archivos sin seguimiento:
  (usa "git add <archivo>..." para incluirlo a lo que será confirmado)
        index.html
        script.js

no hay nada agregado al commit pero hay archivos sin seguimiento presentes (usa "git add" para hacerles seguimiento)
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git add index.html
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git status
En la rama master

No hay commits todavía

Cambios a ser confirmados:
  (usa "git rm --cached <archivo>..." para sacar del área de stage)
        nuevos archivos: index.html

Archivos sin seguimiento:
  (usa "git add <archivo>..." para incluirlo a lo que será confirmado)
        script.js

nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git rm --cached index.html
rm 'index.html'
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git status
En la rama master

No hay commits todavía

Archivos sin seguimiento:
  (usa "git add <archivo>..." para incluirlo a lo que será confirmado)
        index.html
        script.js

no hay nada agregado al commit pero hay archivos sin seguimiento presentes (usa "git add" para hacerles seguimiento)
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git add .
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git status
En la rama master

No hay commits todavía

Cambios a ser confirmados:
  (usa "git rm --cached <archivo>..." para sacar del área de stage)
        nuevos archivos: index.html
        nuevos archivos: script.js

nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git commit -m 'primer commit'
[master (commit-raíz) d7adb2a] primer commit
 2 files changed, 14 insertions(+)
 create mode 100644 index.html
 create mode 100644 script.js
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git remote add origin https://github.com/pamonge/repoTAE2026.git
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git push origin master
Enumerando objetos: 4, listo.
Contando objetos: 100% (4/4), listo.
Compresión delta usando hasta 16 hilos
Comprimiendo objetos: 100% (3/3), listo.
Escribiendo objetos: 100% (4/4), 447 bytes | 447.00 KiB/s, listo.
Total 4 (delta 0), reusados 0 (delta 0), pack-reusados 0
To https://github.com/pamonge/repoTAE2026.git
 * [new branch]      master -> master
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git pull origin master
Desde https://github.com/pamonge/repoTAE2026
 * branch            master     -> FETCH_HEAD
Ya está actualizado.
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git status
En la rama master
Cambios no rastreados para el commit:
  (usa "git add <archivo>..." para actualizar lo que será confirmado)
  (usa "git restore <archivo>..." para descartar los cambios en el directorio de trabajo)
        modificados:     index.html

sin cambios agregados al commit (usa "git add" y/o "git commit-a")
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git add .
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git status
En la rama master
Cambios a ser confirmados:
  (usa "git restore --staged <archivo>..." para sacar del áreade stage)
        modificados:     index.html

nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git commit -m 'refactor: index.html'
[master b958dc0] refactor: index.html
 1 file changed, 3 insertions(+)
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git pull origin master
Desde https://github.com/pamonge/repoTAE2026
 * branch            master     -> FETCH_HEAD
Ya está actualizado.
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git push origin master
Enumerando objetos: 5, listo.
Contando objetos: 100% (5/5), listo.
Compresión delta usando hasta 16 hilos
Comprimiendo objetos: 100% (3/3), listo.
Escribiendo objetos: 100% (3/3), 383 bytes | 383.00 KiB/s, listo.
Total 3 (delta 1), reusados 0 (delta 0), pack-reusados 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/pamonge/repoTAE2026.git
   d7adb2a..b958dc0  master -> master
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git log
commit b958dc0ff738307ec9d5f6bee244e6ce757dbaa7 (HEAD -> master, origin/master)
Author: Pablo Monge <pablomonge55@gmail.com>
Date:   Thu Sep 24 21:13:05 2026 -0300

    refactor: index.html

commit d7adb2a73bc03aa51f9a70382cedb8cd75fcee80
Author: Pablo Monge <pablomonge55@gmail.com>
Date:   Thu Sep 24 20:55:10 2026 -0300

    primer commit
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ ls -la
total 28
drwxrwxr-x  4 nitro nitro 4096 sep 24 21:24 .
drwxrwxr-x 19 nitro nitro 4096 sep 24 20:41 ..
drwxrwxr-x  2 nitro nitro 4096 sep 24 21:24 data
-rw-rw-r--  1 nitro nitro    0 sep 24 21:22 .env
-rw-rw-r--  1 nitro nitro    0 sep 24 21:23 .env.example
drwxrwxr-x  8 nitro nitro 4096 sep 24 21:13 .git
-rw-rw-r--  1 nitro nitro   11 sep 24 21:24 .gitignore
-rw-rw-r--  1 nitro nitro  306 sep 24 21:10 index.html
-rw-rw-r--  1 nitro nitro    0 sep 24 21:23 README.md
-rw-rw-r--  1 nitro nitro   18 sep 24 20:44 script.js
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git status
En la rama master
Archivos sin seguimiento:
  (usa "git add <archivo>..." para incluirlo a lo que será confirmado)
        .env.example
        .gitignore
        README.md

no hay nada agregado al commit pero hay archivos sin seguimiento presentes (usa "git add" para hacerles seguimiento)
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git add .
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git status
En la rama master
Cambios a ser confirmados:
  (usa "git restore --staged <archivo>..." para sacar del áreade stage)
        nuevos archivos: .env.example
        nuevos archivos: .gitignore
        nuevos archivos: README.md

nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git commit -m 'add: env, ignore, readme'
[master d78a7d0] add: env, ignore, readme
 3 files changed, 2 insertions(+)
 create mode 100644 .env.example
 create mode 100644 .gitignore
 create mode 100644 README.md
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git push origin master
Enumerando objetos: 5, listo.
Contando objetos: 100% (5/5), listo.
Compresión delta usando hasta 16 hilos
Comprimiendo objetos: 100% (2/2), listo.
Escribiendo objetos: 100% (4/4), 391 bytes | 391.00 KiB/s, listo.
Total 4 (delta 0), reusados 0 (delta 0), pack-reusados 0
To https://github.com/pamonge/repoTAE2026.git
   b958dc0..d78a7d0  master -> master
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git push origin master
Everything up-to-date
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git push origin master
Everything up-to-date
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ git push origin master
Everything up-to-date
nitro@Nitro:~/Documentos/Terciario TAE/2026/Programacion/Tec Sup CD/clasegit_24sep$ 