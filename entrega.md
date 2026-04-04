# 🚀 Pitch Deck Template — Solana Hackathon / Submissão

> **Como usar este documento:** Preencha cada seção respondendo às perguntas-guia. As perguntas em *itálico* são orientações — não precisam aparecer na versão final. O objetivo é que você tenha um documento completo antes de montar os slides.

---

## PARTE 1 — PITCH DECK (até 10 slides)

---

### Slide 1 — Capa

**Nome do Projeto:**
> _Qual é o nome da sua solução? Se ainda não tiver, qual seria um nome que capture a essência do projeto?_

**Tagline (1 frase):**
> _Em uma frase, o que o projeto faz? Ex: "A plataforma que transforma X em Y para Z."_

**Nome do time / Organização:**

**Data da submissão:**

---

### Slide 2 — Problema

> _Qual dor você está endereçando? Para quem? Seja específico — evite problemas genéricos. Um bom problema tem um dono claro (persona), uma frequência (acontece todo dia? todo mês?) e uma consequência real (perda de dinheiro, tempo, oportunidade)._

**Qual é o problema central?**

O Brasil é o 5º maior mercado de cripto do mundo, mas a tecnologia ainda é inacessível para a maioria. A jornada de entrada exige seed phrases, jargões técnicos, instalação de carteiras e cadastros complexos em corretoras que, no fim, ainda retêm a custódia dos ativos do usuário. Para quem já vive dentro do WhatsApp, esse atrito é intransponível. Ao mesmo tempo, quem quer diversificar os próprios investimentos para cripto esbarra em uma curva de aprendizado que não deveria existir — o problema não é falta de interesse, é falta de uma porta de entrada decente.

**Quem sofre com esse problema? (Persona)**

O público é amplo mas tem um perfil claro: pessoas entre 20 e 40 anos que já ouviram falar de cripto, têm alguma curiosidade, mas nunca conseguiram dar o primeiro passo porque o processo parecia técnico, arriscado ou burocrático demais. Não são traders nem entusiastas de blockchain — são pessoas comuns que querem guardar uma parte do dinheiro em dólar, fazer uma remessa sem pagar fortuna de taxa ou simplesmente experimentar um investimento diferente. Esse perfil existe no Brasil e em toda a América Latina, onde o WhatsApp já é o principal canal de comunicação do dia a dia.

**Por que esse problema ainda não foi resolvido?**

As corretoras centralizadas resolvem o acesso mas criam novo problema: custodiam os ativos e exigem onboarding burocrático. As carteiras descentralizadas preservam a autonomia mas exigem literacia técnica que o público de massa não tem e não quer ter. O canal que esse público já usa diariamente, o WhatsApp, nunca foi aproveitado como interface financeira não-custodial. A barreira não é técnica: as ferramentas já existem. A barreira é de produto.

**Evidência do problema (dado, citação ou exemplo real):**

O Brasil movimentou **US$ 318,8 bilhões em cripto** entre julho de 2024 e junho de 2025, crescimento de 109,9% em um ano. Mesmo assim, apenas **24% dos brasileiros possuem algum criptoativo** (Sherlock Communications, 2024), e o engajamento nos apps cai 34% após o primeiro acesso (Adjust, 2024). O mercado cresce, mas a experiência expulsa o usuário antes de ele se engajar. Projeções do Mercado Bitcoin estimam que esse número pode chegar a **120 milhões de brasileiros** até 2030, desde que a barreira de entrada seja resolvida.

---

### Slide 3 — Solução

> _Como sua ideia resolve o problema? Seja direto. Descreva o que o produto faz, não como ele funciona por baixo do capô (isso vem depois)._

**O que o produto faz (em 2–3 frases):**

O ZOP leva o ecossistema Solana para dentro do WhatsApp, o app que 147 milhões de brasileiros já usam todo dia. Por meio de um chat com inteligência artificial, o usuário cria carteira, faz transferências em stablecoin e acessa perfis de investimento no ecossistema Solana usando linguagem natural, sem instalar nada, sem seed phrase visível e sem pagar taxas de rede.

**Como o usuário interage com a solução? (fluxo simplificado)**
> _Ex: "O usuário conecta sua carteira → seleciona X → recebe Y em Z segundos."_

