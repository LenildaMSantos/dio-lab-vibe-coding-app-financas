# 💰 MeuFluxo IA

## App de Organização de Finanças Pessoais com Inteligência Artificial

Projeto desenvolvido para o desafio **App de Organização de Finanças Pessoais com Vibe Coding**, da Digital Innovation One (DIO).

O objetivo é aplicar conceitos de **Vibe Coding, Inteligência Artificial, engenharia de prompts, definição de PRD e MVP**, transformando uma ideia de produto em uma proposta clara, estruturada e pronta para ser explorada com ferramentas de IA.

> **Status:** conceito e PRD estruturados. As evidências das interações com Copilot/Lovable serão adicionadas ao longo da execução do desafio.

---

## 📌 Visão do Projeto

O **MeuFluxo IA** é um conceito de aplicativo de organização financeira pessoal baseado em conversação.

A proposta é permitir que uma pessoa organize sua vida financeira falando com a aplicação de maneira natural, sem depender de planilhas complexas ou preencher muitos formulários.

Exemplos de interação:

> “Gastei R$ 32 no mercado hoje.”

> “Recebi R$ 1.800.”

> “Quero guardar R$ 300 por mês.”

> “Quanto eu gastei com alimentação esta semana?”

A IA interpreta essas mensagens, organiza as informações e apresenta ao usuário uma visão simples da sua situação financeira.

---

## 🎯 Problema

Muitas pessoas querem controlar melhor suas finanças, mas abandonam aplicativos financeiros porque precisam:

- registrar muitas informações manualmente;
- preencher vários campos;
- criar categorias manualmente;
- interpretar gráficos difíceis;
- manter planilhas constantemente atualizadas.

O MeuFluxo IA busca reduzir esse atrito usando **linguagem natural como principal forma de interação**.

---

## 👥 Público-Alvo

O produto foi pensado principalmente para:

- pessoas iniciantes em organização financeira;
- pessoas que não gostam de utilizar planilhas;
- usuários que querem registrar gastos rapidamente;
- pessoas que desejam criar o hábito de acompanhar suas finanças;
- usuários que preferem uma experiência simples e educativa.

---

## 💡 Proposta de Valor

**Organizar as finanças por meio de uma conversa simples.**

Em vez de obrigar o usuário a aprender como utilizar um sistema financeiro, o sistema procura entender como o usuário naturalmente fala sobre dinheiro.

---

## 🤖 Agente Financeiro

O MeuFluxo IA possui um agente de inteligência artificial que funciona como um **assistente de organização financeira pessoal**.

O agente deve:

- utilizar linguagem simples;
- explicar informações financeiras de forma educativa;
- evitar julgamentos sobre os gastos do usuário;
- identificar padrões de despesas;
- sugerir pequenas melhorias de organização;
- ajudar a criar metas realistas;
- mostrar a evolução dessas metas;
- solicitar confirmação quando uma informação estiver ambígua.

### Exemplo

**Usuário**

> Gastei 45 reais no almoço.

**MeuFluxo IA**

> Registrei R$ 45,00 em Alimentação. Quer que eu considere esse gasto como parte do seu orçamento de refeições deste mês?

---

# 🚀 MVP

O MVP terá cinco funcionalidades principais.

## 1. Registro de gastos por conversa

O usuário poderá registrar despesas usando linguagem natural.

Exemplo:

> “Paguei R$ 120 de internet.”

O sistema identifica:

- valor;
- tipo de movimentação;
- categoria;
- data.

---

## 2. Classificação automática

A IA poderá sugerir categorias como:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Assinaturas
- Outros

O usuário poderá corrigir uma classificação quando necessário.

---

## 3. Visão financeira simplificada

A tela inicial apresentará:

- receitas;
- despesas;
- saldo do período;
- principais categorias de gastos;
- progresso das metas.

---

## 4. Metas financeiras

O usuário poderá criar metas por conversa.

Exemplo:

> “Quero guardar R$ 1.200 nos próximos seis meses.”

A aplicação poderá calcular uma referência mensal e acompanhar o progresso.

---

## 5. Insights do Agente Financeiro

O agente poderá identificar padrões simples, por exemplo:

> “Seus gastos com alimentação fora de casa aumentaram neste mês.”

> “Você já alcançou 70% da sua meta.”

> “Existem três assinaturas recorrentes registradas neste mês.”

Os insights devem ser informativos e educativos, sem substituir orientação financeira profissional.

---

# 📱 Fluxo Conceitual de Telas

### 1. Onboarding

Apresentação rápida da proposta:

**“Organize seu dinheiro conversando.”**

### 2. Home

Resumo financeiro com:

- saldo;
- receitas;
- despesas;
- metas;
- principais categorias;
- acesso rápido ao chat.

### 3. Conversa com a IA

Principal área de interação para registrar movimentações e fazer perguntas sobre as próprias finanças.

### 4. Transações

Histórico organizado por:

- data;
- categoria;
- tipo;
- valor.

### 5. Metas

Área para criação e acompanhamento das metas financeiras.

### 6. Insights

Resumo dos principais padrões identificados pela IA.

---

# 🧠 PRD / Prompt Final

