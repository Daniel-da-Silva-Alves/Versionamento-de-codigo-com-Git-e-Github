<h1>
    <a href="https://git-scm.com/"><img alingn="center" alt="Logo git" width="36px" src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.svg"></a>
    <span> Versionamento de Código com Git e GitHub</span>
</h1>


<p alingn="justify" >Guia essencial de comandos Git para desenvolvedores. Inclui configuração inicial, operações básicas e avançadas, gerenciamento de branches, sincronização com repositórios remotos e resolução de conflitos. Ideal para quem deseja aprender ou revisar o uso de Git no gerenciamento de código.</p>

## Ferramentas
[![Git](https://img.shields.io/badge/Git-000?style=for-the-badge&logo=git&logoColor=E94D5F)](https://git-scm.com/doc) 
[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=30A3DC)](https://docs.github.com/)
<br>

# Sumário da Aula: Git - Comandos Essenciais e Resolução de Conflitos

# 1. Configuração Inicial e Básica

| Comando                                 | Descrição                                                    |
|-----------------------------------------|--------------------------------------------------------------|
| `git config --global user.name "Seu Nome"` | Define o nome para commits.                                |
| `git config --global user.email "seuemail@example.com"` | Define o e-mail para commits.                              |
| `git config --list`                     | Exibe configurações atuais do Git.                           |

# 2. Trabalhando com Repositórios

| Comando                                 | Descrição                                                    |
|-----------------------------------------|--------------------------------------------------------------|
| `git clone https://github.com/usuario/repo.git` | Copia um repositório remoto para o local.                    |
| `git init`                             | Inicializa um novo repositório Git vazio.                    |

# 3. Monitorando Alterações

| Comando                                 | Descrição                                                    |
|-----------------------------------------|--------------------------------------------------------------|
| `git status`                           | Mostra status dos arquivos modificados e prontos para commit. |
| `git log`                              | Exibe o histórico dos commits.                               |
| `git diff`                             | Mostra diferenças entre arquivos modificados e a última versão comitada. |

# 4. Alterações e Commits

| Comando                                 | Descrição                                                    |
|-----------------------------------------|--------------------------------------------------------------|
| `git add <arquivo>`                    | Adiciona um arquivo específico à área de preparação.        |
| `git add .`                            | Adiciona todos os arquivos modificados à área de preparação.|
| `git commit -m "Mensagem do commit"`   | Cria um commit com as alterações.                           |
| `git commit`                           | Abre um editor para uma mensagem de commit mais detalhada.   |

# 5. Trabalhando com Branches

| Comando                                 | Descrição                                                    |
|-----------------------------------------|--------------------------------------------------------------|
| `git branch <nome-da-branch>`          | Cria uma nova branch.                                       |
| `git checkout <nome-da-branch>`        | Alterna para a branch especificada.                         |
| `git checkout -b <nome-da-branch>`     | Cria e muda para uma nova branch em um comando.             |
| `git branch`                           | Exibe todas as branches locais.                             |
| `git merge <nome-da-branch>`           | Mescla alterações de uma branch na branch atual.            |
| `git branch -d <nome-da-branch>`       | Exclui uma branch local.                                    |

# 6. Sincronizando com o Repositório Remoto

| Comando                                 | Descrição                                                    |
|-----------------------------------------|--------------------------------------------------------------|
| `git remote add origin https://github.com/usuario/repo.git` | Adiciona um repositório remoto.                              |
| `git push origin <nome-da-branch>`     | Envia commits para o repositório remoto.                    |
| `git pull origin <nome-da-branch>`     | Baixa e mescla alterações do remoto.                        |
| `git remote -v`                        | Exibe URLs dos repositórios remotos associados.              |

# 7. Gerenciamento de Commits

| Comando                                 | Descrição                                                    |
|-----------------------------------------|--------------------------------------------------------------|
| `git reset --soft HEAD~1`              | Remove o último commit, mantendo alterações no diretório de trabalho. |
| `git reset --hard HEAD~1`              | Remove o último commit e todas as alterações.              |
| `git revert <hash-do-commit>`           | Cria um novo commit que reverte as mudanças de um commit específico. |
| `git commit --amend`                    | Modifica o último commit.                                   |

# 8. Resolução de Conflitos

| Comando                                 | Descrição                                                    |
|-----------------------------------------|--------------------------------------------------------------|
| `git merge <nome-da-branch>` ou `git pull origin <nome-da-branch>` | Executa uma mesclagem ou pull que pode resultar em conflitos. |
| `git status`                           | Identifica arquivos com conflitos.                          |
| Editar arquivos conflitantes            | Resolve conflitos editando os arquivos e removendo marcas de conflito. |
| `git add <arquivo>`                    | Adiciona arquivos após resolver os conflitos.               |
| `git commit`                           | Cria um commit que inclui a resolução dos conflitos.        |

# 9. Outras Operações Úteis

| Comando                                 | Descrição                                                    |
|-----------------------------------------|--------------------------------------------------------------|
| `git checkout -- <arquivo>`            | Desfaz alterações em um arquivo específico antes de commit. |
| `git reset <arquivo>`                  | Remove um arquivo da área de preparação.                    |
| `git stash`                            | Armazena temporariamente alterações não comitadas.          |
| `git stash pop`                        | Aplica as alterações armazenadas novamente.                 |
| `git remote show origin`               | Exibe informações detalhadas sobre o repositório remoto.    |