1. Usuário manda mensagem para o bot: "quero guardar 200 reais em dólar"
2. O bot confirma os detalhes e abre uma tela de confirmação dentro do próprio WhatsApp
3. Usuário autentica com Face ID ou digital e a transação é executada na Solana em menos de 1 segundo

**Qual é a transformação que o usuário experimenta?**
> _Antes: [situação atual]. Depois: [situação com sua solução]._

- **Antes:** para entrar em cripto, a pessoa precisava criar conta em corretora, passar por verificação de identidade, entender o que é uma seed phrase, descobrir como funciona uma carteira e ainda torcer para não errar nada no processo. A maioria desistia antes de fazer a primeira transação.
- **Depois:** o usuário manda uma mensagem no WhatsApp como manda para qualquer contato. A carteira já existe, as taxas já estão cobertas, e cada transação importante pede só uma digital para confirmar. Cripto virou parte do cotidiano sem que o usuário precise saber que está usando cripto.

---

### Slide 4 — Fit com Solana (Atualizado)

**Quais características da Solana são críticas para o seu projeto?**

| Característica Solana | Como ela habilita sua solução |
|---|---|
| Alta throughput (65k+ TPS) | Suporta a escala massiva do WhatsApp no Brasil sem gargalos em horários comerciais. |
| Baixo custo (~$0.00025) | Permite ao ZOP subsidiar transações, oferecendo uma experiência "Taxa Zero" ao usuário. |
| Tempo de finalidade (~400ms) | Garante que o pagamento seja confirmado no tempo de leitura de uma mensagem no chat. |
| Composabilidade | Integração nativa com Kamino (Rendimento) e Jupiter (Conversão de juros para SOL). |
| Oráculos Rápidos (Pyth) | Converte o saldo de USDC para a moeda nativa (Real) em tempo real com precisão bancária. |

**Quais programas/protocolos Solana você planeja usar ou integrar?**
* **USDC Nativo (SPL Token):** Estabilidade e segurança de lastro para o capital principal do leigo.
* **Kamino Finance:** Protocolo central de liquidez onde o USDC do usuário gera juros automáticos (Yield).
* **Jupiter API:** Motor que converte os juros de USDC gerados no Kamino para SOL de forma invisível.
* **Jito (Native Staking):** Destino final do rendimento, onde o SOL cresce via staking e valorização.
* **P2P.me & MoonPay:** Portas de entrada (On-Ramp). Pix para o dia a dia e Apple Pay/Cartão para conveniência global.
* **Turnkey / Privy (MPC):** Infraestrutura para garantir que a custódia seja partilhada e segura via biometria.

---

### Slide 5 — Mercado

> _Quem são os usuários-alvo? Qual o tamanho da oportunidade? Use a estrutura TAM → SAM → SOM para mostrar que você entende o mercado e está sendo realista._

**Usuário-alvo primário (ICP — Ideal Customer Profile):**

O usuário principal é a pessoa entre 20 e 40 anos que quer diversificar onde guarda e investe o dinheiro, tem curiosidade por cripto, mas não quer ter que estudar blockchain para fazer isso. Ela não precisa entender o que é uma seed phrase, como funciona uma DEX ou o que é gas fee. Ela só precisa de uma interface que já conhece e uma experiência simples o suficiente para não dar medo. O Zop é o primeiro passo dela dentro do ecossistema cripto sem que ela precise saber que está nele.

**TAM — Total Addressable Market:**

O mercado de pagamentos no Brasil movimentou R\$ 99,7 trilhões em 2023 (Demarest), com o setor de pagamentos digitais atingindo R\$ 4,1 trilhões só em transações com cartão em 2024 (Stark Bank). Somado ao volume cripto, o Brasil transacionou US\$ 318,8 bilhões em criptoativos entre julho de 2024 e junho de 2025, quase um terço de toda a atividade da América Latina (BSC News). O TAM considera toda a América Latina como mercado endereçável, dado que o WhatsApp domina a comunicação cotidiana em países como México, Colômbia, Argentina e Chile da mesma forma que no Brasil. O volume endereçável regional por infraestrutura de pagamento e investimento via stablecoin é estimado em mais de R\$ 1 trilhão/ano.

**SAM — Serviceable Addressable Market:**

