# 💸 App de Organização de Finanças Pessoais Thaís com Vibe Coding

PRD refinado no Copilot Web:

´´´´´´markdown
Contexto
O objetivo é ajudar usuários iniciantes a organizarem suas finanças de forma simples, sem planilhas complexas ou formulários extensos.
A principal proposta de valor é:
"Controlar as finanças conversando."
O usuário deve conseguir registrar receitas, despesas, consultar relatórios e acompanhar metas financeiras apenas através de mensagens em linguagem natural.
Exemplos de mensagens:

- "Gastei R$ 42 no almoço."
- "Recebi meu salário de R$ 4.500."
- "Paguei R$ 120 de internet."
- "Quero guardar R$ 300 por mês para uma viagem."
- "Quanto gastei com alimentação este mês?"


Público-Alvo
Pessoas entre 20 e 45 anos que:

- Desejam organizar suas finanças.
- Nunca conseguiram manter o hábito de usar aplicativos financeiros.
- Não gostam de preencher planilhas.
- Procuram uma experiência simples e intuitiva.


Objetivos do Produto
Permitir que o usuário:

- Registre receitas e despesas através de conversa.
- Receba categorização automática das movimentações.
- Visualize sua situação financeira rapidamente.
- Defina metas financeiras.
- Receba recomendações de economia personalizadas.
- Entenda seus hábitos financeiros sem conhecimento técnico.


Funcionalidades do MVP
1. Chat Financeiro Inteligente
Tela principal baseada em conversa.
A IA deve interpretar mensagens em português do Brasil e extrair automaticamente:

- Valor
- Tipo da movimentação
- Categoria
- Data
- Descrição
Exemplo:
Mensagem: "Abasteci o carro hoje e gastei R$ 180."
Resultado:

- Tipo: Despesa
- Categoria: Transporte
- Valor: R$ 180
- Data: Hoje
A IA deve confirmar o registro de forma amigável.


2. Classificação Automática
Categorias padrão:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Salário
- Renda Extra
- Outros
Permitir futura personalização de categorias.


3. Dashboard Financeiro
Criar uma tela visual simples contendo:

- Saldo atual
- Receitas do mês
- Despesas do mês
- Economia acumulada
- Gastos por categoria
- Evolução financeira mensal
Utilizar gráficos claros e fáceis de entender.


4. Metas Financeiras
Permitir criar metas como:

- Viagem
- Reserva de emergência
- Compra de veículo
- Compra de imóvel
Cada meta deve apresentar:

- Valor objetivo
- Valor acumulado
- Percentual concluído
- Prazo
- Projeção de conclusão


5. Agente Financeiro
Criar um assistente virtual chamado:
Agente Financeiro
Responsabilidades:

- Analisar hábitos financeiros
- Detectar padrões de consumo
- Gerar insights automáticos
- Sugerir oportunidades de economia
Exemplos:
"Você gastou 18% mais em delivery neste mês."
"Sua meta de viagem está atrasada em relação ao planejamento."
"Se reduzir R$ 10 por dia em gastos supérfluos, poderá economizar R$ 300 por mês."


Fluxo do Usuário
Primeiro acesso

1. Criar conta
2. Informar renda mensal
3. Informar objetivo financeiro principal
4. Entrar no chat
Uso diário

1. Registrar movimentações via conversa
2. Receber confirmação automática
3. Consultar saldo e relatórios
Acompanhamento

1. Visualizar metas
2. Consultar dashboards
3. Receber insights personalizados


Telas Necessárias
Tela de Onboarding
Campos:

- Nome
- Renda mensal
- Objetivo financeiro principal


Tela de Chat
Elementos:

- Histórico de conversa
- Campo de mensagem
- Sugestões rápidas
- Respostas do Agente Financeiro
Esta deve ser a principal tela da aplicação.


Tela Dashboard
Exibir:

- Saldo
- Receitas
- Despesas
- Gráficos
- Categorias


Tela de Metas
Exibir:

- Lista de objetivos
- Progresso individual
- Valor acumulado
- Indicadores visuais


Tela de Perfil

- Dados do usuário
- Categorias personalizadas
- Configurações
- Notificações


Design e UX
Criar uma interface:

- Mobile-first
- Minimalista
- Moderna
- Amigável
- Visual semelhante a aplicativos bancários modernos
Utilizar:

- Cartões informativos
- Gráficos simples
- Ícones intuitivos
- Navegação clara
Priorizar facilidade de uso para pessoas sem conhecimento financeiro.


Regras de Negócio

- Toda movimentação registrada deve possuir categoria.
- Usuário pode editar registros.
- Usuário pode excluir registros.
- O saldo deve ser atualizado automaticamente.
- Metas devem atualizar automaticamente quando houver economia acumulada.
- O agente financeiro deve utilizar os dados registrados para gerar recomendações contextualizadas.


Critérios de Sucesso
O produto deve permitir que um usuário iniciante:

1. Registre uma despesa em menos de 10 segundos.
2. Entenda sua situação financeira sem treinamento.
3. Crie uma meta financeira em menos de 1 minuto.
4. Receba recomendações personalizadas baseadas em seus hábitos.


Entregáveis Esperados
Gere:

- Interface completa do MVP
- Fluxo de navegação
- Banco de dados sugerido
- Estrutura de componentes
- Design system básico
- Dados fictícios para demonstração
- Experiência totalmente em português do Brasil
- Aplicação pronta para evolução futura com IA e integrações bancárias


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
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
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

Interações com o Lovable:

