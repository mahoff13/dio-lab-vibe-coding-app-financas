# 💸 Desafio de Projeto - App de Organização de Finanças Pessoais com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
PRD - Agente Financeiro Inteligente

Visão do Produto

Criar uma aplicação de finanças pessoais baseada em conversação que permita aos utilizadores gerir receitas, despesas, gastos fixos e objetivos financeiros através de linguagem natural.

A aplicação deverá funcionar como um Agente Financeiro Inteligente, simplificando o controlo financeiro, oferecendo insights personalizados e incentivando bons hábitos através de gamificação.

---

Problema

Muitas pessoas abandonam o controlo financeiro porque:

- O registo manual de despesas é trabalhoso.
- Aplicações tradicionais são complexas para iniciantes.
- Existem demasiadas categorias e gráficos difíceis de interpretar.
- Falta acompanhamento personalizado.
- Os utilizadores não sabem exatamente como melhorar a sua situação financeira.

Como consequência, acabam por perder o controlo do orçamento, acumular gastos desnecessários e atrasar objetivos financeiros.

---

Público-Alvo

Perfil Principal

Pessoas entre 18 e 45 anos que desejam organizar as finanças de forma simples e prática.

Características

- Não utilizam planilhas regularmente.
- Procuram uma solução fácil de manter.
- Querem aprender a gerir melhor o dinheiro.
- Preferem interações simples por chat.
- Desejam poupar dinheiro e atingir objetivos financeiros.

---

Proposta de Valor

Organize sua vida financeira conversando com um Agente Financeiro Inteligente. Registre receitas, despesas e contas fixas em segundos, acompanhe metas financeiras, melhore seu Score Financeiro e receba recomendações personalizadas para economizar mais e alcançar seus objetivos.

---

Objetivos do MVP

Objetivos do Negócio

- Validar o interesse numa experiência financeira conversacional.
- Testar a aceitação de recomendações geradas por IA.
- Medir o impacto da gamificação na retenção dos utilizadores.

Objetivos do Utilizador

- Registar movimentações financeiras em menos de 10 segundos.
- Compreender para onde o dinheiro está a ser direcionado.
- Organizar receitas e despesas sem esforço.
- Acompanhar metas financeiras.
- Melhorar hábitos financeiros de forma gradual.

---

Moeda Padrão

A aplicação deverá utilizar exclusivamente o Real Brasileiro (BRL) como moeda padrão.

Formato monetário:

R$ 1.234,56

Todas as funcionalidades deverão utilizar BRL:

- Receitas
- Despesas
- Gastos fixos
- Metas
- Relatórios
- Dashboard
- Score Financeiro

A opção para múltiplas moedas ficará para versões futuras.

---

Funcionalidades-Chave

1. Registro de Receitas e Despesas por Chat

O utilizador deverá conversar naturalmente com o sistema.

Exemplos

- Gastei R$ 45 no almoço.
- Paguei R$ 180 de energia.
- Recebi R$ 4.500 de salário.
- Ganhei R$ 800 como freelancer.

A IA deverá identificar automaticamente:

- Tipo (Receita ou Despesa)
- Valor
- Categoria
- Data
- Descrição

---

2. Classificação Automática

Categorias de Despesas

- Alimentação
- Transporte
- Habitação
- Saúde
- Educação
- Lazer
- Compras
- Streaming
- Serviços
- Outros

Categorias de Receitas

- Salário
- Freelance
- Investimentos
- Vendas
- Reembolsos
- Bônus
- Outros

---

3. Gastos Fixos e Assinaturas

Permitir o cadastro de despesas recorrentes.

Exemplos

- Pago R$ 120 de internet todo dia 10.
- Minha conta de energia é cerca de R$ 180 por mês.
- Tenho Netflix de R$ 55 por mês.
- Pago R$ 39,90 de Spotify.

Informações Armazenadas

- Nome da despesa
- Categoria
- Valor
- Frequência
- Data de vencimento
- Status

Frequências

- Semanal
- Quinzenal
- Mensal
- Anual