24% dos brasileiros já possuem algum criptoativo em 2024, ante 14% em 2023 (Exame), mas o engajamento ainda é baixo e a experiência continua quebrando o funil. Esse grupo, somado aos curiosos que nunca completaram o onboarding em corretoras tradicionais, forma uma base de 40 a 50 milhões de pessoas só no Brasil que já têm intenção mas não têm interface. Na América Latina como um todo, esse número ultrapassa 150 milhões de pessoas com acesso a smartphone e WhatsApp ativo.

**SOM — Serviceable Obtainable Market:**

Nos primeiros 12 a 18 meses, o foco é no Brasil: curiosos que já pesquisaram cripto mas não avançaram e usuários indicados organicamente dentro do próprio WhatsApp. A meta realista é 50 mil usuários ativos mensais com volume de R\$ 50 milhões em transações, o que a uma margem média de 0,6% representa R\$ 300 mil de receita recorrente mensal. A expansão para México e Colômbia entra como segunda fase, aproveitando a mesma infraestrutura sem necessidade de reconstruir o produto.

**Referência de dados de mercado (fonte):**

Fontes: Chainalysis (2025), Banco Central do Brasil (2024), Mercado Bitcoin Research (2024), BSC News (2025)

---

### Slide 6 — Modelo de Negócio

> _Como o projeto gera ou captura valor? Um projeto Web3 pode ter receita on-chain (fees, treasury, tokens) e/ou off-chain (SaaS, licenciamento, serviços). Seja claro sobre de onde vem o dinheiro._

**Fonte primária de receita:**

Spread cambial capturado nas conversões entre real e USDC. Toda vez que o usuário deposita via Pix ou saca para sua conta bancária, a plataforma aplica uma margem sobre a cotação do mercado. Para o usuário a operação aparece como gratuita. Na prática ele paga uma taxa que nunca vê, embutida na cotação, ainda assim muito menor do que qualquer corretora ou banco tradicional cobram pelo mesmo serviço.


**Modelo de precificação:**
> _Ex: taxa por transação (X%), assinatura mensal, freemium, token utility, etc._

Taxa por conversão, invisível ao usuário. 0,5% a 0,8% no onramp (Pix para USDC) e 0,3% a 0,5% no offramp (USDC para Pix). Em fases futuras, yield sharing retendo 30% do rendimento gerado pelo saldo alocado em protocolos DeFi como o Jito, repassando 70% ao usuário. Transferências P2P entre usuários Zop são gratuitas e custeadas pelas fees sub-centavo da Solana.

**Quem paga? (payer ≠ usuário?)**
> _Em alguns modelos o usuário e o pagador são pessoas diferentes._

O usuário paga indiretamente via spread cambial, sem perceber que existe uma taxa. Ele compara a cotação com o dólar do Google, vê que a diferença é pequena, e conclui que o serviço é gratuito. Em fases futuras, empresas que integrarem a infraestrutura Zop via API pagam uma mensalidade pelo volume de transações dos seus próprios clientes, num modelo parecido com o da Stripe.

**Unit Economics (estimativas iniciais):**

| Métrica | Estimativa |
|---|---|
| CAC (Custo de Aquisição de Cliente) | R\$20 a R\$60 — crescimento orgânico via indicação, mas com custo real de gestão de comunidade, parcerias e tempo da equipe nos primeiros usuários  |
| LTV (Lifetime Value) | R\$120 a R\$250 — usuário movimentando R\$500/mês com spread médio de 0,6% por 18–24 meses; LTV = R\$500 × 0,6% × 18–24 = R\$54–R\$72/mês de receita × 12–18 meses de retenção |
| Custo por transação | R$0,30 a R$0,60 — inclui LLM (Claude Haiku), WhatsApp Business API, Privy (MPC) e infraestrutura AWS; custo escala com volume  |
| Margem bruta estimada | 40% a 55% — menor que o ideal, mas cresce conforme volume escala e custo fixo dilui; margem % sobe quando CAC dilui e custo unitário de IA/infra cai com negotiating tiers |
| Break-even estimado | ~25 mil usuários ativos com volume médio de R\$600/mês cada, gerando R$\15M/mês de volume × 0,6% spread = R\$90k/mês de receita, cobrindo custos fixos de IA, infra e equipe inicial |
| LTV/CAC ratio| 2,5x a 4x — saudável para fintech inicial; meta é chegar a 4x–6x com automação e escala |

