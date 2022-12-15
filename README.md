# GIT Commands on CMD

command: git status

command: git add [nome_arquivo]
exemplo: git add index.html

command: git add [nome_arquivo] [nome_arquivo]
exemplo: git add css/style.css javascript/script.js

command: git reset [nome_arquivo]
exemplo: git reset index.html

command: git add *  (todos os arquivos da pasta atual)
command: git add .  (todos os arquivos novos e modificados, não adiciona arquivos deletados)
command: git add -A (todos os arquivos modificados em qualquer pasta do prjeto)
command: git reset  (git reset sem o nome do arquivo retira todos os arquivos da stage area)

command: git commit -m "[mensagem]"
exemplo: git commit -m ":tada: Commit Inicial"

command: git log           (Exibe historico de commits efetuados no repositorio)
command: git log --oneline (Exibe historico de commits efetuados no repositorio de forma reduzida)

