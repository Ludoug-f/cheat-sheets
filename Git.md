## Comandos Gerais

| COMANDO                               | DESCRIÇÃO                                                     |
|--------------------------------------|---------------------------------------------------------------|
| `git init`                            | Transforma uma pasta em um repositório Git.                   |
| `git add nome-do-arquivo`             | Adiciona o arquivo especificado em staging (espaço temporário antes do commit). |
| `git add .`                           | Adiciona todos os arquivos modificados em staging (espaço temporário antes do commit). |
| `git status`                          | Verifica o status dos arquivos do projeto.                   |
| `git commit -m "Mensagem"`            | Cria um ponto de acesso para a alteração e inclui uma mensagem descrevendo as alterações feitas. |
| `git branch`                          | Verifica as branches existentes e mostra a branch atual.      |
| `git checkout -b nome-da-branch`      | Cria uma nova branch (a partir da atual) e muda automaticamente para ela. |
| `git checkout nome-da-branch`         | Muda para a branch especificada.                               |
| `git log`                             | Mostra os registros dos commits (alterações realizadas).       |
| `git merge nome-da-branch`            | Realiza a mesclagem das alterações da branch especificada.     |
| `git clone URL`                       | Clona um repositório Git existente para o seu ambiente local. |
| `git pull`                            | Atualiza o repositório local com as alterações do repositório remoto. |
| `git push`                            | Envia as alterações locais para o repositório remoto.          |
| `git diff`                            | Exibe as diferenças entre as alterações no seu diretório de trabalho e o último commit. |
| `git remote add nome URL`              | Adiciona um repositório remoto com um nome e uma URL específicos. |
| `git remote -v`                        | Lista os repositórios remotos configurados.                    |
| `git branch -d nome-da-branch`         | Exclui uma branch especificada após mesclar as alterações.      |
| `git reset nome-do-arquivo`            | Remove um arquivo específico da staging area.                  |
| `git stash`                            | Salva as alterações locais em um local temporário.            |
| `git stash pop`                        | Recupera as alterações salvas anteriormente com `git stash`.   |

## Configurações

| Comando                                       | Descrição                                        |
|-----------------------------------------------|--------------------------------------------------|
| `git config --global user.name "Nome"`        | Define o nome do usuário.                       |
| `git config --global user.email "Email"`       | Define o email do usuário.                      |
| `git config --global core.editor "Nome do editor"` | Define o editor de texto padrão.            |
| `git config --global core.pager "Nome do pager"`   | Define o pager padrão.                       |
| `git config --global core.excludesfile "Nome do arquivo"` | Define o arquivo de exclusão padrão.  |
| `git config --global alias.nome-do-alias "Comando"` | Cria um alias para um comando.          |
| `git config --global --unset alias.nome-do-alias` | Remove um alias.                            |
| `git config --global --edit`                   | Abre o arquivo de configuração do Git.        |
| `git config --global --list`                   | Lista as configurações do Git.                |