**Papel do token (se houver):**
> _O token é necessário para o modelo funcionar, ou é opcional? Como ele captura valor?_

O Zop **não depende de token** para funcionar e **não planeja lançar um na fase inicial**. Receita vem de spread cambial e yield sharing, não de emissão de ativos. Se houver token no futuro, entraria como mecanismo de governança para usuários com alto volume (voto em parâmetros de spread, programas de fidelidade), não como fonte primária de receita. Isso diferencia o modelo de esquemas Ponzi/pumped tokens e mostra maturidade para banca técnica.

---

### Slide 7 — Diferencial

&emsp; Entendendo a rede e o ecossistema Solana, sabemos que a concorrência não é apenas outras soluções Web3, mas também as alternativas Web2 que as pessoas usam hoje para resolver o mesmo problema. Por isso, é importante mapear tanto os concorrentes diretos, decritos na tabela abaixo, quanto os indiretos, que são tradicionais, como aplicativos de banco, que permitem fazer transações e investimentos diversos.

### Benchmark Comparativo: ZOP vs. Soluções de Entrada (2026)

| Característica | 🟢 **ZOP (Sua Infra)** | 🔵 **Telegram Wallet (Nativo)** | 🟠 **Bipa (App + Pix)** | 🟣 **Corretoras (Binance/Mynt)** |
| :--- | :--- | :--- | :--- | :--- |
| **Interface Principal** | **WhatsApp** (Nativo via Chat e Flows) | Telegram (Mini Apps e Bots) | App Mobile Próprio | App Mobile Complexo |
| **Público-Alvo** | **Leigos com medo de Cripto** (Foco em facilitação) | Usuários de Telegram (Geral/Crypto-natives) | Brasileiros focados em BTC e Pix | Investidores de Varejo e Traders |
| **Custódia e Segurança** | **Não-Custodial (MPC)** + Biometria (FaceID/Digital) | Híbrida (Custodial ou TON Space) | Custodial (Empresa detém as chaves) | Custodial (Empresa detém as chaves) |
| **Blockchain** | **Solana** (USDC Nativo e JitoSOL) | TON Network | Bitcoin (On-chain e Lightning) | Múltiplas Redes (Complexo para leigos) |
| **On-Ramp / Off-Ramp** | **P2P.me** (Pix) + **MoonPay** (Apple/Google Pay) | P2P Interno / Cartão de Crédito | Pix Direto (Foco em Real → BTC) | Pix / TED / Cartão (Fluxo com KYC alto) |
| **Motor de Rendimento** | **Native Staking (Jito)** - "Invisível" ao usuário | Staking de TON (Exige interação manual) | Sem rendimento (Apenas valorização do ativo) | "Earn" (Lending/Empréstimos com taxas) |
| **Diferencial Competitivo** | **Abstração Total:** Linguagem natural e "estilo Pix" no app que o brasileiro já usa. | Integração com ecossistema TON e anúncios no app. | Simplicidade extrema para Bitcoin e integração Pix rápida. | Grande variedade de ativos e liquidez global. |

---

### Análise Técnica do Posicionamento ZOP

**1. O Poder da Abstração MPC para o "Inseguro":**
O seu maior trunfo é que o usuário não precisa saber o que é uma *private key*. No ZOP, a carteira está "partida" entre a infraestrutura e o dispositivo do cliente. Se ele perder o celular, a conta é recuperada via biometria/identidade, e não via uma semente de 12 palavras que gera pânico em quem é leigo.

**2. Linguagem Natural como Interface de Confiança:**
Enquanto as corretoras usam botões de "Trade", "Limit Order" e "Slippage", o ZOP usa: 
> *"Quero colocar 50 reais em dólar pra render."* Isso transforma a barreira tecnológica em uma conversa amigável. A Solana roda no fundo como um "backend invisível", garantindo que a transação seja confirmada antes mesmo do usuário fechar a janela do chat.

**3. Fluxo de Dinheiro (On-Ramp) Descentralizado:**
Ao usar o **P2P.me** para o Pix, você mantém a filosofia da descentralização, mas com a conveniência de um pagamento instantâneo brasileiro. A adição da **MoonPay** (Apple Pay/Google Wallet) atende o público que prefere a conveniência do cartão, cobrindo todas as frentes de entrada de capital.

