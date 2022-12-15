# GIT Commands on CMD

command: git status

command: git add [nome_arquivo]<br>
exemplo: git add index.html

command: git add [nome_arquivo] [nome_arquivo]<br>
exemplo: git add css/style.css javascript/script.js

command: git add *  (Adiciona todos os arquivos da pasta atual)<br>
command: git add .  (Adiciona todos os arquivos novos e modificados, não adiciona arquivos deletados)<br>
command: git add -A (Adiciona todos os arquivos modificados em qualquer pasta do prjeto)

command: git reset [nome_arquivo]<br>
exemplo: git reset index.html

command: git reset  (Retira todos os arquivos da stage area)<br>
command: git reset [hash_commit] (Retrocede a branch para o commit referenciado)<br>
command: git reset HEAD~[quantidade_de_commits_a_retroceder] (Retrocede a branch em uma quantidade especifica de commits)

command: git commit -m "[mensagem]"<br>
exemplo: git commit -m ":tada: Commit Inicial"

command: git commit --amend -m "[mensagem]" (Efetua alteração da mensagem do commit)<br>
command: git commit --amend --no-edit (Adiciona novos arquivos na stage área ao commit anterior sem precisar modificar a mensagem)

command: git log           (Exibe historico de commits efetuados no repositorio)<br>
command: git log --oneline (Exibe historico de commits efetuados no repositorio de forma reduzida)

