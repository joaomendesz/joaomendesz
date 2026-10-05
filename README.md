<div align="center">

# João Passos

**Software útil, local-first e construído para resolver problemas reais.**

Aplicações desktop, mobile e web · Automação · Integrações · Experiência de produto

[GitHub](https://github.com/joaomendesz) · Brasil

</div>

---

## Sobre mim

Desenvolvo produtos que transformam tarefas confusas em fluxos simples e explicáveis. Meu trabalho recente está concentrado em aplicações desktop para Windows, ferramentas de automação, monitoramento local, integrações com APIs e experiências mobile.

Gosto de explorar uma ideia desde o problema até uma solução utilizável: arquitetura, interface, persistência, segurança, testes, documentação e distribuição. Tenho interesse especial em software que respeita a privacidade do usuário, funciona localmente e apresenta informações de forma clara.

```text
foco atual  aplicações desktop · automação · ferramentas local-first
interesses  arquitetura de software · IA aplicada · experiência de produto
princípio   construir menos ruído e mais utilidade
```

## Projetos em destaque

### [PC Migration Assistant](https://github.com/joaomendesz/PC-Migration-Assistant)

Aplicação desktop para registrar o ambiente de software de um computador antes da formatação e ajudar a reconstruí-lo depois.

- Lê programas instalados pelo Registro do Windows.
- Detecta pacotes disponíveis no Winget e relaciona os resultados por score.
- Cria snapshots portáteis `.pcma` com manifestos e checksums SHA-256.
- Valida, importa e compara snapshots com o estado atual da máquina.
- Mantém operações privilegiadas isoladas no processo principal do Electron.
- Possui testes para parsing, normalização, integridade e comparação de dados.

`Electron` `React` `TypeScript` `Tailwind CSS` `Zod` `Vitest` `Winget`

### [WhyIsMyPCSlow](https://github.com/joaomendesz/WhyIsMyPCSlow---Diagnostico-Local-de-PC-Lento-para-Windows)

Diagnóstico local de desempenho para Windows 10 e 11. Em vez de mostrar apenas métricas, o aplicativo correlaciona os dados e explica por que o computador pode estar lento.

- Monitora CPU, memória, armazenamento, disco e processos em tempo real.
- Executa um motor determinístico com regras de diagnóstico explicáveis.
- Apresenta impacto, confiança, evidências e recomendações para cada resultado.
- Mantém histórico local das análises e amostras em SQLite.
- Gera linhas do tempo e relatórios exportáveis em Markdown e HTML.
- Não promete “otimização mágica”: observa, correlaciona, diagnostica e explica.

`Electron` `React` `TypeScript` `Zustand` `Recharts` `SQLite` `Vitest`

### [ScanPrice](https://github.com/joaomendesz/Scanner-de-Produtos-para-OLX)

Scanner de preços para classificados brasileiros, criado para acompanhar anúncios e avisar quando uma oportunidade atende aos critérios definidos.

- Monitora a OLX e páginas personalizadas em intervalos programados.
- Aceita preço-alvo, preço-teto e palavras-chave de exclusão.
- Permite cadastrar sites por meio de seletores CSS.
- Envia notificações por webhook do Discord e bot do Telegram.
- Reúne produtos, alertas recentes e deal score em um dashboard web.

`Python` `Flask` `SQLAlchemy` `APScheduler` `Beautiful Soup` `Bootstrap`

### [Poke Idle World — Multi-Telas](https://github.com/joaomendesz/Poke-Idle-World-Multi-Telas)

Aplicação desktop para organizar várias contas do Poke Idle World em uma única janela, mantendo cada sessão em um perfil separado.

- Exibe até quatro navegadores com layouts 2×2, vertical ou 1+3.
- Permite destacar, minimizar, restaurar e silenciar cada tela individualmente.
- Preserva cookies e sessões em perfis isolados por conta.
- Integra uma barra lateral com ferramentas auxiliares do jogo.
- Oferece temas claro e escuro e restauração automática dos layouts.

`Python` `PyQt6` `Qt WebEngine`

### [Platina](https://github.com/joaomendesz/platina_app)

Aplicativo mobile para acompanhar conquistas da Steam e conectar jogadores que buscam completar seus jogos.

- Integra biblioteca, perfil e conquistas reais pela Steam Web API.
- Usa autenticação Steam OpenID com retorno por deep link.
- Oferece guias por conquista e guias completos de jogos.
- Inclui feed social, perfis públicos, seguidores, curtidas e comentários.
- Possui modo convidado e internacionalização em português e inglês.
- Armazena dados no Supabase com PostgreSQL, RLS e Edge Functions.

`Flutter` `Dart` `Riverpod` `GoRouter` `Supabase` `PostgreSQL` `Steam API`

## Outros projetos

| Projeto | Descrição | Tecnologias |
| --- | --- | --- |
| [Bet Analyzer](https://github.com/joaomendesz/betanalyzer) | Interface em evolução para analisar probabilidades e dados de partidas de League of Legends, Counter-Strike 2 e Valorant. [Ver demonstração](https://betanalyzer-ivory.vercel.app). | HTML, CSS, JavaScript |
| [Linktree](https://github.com/joaomendesz/linktree) | Página pessoal compacta para reunir links em um único endereço. [Ver demonstração](https://linktree-nu-two.vercel.app). | HTML, CSS, JavaScript |
| [CountApp](https://github.com/joaomendesz/CountApp) | Exercício colaborativo de contador para praticar os fundamentos da web. | HTML, CSS, JavaScript |

## Stack

| Área | Tecnologias |
| --- | --- |
| Linguagens | TypeScript, JavaScript, Python, Dart, SQL, HTML e CSS |
| Frontend | React, Flutter, Tailwind CSS, Bootstrap e interfaces responsivas |
| Desktop | Electron, PyQt6, Qt WebEngine e integração com Windows |
| Backend e dados | Flask, SQLite, PostgreSQL, Supabase e APIs REST |
| Automação e integrações | Winget, Registro do Windows, web scraping, Discord, Telegram e Steam API |
| Qualidade | Tipagem estática, validação com Zod, Vitest, ESLint e documentação técnica |

## Como penso software

- **Problema antes da tecnologia:** a stack deve servir ao fluxo do usuário.
- **Local-first quando faz sentido:** dados pessoais permanecem na máquina por padrão.
- **Resultados explicáveis:** diagnósticos precisam mostrar evidências, não apenas conclusões.
- **Limites de segurança claros:** interface e operações privilegiadas devem ficar separadas.
- **Evolução verificável:** tipos, validações e testes reduzem regressões durante o crescimento.
- **Documentação como parte do produto:** instalar, usar e contribuir devem ser tarefas previsíveis.

## Atualmente explorando

- Aplicações desktop seguras com Electron e TypeScript.
- Diagnósticos locais baseados em regras, evidências e correlação de métricas.
- Automação de fluxos do Windows e integração com ferramentas do sistema.
- Produtos mobile com Flutter e serviços de backend gerenciados.
- Uso prático de IA e prompts para acelerar pesquisa, prototipagem e desenvolvimento.

## Contato

Para acompanhar meus projetos, trocar ideias ou conversar sobre uma colaboração:

- GitHub: [@joaomendesz](https://github.com/joaomendesz)
- X / Twitter: [@JoakMendes](https://x.com/JoakMendes)

<div align="center">

<sub>Construindo ferramentas pequenas o bastante para serem simples e úteis o bastante para fazer diferença.</sub>

</div>