**4. Staking com Jito como "Caixinha de Rendimento":**
Ao utilizar o **Native Staking da Jito**, você oferece algo que as corretoras penam para explicar: rendimento real on-chain. Para o seu público, isso aparece como "Seu saldo está crescendo", sem que ele precise entender o que é um validador ou MEV.

**5. A Ilusão Perfeita da Moeda Local (UX Invisível):** O usuário nunca lida com jargões, tokens ou cotações complexas. Pelo WhatsApp, ele vê seu saldo e faz transferências usando comandos simples em Reais (ex: "Enviar R$ 50"). A experiência é idêntica à de um app bancário tradicional, removendo o atrito e o medo da Web3.

**6. Motor Invisível em Dólar Digital (USDC):** Por trás do saldo em Reais, o dinheiro real guardado na carteira MPC é o USDC. O backend do ZOP usa oráculos em tempo real (como Pyth) para fazer a matemática instantânea: converte a intenção de "enviar Reais" na quantia exata de dólares, liquidando a transação via Solana em 400 milissegundos sem expor o cliente à volatilidade.

**7. Rendimento Híbrido (Proteção + Upside em SOL):** O capital principal do cliente fica blindado contra quedas de mercado (guardado em USDC) rendendo juros seguros em DeFi. O ZOP coleta automaticamente apenas esses juros gerados e os converte em Solana (SOL) para a "Caixinha" do usuário. Ele ganha o potencial de alta das criptos sem arriscar o seu depósito inicial.

**Resumo da estratégia:**
O ZOP não compete por "quem tem mais tokens", mas por **quem remove mais fricção**. Você está pegando a tecnologia mais robusta da Solana (Jito, MPC, USDC) e "escondendo" ela atrás de uma conversa de WhatsApp para quem hoje tem medo de investir.

---

### Slide 8 — Roadmap Inicial

> _Quais seriam os primeiros passos para validar a ideia? Foque nos próximos 3–6 meses. Mostre que você sabe a diferença entre construir e validar._

**Hipótese central a ser validada:**

Uma pessoa sem nenhum conhecimento técnico de cripto consegue guardar dinheiro em dólar ou fazer uma transferência usando só o WhatsApp, sem precisar de instrução. Se isso for verdade, o que impede a adoção em massa de cripto no Brasil não é cultura nem desinteresse, é ausência de uma interface que o público já domina.

**Marco 0 — Validação do Conceito: Ideathon Superteam Brasil**

- [ ] Apresentar a proposta para banca técnica do ecossistema Solana e coletar feedback qualificado
- [ ] Validar se o modelo não-custodial via MPC é compreendido e aceito como diferencial pelos avaliadores
- [ ] Identificar parceiros de time com perfil técnico para avançar para o hackathon global

**Marco 1 — Construção do MVP: Hackathon Global Solana (semanas 1 a 6)**

- [ ] Bot funcional no WhatsApp criando carteira Solana automaticamente vinculada ao número via Privy
- [ ] Consulta de saldo e transferência P2P de USDC entre números cadastrados
- [ ] Onramp via Pix com conversão para USDC e confirmação biométrica via WhatsApp Flow
- [ ] Arquitetura de mensageria desacoplada do backend desde o início, permitindo migração para Telegram ou SMS caso necessário
- [ ] Fluxo completo rodando em devnet Solana antes de subir para mainnet

**Marco 2 — Primeiros Usuários Reais (semanas 6 a 16)**

- [ ] Lançar para grupo fechado de 50 a 100 pessoas priorizando quem nunca usou cripto
- [ ] Medir taxa de conclusão do onboarding sem suporte e taxa de segunda transação em 7 dias
- [ ] Ativar indicação orgânica dentro do WhatsApp e rastrear CAC real do canal
- [ ] Testar a percepção do produto com usuários da América Latina fora do Brasil para calibrar expansão regional

**Métricas de sucesso do MVP:**

Taxa de conclusão do onboarding acima de 60% sem ajuda. Pelo menos 40% dos usuários fazendo uma segunda transação espontânea em até 7 dias. Custo por transação abaixo de R$ 0,80 mesmo em baixo volume. E ao menos um usuário que nunca tocou em cripto completando uma transferência P2P sem nenhum suporte.

