# Relatório Final - Página Colaborativa de Receitas

## Integrantes do Grupo
- Nome do projeto:Página Colaborativa de Receitas [grupo-receitas-TC-GA]
- Integrantes: Tomás Cerqueira(Tmfcerqueira|TomasCerqueira), Guilherme Antunes(gui-antunes-gh), Marco Neto (Marcopolo017)
- Repositório: [https://github.com/Tmfcerqueira/grupo-receitas-TC-GA.git]

## Branches Criadas
- **feature/bolo-cenoura** [CLOSED] - Criar página de receita de bolo de cenoura
- **feature/bolo-chocolate** - Criar página de receita de bolo de chocolate  
- **feature/bolo-laranja** - Criar página de receita de bolo de laranja
- **feature/bolo-iogurte** - Criar página de receita de bolo de iogurte
- **feature/bolo-morango** - Criar página de receita de bolo de morango

**Objetivo de cada branch**: Desenvolver uma página HTML completa com receita detalhada, ingredientes, modo de preparo e dicas para cada tipo específico de bolo.

### Processo de Merge Realizado:
1. **Push** das alterações para a branch de feature
2. **Criação de Pull Request** com descrição detalhada das mudanças
3. **Atribuição de Reviewers** para revisão do código
4. **Atribuição de Assignees** para responsabilidade do PR
5. **Revisão e aprovação** pelos membros do grupo
6. **Merge do Pull Request** após aprovação

**Fluxo de trabalho**: feature branch → Push → Pull Request → Review → Merge

## Histórico de Commits
### Exemplos de Mensagens de Commit:
- "Receita Bolo de Morango"
- "Receita Bolo de iogurte" 
- "Receita Bolo de chocolate"

### Gráfico de Contribuições:
Link: [https://github.com/Tmfcerqueira/grupo-receitas-TC-GA/graphs/contributors](https://github.com/Tmfcerqueira/grupo-receitas-TC-GA/graphs/contributors)

## Issues Criadas
| Issue | Responsáveis | Label | Descrição |
|-------|-------------|-------|-----------|
| Bug Página Receita Bolo de Chocolate | Tmfcerqueira \| gui-antunes-gh | bug | Something isn't working |
| Aparência das receitas | Tmfcerqueira \| MarcoPolo017 | enhancement | New feature or request |
| Criar Receita Mousse de Chocolate | gui-antunes-gh | enhancement | New feature or request |
| Criar Categoria "Sobremesa" | gui-antunes-gh \| MarcoPolo017 | enhancement | New feature or request |
| Criar Receita de Bolo de Cenoura | Tmfcerqueira \| gui-antunes-gh | enhancement | New feature or request |

## Pull Requests
O processo de revisão e merges foram realizados pelos colegas do projeto, seguindo o fluxo:
1. Criação do Pull Request
2. Revisão pelos membros do projeto
3. Aprovação e merge

## Conflitos e Resoluções
**Conflito na receita de bolo de cenoura:**
- Houve um conflito onde a receita do bolo de laranja foi anexada ao stash do commit
- Durante o push do commit ocorreu um conflito no ficheiro
- **Resolução**: Decidimos fechar o pull request devido à complexidade do conflito

## Dificuldades Enfrentadas
- **Dificuldade principal**: Resolver conflitos devido à aplicação que estávamos utilizando (Fork)
- Problemas com merge de branches quando havia conflitos de código
- Complexidade na resolução de conflitos entre diferentes versões de arquivos

## Principais Comandos Git Utilizados

### Comandos Básicos de Navegação:
```bash
# Garantir que está dentro da pasta do projeto
cd Path do projeto
```

### Comandos de Branch:
```bash
# Criar e mudar para nova branch
git checkout -b feature/nome
```

### Comandos de Commit:
```bash
# Adicionar alteração ao stage
git add receitas/nomedoficheiro

# Fazer o commit
git commit -m "descrição do commit"

# Enviar para o GitHub
git push origin feature/nome
```

## Conclusão

Ao longo desta atividade, o grupo teve a oportunidade de aplicar na prática os principais conceitos de versionamento com Git e colaboração com GitHub. Entre os aprendizados mais importantes, destacamos:

- **Criação e uso de branches** para separar funcionalidades (receitas) individuais;
- **Utilização de commits claros e organizados** para acompanhar o histórico de alterações;
- **Resolução de pequenos conflitos de merge**, promovendo uma melhor comunicação entre os membros;
- **Abertura e gestão de issues** para organização de tarefas;
- **Compreensão do fluxo de trabalho** com pull requests e revisões;
- **Estruturação de um projeto colaborativo** com diretórios organizados.

Este projeto permitiu reforçar a importância da **colaboração**, da **comunicação** e do uso correto de ferramentas de controlo de versão em equipa. Finalizamos o trabalho com uma maior confiança para participar em projetos reais com Git e GitHub.
