# Guia de Contribuição

Este projeto segue o padrão **Conventional Commits** para mensagens de commit.  
Isso garante clareza, consistência e facilita a geração de changelogs.

## Estrutura
<tipo>[escopo opcional]: <descrição curta>

### Tipos principais
- **feat** → nova funcionalidade  
- **fix** → correção de bug  
- **docs** → mudanças na documentação  
- **style** → ajustes de formatação (sem impacto no código)  
- **refactor** → refatoração sem alterar comportamento  
- **test** → inclusão ou ajuste de testes  
- **chore** → tarefas de manutenção (dependências, configs)

### Boas práticas
- Use **imperativo**: "adicionar", "corrigir", "remover".
- Seja **curto e claro** (máx. ~50 caracteres na descrição).
- Inclua **escopo** quando útil: `feat(ui): ...`.
- Use o corpo do commit para explicar o **porquê** da mudança, se necessário.

### Exemplos
feat(auth): adicionar suporte a login com Facebook

fix(ui): corrigir botão de logout não responsivo