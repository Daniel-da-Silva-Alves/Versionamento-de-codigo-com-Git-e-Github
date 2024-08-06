## 5. Trabalhando com Branches

| Comando                                     | Descrição                                                    |
|---------------------------------------------|--------------------------------------------------------------|
| `git branch <nome-da-branch>`              | Cria uma nova branch com o nome especificado.                |
| `git checkout <nome-da-branch>`            | Muda para a branch especificada.                            |
| `git checkout -b <nome-da-branch>`         | Cria e muda para uma nova branch em um único comando.        |
| `git branch`                               | Exibe uma lista de todas as branches locais.                 |
| `git merge <nome-da-branch>`               | Mescla as alterações da branch especificada na branch atual. |
| `git branch -d <nome-da-branch>`           | Exclui uma branch local.                                    |

### Explicações:

- **`git branch <nome-da-branch>`**:
  - **Significado:** Cria uma nova branch com o nome fornecido.
  - **Quando Utilizar:** Quando você deseja iniciar uma nova linha de desenvolvimento ou trabalho.
  - **Caso de Uso:** Para criar uma branch para uma nova feature ou correção de bug.

- **`git checkout <nome-da-branch>`**:
  - **Significado:** Alterna para a branch especificada.
  - **Quando Utilizar:** Quando você deseja começar a trabalhar em uma branch diferente.
  - **Caso de Uso:** Para mudar para uma branch de desenvolvimento ou uma branch específica para trabalhar em alterações.

- **`git checkout -b <nome-da-branch>`**:
  - **Significado:** Cria uma nova branch e muda para ela em um único comando.
  - **Quando Utilizar:** Quando você deseja criar e começar a trabalhar em uma nova branch imediatamente.
  - **Caso de Uso:** Para iniciar rapidamente uma nova branch e começar a trabalhar nela sem precisar criar e depois alternar.

- **`git branch`**:
  - **Significado:** Lista todas as branches locais.
  - **Quando Utilizar:** Para visualizar as branches disponíveis e identificar a branch atual.
  - **Caso de Uso:** Para verificar quais branches estão disponíveis e qual branch você está atualmente.

- **`git merge <nome-da-branch>`**:
  - **Significado:** Mescla as alterações da branch especificada na branch atual.
  - **Quando Utilizar:** Após concluir o trabalho em uma branch e deseja integrar as alterações na branch principal ou em outra branch.
  - **Caso de Uso:** Para combinar as alterações feitas em uma branch de feature com a branch principal do projeto.

- **`git branch -d <nome-da-branch>`**:
  - **Significado:** Exclui uma branch local.
  - **Quando Utilizar:** Quando a branch não é mais necessária, por exemplo, após a fusão das alterações.
  - **Caso de Uso:** Para limpar branches antigas ou branches que não são mais necessárias.
