# Decisões Oficiais STAKIM

## Decisão 001
Marca oficial: STAKIM.
Assinatura institucional: Inteligência Aplicada.

## Decisão 002
Todo documento importante terá versão legível no Painel STAKIM. O CEO não será obrigado a ler arquivos Markdown.

## Decisão 003
Reuniões importantes sempre incluem a Secretária Executiva.

## Decisão 004
A STAKIM começa com GitHub e Claude Cowork. Servidor 24h ficará para etapa futura.

## Decisão 005
Repositório Git local criado em 02/07/2026 (`git init` + commit inicial "STAKIM Foundation v1.0", 32 arquivos, branch `master`). GitHub CLI não disponível no ambiente do Claude Cowork — conexão com repositório remoto no GitHub deve ser feita pelo CEO no próprio Mac, com orientação passo a passo.

## Decisão 006
Repositório remoto `https://github.com/gugacriacao/STAKIM.git` criado pelo CEO. Conexão e primeiro push feitos em 02/07/2026 via GitHub Desktop (já autenticado no Mac do CEO), com o Claude Cowork operando o app pela tela. Branch `master` publicada com sucesso. Esse é o caminho oficial de sincronização: Claude prepara commits localmente, GitHub Desktop autentica e envia.

## Decisão 007
Os 14 arquivos de agentes (Secretária, Coordenador, Conselheiro + 11 Diretores) ganharam frontmatter técnico (`name` + `description`) em 02/07/2026, condição necessária para funcionarem como subagentes de verdade. Ficam salvos em `equipe/agentes/`, e não em `.claude/agents/`, porque o Cowork bloqueia escrita direta nesse diretório por segurança (evita que um agente crie outros agentes com execução automática de ferramentas sem revisão humana). Os arquivos originais em `.claude/agents/` permanecem intactos, sem frontmatter. Para que o Diretor de Tecnologia (ou qualquer subagente Claude Code) reconheça os arquivos de `equipe/agentes/` como subagentes discadeáveis automaticamente, alguém com acesso direto ao Finder/VS Code do CEO precisa copiá-los para `.claude/agents/` — o Claude Cowork não pode fazer essa cópia final sozinho.
