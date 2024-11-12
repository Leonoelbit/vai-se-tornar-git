### UC13 - Executar os Processos de Codificação, Manutenção e Documentação de Aplicativos Computacionais para Desktop

## Exercícios - Aula 02

### Objetivo
Este documento detalha os exercícios da Aula 02, com o objetivo de praticar operações Git, incluindo a configuração de repositórios remotos, envio de commits para repositórios on-line e clonagem de repositórios.

---

## Exercício 1 - Configurando um Repositório Git On-line

**Prosseguimento**:

1. **Registro no GitHub**:
   - Registrei-me em uma conta no GitHub acessando GitHub e criando uma conta.

2. **Criação do Repositório On-line**:
   - No GitHub, criei um novo repositório chamado `git-test`.
   - Anotei a URL do repositório Git on-line: `https://github.com/usuario/git-test.git`.

3. **Definição do Repositório Remoto**:
   - No terminal, naveguei até o diretório do meu repositório local.
   - Configurei o repositório local para vincular-se ao repositório Git on-line:
     ```bash
     git remote add origin https://github.com/usuario/git-test.git
     ```

4. **Envio de Commits para o Repositório On-line**:
   - No terminal, enviei os commits para o repositório on-line:
     ```bash
     git push -u origin master
     ```

5. **Clonagem de um Repositório On-line**:
   - Para clonar um repositório on-line em meu computador, usei o comando:
     ```bash
     git clone https://github.com/usuario/git-test.git
     ```


### Passo a Passo 1

1. **Criação da Pasta do Projeto**:
   - Crie uma nova pasta para o seu projeto:
     ```bash
     mkdir nome-do-projeto
     cd nome-do-projeto
     ```

2. **Inicialização do Repositório Git**:
   - Inicialize a pasta como um repositório Git:
     ```bash
     git init
     ```

3. **Criação dos Arquivos Iniciais**:
   - Crie os arquivos necessários para o seu projeto. Por exemplo:
     ```bash
     echo "Conteúdo inicial do arquivo principal" > principal.txt
     echo "Informações sobre novidades" > novidades.md
     ```

4. **Adição dos Arquivos ao Staging**:
   - Adicione os arquivos ao staging para preparar para o commit:
     ```bash
     git add principal.txt novidades.md
     ```

5. **Commit dos Arquivos com Mensagens Detalhadas**:
   - Faça o commit dos arquivos com mensagens que expliquem o conteúdo e a intenção de cada mudança:
     ```bash
     git commit -m "Adiciona principal.txt com conteúdo inicial"
     git commit -m "Adiciona novidades.md com informações sobre atualizações"
     ```

6. **Criação do Repositório Remoto**:
   - No GitHub (ou outro serviço de hospedagem), crie um novo repositório e anote a URL.

7. **Definição do Repositório Remoto**:
   - Associe o repositório remoto ao seu repositório local:
     ```bash
     git remote add origin https://github.com/usuario/nome-do-repositorio.git
     ```

8. **Envio dos Commits para o Repositório Remoto**:
   - Envie os commits locais para o repositório remoto:
     ```bash
     git push -u origin master
     ```

9. **Verificação do Histórico de Commits**:
   - Verifique o histórico de commits para garantir que tudo foi enviado corretamente:
     ```bash
     git log
     ```

### Passo a Passo 2


# Criação da Pasta do Projeto
mkdir nome-do-projeto
cd nome-do-projeto

# Inicialização do Repositório Git
git init

# Criação dos Arquivos Iniciais
echo "Conteúdo inicial do arquivo principal" > principal.txt
echo "Informações sobre novidades" > novidades.md

# Adição dos Arquivos ao Staging
git add principal.txt novidades.md

# Commit dos Arquivos com Mensagens Detalhadas
git commit -m "Adiciona principal.txt com conteúdo inicial"
git commit -m "Adiciona novidades.md com informações sobre atualizações"

# Criação do Repositório Remoto no GitHub
# (Realize esta etapa no site do GitHub e anote a URL do repositório)

# Definição do Repositório Remoto
git remote add origin https://github.com/usuario/nome-do-repositorio.git

# Envio dos Commits para o Repositório Remoto
git push -u origin master

# Verificação do Histórico de Commits
git log
---

### Conclusão & Anotações

Ao completar esses exercícios, aprendi a configurar um repositório Git remoto, sincronizar o repositório local com o repositório remoto e clonar um repositório remoto. Aqui estão algumas anotações e situações encontradas:

- **Erro ao Definir o Repositório Remoto**:
  - Certifique-se de usar a URL correta do repositório remoto. Um erro comum é digitar a URL incorretamente, o que resulta em falha ao adicionar o repositório remoto.

- **Envio de Commits**:
  - O comando `git push -u origin master` define `origin` como o repositório remoto padrão para a branch `master`, facilitando futuros envios de commits.

- **Clonagem de Repositórios**:
  - A clonagem cria uma cópia completa do repositório remoto, incluindo todo o histórico de commits, branches e arquivos.

---
