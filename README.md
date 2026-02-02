# 💸 App de Finanças Pessoais do Pedro com Vibe Coding

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

PRD refinado no Copilot web:

```markdown
# PRD: MoneyFlow AI - Organizacao Financeira Conversacional

## 1. Visao Geral
Um assistente financeiro minimalista baseado em chat e principios de Design Universal. O foco e reduzir barreiras de entrada para o controle financeiro pessoal atraves de uma interface acessivel e intuitiva.

## 2. O Problema
O alto atrito de entrada de dados e interfaces complexas que geram exclusao. Aplicativos tradicionais exigem preenchimento de formularios exaustivos, o que afasta pessoas com dificuldades motoras, baixa visao ou baixa literacia digital.

## 3. Publico-Alvo
Usuarios que buscam organizar suas financas de forma pratica, com enfase em iniciantes e pessoas que necessitam de uma interface altamente acessivel e adaptavel.

## 4. Requisitos Funcionais (User Stories)
* Entrada Multimodal: O usuario deve ser capaz de registrar gastos via texto ou comandos de voz.
* Categorizacao Automatica: A IA deve extrair Valor, Categoria e Data a partir de frases em linguagem natural.
* Feedback de Confirmacao: O sistema deve confirmar as informacoes extraidas antes de efetivar o registro para evitar erros.
* Gestao de Metas: Definicao e acompanhamento de metas financeiras simples via chat.

## 5. Experiencia do Usuario e Design Universal (UX/UI)
* Acessibilidade Visual: Cores com alto contraste seguindo as diretrizes WCAG e suporte nativo a leitores de tela.
* Interface Limpa e Intuitiva: Fontes com tamanho minimo de 16px e elementos clicaveis amplos para facilitar a interacao motora.
* Flexibilidade de Uso: Suporte a temas claro/escuro e ajuste dinamico de escala de interface.
* Arquitetura de Informacao: Navegação linear e simples, focada na conversa, evitando menus ocultos ou complexos.

## 6. Stack Tecnologica Sugerida
* Frontend: React (Vite) com Tailwind CSS.
* Componentes: Radix UI ou Headless UI (focados em acessibilidade).
* IA/Backend: API do Google Gemini para processamento de linguagem natural e transcricao.
* Armazenamento: Supabase ou LocalStorage para persistencia de dados no MVP.

## 7. Metricas de Sucesso e Validacao
* Precisao da IA: A taxa de acerto na extracao de dados de frases naturais deve ser superior a 90%.
* Usabilidade: O usuario deve conseguir registrar uma despesa em menos de 10 segundos.
* Acessibilidade: Validacao completa via ferramentas de auditoria (como Lighthouse ou Axe).
```
Interações com o Lovable:

> Crie um APP de finanças pessoais com base no seguinte PRD (Product Requirements Document): {PRD}

Resultado Final no Lovable: https://chat-your-cents-09.lovable.app

<img width="772" height="848" alt="image" src="https://github.com/user-attachments/assets/5e1e7706-f45c-4541-a89f-3ffc86d7a7eb" />


  ## Funcionalidades do App "MoneyFlow"

### 1. Registro de Gastos por Conversa Natural
O usuário informa seus gastos como se estivesse conversando com um assistente, usando frases como:
- "Gastei 50 reais no almoço hoje"
- "Paguei 150 de Uber essa semana"
- "Comprei remédios por 80 reais ontem"

Essa abordagem elimina a necessidade de formulários ou planilhas complexas.

### 2. Interface Conversacional Intuitiva
A tela principal é um chat com o assistente financeiro, que guia o usuário e responde de forma amigável.  
Há um campo de entrada simples e sugestões de como interagir.

### 3. Navegação por Áreas-Chave
O app possui três seções principais:
- **Chat**: para registrar e conversar sobre despesas.
- **Resumo**: para visualizar relatórios financeiros simplificados.
- **Metas**: para definir e acompanhar objetivos financeiros.

### 4. Classificação Automática de Transações
Com base nas mensagens do usuário, o app identifica o tipo de gasto (alimentação, transporte, saúde etc.) e organiza automaticamente.

### 5. Dicas Personalizadas do “Agente Financeiro”
O assistente oferece sugestões de economia com base nos hábitos do usuário, promovendo educação financeira.

### 6. Design Universal e Acessível
A interface é pensada para funcionar bem para todos os perfis de usuários, incluindo iniciantes, pessoas com baixa familiaridade digital e usuários com limitações visuais ou motoras.


## Reflexão  

### O que funcionou bem?  
  O Refinamento previamente feito no Copilot ajudou muito.
  
### O que não funcionou como o esperado?  
Espera Poder interadir mais vezez gratuitamente com o Lovable.

### O que aprendeu sobre conversar com IAs?
Aprendi que é basicamente conversar com uma pessoa, quanto mais clareza você dá melhor a interação.

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
