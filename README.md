[Curso completo de Git de Bonieky Lacerda](https://www.youtube.com/watch?v=OuOb1_qADBQ)

tree /f -> lista todas as pastas e arquivos a partir da localização atual de forma recursiva

git config user.name -> mostra o nome do seu usuário

git config user.email -> mostra o email do usuário

git config --list -> lista todas as configurações do git

git init -> inicia um repositório do git

git add , -> adiciona todas as alterações

git commit -m "mensagem" -> faz commit de todas as alterações adicionadas e adiciona uma mensagem

git commit -am "mensagem" -> adiciona e faz commit de todas as alterações
git log -> mostra todos os commits

git reset --soft hash -> volta para o estado do hash passado, com as alterações adicionadas

git reset --mixed hash -> volta para o estado do hash passado, sem a adição das alterações

git reset --hard hash -> volta para o estado do hash passado, deleta completamente as alterações feitas após esse estado

git branch -> mostra todas as branchs, e indica com um asterísco a branch atual

git branch nova-branch --> cria uma nova branch chamada nova-branch

git checkout nova-branch --> sai da branch atual e vai para a nova-branch

git checkout HEAD -- nome-do-arquivo --> descarta as alterações do arquivo na branch atual

git diff --> mostra todos os arquivos modificados e suas respectivas modificações

git diff --name-only --> mostra apenas o nome dos arquivos modificados

git diff nome-do-arquivo --> mostra as modificações do arquivo

git remote add origin git@github.com:nome-do-usuario/nome-do-reposiorio.git --> vincula um repositório remoto ao repositório local, com o nome origin

git push -u origin nome-da-branch --> envia os commits da branch para o repositório vinculado ao projeto local. A opção -u faz com que não seja necessário especificar o nome do repositório remoto, nem a branch ao fazer um git push ou git pull. Pois os valores passados tornam-se o padrão