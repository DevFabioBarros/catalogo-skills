# Catálogo de Skills para Agentes

> Referência de skills, bibliotecas, ferramentas e coleções para agentes de programação, incluindo OpenAI Codex, Cursor e Claude Code.

**154 recursos · 14 categorias · 26/10/2026**

## Índice

1. [Descoberta e criação de skills](#descoberta-e-criação-de-skills)
2. [Planejamento, especificação e orquestração](#planejamento-especificação-e-orquestração)
3. [Frontend, UI e design](#frontend-ui-e-design)
4. [Design systems e referências visuais](#design-systems-e-referências-visuais)
5. [Imagem, wireframes, 3D e visão computacional](#imagem-wireframes-3d-e-visão-computacional)
6. [Motion, áudio e vídeo](#motion-áudio-e-vídeo)
7. [Arquitetura e revisão de código](#arquitetura-e-revisão-de-código)
8. [Testes, segurança e qualidade](#testes-segurança-e-qualidade)
9. [Integrações e infraestrutura de agentes](#integrações-e-infraestrutura-de-agentes)
10. [Eficiência e roteamento de modelos](#eficiência-e-roteamento-de-modelos)
11. [Pesquisa, web e automação](#pesquisa-web-e-automação)
12. [Marketing e conteúdo](#marketing-e-conteúdo)
13. [Documentos, apresentações e dados](#documentos-apresentações-e-dados)
14. [Ferramentas, documentação e utilitários](#ferramentas-documentação-e-utilitários)

## Descoberta e criação de skills

| Skill / recurso | Descrição |
|---|---|
| [Find Skills](https://github.com/vercel-labs/skills/tree/main/skills/find-skills) | Descobre skills pertinentes para tarefas. |
| [Skill Creator](https://github.com/anthropics/skills/tree/main/skills/skill-creator) | Cria skills personalizadas. |

## Planejamento, especificação e orquestração

| Skill / recurso | Descrição |
|---|---|
| [plan-screen](https://github.com/rtadewald/skills/blob/main/plan-screen) | Planejamento de telas e fluxos com wireframes tipados e mocks PNG. |
| [grill-me](https://github.com/mattpocock/skills/tree/main/skills/productivity/grill-me) | Entrevista guiada para aprofundar requisitos, prioridades e decisões de produto ou engenharia. |
| [AIS-OS — Onboard](https://github.com/nateherkai/AIS-OS/blob/main/.agents/skills/onboard/SKILL.md) | Entrevista inicial de sete perguntas que cria contexto, arquivos básicos e rotas AGENTS.md/CLAUDE.md no kit AIS-OS. |
| [AIS-OS — Grill Me](https://github.com/nateherkai/AIS-OS/blob/main/.agents/skills/grill-me/SKILL.md) | Entrevista aprofundada com checkpoint de cada resposta em Markdown, para preservar contexto e decisões; distinto do Grill Me de Matt Pocock. |
| [AIS-OS — Audit](https://github.com/nateherkai/AIS-OS/blob/main/.agents/skills/audit/SKILL.md) | Audita a confiabilidade operacional do sistema pessoal em Context, Connections, Capabilities e Cadence, salvando relatórios locais. |
| [AIS-OS — Link](https://github.com/nateherkai/AIS-OS/blob/main/.agents/skills/link/SKILL.md) | Adiciona rotas mínimas para projetos, arquivos e fontes nos índices/AGENTS.md, verificando se as referências resolvem. |
| [AIS-OS — Level Up](https://github.com/nateherkai/AIS-OS/blob/main/.agents/skills/level-up/SKILL.md) | Identifica gargalos recorrentes pelo método 3Ms e orienta uma automação ou reparo de workflow por ciclo. |
| [to-tickets](https://github.com/rtadewald/skills/blob/main/to-tickets) | Transforma plano, especificação ou conversa em tickets com dependências. |
| [handoff](https://github.com/rtadewald/skills/blob/main/handoff) | Resume contexto e decisões para transferência entre agentes. |
| [Grill With Docs](https://github.com/mattpocock/skills/tree/main/skills/engineering/grill-with-docs) | Entrevista técnica com produção de glossário, documentação de domínio e registros de decisões arquiteturais. |
| [Superpowers](https://github.com/obra/superpowers) | Fluxo com brainstorming, TDD, planejamento, execução e revisão. |
| [Addy Osmani — Agent Skills](https://github.com/addyosmani/agent-skills) | Coleção de 25 skills para requisitos, planejamento, arquitetura de APIs, documentação oficial, testes, segurança, performance, CI/CD, observabilidade e entrega. |
| [Agent Skills for Context Engineering](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering) | Coleção de skills para gestão de contexto, compactação, memória, padrões multiagentes, avaliação e engenharia de agentes. |
| [GSD / Get Shit Done](https://github.com/gsd-build/get-shit-done) | Framework de especificação e execução de tarefas complexas. |
| [MassGen](https://github.com/massgen/massgen) | Framework multiagente para execução paralela, revisão cruzada, refinamento iterativo e consenso entre agentes, com integração ao Codex. |
| [Planning With Files](https://github.com/OthmanAdi/planning-with-files) | Planos persistentes em arquivos para sessões longas. |
| [OpenSpec](https://github.com/Fission-AI/OpenSpec) | Desenvolvimento orientado por especificações e mudanças. |
| [Spec-Driven Development](https://github.com/FredAntB/Spec-Driven-Development) | Requirements, design e tasks para implementação. |
| [Allium](https://github.com/juxt/allium) | Especificações comportamentais próximas ao código. |
| [PAUL](https://github.com/ChristopherKahler/paul) | Ciclo leve Plan–Apply–Unify. |
| [BMAD Skills](https://github.com/aj-geddes/claude-code-bmad-skills) | Método BMAD adaptado para agentes de desenvolvimento. |
| [Setup Matt Pocock Skills](https://github.com/mattpocock/skills/tree/main/skills/engineering/setup-matt-pocock-skills) | Configuração do conjunto de skills e dependências de Matt Pocock. |
| [Self Improving Agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | Registra erros, correções e aprendizados reutilizáveis entre sessões de agentes. |
| [Triage — Matt Pocock](https://www.skills.sh/mattpocock/skills/triage) | Triagem de issues e PRs por estados, com investigação de bugs, briefs e transição de tarefas no issue tracker. |
| [To PRD — Matt Pocock](https://www.skills.sh/mattpocock/skills/to-prd) | Sintetiza requisitos e decisões da conversa em PRD estruturado, com integração ao issue tracker. |
| [Loop Me — Matt Pocock](https://www.skills.sh/mattpocock/skills/loop-me) | Identifica rotinas repetitivas e as converte em especificações de workflows com checkpoints e gatilhos. |
| [Agency Agents](https://github.com/msitarzewski/agency-agents) | Coleção de personas e agentes especializados em engenharia, design, produto, testes, segurança e marketing, com conversão para agentes de diferentes IDEs, inclusive Codex. |

## Frontend, UI e design

| Skill / recurso | Descrição |
|---|---|
| [Taste Skill](https://github.com/tasteskill/tasteskill) | Diretrizes anti-interface-genérica para composição, tipografia e motion. |
| [Web Design Guidelines](https://github.com/vercel-labs/agent-skills/tree/main/skills/web-design-guidelines) | Auditoria de UX, UI e acessibilidade. |
| [Image to Code](https://github.com/tasteskill/tasteskill/tree/main/skills/image-to-code-skill) | Pipeline visual de imagem para implementação frontend (skill no repositório Taste). |
| [Frontend Design](https://github.com/anthropics/skills/tree/main/skills/frontend-design) | Diretrizes de design frontend. |
| [10K Websites](https://github.com/malboashe/10k-websites-skill) | Workflow de landing pages cinematográficas com vídeo controlado pelo scroll, HTML/CSS/JS, geração Higgsfield, processamento ffmpeg e publicação Hostinger. Fonte analisada: `10k-websites-skill.zip`; repositório público similar, correspondência exata da versão não confirmada. |
| [Scroll Craft](https://github.com/nateherkai/scroll-craft) | Skill de experiências web premium orientadas por scroll: direção visual, profundidade, mídia, engine de animação e testes automatizados no navegador; compatível com Codex. |
| [GSAP Skills — GreenSock](https://github.com/greensock/gsap-skills) | Coleção oficial de oito skills GSAP para tweens, timelines, ScrollTrigger, plugins, utilitários, integração com frameworks e performance de animações. |
| [UI UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | Inteligência visual para UI e UX. |
| [MengTo Skills](https://github.com/MengTo/Skills) | Coleção de skills para design criativo, interfaces, captura de referências visuais, animação, Three.js, games e workflows de agentes. |
| [Impeccable](https://github.com/pbakaus/impeccable) | Sistema de direção, auditoria e refinamento visual de interfaces: composição, tipografia, cores, consistência e acessibilidade. |
| [Frontend AI Skills](https://github.com/JustineBijuPaul/frontend-ai-skills) | Coleção modular de cerca de 70 skills para arquitetura frontend, React, animações, 3D, acessibilidade, performance e testes. |
| [Web Artifacts Builder](https://github.com/anthropics/skills/tree/main/skills/web-artifacts-builder) | Criação de experiências interativas web. |
| [shadcn/ui](https://github.com/shadcn-ui/ui) | Biblioteca e CLI de componentes React personalizáveis, com integração de skills e MCP. |
| [React Bits](https://github.com/DavidHDev/react-bits) | Biblioteca de componentes React animados e interativos, com demos e integração para agentes; utilizar componentes por projeto. |
| [Transitions.dev](https://github.com/Jakubantalik/transitions.dev) | Biblioteca e skills de transições e microinterações de UI, com receitas gratuitas e opções Pro. |

## Design systems e referências visuais

| Skill / recurso | Descrição |
|---|---|
| [ds-from-html](https://github.com/rtadewald/skills/blob/main/ds-from-html) | HTML de referência para pattern library e design-system.html. |
| [extract-ds](https://github.com/rtadewald/skills/blob/main/extract-ds) | Extrai um site funcional e estrutura visão geral e componentes. |
| [clean-ds-from-html](https://github.com/rtadewald/skills/blob/main/clean-ds-from-html) | Extrai design system limpo e assets de HTML. |
| [ds-from-react](https://github.com/rtadewald/skills/blob/main/ds-from-react) | React hospedado para design-system.html. |
| [ds-from-img](https://github.com/rtadewald/skills/blob/main/ds-from-img) | Imagem de mock para HTML/CSS em design-systems/. |
| [ds-from-svg](https://github.com/rtadewald/skills/blob/main/ds-from-svg) | SVG para HTML/CSS em design-systems/. |
| [ds-cards-from-img](https://github.com/rtadewald/skills/blob/main/ds-cards-from-img) | Recorta e reproduz cards de referência com precisão. |
| [ds-cards-from-img-2](https://github.com/rtadewald/skills/blob/main/ds-cards-from-img-2) | Alternativa rápida de reconstrução de cards com PIL. |
| [img-to-html](https://github.com/rtadewald/skills/blob/main/img-to-html) | Mock para wireframe, aprovação e implementação HTML/CSS em etapas. |
| [img-to-html2](https://github.com/rtadewald/skills/blob/main/img-to-html2) | Wireframe e aprovação, reconhecimento de fontes e shell HTML. |
| [img-to-html3](https://github.com/rtadewald/skills/blob/main/img-to-html3) | Ferramentas de conversão visuais orientadas por prompt, sem pipeline fixo. |
| [Awesome Design Skills](https://github.com/bergside/awesome-design-skills) | Biblioteca de estilos visuais, referências de interface e arquivos de design system. |
| [Diagram Design](https://github.com/cathrynlavery/diagram-design) | Cria diagramas editoriais de arquitetura, fluxos, sequência e dados em HTML/SVG, com temas personalizáveis e integração ao Codex. |
| [Theme Factory](https://github.com/anthropics/skills/tree/main/skills/theme-factory) | Temas visuais consistentes. |
| [Designlang](https://github.com/Manavarya09/design-extract) | CLI e skill para extrair design systems de sites via navegador, incluindo tokens, tipografia, CSS, componentes e relatórios de acessibilidade. |
| [Archify](https://github.com/tt-a1i/archify) | Skill para transformar descrições ou projetos em diagramas interativos de arquitetura, sequência, fluxo de dados e processos, com validação e exportação HTML/SVG. |

## Imagem, wireframes, 3D e visão computacional

| Skill / recurso | Descrição |
|---|---|
| [to-img](https://github.com/rtadewald/skills/blob/main/to-img) | Gera imagens PNG em paralelo usando modelos de imagem. |
| [to-wireframe](https://github.com/rtadewald/skills/blob/main/to-wireframe) | Imagem ou briefing para wireframe tipado ASCII/SVG. |
| [img2threejs](https://github.com/img2threejs/img2threejs) | Converte uma imagem de objeto ou personagem em modelo 3D procedural Three.js, com geração de código TypeScript e validação visual por etapas; compatível com Codex. |
| [WebGL Animation Skills — iart.ai](https://github.com/iart-ai/webgl-animation-skills) | Coleção de três skills para shaders GLSL, animações Three.js/WebGL e sistemas de partículas; inclui orientações de GPU e gerenciamento de recursos. |
| [AIS-OS — 3D Brain](https://github.com/nateherkai/AIS-OS/blob/main/.agents/skills/3d-brain/SKILL.md) | Cria visualizador 3D local de conhecimento em Markdown/texto, com categorias, conexões, busca e replay; inclui app Node.js 22+. |
| [Gerador de Foto Multi Ângulo](https://hub.asimov.academy/curso/atividade/saindo-do-zero-com-o-gpt-6-astra/) | Cria folhas de referência com vistas múltiplas de um objeto a partir de fotografias, indicando detalhes não observados como inferidos. Fonte: `Dominando Elementos 3D.zip` (Google Drive; URL pendente) e aula da Asimov Academy. |
| [Modelagem 3D Fiel](https://hub.asimov.academy/curso/atividade/saindo-do-zero-com-o-gpt-6-astra/) | Orienta reconstrução e refinamento geométrico de modelos 3D com base em fotos, escultura e validação de BLEND/GLB. Fonte: `Dominando Elementos 3D.zip` (Google Drive; URL pendente) e aula da Asimov Academy. |
| [Drei](https://github.com/pmndrs/drei) | Biblioteca de helpers para React Three Fiber, como câmeras, controles, carregadores, ambientes, texto e efeitos. |
| [React Three Fiber](https://github.com/pmndrs/react-three-fiber) | Renderer de Three.js para React, permitindo construir e controlar cenas 3D como componentes React. |
| [Text to CAD](https://github.com/earthtojake/text-to-cad) | Cria e inspeciona peças e montagens CAD paramétricas a partir de descrições, com exportação STEP, STL, 3MF e GLB e integração ao Codex. |
| [openrouter-img](https://github.com/rtadewald/skills/blob/main/openrouter-img) | CLI de modelos de imagem via OpenRouter. |
| [nano-banana-pro](https://github.com/rtadewald/skills/blob/main/nano-banana-pro) | Geração e edição de imagens com Gemini Nano Banana Pro. |
| [fal-ai](https://github.com/rtadewald/skills/blob/main/fal-ai) | Integração com fal.ai e recursos de visão Moondream. |
| [Canvas Design](https://github.com/anthropics/skills/tree/main/skills/canvas-design) | Composições gráficas. |
| [Algorithmic Art](https://github.com/anthropics/skills/tree/main/skills/algorithmic-art) | Arte algorítmica. |
| [Claude Art Skill](https://github.com/aplaceforallmystuff/claude-art-skill/tree/main/skills/art) | Direção visual de peças artísticas. |
| [Image Blaster](https://github.com/neilsonnn/image-blaster) | Pipeline de imagem para ambiente 3D explorável, malhas e áudio usando World Labs e fal.ai; requer serviços/API externos. |
| [ArtCraft](https://github.com/storytold/artcraft) | Aplicação open source de criação e edição visual para imagens, vídeo e cenas 2D/3D, com ferramentas interativas. |

## Motion, áudio e vídeo

| Skill / recurso | Descrição |
|---|---|
| [animate](https://github.com/rtadewald/skills/blob/main/animate) | Define e implementa animações com intenção e critérios. |
| [mediabunny](https://github.com/rtadewald/skills/blob/main/mediabunny) | Processamento de áudio/vídeo usando Mediabunny. |
| [Brag](https://github.com/latent-spaces/brag) | Cria vídeos promocionais de lançamento a partir de um projeto. |
| [Web Animation Skills](https://github.com/iart-ai/web-animation-skills) | Coleção para microinterações, SVG/Lottie, transições de páginas, acessibilidade e performance de animações web, incluindo GSAP. |
| [Remotion Best Practices](https://github.com/remotion-dev/skills/tree/main/skills/remotion-best-practices) | Vídeos programáticos em React/Remotion. |
| [Music Creation](https://github.com/bitwize-music-studio/claude-ai-music-skills) | Criação musical. |
| [HyperFrames CLI](https://github.com/heygen-com/hyperframes) | Ferramenta de composição, pré-visualização e renderização de vídeos baseados em HTML. |
| [Lenis](https://github.com/darkroomengineering/lenis) | Biblioteca JavaScript de smooth scrolling para websites, com integração a GSAP ScrollTrigger e suporte a múltiplos frameworks. |
| [Motionmaxxing](https://github.com/tejashmakwana/motionmaxxing) | Produção e refinamento de motion graphics, vídeos promocionais e animações tipográficas a partir de briefs e referências visuais. |
| [Emil Kowalski — Skills for Designers and Engineers](https://github.com/emilkowalski/skills) | Coleção de skills para design engineering, revisão e performance de animações, responsividade e testes de robustez visual. |
| [Herk Edit Kit](https://github.com/nateherkai/herk-edit-kit) | Kit de edição audiovisual com 15 skills, cortes por transcrição, reels, legendas, biblioteca de motion graphics e templates HyperFrames/GSAP para Codex e Claude Code. |
| [OneTake](https://github.com/feitangyuan/onetake) | Skill para vídeos de lançamento em plano-sequência, com movimento contínuo, bibliotecas de animação e verificação de ritmo; licença não comercial. |
| [Collage B-roll](https://github.com/pyang5166/gbro-collage-broll) | Skill para produzir clipes curtos de colagem editorial animada, com aprovação em etapas e geração por modelos externos. |
| [Claude Animation Base](https://github.com/JohnHeibel/ClaudeAnimationBase) | Projeto-base de animação ilustrada de personagens com p5.js e p5.brush, originalmente orientado a Claude. |
| [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar) | Biblioteca de estilos cinematográficos construídos em código, com guias de direção, técnica e modelos de estilo; afinada para Claude Opus. |
| [OpenMontage](https://github.com/calesthio/OpenMontage) | Sistema aberto de produção audiovisual assistida por agentes, com pipelines para roteiro, pesquisa, imagens e filmagens, narração, montagem com Remotion/HyperFrames e pós-produção via FFmpeg. |

## Arquitetura e revisão de código

| Skill / recurso | Descrição |
|---|---|
| [Graphify](https://github.com/Graphify-Labs/graphify) | Gera um grafo navegável de relações entre código, símbolos e documentação para compreensão arquitetural. |
| [Trail-Code (antigo Graft)](https://github.com/trailhq/Trail-Code) | CLI e MCP para agentes de programação: originado do Graft, indexa símbolos e dependências do código com tree-sitter, mantém o mapa atualizado e registra decisões persistentes por projeto. |
| [Improve Codebase Architecture](https://github.com/mattpocock/skills/tree/main/skills/engineering/improve-codebase-architecture) | Inspeciona arquitetura, identifica problemas estruturais e orienta refatorações. |
| [Thermo-Nuclear Code Quality Review](https://github.com/cursor/plugins/blob/main/cursor-team-kit/skills/thermo-nuclear-code-quality-review/SKILL.md) | Auditoria rigorosa de legibilidade, arquitetura e manutenibilidade. |
| [Claude Code Kit](https://github.com/blencorp/claude-code-kit) | Skills de engenharia full-stack e stacks web. |
| [Jeff Allan Claude Skills](https://github.com/jeffallan/claude-skills) | Coleção de workflows e skills para desenvolvimento. |
| [Vercel React Best Practices](https://github.com/vercel-labs/agent-skills/tree/main/skills/react-best-practices) | Performance e práticas React/Next.js. |
| [Vercel Composition Patterns](https://github.com/vercel-labs/agent-skills/tree/main/skills/composition-patterns) | Composição de componentes React. |
| [Axiom](https://github.com/CharlesWiltgen/Axiom) | Desenvolvimento Swift, iOS e Xcode. |
| [Karpathy Guidelines](https://github.com/multica-ai/andrej-karpathy-skills/tree/main/skills/karpathy-guidelines) | Simplicidade e mudanças cirúrgicas no código. |
| [Codebase Design](https://github.com/mattpocock/skills/tree/main/skills/engineering/codebase-design) | Princípios para modelagem de módulos, APIs internas e abstrações sustentáveis. |
| [Writing for Agents](https://www.skills.sh/mattpocock/skills/writing-for-agents) | Boas práticas para escrever SKILL.md, AGENTS.md e documentos destinados a agentes, com gatilhos e contexto progressivo. |
| [Codebase Memory MCP](https://github.com/DeusData/codebase-memory-mcp) | Servidor MCP de inteligência local de código com grafo persistente, relações de chamadas e dependências, análise de impacto e ferramentas de inspeção de projetos. |

## Testes, segurança e qualidade

| Skill / recurso | Descrição |
|---|---|
| [Playwright CLI + skill oficial](https://github.com/microsoft/playwright-cli) | CLI oficial para automação e testes web com sessões Chrome, snapshots, screenshots, geração e depuração de testes; oferece skill compatível com agentes. |
| [Git Guardrails](https://github.com/mattpocock/skills/tree/main/skills/misc/git-guardrails-claudecode) | Diretrizes e verificações para reduzir o risco de comandos Git destrutivos. |
| [Webapp Testing](https://github.com/anthropics/skills/tree/main/skills/webapp-testing) | Teste de aplicações web com browser. |
| [Trail of Bits Security](https://github.com/trailofbits/skills) | Skills de segurança e análise de vulnerabilidades. |
| [Cloudflare Security Audit](https://github.com/cloudflare/security-audit-skill) | Workflow de auditoria de segurança em fases, com análise de superfícies de ataque e validação de achados. |
| [Strix](https://github.com/usestrix/strix) | Plataforma open source de pentest com agentes; possui skills para testes de aplicações, APIs, OWASP Top 10, revisão de código e correção de vulnerabilidades. |
| [Supply Chain Risk Auditor](https://github.com/trailofbits/skills/tree/main/plugins/supply-chain-risk-auditor) | Avalia riscos de dependências de terceiros, publicadores, manutenção, advisories e scripts de instalação. |
| [Insecure Defaults](https://github.com/trailofbits/skills/tree/main/plugins/insecure-defaults) | Audita senhas padrão, segredos de fallback, configurações permissivas e padrões inseguros. |
| [TDD — Matt Pocock](https://github.com/mattpocock/skills/tree/main/skills/engineering/tdd) | Fluxo de desenvolvimento guiado por testes e verificações incrementais. |
| [Agent Browser](https://github.com/vercel-labs/agent-browser) | CLI para navegação, screenshots, inspeção e testes reais de interfaces. |
| [Diagnosing Bugs — Matt Pocock](https://www.skills.sh/mattpocock/skills/diagnosing-bugs) | Investigação de bugs a partir de um sinal reproduzível de falha, instrumentação, hipóteses e evidências. |
| [Code Review — Matt Pocock](https://www.skills.sh/mattpocock/skills/code-review) | Revisa diffs em dois eixos: conformidade com padrões do repositório e aderência à especificação. |
| [Resolving Merge Conflicts — Matt Pocock](https://www.skills.sh/mattpocock/skills/resolving-merge-conflicts) | Investiga e resolve conflitos de merge/rebase respeitando a intenção das alterações e executando verificações. |

## Integrações e infraestrutura de agentes

| Skill / recurso | Descrição |
|---|---|
| [MCP Builder](https://github.com/anthropics/skills/tree/main/skills/mcp-builder) | Criação de servidores MCP. |
| [Awesome Codex Subagents](https://github.com/VoltAgent/awesome-codex-subagents) | Coleção de definições de subagentes Codex em TOML para tarefas especializadas de desenvolvimento, segurança, testes e infraestrutura. |
| [21st MCP (antigo Magic MCP)](https://github.com/21st-dev/magic-mcp) | Servidor MCP de componentes e referências de interface React/Tailwind, com pesquisa, obtenção de código e recursos opcionais de geração de UI. |
| [Claude API](https://github.com/anthropics/skills/tree/main/skills/claude-api) | Skills para desenvolvimento de integrações com a API da Anthropic. |
| [Microsoft Azure Skills](https://github.com/microsoft/azure-skills) | Coleção oficial de workflows de infraestrutura Azure: computação, RBAC, custos, Kubernetes, migração e operações. |
| [Microsoft Foundry](https://www.skills.sh/microsoft/azure-skills/microsoft-foundry) | Skill de ciclo de vida de agentes no Microsoft Foundry, com provisionamento, deploy, avaliação e observabilidade. |

## Eficiência e roteamento de modelos

| Skill / recurso | Descrição |
|---|---|
| [Ponytail](https://github.com/DietrichGebert/ponytail) | Skills de revisão e simplificação de código, com foco em complexidade desnecessária. |
| [Caveman](https://github.com/JuliusBrussee/caveman) | Respostas curtas e redução de verbosidade. |
| [OmniRoute](https://github.com/diegosouzapw/OmniRoute) | Plataforma de roteamento e orquestração de modelos e provedores de IA. |
| [Billion Context](https://github.com/ranxianglei/billion-context) | Proxy de compressão incremental de contexto para sessões longas de agentes; intercepta e reescreve tráfego entre cliente e modelo. |

## Pesquisa, web e automação

| Skill / recurso | Descrição |
|---|---|
| [Last30Days](https://github.com/mvanhorn/last30days-skill/tree/main/skills/last30days) | Pesquisa conversas e notícias recentes em múltiplas fontes. |
| [Firecrawl](https://github.com/firecrawl/cli/tree/main/skills/firecrawl-agent) | Raspagem e pesquisa web. |
| [Printing Press](https://github.com/mvanhorn/cli-printing-press/tree/main/skills/printing-press) | Transforma fontes web/API em ferramentas de agentes. |
| [Browser Use](https://github.com/browser-use/browser-use) | Framework para desenvolver agentes que interagem com navegadores. |
| [Reverse API Engineer](https://github.com/kalil0321/reverse-api-engineer) | CLI que captura tráfego de rede do navegador em HAR e gera clientes tipados de APIs HTTP observadas, integrando navegação e modelos configuráveis. |

## Marketing e conteúdo

| Skill / recurso | Descrição |
|---|---|
| [Corey Haines Marketing Skills](https://github.com/coreyhaines31/marketingskills) | SEO, CRO, marketing e growth. |
| [Human Speak](https://github.com/nateherkai/human-speak) | Skill para redigir, auditar e revisar textos com naturalidade, reduzindo padrões de escrita de IA sem apagar a voz do autor. |
| [Humanizer](https://github.com/blader/humanizer) | Skill para identificar e reescrever padrões comuns de escrita de IA, inspirada na lista de sinais da Wikipédia; compatível com Codex. |

## Documentos, apresentações e dados

| Skill / recurso | Descrição |
|---|---|
| [DOCX](https://github.com/anthropics/skills/tree/main/skills/docx) | Documentos Word. |
| [PDF](https://github.com/anthropics/skills/tree/main/skills/pdf) | Arquivos PDF. |
| [PPTX](https://github.com/anthropics/skills/tree/main/skills/pptx) | Apresentações PowerPoint. |
| [XLSX](https://github.com/anthropics/skills/tree/main/skills/xlsx) | Planilhas Excel. |
| [Doc Coauthoring](https://github.com/anthropics/skills/tree/main/skills/doc-coauthoring) | Redação colaborativa de documentos. |
| [Brand Guidelines](https://github.com/anthropics/skills/tree/main/skills/brand-guidelines) | Identidade de marca em materiais. |
| [Internal Comms](https://github.com/anthropics/skills/tree/main/skills/internal-comms) | Comunicados internos e updates. |
| [Deckset Presentation Expert](https://github.com/doudou1337/deckset-claude-skill/tree/main/skills/deckset-presentation-expert) | Slides baseados em Markdown/Deckset. |
| [Data Analysis](https://github.com/anthropics/skills/tree/main/skills/xlsx) | Exploração, transformação e análise de dados tabulares. |
| [Document Skills](https://github.com/anthropics/skills) | Coleção de skills para criação, edição e análise de arquivos de escritório. |
| [Slide Maker](https://github.com/addsumtech/slides_maker) | Skill de geração de apresentações PPTX editáveis com pesquisa de fontes, layouts, gráficos, notas e revisão independente por agentes. |
| [Paper Context Resolver](https://www.skills.sh/lllllllama/rigorpilot-skills/paper-context-resolver) | Localiza evidências complementares para reproduzir artigos científicos, como versões de datasets, splits e protocolos. |

## Ferramentas, documentação e utilitários

| Skill / recurso | Descrição |
|---|---|
| [find-font](https://github.com/rtadewald/skills/blob/main/find-font) | Identificação de fontes com API local e crop de texto. |
| [context7-mcp](https://github.com/rtadewald/skills/blob/main/context7-mcp) | Consulta documentação atualizada de bibliotecas pelo Context7. |
| [REA](https://github.com/morluto/rea) | Análise e engenharia reversa de apps, JavaScript e binários, inclusive via MCP. |
| [Supabase Postgres Best Practices](https://www.skills.sh/supabase/agent-skills/supabase-postgres-best-practices) | Diretrizes oficiais de consultas SQL, índices, schema, pooling, RLS e performance no PostgreSQL. |
