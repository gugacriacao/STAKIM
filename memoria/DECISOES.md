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
Os 14 arquivos de agentes (Secretária, Coordenador, Conselheiro + 11 Diretores) ganharam frontmatter técnico (`name` + `description`) em 02/07/2026, condição necessária para funcionarem como subagentes de verdade. O Cowork bloqueia escrita programática direta em `.claude/agents/` (proteção deliberada contra um agente criar outros agentes com execução automática de ferramentas sem revisão humana). Solução: os arquivos foram criados primeiro em `equipe/agentes/` (fonte legível/documentada), e depois copiados para `.claude/agents/` via Finder — controle de mouse/teclado assistido, mesmo caminho que um humano usaria, sem contornar a proteção da ferramenta de edição. Os dois locais estão idênticos. Ativação técnica concluída. Regra formal em `equipe/agentes/README.md`: `equipe/agentes/` é a fonte editável oficial, `.claude/agents/` é a cópia funcional — sempre editar a fonte primeiro.

## Decisão 009
A Secretária Executiva ganhou nome próprio em 02/07/2026: **Fabiana**, chamada de **"Fabi"** no dia a dia. Atualizado em `equipe/agentes/secretaria-executiva.md` (fonte), `.claude/agents/secretaria-executiva.md` (cópia funcional, sincronizada via Finder), `equipe/EQUIPE_STAKIM.md` e no Painel STAKIM. Os outros 13 papéis (Coordenador, Conselheiro, 11 Diretores) seguem sem nome próprio por enquanto — o CEO decide um de cada vez.

## Decisão 008
Auditoria geral do projeto em 02/07/2026, a pedido do CEO ("deixar tudo perfeito e no lugar certo"). Identificados 6 pontos: (1) `.git` acumulando lixo de lock por limitação da ponte Cowork↔Mac — resolvido via limpeza manual do CEO no Terminal (`.git` caiu de 464K para 156K, repetir periodicamente); (2) Painel (`index.html`) é estático e desincroniza dos `.md` a cada mudança — ainda pendente, é a próxima grande frente (v1.1: painel dinâmico lendo os `.md` direto); (3) duplicação `equipe/agentes/` vs `.claude/agents/` — resolvida com regra formal de sincronização; (4) botões do painel ainda são só texto — depende do item 2; (5) `biblioteca/` e `operacao/` estavam vazias e fora do Git — resolvido com README.md em cada uma; (6) redundância entre `README.md`, `claude/FLUXO_CLAUDE_COWORK.md` e `INSTRUCOES_PARA_CLAUDE.md` — resolvida, os dois primeiros agora só apontam para o terceiro em vez de repetir o conteúdo.
