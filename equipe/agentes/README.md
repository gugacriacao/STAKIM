# Agentes STAKIM — regra de sincronização

Esta pasta (`equipe/agentes/`) é a **fonte oficial e editável** dos 14 agentes da STAKIM (Secretária, Coordenador, Conselheiro + 11 Diretores).

## Por que existe uma cópia em `.claude/agents/`

O Claude Cowork bloqueia escrita programática direta em `.claude/agents/` por segurança (evita que um agente crie outros agentes com execução automática de ferramentas sem revisão humana). Por isso os arquivos reais e funcionais moram em `.claude/agents/`, mas qualquer edição de conteúdo deve começar aqui.

## Regra

1. Editar sempre primeiro em `equipe/agentes/`.
2. Copiar manualmente (Finder, ou pedindo ao Claude Cowork para orientar/operar a cópia) para `.claude/agents/`, sobrescrevendo.
3. Conferir com `diff -rq equipe/agentes/ .claude/agents/` — deve retornar vazio.
4. Nunca editar `.claude/agents/` primeiro — isso quebra a sincronização e não fica registrado em nenhum histórico legível.

Ver Decisão 007 em `memoria/DECISOES.md` para o histórico completo.