Crie um app de finanças pessoais com base no seguinte PRD (Product Requirements Document) Visão do Produto Criar um aplicativo de finanças pessoais que permita ao usuário registrar e acompanhar sua vida financeira por meio de conversas em linguagem natural. Em vez de preencher formulários ou planilhas, o usuário conversa com um assistente financeiro virtual que interpreta suas mensagens, registra movimentações, acompanha metas e oferece recomendações práticas para melhorar sua saúde financeira. O objetivo é tornar o controle financeiro simples, acessível e sustentável para pessoas sem experiência em gestão financeira.

Problema Muitas pessoas desejam controlar seus gastos, mas abandonam aplicativos financeiros porque:

Exigem preenchimento manual excessivo.
Possuem interfaces complexas.
Apresentam relatórios difíceis de interpretar.
Não oferecem orientação personalizada.
Demandam disciplina constante para registrar movimentações. Como consequência, usuários perdem visibilidade sobre seus gastos e têm dificuldade para economizar e atingir objetivos financeiros.
Objetivo Permitir que qualquer pessoa organize suas finanças simplesmente conversando com o aplicativo. O sistema deve:

Registrar receitas e despesas automaticamente.
Categorizar movimentações.
Gerar insights financeiros.
Incentivar hábitos saudáveis de consumo.
Ajudar na criação e acompanhamento de metas.
Público-Alvo Primário Pessoas entre 20 e 45 anos que:

Desejam organizar suas finanças.

Não gostam de planilhas.

Nunca utilizaram aplicativos financeiros de forma consistente.

Querem uma solução simples e intuitiva. Secundário

Universitários.

Jovens profissionais.

Autônomos.

Pequenos empreendedores com finanças pessoais simples.

Proposta de Valor "Controle suas finanças conversando." O usuário não precisa aprender conceitos financeiros ou preencher formulários complexos. Exemplos: "Comprei um lanche por R$ 18." "Recebi meu salário de R$ 3.500." "Quero guardar R$ 500 por mês para viajar." A IA identifica automaticamente:

Valor.
Tipo da transação.
Categoria.
Data.
Impacto financeiro.
Funcionalidades do MVP

Registro Conversacional O usuário envia mensagens em linguagem natural. Exemplos: "Abasteci o carro com R$ 200." "Paguei R$ 120 de internet." "Recebi R$ 1.500 de um freela." O sistema extrai:
Valor.
Categoria.
Tipo (receita ou despesa).
Data.
Classificação Automática Categorias iniciais:
Alimentação
Transporte
Moradia
Saúde
Educação
Lazer
Compras
Salário
Renda Extra
Outros A IA sugere automaticamente a categoria mais adequada.
Dashboard Financeiro Exibir:
Saldo atual.
Receitas do mês.
Despesas do mês.
Evolução mensal.
Distribuição de gastos por categoria.
Metas Financeiras Usuário pode criar metas como: "Quero economizar R$ 5.000 para uma viagem." O sistema calcula:
Valor restante.
Percentual concluído.
Economia mensal necessária.
Agente Financeiro Assistente virtual que gera recomendações. Exemplos: "Você gastou 25% a mais em alimentação este mês." "Sua meta de viagem está 15% atrasada." "Você pode economizar aproximadamente R$ 120 reduzindo gastos com delivery."
Fluxo Principal do Usuário Primeiro acesso

Criar conta.

Informar renda mensal.

Definir objetivo financeiro opcional.

Iniciar conversa com o agente. Uso diário

Registrar receita ou despesa.

Confirmar classificação sugerida.

Visualizar impacto financeiro. Acompanhamento

Consultar dashboard.

Revisar metas.

Receber recomendações.

Principais Telas Tela 1 – Onboarding Objetivo: Coletar informações iniciais. Campos:

Nome
Renda mensal
Objetivo financeiro
Tela 2 – Chat Financeiro Funcionalidades:

Conversação com IA
Registro de transações
Sugestões automáticas
Histórico de mensagens
Tela 3 – Dashboard Exibir:

Saldo atual
Receitas
Despesas
Categorias
Gráficos simples
Tela 4 – Metas Financeiras Exibir:

Lista de metas
Progresso
Prazo
Valor economizado
Tela 5 – Perfil e Configurações

Editar dados
Categorias personalizadas
Preferências de notificações
Requisitos Funcionais RF01 – Registrar receitas via chat. RF02 – Registrar despesas via chat. RF03 – Categorizar movimentações automaticamente. RF04 – Permitir edição de movimentações. RF05 – Criar metas financeiras. RF06 – Gerar relatórios básicos. RF07 – Exibir recomendações automáticas.

Requisitos Não Funcionais RNF01 – Interface simples e amigável. RNF02 – Resposta da IA em menos de 3 segundos. RNF03 – Aplicação responsiva para celular. RNF04 – Proteção de dados financeiros do usuário. RNF05 – Linguagem clara e acessível.

Métricas de Sucesso

80% dos usuários registram pelo menos uma transação no primeiro dia.
50% retornam após 7 dias.
Pelo menos 5 transações registradas por usuário na primeira semana.
Avaliação média superior a 4/5.
Validação Inicial Hipótese Principal Usuários registrarão gastos com maior frequência quando puderem utilizar linguagem natural em vez de formulários. Experimento MVP Recrutar entre 10 e 20 usuários. Solicitar uso durante 7 dias. Coletar:

Número de registros criados.
Frequência de uso.
Facilidade percebida.
Feedback qualitativo. Critério de Sucesso Pelo menos 70% dos participantes afirmam que registrar despesas por conversa é mais fácil do que utilizar aplicativos tradicionais.

Resultado final no Lovable: https://lovable.dev/projects/3e519ee2-5998-4a95-ad14-972c4ab83939?preview-path=%2Fchat

<img width="1522" height="922" alt="image" src="https://github.com/user-attachments/assets/ebb4e68f-d41f-457c-b4d8-d3db82e152eb" />


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
