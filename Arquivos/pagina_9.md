## 9. Outras Operações Úteis

| Comando                                     | Descrição                                                    |
|---------------------------------------------|--------------------------------------------------------------|
| `git checkout -- <arquivo>`                | Desfaz alterações em um arquivo específico e restaura a versão comitada mais recente. |
| `git reset <arquivo>`                      | Remove um arquivo da área de preparação, mas mantém as alterações no diretório de trabalho. |
| `git stash`                                | Armazena temporariamente alterações não comitadas para limpar o diretório de trabalho. |
| `git stash pop`                            | Aplica as alterações armazenadas anteriormente e remove da pilha de stash. |
| `git remote show origin`                   | Exibe informações detalhadas sobre o repositório remoto associado. |

### Explicações:

- **`git checkout -- <arquivo>`**:
  - **Significado:** Desfaz alterações em um arquivo específico e restaura a versão comitada mais recente.
  - **Quando Utilizar:** Quando você deseja reverter um arquivo a uma versão anterior sem afetar outros arquivos.
  - **Caso de Uso:** Para descartar alterações não desejadas em um arquivo específico.

- **`git reset <arquivo>`**:
  - **Significado:** Remove um arquivo da área de preparação, mas mantém as alterações no diretório de trabalho.
  - **Quando Utilizar:** Quando você adicionou um arquivo à área de preparação por engano e deseja removê-lo.
  - **Caso de Uso:** Para remover um arquivo da área de preparação sem descartar as alterações feitas.

- **`git stash`**:
  - **Significado:** Armazena temporariamente alterações não comitadas, permitindo que você limpe o diretório de trabalho para outras tarefas.
  - **Quando Utilizar:** Quando você precisa mudar de contexto rapidamente sem fazer um commit das alterações atuais.
  - **Caso de Uso:** Para guardar alterações não concluídas e retornar a elas mais tarde sem comprometer o estado atual do repositório.

- **`git stash pop`**:
  - **Significado:** Aplica as alterações armazenadas anteriormente com `git stash` e remove da pilha de stash.
  - **Quando Utilizar:** Após completar a tarefa que necessitou do stash e deseja recuperar as alterações armazenadas.
  - **Caso de Uso:** Para restaurar alterações previamente armazenadas com `git stash`.

- **`git remote show origin`**:
  - **Significado:** Exibe informações detalhadas sobre o repositório remoto associado ao seu repositório local.
  - **Quando Utilizar:** Para obter informações sobre o repositório remoto, como URL e branches.
  - **Caso de Uso:** Para verificar detalhes do repositório remoto e suas branches associadas.
