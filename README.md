# IA agêntica: da ideia à operação

Apresentação interativa sobre **IBM watsonx Orchestrate + IBM Bob**, construída como um **único arquivo HTML** (sem dependências, sem build, sem servidor). Abre direto no navegador e funciona offline.

> Tema: como construir, conectar e governar agentes de IA para transformar trabalho em resultados mensuráveis.

## Visão geral

- **37 slides** em português (pt-BR), com notas do apresentador em cada um
- **3 roteiros** selecionáveis no topo da tela:

| Roteiro | Duração | Conteúdo |
|---|---|---|
| Executiva | 20 min | Cenário de mercado, valor/ROI, Marketplace, IBM Bob, governança e casos de uso |
| Técnica | 40 min | Arquitetura, control plane, identidade, AI Gateway, AgentOps e piloto |
| Total | 60 min | Bloco executivo seguido do aprofundamento técnico |

## Como usar

### Localmente

1. Baixe o arquivo `apresentacao_ibm_watsonx_orchestrate.html`
2. Abra com um duplo clique (Chrome, Edge, Firefox ou Safari atuais)

### Publicar no GitHub Pages

1. Renomeie o arquivo para `index.html` e deixe na raiz do repositório
2. No repositório: **Settings → Pages → Build and deployment → Deploy from a branch**
3. Escolha a branch `main`, pasta `/ (root)` e salve
4. O site fica em `https://SEU_USUARIO.github.io/NOME_DO_REPO/`

## Navegação

| Tecla | Ação |
|---|---|
| `→` / `PageDown` / `Espaço` | Próximo slide |
| `←` / `PageUp` | Slide anterior |
| `Home` / `End` | Primeiro / último slide |
| `N` | Mostrar ou ocultar notas do apresentador |
| `Esc` | Fechar janelas, sair do modo foco |

Também é possível clicar nos tópicos da barra lateral ou deslizar em telas touch.

## Recursos do editor embutido

Tudo é feito pela barra superior, sem editar o código:

- **✎ Editar textos:** edita blocos de texto diretamente nos slides
- **▧ Inserir imagem:** clique em qualquer card ou área para inserir uma imagem (logos, capturas de tela). Recomendado até 12 MB
- **▶＋ Página de demo:** cria um slide com vídeo por link (YouTube, Vimeo, Google Drive, MP4/WebM direto) ou arquivo local (recomendado até 150 MB)
- **▣＋ Página de cases:** cria um slide com dois cases lado a lado, cada um com logo e texto
- **↕ Ordenar slides:** reordena por arrastar ou setas e oculta slides sem apagá-los
- **✦ Editar ícones:** troca o ícone e a cor de cada card
- **🎨 Cores:** personaliza a paleta (principal, secundária, apoio e fundo)
- **◱ Modo foco:** esconde as barras para apresentar
- **Notas / Tela cheia:** notas do apresentador e fullscreen
- **↓ Exportar HTML:** baixa uma cópia com todas as edições, imagens e vídeos locais embutidos (`apresentacao_ibm_watsonx_orchestrate_editada.html`)

> **Importante:** as edições ficam apenas na página aberta. Para guardá-las, use **Exportar HTML** e substitua o arquivo do repositório pela versão exportada.

## Estrutura de conteúdo

**Bloco executivo (slides 1–16)**
Abertura · Agenda · Cenário em números · Empresas com agentes · O iceberg dos agentes · Introdução ao Orchestrate · ROI e valor · Como construir agentes · Marketplace · Construção com IBM Bob · Funções e integrações · Governança e observabilidade · watsonx.governance · Governance define; Orchestrate aplica · Casos de uso · Resumo e próximos passos

**Bloco técnico (slides 17–36)**
Visão técnica · Agenda técnica · Arquitetura do control plane · Arquitetura geral · Ciclo de vida do agente · Padrões de projeto · Tools e connections · Langflow, ADK e padrões abertos · Marketplace técnico · Identidade e autorização · AI Gateway · AgentOps (build-time, runtime, analytics) · Ciclo fechado com watsonx.governance · Implantação e operação · Arquitetura candidata para piloto · Build with Bob técnico · Roteiro de demo · Checklist do piloto

**Encerramento (slide 37):** Obrigado

## Detalhes técnicos

- HTML + CSS + JavaScript puro, em um só arquivo
- Diagramas e ilustrações em SVG inline, com animações leves (respeita `prefers-reduced-motion`)
- Layout responsivo: ajusta densidade dos slides conforme a altura da tela e permite rolagem horizontal dos diagramas em telas pequenas
- Tipografia: IBM Plex Sans, com fallback para Helvetica Neue/Arial (não requer fonte instalada)
- Tema em variáveis CSS (`--primary`, `--ibm`, `--purple`), inspirado no IBM Carbon Design System

## Observações sobre o conteúdo

- Estatísticas de mercado e ROI (Gartner, IDC, Gravitee, EY, IBM, Futurum Group) são **referências do material-fonte**, não verdades universais nem garantias de resultado.
- Os casos de uso e a arquitetura de piloto são **hipóteses de descoberta** a validar com as áreas envolvidas.
- Diagramas de arquitetura são conceituais; protocolos, produtos e disponibilidade de recursos devem ser confirmados no ambiente-alvo.
- Logos e marcas de terceiros inseridos pelo editor devem ter uso autorizado.

## Licença e uso

Material de discussão para apresentações. Produtos e marcas citados pertencem aos seus respectivos titulares. Defina aqui a licença ou as restrições de uso e compartilhamento que se aplicam ao seu caso.