---

### Slide 9 — Time

> _Quem são os integrantes e quais habilidades trazem? Mostre que o time tem os "unfair advantages" para executar esta ideia específica._

**Integrante 1**
- **Nome:**
- **Papel no projeto:**
- **Background relevante:**
- **Por que essa pessoa para esse projeto?**

**Integrante 2**
- **Nome:**
- **Papel no projeto:**
- **Background relevante:**
- **Por que essa pessoa para esse projeto?**

**Integrante 3** _(se houver)_
- **Nome:**
- **Papel no projeto:**
- **Background relevante:**
- **Por que essa pessoa para esse projeto?**

**Lacunas do time (honestidade paga):**
> _O que ainda falta no time? Você precisa de um dev Solana? Um designer? Um especialista de domínio?_


---

### Slide 10 — Call to Action / O que buscamos

> _O que você quer do avaliador, investidor ou parceiro? Seja específico._

**O que estamos buscando:**
- [ ] Mentoria técnica em:
- [ ] Conexão com:
- [ ] Grant / Investimento de:
- [ ] Parceiros de:
- [ ] Primeiros usuários beta

**Contato:**
> _E-mail, Twitter/X, Telegram, GitHub_


---
---

## PARTE 2 — DOCUMENTAÇÃO DE NEGÓCIOS / MERCADO

> Esta seção vai além do pitch. É o material de apoio que torna sua solução bem fundamentada — útil para due diligence, conversas com investidores e para você mesmo não perder o fio da meada.

---

### 2.1 — Problem Statement Detalhado

> _Versão expandida do Slide 2. Aprofunde a dor, com dados primários e secundários._

**Contexto do problema:**


**Evidências quantitativas:**
> _Pesquisas, relatórios, dados públicos que comprovam o problema._

| Dado | Fonte | Ano |
|---|---|---|
| | | |
| | | |

**Jobs To Be Done (JTBD):**
> _O que o usuário está tentando realizar quando "contrata" sua solução?_

- Functional job:
- Emotional job:
- Social job:

**Dores principais (pains):**
1.
2.
3.

**Ganhos desejados (gains):**
1.
2.
3.

---

### 2.2 — Personas

> _Descreva com profundidade os perfis de usuário que você está atendendo._

#### Persona Primária

| Campo | Descrição |
|---|---|
| Nome fictício | |
| Idade / Perfil | |
| Ocupação | |
| Nível de familiaridade com crypto/Web3 | |
| Plataformas que usa | |
| Principal dor relacionada ao problema | |
| O que ela ganha com sua solução | |
| Possível objeção ao produto | |

#### Persona Secundária _(se houver)_

| Campo | Descrição |
|---|---|
| Nome fictício | |
| Ocupação | |
| Relação com a persona primária | |
| Papel no fluxo do produto | |

---

### 2.3 — Análise de Mercado Detalhada

**Segmentação de mercado:**
> _Quais são os sub-segmentos dentro do seu mercado? Você está atacando qual primeiro e por quê?_


**Tendências macro favoráveis:**
> _Quais tendências de mercado, regulação, tecnologia ou comportamento jogam a favor da sua solução?_

1.
2.
3.

**Riscos de mercado:**
> _O que poderia fazer o mercado não se desenvolver como esperado?_

1.
2.
3.

**Dados do ecossistema Solana (relevante para o contexto):**
> _Ex: TVL, número de wallets ativas, volume de DEX, usuários de dApps._


---

### 2.4 — Análise Competitiva Detalhada

**Mapa de concorrentes:**

| Solução | Tipo | Pontos Fortes | Pontos Fracos | Blockchain/Plataforma | Tração |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

**Seu posicionamento:**
> _Em que quadrante do mercado você se posiciona? (ex: baixo custo + alta customização, ou premium + simplicidade)_


**Barreiras de entrada que você está construindo:**
> _O que torna sua posição defensável no longo prazo?_


---

### 2.5 — Modelo de Negócio Canvas (Simplificado)

| Bloco | Conteúdo |
|---|---|
| **Proposta de Valor** | |
| **Segmentos de Clientes** | |
| **Canais de Distribuição** | |
| **Relacionamento com Clientes** | |
| **Fontes de Receita** | |
| **Recursos-Chave** | |
| **Atividades-Chave** | |
| **Parceiros-Chave** | |
| **Estrutura de Custos** | |

