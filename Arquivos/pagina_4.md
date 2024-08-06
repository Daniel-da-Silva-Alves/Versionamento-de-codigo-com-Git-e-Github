## 4. Alterações e Commits

| Comando                                     | Descrição                                                    |
|---------------------------------------------|--------------------------------------------------------------|
| `git add <arquivo>`                        | Adiciona um arquivo específico à área de preparação para o próximo commit. |
| `git add .`                                | Adiciona todos os arquivos modificados à área de preparação. |
| `git commit -m "Mensagem do commit"`       | Cria um commit com as alterações na área de preparação e adiciona uma mensagem descrevendo as mudanças. |
| `git commit`                               | Abre um editor de texto para escrever uma mensagem de commit mais detalhada. |

### Explicações:

- **`git add <arquivo>`**:
  - **Significado:** Adiciona um arquivo específico à área de preparação.
  - **Quando Utilizar:** Quando você deseja incluir apenas arquivos específicos em um commit.
  - **Caso de Uso:** Para adicionar alterações de um único arquivo ou conjunto de arquivos específicos ao próximo commit.

- **`git add .`**:
  - **Significado:** Adiciona todos os arquivos modificados no diretório atual à área de preparação.
  - **Quando Utilizar:** Quando você deseja preparar todas as mudanças feitas no diretório para o próximo commit.
  - **Caso de Uso:** Para preparar todas as alterações de uma vez antes de fazer um commit.

- **`git commit -m "Mensagem do commit"`**:
  - **Significado:** Cria um commit com as alterações preparadas e adiciona uma mensagem curta descrevendo as mudanças.
  - **Quando Utilizar:** Após adicionar arquivos à área de preparação para registrar as alterações no repositório.
  - **Caso de Uso:** Para documentar mudanças e atualizações no projeto com uma mensagem descritiva.

- **`git commit`**:
  - **Significado:** Abre um editor para escrever uma mensagem de commit mais detalhada.
  - **Quando Utilizar:** Quando você deseja fornecer uma descrição mais longa e detalhada das alterações feitas.
  - **Caso de Uso:** Para adicionar uma mensagem de commit mais descritiva que explique as mudanças em maior detalhe.