Categorias de Gastos Fixos

Moradia

- Aluguel
- Condomínio
- IPTU

Utilidades

- Energia
- Água
- Gás

Telecomunicações

- Internet
- Plano de telemóvel

Streaming

- Netflix
- Spotify
- Disney+
- Amazon Prime
- Max
- YouTube Premium

Outros

- Academia
- Escola
- Seguro
- Empréstimos
- Financiamentos

---

4. Metas Financeiras

O utilizador poderá criar metas como:

- Poupar R$ 5.000
- Montar fundo de emergência
- Juntar R$ 10.000 para uma viagem
- Comprar um carro

Dados da Meta

- Nome
- Valor objetivo
- Valor atual
- Data alvo
- Percentagem de conclusão

---

5. Agente Financeiro Inteligente

O sistema deverá atuar como um consultor financeiro virtual.

Responsabilidades

- Analisar gastos
- Identificar excessos
- Gerar recomendações
- Incentivar hábitos saudáveis
- Explicar o Score Financeiro
- Sugerir melhorias

Exemplos

- Seus gastos com alimentação aumentaram 18% este mês.
- Você possui R$ 420 em assinaturas recorrentes.
- Se reduzir R$ 10 por dia em entregas, poderá poupar R$ 300 por mês.

---

6. Score Financeiro e Gamificação

Objetivo

Ajudar o utilizador a visualizar a evolução da sua saúde financeira através de uma pontuação simples.

Escala

Score de 0 a 100.

| Score | Nível |
|---------|---------|
| 0 a 39 | Atenção |
| 40 a 59 | Em Evolução |
| 60 a 79 | Saudável |
| 80 a 100 | Excelente |

Critérios de Cálculo

Controle Financeiro (25%)

- Registro consistente de movimentações.

Taxa de Poupança (25%)

- Percentagem da renda poupada.

Metas Financeiras (20%)

- Criação e progresso em metas.

Gestão de Gastos Fixos (15%)

- Percentual da renda comprometido.

Consistência de Uso (15%)

- Frequência de utilização da aplicação.

Feedback do Agente

- Seu Score aumentou 6 pontos esta semana.
- Você está próximo do nível Excelente.
- Reduzir despesas recorrentes pode aumentar seu score.

---

Sistema de Conquistas

Primeiros Passos

- Primeira Receita
- Primeira Despesa
- Primeira Meta
- Primeira Conta Fixa

Organização

- 7 Dias Consecutivos
- 30 Dias Consecutivos
- 100 Movimentações
- Todas as Contas Cadastradas

Economia

- Primeiros R$ 500 Poupados
- Primeiros R$ 1.000 Poupados
- Primeira Meta Concluída
- Taxa de Poupança Superior a 20%

Excelência Financeira

- Score acima de 70
- Score acima de 85
- Score acima de 95
- Três Meses de Evolução Contínua

---

Dashboard

Cartão Principal

Saúde Financeira

Exibir:

- Score Financeiro
- Nível Atual
- Variação do Score
- Próxima Conquista
- Recomendações do Agente

Resumo Financeiro

- Receitas do mês
- Despesas do mês
- Gastos fixos
- Saldo disponível
- Taxa de poupança

Indicadores

- Percentual da renda comprometido
- Total de assinaturas
- Gastos por categoria
- Progresso de metas

Gráficos

- Receitas vs Despesas
- Gastos Fixos vs Variáveis
- Evolução do Saldo
- Distribuição por Categoria

---

Calendário Financeiro

Mostrar próximos compromissos financeiros.

Exemplo

- 05/11 - Energia - R$ 180
- 08/11 - Spotify - R$ 21,90
- 10/11 - Internet - R$ 120
- 15/11 - Netflix - R$ 55,90

Objetivos:

- Evitar esquecimentos
- Melhorar o planeamento financeiro
- Antecipar gastos futuros

---

Telas do MVP

Tela 1 - Onboarding

- Boas-vindas
- Criação de conta
- Definição da primeira meta
- Configuração inicial

