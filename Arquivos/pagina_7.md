## 7. Gerenciamento de Commits

| Comando                                     | Descrição                                                    |
|---------------------------------------------|--------------------------------------------------------------|
| `git reset --soft HEAD~1`                  | Remove o último commit, mas mantém as alterações no diretório de trabalho e na área de preparação. |
| `git reset --hard HEAD~1`                  | Remove o último commit e todas as alterações no diretório de trabalho. |
| `git revert <hash-do-commit>`               | Cria um novo commit que reverte as mudanças de um commit específico. |
| `git commit --amend`                        | Modifica o último commit, permitindo alterar a mensagem ou adicionar mudanças. |

### Explicações:

- **`git reset --soft HEAD~1`**:
  - **Significado:** Remove o último commit, mas preserva as alterações no diretório de trabalho e na área de preparação.
  - **Quando Utilizar:** Quando você deseja desfazer um commit recente, mas manter as alterações para revisão ou reenvio.
  - **Caso de Uso:** Para corrigir um commit recente sem perder as mudanças realizadas.

- **`git reset --hard HEAD~1`**:
  - **Significado:** Remove o último commit e descarta todas as alterações no diretório de trabalho.
  - **Quando Utilizar:** Quando você deseja desfazer um commit recente e descartar todas as mudanças associadas.
  - **Caso de Uso:** Para reverter completamente a um estado anterior, eliminando mudanças indesejadas.

- **`git revert <hash-do-commit>`**:
  - **Significado:** Cria um novo commit que reverte as alterações feitas em um commit específico.
  - **Quando Utilizar:** Quando você deseja desfazer as mudanças de um commit anterior sem alterar o histórico.
  - **Caso de Uso:** Para desfazer alterações de um commit específico, mas manter o histórico de commits intacto.

- **`git commit --amend`**:
  - **Significado:** Permite modificar o último commit, seja para alterar a mensagem ou adicionar novas mudanças.
  - **Quando Utilizar:** Quando você precisa corrigir a mensagem de commit ou adicionar alterações adicionais ao último commit.
  - **Caso de Uso:** Para atualizar ou corrigir o último commit antes de fazer o push para o repositório remoto.