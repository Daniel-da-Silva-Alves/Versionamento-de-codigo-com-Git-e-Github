## 8. Resolução de Conflitos

| Comando                                     | Descrição                                                    |
|---------------------------------------------|--------------------------------------------------------------|
| `git merge <nome-da-branch>` ou `git pull origin <nome-da-branch>` | Executa uma mesclagem ou pull que pode resultar em conflitos se houver alterações conflitantes. |
| `git status`                               | Identifica arquivos com conflitos que precisam ser resolvidos. |
| Editar arquivos conflitantes                | Resolve conflitos manualmente editando os arquivos e removendo as marcas de conflito. |
| `git add <arquivo>`                        | Adiciona arquivos resolvidos à área de preparação após resolver conflitos. |
| `git commit`                               | Cria um commit que inclui a resolução dos conflitos. |

### Explicações:

- **`git merge <nome-da-branch>` ou `git pull origin <nome-da-branch>`**:
  - **Significado:** Mescla as alterações da branch especificada na branch atual, podendo gerar conflitos se houver alterações incompatíveis.
  - **Quando Utilizar:** Para integrar alterações de outras branches ou atualizar a branch local com as alterações do repositório remoto.
  - **Caso de Uso:** Quando você está combinando mudanças de diferentes branches ou atualizando sua branch com alterações recentes de outras fontes.

- **`git status`**:
  - **Significado:** Mostra o status dos arquivos e indica quais arquivos estão com conflitos.
  - **Quando Utilizar:** Após uma tentativa de merge ou pull que resultou em conflitos.
  - **Caso de Uso:** Para identificar quais arquivos precisam ser resolvidos antes de completar a operação de merge ou pull.

- **Editar arquivos conflitantes**:
  - **Significado:** Resolva conflitos manualmente editando arquivos para remover as marcas de conflito e decidir qual versão das alterações deve ser mantida.
  - **Quando Utilizar:** Quando há conflitos durante uma operação de merge ou pull e é necessário ajustar manualmente os arquivos.
  - **Caso de Uso:** Para corrigir conflitos e preparar os arquivos para a próxima etapa de commit.

- **`git add <arquivo>`**:
  - **Significado:** Adiciona arquivos resolvidos à área de preparação para o próximo commit.
  - **Quando Utilizar:** Após resolver conflitos e ajustar arquivos.
  - **Caso de Uso:** Para marcar arquivos resolvidos como prontos para o próximo commit.

- **`git commit`**:
  - **Significado:** Cria um commit que inclui a resolução dos conflitos.
  - **Quando Utilizar:** Após resolver conflitos e preparar os arquivos para o commit.
  - **Caso de Uso:** Para registrar a resolução dos conflitos e atualizar o repositório com as alterações finalizadas.