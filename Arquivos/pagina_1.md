## 1. Configuração Inicial e Básica

| Comando                                     | Descrição                                                    |
|---------------------------------------------|--------------------------------------------------------------|
| `git config --global user.name "Seu Nome"` | Define o nome do autor que aparecerá em cada commit. É usado para identificar quem fez as alterações. |
| `git config --global user.email "seuemail@example.com"` | Define o e-mail do autor para os commits. Assim como o nome, é usado para rastrear a autoria das alterações. |
| `git config --list`                       | Exibe todas as configurações atuais do Git, como nome de usuário e e-mail. É útil para verificar se suas configurações estão corretas. |

### Explicações:

- **`git config --global user.name "Seu Nome"`**:
  - **Significado:** Define o nome que será associado aos commits.
  - **Quando Utilizar:** Sempre que configurar um novo ambiente Git ou quando alterar o nome associado aos commits.
  - **Caso de Uso:** Ao iniciar um novo projeto ou quando configurar Git pela primeira vez em um sistema.

- **`git config --global user.email "seuemail@example.com"`**:
  - **Significado:** Define o e-mail associado aos commits.
  - **Quando Utilizar:** Após configurar o nome, deve-se definir o e-mail para garantir que todos os commits sejam corretamente identificados.
  - **Caso de Uso:** Ao configurar um novo ambiente de desenvolvimento ou atualizar seu e-mail de contato.

- **`git config --list`**:
  - **Significado:** Mostra uma lista de todas as configurações atuais do Git.
  - **Quando Utilizar:** Para verificar as configurações atuais, como nome e e-mail, e confirmar que estão corretas.
  - **Caso de Uso:** Para validar suas configurações de usuário ou resolver problemas relacionados à identificação dos commits.