Tela 2 - Chat Principal

- Conversa com o Agente Financeiro
- Sugestões rápidas
- Registro de movimentações

Tela 3 - Dashboard

- Saúde Financeira
- Indicadores financeiros
- Resumo mensal

Tela 4 - Histórico

- Receitas
- Despesas
- Filtros
- Pesquisa

Tela 5 - Gastos Fixos

- Lista de contas
- Assinaturas
- Próximos vencimentos

Tela 6 - Metas Financeiras

- Lista de metas
- Evolução
- Previsão de conclusão

Tela 7 - Conquistas

- Score Financeiro
- Conquistas desbloqueadas
- Histórico de evolução

---

Modelo de Dados

Usuário

```json
{
  "id": "string",
  "nome": "string",
  "email": "string"
}
```

Transação

```json
{
  "id": "string",
  "tipo": "receita",
  "valor": 4500,
  "categoria": "Salário",
  "descricao": "Salário Outubro",
  "data": "2026-10-01"
}
```

Gasto Fixo

```json
{
  "id": "string",
  "nome": "Netflix",
  "valor": 55.90,
  "frequencia": "mensal",
  "diaVencimento": 15,
  "categoria": "Streaming",
  "ativo": true
}
```

Meta

```json
{
  "id": "string",
  "titulo": "Viagem",
  "valorObjetivo": 10000,
  "valorAtual": 3200
}
```

Score Financeiro

```json
{
  "usuarioId": "123",
  "score": 78,
  "nivel": "Saudável",
  "ultimaAtualizacao": "2026-10-01"
}
```

---

Métricas de Sucesso

MVP

- Retenção após 7 dias superior a 60%
- Mais de 70% dos utilizadores registando movimentações sem ajuda
- Média mínima de 10 transações por utilizador no primeiro mês
- Pelo menos uma meta criada por utilizador ativo
- Utilização semanal do Score Financeiro
- Satisfação do utilizador acima de 4/5

---

Validação Inicial

Hipótese Principal

Os utilizadores preferem gerir as finanças através de conversação em linguagem natural do que através de formulários tradicionais.

Grupo de Teste

20 a 50 utilizadores.

Dados a Coletar

- Facilidade de utilização
- Frequência de uso
- Precisão da classificação automática
- Interesse pelas recomendações da IA
- Impacto do Score Financeiro na motivação

Critérios de Validação

- Mais de 60% retornam após 7 dias.
- Mais de 70% registam uma transação sem ajuda.
- Mais de 50% acompanham regularmente o Score Financeiro.
- Mais de 70% consideram a aplicação fácil de usar.

---

Prompt para Lovable

Crie uma aplicação web responsiva de finanças pessoais baseada em conversação, mobile-first e focada em utilizadores iniciantes. A aplicação deve utilizar Real Brasileiro (R$) como moeda padrão e permitir o registo de receitas, despesas e gastos fixos através de linguagem natural. A IA deve identificar automaticamente tipo, valor, categoria, descrição e data das transações. O sistema deve incluir um Agente Financeiro Inteligente capaz de fornecer insights personalizados, recomendações de economia e acompanhamento financeiro. Inclua dashboard com resumo financeiro, score financeiro de 0 a 100, sistema de gamificação com conquistas, gestão de metas financeiras, gestão de contas recorrentes, calendário financeiro, histórico de transações e autenticação. O design deve ser moderno, amigável, educativo e com forte foco em simplicidade, retenção e engajamento. O Score Financeiro deve ser um elemento central da experiência do utilizador.
```

Depois de preencher o modelo, use o Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable. A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

> [!TIP]
> Se preferir, você pode fazer tudo com o **Copilot**. O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

- Seu **prompt final** (PRD);  
- Prints ou pequenos vídeos das interações com a IA;  
- Um resumo do que o seu **App de Finanças Pessoais** faz;  
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?  
  - O que não funcionou como o esperado?  
  - O que aprendeu sobre conversar com IAs?

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