---

### 2.6 — Go-to-Market (GTM)

**Estratégia de entrada no mercado:**
> _Como você vai chegar nos primeiros 100 usuários? E nos próximos 1.000?_


**Canal primário de aquisição:**
> _Ex: comunidades no Discord/Telegram, Twitter/X, parcerias com protocolos, eventos presenciais, conteúdo, etc._


**Estratégia de retenção:**
> _O que faz o usuário voltar? Network effects, utilidade recorrente, incentivos?_


**Possíveis parcerias estratégicas:**

| Parceiro potencial | Tipo de parceria | Benefício mútuo |
|---|---|---|
| | | |
| | | |

---

### 2.7 — Tokenomics (se aplicável)

> _Preencha apenas se o projeto tiver um token nativo._

**Utilidade do token:**
> _Por que o token existe? O que ele habilita que não seria possível sem ele?_


**Distribuição inicial (%):**

| Destinatário | % | Vesting |
|---|---|---|
| Time | | |
| Investidores | | |
| Comunidade / Airdrop | | |
| Treasury / Ecosistema | | |
| Reserva / Liquidez | | |

**Mecanismo de captura de valor:**
> _Como o token se valoriza com o crescimento do protocolo?_


**Mecanismo antiinflacionário (se houver):**
> _Burn, staking, recompra?_


---

### 2.8 — Riscos e Mitigações

> _Todo projeto tem riscos. Mostrá-los com seriedade aumenta a credibilidade._

| Risco | Probabilidade (A/M/B) | Impacto (A/M/B) | Mitigação |
|---|---|---|---|
| Risco técnico: | | | |
| Risco de mercado: | | | |
| Risco regulatório: | | | |
| Risco de execução: | | | |
| Risco de concorrência: | | | |

---

### 2.9 — Métricas e KPIs

> _Quais números você vai acompanhar para saber se está no caminho certo?_

**Métricas de produto (North Star):**
- North Star Metric:
- Métricas de suporte:

**Métricas de negócio:**

| Métrica | Meta — Mês 1 | Meta — Mês 3 | Meta — Mês 6 |
|---|---|---|---|
| Usuários ativos | | | |
| Transações / Volume | | | |
| Receita | | | |
| Retenção (D7 / D30) | | | |
| NPS | | | |

---

### 2.10 — Necessidades de Capital (se aplicável)

**Quanto você precisa e para quê:**

| Uso dos recursos | Valor estimado | % do total |
|---|---|---|
| Desenvolvimento de produto | | |
| Crescimento / Marketing | | |
| Infraestrutura / Operações | | |
| Pesquisa / Auditoria | | |
| Reserva | | |
| **Total** | | **100%** |

**Tipo de capital buscado:**
- [ ] Grant (Solana Foundation, Superteam, etc.)
- [ ] Acelerador / Hackathon prize
- [ ] Investimento anjo
- [ ] Seed round
- [ ] Outro:

**Runway esperado com esse capital:**

---

## ✅ Checklist de Qualidade — Antes de Submeter

### Pitch Deck
- [ ] O problema tem uma persona clara e evidência concreta
- [ ] A solução é descrita em linguagem simples (alguém de fora entende)
- [ ] O fit com Solana é específico, não genérico
- [ ] TAM/SAM/SOM têm fontes ou metodologia de cálculo
- [ ] O modelo de negócio responde "quem paga e quanto"
- [ ] A análise competitiva é honesta (reconhece fraquezas)
- [ ] O roadmap tem marcos mensuráveis, não apenas tarefas
- [ ] Cada membro do time tem um "por que essa pessoa" claro

### Documentação de Apoio
- [ ] As personas têm profundidade suficiente para guiar decisões de produto
- [ ] O GTM tem um canal primário definido (não "vamos fazer tudo")
- [ ] Os riscos foram listados com mitigações realistas
- [ ] As métricas incluem uma North Star Metric clara
- [ ] Se houver token: a utilidade é real, não cosmética

---

*Template elaborado para submissões em ecossistema Solana. Adapte conforme o contexto específico do hackathon ou programa de aceleração.*