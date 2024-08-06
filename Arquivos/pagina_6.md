## 6. Sincronizando com o Repositório Remoto

| Comando                                     | Descrição                                                    |
|---------------------------------------------|--------------------------------------------------------------|
| `git remote add origin https://github.com/usuario/repo.git` | Adiciona um repositório remoto com o nome `origin`.           |
| `git push origin <nome-da-branch>`         | Envia commits da branch local para o repositório remoto.    |
| `git pull origin <nome-da-branch>`         | Baixa e mescla alterações do repositório remoto para a branch local. |
| `git remote -v`                            | Exibe as URLs dos repositórios remotos associados.           |

### Explicações:

- **`git remote add origin https://github.com/usuario/repo.git`**:
  - **Significado:** Adiciona um repositório remoto com o nome `origin` e a URL fornecida.
  - **Quando Utilizar:** Quando você cria um novo repositório local e deseja associá-lo a um repositório remoto.
  - **Caso de Uso:** Para conectar seu repositório local a um repositório remoto onde você pode compartilhar e sincronizar alterações.

- **`git push origin <nome-da-branch>`**:
  - **Significado:** Envia commits da branch local para a branch correspondente no repositório remoto.
  - **Quando Utilizar:** Após fazer commits na branch local e querer atualizar o repositório remoto com suas alterações.
  - **Caso de Uso:** Para compartilhar suas alterações com outros colaboradores ou para fazer backup das suas alterações.

- **`git pull origin <nome-da-branch>`**:
  - **Significado:** Baixa alterações da branch especificada no repositório remoto e as mescla com a branch local.
  - **Quando Utilizar:** Quando você deseja atualizar sua branch local com as últimas mudanças do repositório remoto.
  - **Caso de Uso:** Para obter as alterações mais recentes feitas por outros colaboradores ou atualizar seu repositório local com mudanças remotas.

- **`git remote -v`**:
  - **Significado:** Exibe URLs dos repositórios remotos associados ao repositório local.
  - **Quando Utilizar:** Para verificar quais repositórios remotos estão configurados e suas URLs.
  - **Caso de Uso:** Para verificar a configuração de repositórios remotos, especialmente se você precisar confirmar a URL do repositório remoto.