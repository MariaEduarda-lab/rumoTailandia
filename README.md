# rumoTailandia

Nome do Projeto: ZAPI - Infraestrutura Solana via WhatsApp

* O Problema: A adoção em massa da Web3 esbarra em uma jornada de usuário difícil para pessoas comuns, exigindo lidar com jargões técnicos, seed phrases e taxas de rede. O brasileiro médio já vive dentro do WhatsApp (147 milhões de usuários). Exigir que ele saia do seu ambiente nativo para usar um app descentralizado destrói o funil de conversão logo no início.

* A Solução: O ZAPI usa o WhatsApp como a única interface de interação com a blockchain. Através de um bot, o usuário faz gestão da carteira e transferências de stablecoins (USDC) usando apenas comandos em linguagem natural. É uma solução non-custodial (via MPC) e extremamente segura, exigindo confirmação biométrica (Face ID/Digital) via WhatsApp Flows para transações críticas.

* Por que só funcionaria na Solana: A Solana é o único ecossistema que viabiliza essa arquitetura por atuar como um backend invisível perfeito. Ela oferece:
- Finalidade de transação em ~400ms (essencial para pagamentos instantâneos).
- Taxas sub-centavo, permitindo subsidiar os custos e oferecer "taxa zero".
- USDC emitido nativamente pela Circle (sem risco de bridges).

* Mercado: Estamos atacando um TAM de R$ 2,3 trilhões/ano (mercado de remessas e pagamentos digitais no Brasil). Nossos focos principais são os pequenos comércios B2B (economia agressiva em taxas de maquininhas para os ~14 milhões de MEIs) e remessas/poupança em dólar B2C.

* Modelo de Negócios: Experiência "taxa zero" para o usuário final. A monetização é invisível, capturando receita primariamente através de um spread (0,5 a 0,8%) no onramp e offramp de Pix para USDC, idêntico ao modelo de corretoras de câmbio.

* O Grande Diferencial: Distribuição. Bots de transação já existem no Telegram, mas focam em um público de ~950 mil usuários já nativos em cripto. O WhatsApp tem 147 milhões de brasileiros leigos financeiramente. Nós não competimos com os bots do Telegram; o ZAPI serve o mercado virgem que eles nunca vão alcançar.