```txt
# Contexto

Quero criar o conceito de um aplicativo chamado MeuFluxo IA, voltado para organização de finanças pessoais através de uma experiência conversacional.

A principal interface do produto deverá ser uma conversa em linguagem natural.

O usuário deverá conseguir registrar receitas, despesas e metas usando frases comuns, sem precisar preencher vários formulários.

O produto deverá priorizar simplicidade, clareza, baixo número de etapas e facilidade de uso.

# Problema

Muitas pessoas têm dificuldade para manter controle financeiro porque aplicativos tradicionais exigem entrada manual frequente, configuração de categorias e interpretação de muitas informações.

Isso cria atrito e faz com que usuários abandonem o processo.

Quero reduzir esse problema utilizando IA para interpretar linguagem natural, organizar informações e apresentar os dados de maneira simples.

# Público-Alvo

Pessoas que estão começando a organizar suas finanças e desejam uma solução simples.

O produto deve ser especialmente acessível para usuários que não possuem conhecimento avançado de finanças ou que não gostam de utilizar planilhas.

# Objetivo do Produto

Permitir que o usuário organize sua vida financeira através de conversas simples com um agente de inteligência artificial.

A experiência deve transmitir a sensação de estar conversando com um assistente de organização financeira.

# Funcionalidades do MVP

1. Registro conversacional de transações

Interpretar mensagens como:

“Gastei 25 reais com transporte.”

“Recebi 1500 reais hoje.”

Extrair automaticamente:

- tipo da movimentação;
- valor;
- categoria;
- data.

2. Classificação automática

Classificar despesas automaticamente e permitir correção manual quando necessário.

3. Dashboard simplificado

Apresentar:

- receitas;
- despesas;
- saldo;
- gastos por categoria;
- progresso das metas.

Evitar excesso de gráficos ou informações.

4. Metas financeiras

Permitir a criação de metas utilizando linguagem natural.

Exemplo:

“Quero economizar R$ 600 em três meses.”

Mostrar progresso e referências de acompanhamento.

5. Agente Financeiro

Criar um agente de IA com linguagem:

- clara;
- educativa;
- respeitosa;
- objetiva;
- não julgadora.

O agente deverá explicar padrões encontrados nos dados do usuário e ajudá-lo a entender melhor sua organização financeira.

# Regras de Experiência

Priorizar:

- mobile first;
- interface limpa;
- poucos elementos por tela;
- linguagem acessível;
- respostas curtas;
- ações rápidas;
- confirmação de informações ambíguas.

O sistema não deve inventar transações ou informações financeiras.

Sempre que a interpretação de uma mensagem não for suficientemente segura, deverá solicitar confirmação ao usuário.

# Entregável Esperado da IA

Com base neste PRD:

1. Estruture o MVP do produto.
2. Proponha a arquitetura conceitual das telas.
3. Defina o fluxo principal do usuário.
4. Defina o comportamento do agente financeiro.
5. Crie exemplos de conversas.
6. Sugira os componentes principais da interface.
7. Proponha uma estratégia simples de validação do MVP.
8. Não adicione funcionalidades complexas que não sejam necessárias para validar a proposta inicial.

Use português do Brasil e linguagem simples.
```

---

# 🧪 Estratégia de Validação

### Facilidade de registro

Avaliar se um novo usuário consegue registrar sua primeira movimentação rapidamente.

### Taxa de correção da IA

Medir quantas classificações automáticas precisam ser corrigidas.

### Frequência de uso

Verificar se os usuários continuam registrando movimentações ao longo das semanas.

### Utilização das metas

Avaliar quantos usuários criam e acompanham pelo menos uma meta.

### Compreensão financeira

Perguntar aos usuários se o aplicativo ajudou a entender melhor para onde o dinheiro está indo.

---

# 🛠️ Ferramentas do Processo

Ferramentas usadas ou previstas no fluxo do desafio:

- **ChatGPT** — estruturação do conceito, PRD e documentação;
- **GitHub** — versionamento e entrega do projeto;
- **GitHub Copilot** — refinamento e experimentação de prompts;
- **Lovable** — exploração do conceito e do fluxo do MVP.

---

# 📸 Evidências das Interações com IA

Esta seção será atualizada com os registros reais das interações realizadas durante o desafio.

Arquivos previstos:

- `assets/prd.png`
- `assets/mvp.png`
- `assets/fluxo-telas.png`
- `assets/agente-financeiro.png`

---

# 📚 Reflexão sobre o Processo

Até esta etapa, o principal aprendizado foi perceber que trabalhar com Inteligência Artificial não significa simplesmente pedir para uma ferramenta “criar um aplicativo”.

A qualidade da resposta depende muito da qualidade do contexto fornecido.

Um prompt melhor precisa explicar:

- qual problema deve ser resolvido;
- quem possui esse problema;
- qual é o objetivo do produto;
- quais funcionalidades realmente fazem parte do MVP;
- quais limites devem ser respeitados;
- qual resultado é esperado da IA.

Também ficou evidente a importância de trabalhar de forma iterativa: usar a IA para analisar a ideia, identificar lacunas, melhorar requisitos e evoluir a solução gradualmente.

O principal aprendizado é que **Vibe Coding não elimina a necessidade de pensar sobre o produto**.

Quanto mais clara for a intenção humana, melhor a IA consegue colaborar na construção da solução.

Esta reflexão será complementada após as interações finais com Copilot e Lovable.

---

# 🔮 Evoluções Futuras

Depois da validação do MVP, o produto poderia evoluir para recursos como:

- identificação de despesas recorrentes;
- importação automática de dados financeiros mediante integrações autorizadas;
- alertas personalizados;
- comparação de períodos;
- projeções simples de orçamento;
- maior personalização do agente;
- acessibilidade ampliada;
- entrada por voz.

Essas funcionalidades **não fazem parte do MVP inicial**.

---

# ✅ Status do Projeto

**Conceito / MVP em desenvolvimento para o desafio DIO de Vibe Coding.**

O foco desta entrega é demonstrar:

- pensamento de produto;
- engenharia de prompts;
- uso estratégico de IA;
- definição de MVP;
- documentação;
- capacidade de transformar um problema em uma proposta estruturada.

---

## 👩‍💻 Autora

**Lenilda M. dos Santos**

Projeto desenvolvido para fins de estudo, prática e portfólio profissional.

