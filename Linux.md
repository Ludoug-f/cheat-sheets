| COMANDO                              | DESCRIÇÃO                                                                                                  |
|--------------------------------------|------------------------------------------------------------------------------------------------------------|
| `touch arquivo.extensao`             | Cria um arquivo com o nome e a extensão desejados.                                                       |
| `ls`                                 | Lista arquivos e diretórios.                                                                              |
| `ls -a`                              | Lista arquivos e diretórios, incluindo os ocultos.                                                         |
| `mkdir nome-diretorio`               | Cria um diretório com um nome especificado.                                                                |
| `cd diretorio`                       | Muda para o diretório nomeado. Aqui você pode navegar por múltiplos diretórios com o uso da `/`, como em `cd Documentos/exemplo`. |
| `cd`                                 | Muda para o diretório inicial.                                                                            |
| `cd ~`                               | Muda para o diretório inicial.                                                                            |
| `cd ..`                              | Muda para o diretório-pai do diretório atual.                                                             |
| `pwd`                                | Mostra o caminho do diretório atual.                                                                      |
| `cp arquivo1 arquivo2`               | Copia arquivo1 para o mesmo diretório, chamando-o de arquivo2.                                              |
| `mv arquivo1 arquivo2`               | Renomeia arquivo1 para arquivo2.                                                                          |
| `mv arquivo1 /diretorio`             | Move arquivo1 para o diretório especificado.                                                               |
| `rm arquivo`                         | Remove um arquivo.                                                                                       |
| `rmdir diretorio`                    | Remove um diretório.                                                                                      |
| `cat arquivo`                        | Sem nenhuma opção, o conteúdo do arquivo é exibido no terminal.                                           |
| `cat > arquivo.txt`                  | O operador de redirecionamento cria novos arquivos de texto. Para quebrar linha, pressione enter; para finalizar a edição, utilize CTRL + D. Você pode editar arquivos, mas irá sobrescrever o conteúdo. |
| `less arquivo`                       | Exibe o conteúdo do arquivo no terminal, uma página por vez. Para sair do terminal, aperte a tecla Q.       |
| `head arquivo`                       | Exibe, por padrão, as 10 primeiras linhas do arquivo informado.                                           |
| `head -5 arquivo`                    | Exibe as 5 primeiras linhas do arquivo informado. Você pode utilizar qualquer valor numérico para exibir a quantidade de linhas que desejar. |
| `tail arquivo`                       | Exibe, por padrão, as 10 últimas linhas do arquivo informado.                                              |
| `tail -5 arquivo`                    | Exibe as 5 últimas linhas do arquivo informado. Você pode utilizar qualquer valor numérico para exibir a quantidade de linhas que desejar. |
| `grep 'palavra-chave' arquivo`       | Procura por palavras-chave no arquivo informado. O retorno é exibido no terminal.                        |
| `wc arquivo`                         | Conta o número de linhas, palavras, caracteres ou bytes no arquivo, dependendo da tag usada (-l, -w, -m e -c, respectivamente), e exibe o resultado no terminal. |
| `*`                                  | Corresponde a qualquer número de caracteres.                                                               |
| `?`                                  | Corresponde a um caractere qualquer.                                                                        |
| `man comando`                        | Exibe a página do manual on-line do comando informado.                                                      |
| `whatis comando`                     | Exibe uma breve descrição do comando informado.                                                              |
| `apropos 'palavra-chave'`            | Exibe comandos correspondentes à palavra-chave informada.                                                    |
| `comando > arquivo`                  | Redireciona a saída padrão do comando para o arquivo e sobrescreve o conteúdo existente, se o arquivo já existir. |
| `comando >> arquivo`                 | Adiciona a saída padrão do comando ao final do arquivo.                                                      |
| `comando < arquivo`                  | Direciona o comando para um arquivo, sem alterar esse arquivo.                                               |
| `comando1 \| comando2`                | Envia a saída do comando1 como entrada para o comando2.                                                      |
| `cat arquivo1 arquivo2 > arquivo3`   | Une os conteúdos dos arquivos 1 e 2 no arquivo3.                                                             |
| `sort`                               | Ordena dados.                                                                                                |
| `who`                                | Lista as pessoas usuárias logadas atualmente.                                                               |
| `find diretorio -name nome-arquivo`   | Procura por arquivos com um nome específico dentro de um diretório.                                          |
| `chmod permissões arquivo`            | Altera as permissões de acesso de um arquivo.                                                               |
| `chown novo-proprietario arquivo`     | Altera o proprietário de um arquivo.                                                                       |
| `df`                                 | Exibe informações sobre o espaço em disco usado e disponível.                                                |
| `du`                                 | Mostra o uso de espaço em disco de arquivos e diretórios.                                                     |
| `top`                                | Exibe informações sobre processos em execução e recursos do sistema.                                           |
| `kill PID`                           | Encerra um processo com base no seu ID de processo (PID).                                                   |
| `ps`                                 | Lista os processos em execução no sistema.                                                                 |
| `ifconfig`                           | Exibe informações sobre as interfaces de rede do sistema.                                                    |
| `ping host`                          | Envia pacotes de teste ICMP para um host para verificar a conectividade de rede.                             |
| `scp arquivo origem destino`          | Copia arquivos de ou para um servidor remoto usando SSH.                                                      |
| `wget URL`                           | Baixa arquivos da internet usando o protocolo HTTP ou FTP.                                                   |
| `tar`                                | Utilitário para manipular arquivos tar (compactados).                                                          |
| `zip`                                | Utilitário para criar e extrair arquivos zip compactados.                                                      |
| `unzip`                              | Descompacta arquivos zip.                                                                                   |
| `history`                            | Mostra o histórico de comandos usados no terminal.                                                            |
| `shutdown`                           | Desliga ou reinicia o sistema.                                                                             |
| `reboot`                             | Reinicia o sistema.                                                                                        |
| `date`                               | Exibe a data e a hora atuais.                                                                              |
| `alias`                              | Cria alias para comandos.                                                                                  |
| `echo`                               | Exibe uma mensagem ou valor na saída padrão.                                                               |
