# IA Histórias / AI Livros

Repositório dedicado ao projeto **IA Histórias / AI Livros**.

Este espaço foi criado para organizar o código atual, versões históricas, pacotes ZIP, documentação, catálogos e referências do projeto fora do repositório antigo `desktop-tutorial`.

## Objetivo

Centralizar a evolução do projeto em um repositório próprio, preservando:

- base funcional atual;
- versões antigas usadas como referência histórica;
- documentação de continuidade;
- catálogos de README/HISTORICO;
- MundoIA e materiais embrionários;
- pacotes finais de correção;
- referências de layout, UX e comportamento antigo.

## Organização recomendada

```text
IA_Historias_AI_Livros/
├─ current_source/        # código fonte atual extraído do ZIP funcional mais recente
├─ releases_zip/          # ZIPs finais/corrigidos gerados para teste
├─ versions_historicas/   # ZIPs antigos e transições salvas
├─ mundo_inicial/         # MundoIA.rar e materiais embrionários da ideia
├─ docs/                  # README, HISTORICO, auditorias e prompts de continuidade
├─ catalogos/             # índices e catálogos gerados a partir dos READMEs/ZIPs
└─ referencias/           # prints, anotações e materiais de comparação
```

## Como usar

- `current_source/` deve conter a base atual extraída quando for útil versionar código fonte.
- `releases_zip/` deve guardar pacotes corrigidos entregues para teste.
- `versions_historicas/` deve guardar ZIPs antigos e transições históricas.
- `mundo_inicial/` deve guardar o `MundoIA.rar` e materiais da fase embrionária.
- `docs/` deve guardar documentação principal, histórico, auditorias e prompts de continuidade.
- `catalogos/` deve guardar índices e leituras consolidadas dos README/HISTORICO antigos.
- `referencias/` deve guardar prints e notas de comparação.

## Regra de trabalho

Versões antigas são referência de layout, UX, comportamento antigo, intenção original e histórico de decisões. Elas não devem ser restauradas diretamente no projeto atual sem análise.

A base funcional deve ser sempre o ZIP mais recente aprovado pelo usuário.

Ao corrigir o projeto:

1. analisar primeiro a base atual;
2. localizar arquivo e função exata;
3. consultar versões antigas somente quando houver regressão, bug ou comparação necessária;
4. adaptar a ideia ao fluxo atual;
5. não copiar código antigo cru;
6. preservar layout e experiência quando ainda forem compatíveis;
7. registrar decisões no README/HISTORICO conforme o caso.

## Licença

Este repositório é um acervo pessoal e histórico de desenvolvimento do projeto IA Histórias / AI Livros.

Nenhuma licença de uso público foi definida neste momento. Todos os direitos permanecem reservados ao autor, salvo autorização explícita.
