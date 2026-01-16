# Descrição do Projeto

Este projeto é um site educacional para compartilhar tarefas de casa e exercícios de programação com estudantes. Os estudantes podem navegar, visualizar e baixar tarefas diretamente do portal.

## Estrutura do Projeto

- [`assignments/`](../assignments/) Cada tarefa de casa é armazenada em sua própria subpasta com uma estrutura consistente.
- [`templates/`](../templates/) Templates reutilizáveis para novo conteúdo
- [`assets/`](../assets/) Contém os recursos do site incluindo CSS, JavaScript, imagens e arquivos de configuração
- [`index.html`](../index.html) A página principal do site que serve como um portal estático para navegar e visualizar tarefas. O conteúdo é configurável através do arquivo [`config.json`](../config.json) para gerar dinamicamente listas e detalhes de tarefas.

## Diretrizes do Projeto

- Manter estilo consistente em todas as páginas
- Manter nomes de arquivos e pastas descritivos e organizados

## Padrões Educacionais

Ao gerar conteúdo para este projeto:

- **Focado em aprendizado**: Todo conteúdo deve ser projetado com objetivos de aprendizado claros e níveis de dificuldade apropriados
- **Amigável para estudantes**: Use linguagem clara e encorajadora que motiva os estudantes

## Conventional Commits

Breve: use o formato convencional para mensagens de commit para tornar histórico legível e automatizar releases.

Formato:
type(scope?): subject
[BLANK LINE]
[body]
[BLANK LINE]
[footer — e.g. BREAKING CHANGE: descrição]

Tipos comuns:
- feat: nova funcionalidade
- fix: correção de bug
- docs: documentação
- style: formatação, ponto e vírgula, sem impacto no código
- refactor: mudança de código que não adiciona funcionalidade nem corrige bug
- perf: melhoria de performance
- test: adiciona/ajusta testes
- chore: tarefas de manutenção (build, deps)
- ci: mudanças em config de CI/CD
- build: mudanças no sistema de build
- revert: reverte um commit anterior

Exemplos simples:
```
feat(auth): adiciona suporte a login com Google
fix(api): corrige erro de parsing em respostas vazias
docs: atualiza README com instruções de execução
style: ajusta lint e formatação
refactor(db): simplifica consulta de usuários
chore: atualiza dependências do projeto
```

Exemplo com corpo e breaking change:
```
feat(export): exportar relatórios em CSV

Adiciona opção para exportar relatórios no formato CSV com cabeçalho e tratamento de valores nulos.

BREAKING CHANGE: o endpoint /export foi renomeado para /exports
```

Dicas rápidas:
- Escreva o subject no particípio (adiciona, remove, edita, atualiza, etc) e em minúsculas.
- NÃO utilize verbos no infinitivo (adicionar, remover, editar, atualizar).
- Evite mensagens vagas como "atualiza código".
- Separe subject do body com linha em branco.
- Use footer para referências a issues ou breaking changes.
