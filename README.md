# Miniguia de IA Aplicada à Análise de Dados e Automação


---

## Índice

- [Contexto e Objetivos](#contexto-e-objetivos)
- [Curadoria de Fontes](#curadoria-de-fontes)
- [Engenharia de Prompts e "Cicatrizes"](#engenharia-de-prompts-e-cicatrizes)
- [Miniguia de Estudo](#miniguia-de-estudo)
- [Como Reproduzir](#como-reproduzir)
- [Certificações Relacionadas](#certificações-relacionadas)
- [Autor](#autor)

---

## Contexto e Objetivos

### Sobre o Projeto

Este projeto foi desenvolvido como parte do **Desafio de Projeto da DIO** para explorar o **NotebookLM** como ferramenta de aprendizagem ativa. O objetivo é demonstrar habilidades em:

- **Inteligência Artificial Generativa**: Aplicação prática com Microsoft Copilot
- **Automação de Processos**: RPA e automação inteligente
- **Análise de Dados**: IA aplicada a dados e tomada de decisão
- **Engenharia de Prompts**: Técnicas para extrair o melhor da IA
- **Curadoria de Conhecimento**: Seleção crítica de fontes confiáveis

### Assunto de Interesse

**"Inteligência Artificial Aplicada à Análise de Dados e Automação de Processos"**

### Objetivos de Estudo

| Objetivo | Descrição |
|----------|-----------|
| **1** | Compreender o funcionamento da IA Generativa e suas aplicações práticas |
| **2** | Explorar ferramentas de automação de processos (RPA) |
| **3** | Aplicar IA para extrair insights de dados |
| **4** | Dominar técnicas de engenharia de prompts |
| **5** | Criar materiais de estudo reutilizáveis |

### Metodologia

1. **Curadoria** → Seleção de 5 fontes confiáveis
2. **Experimentação** → Testes de prompts (simples vs estruturados)
3. **Documentação** → Registro de "cicatrizes" (troubleshooting)
4. **Síntese** → Criação de resumos, glossário e prompts

---

## Curadoria de Fontes

### Tema 1: IA Generativa e Microsoft Copilot

| # | Fonte | Tipo | Link | Motivo da Escolha |
|---|-------|------|------|-------------------|
| 1 | Microsoft Copilot Hub de Aprendizagem | Documentação Oficial | [Link](https://learn.microsoft.com/pt-br/copilot/) | Fonte primária da Microsoft, guias práticos e técnicos |
| 2 | Livro: IA Generativa para Iniciantes | PDF | `fontes/tema1-ia-generativa/Livro-IA-Generativa.PDF` | Base teórica sobre IA Generativa |

### Tema 2: Automação de Processos com RPA

| # | Fonte | Tipo | Link | Motivo da Escolha |
|---|-------|------|------|-------------------|
| 1 | UiPath - O que é RPA? | Artigo Oficial | [Link](https://www.uipath.com/rpa/robotic-process-automation) | Líder de mercado RPA, explicação completa |
| 2 | Automation Anywhere - RPA | Artigo Oficial | [Link](https://www.automationanywhere.com/rpa) | Visão de outra ferramenta líder |
| 3 | IBM - O que é RPA? | Artigo Técnico | [Link](https://www.ibm.com/br-pt/think/topics/rpa) | Visão técnica da IBM |

### Tema 3: IA na Análise de Dados

| # | Fonte | Tipo | Link | Motivo da Escolha |
|---|-------|------|------|-------------------|
| 1 | IBM - O que é Ciência de Dados? | Artigo Técnico | [Link](https://www.ibm.com/br-pt/think/topics/data-science) | Conceitos fundamentais e ciclo de vida dos dados |
| 2 | Livro: Python para Análise de Dados | PDF | `fontes/tema3-ia-dados/pdfcoffee.com_python-para-analise-de-dados-wes-mckinney-pdf-free.PDF` | Referência em análise de dados com Python |
| 3 | AWS - IA e Análise de Dados | Documentação | [Link](https://aws.amazon.com/pt/machine-learning/data-analytics/) | Visão prática de IA em dados na nuvem |

### Fontes Disponíveis

Todas as fontes estão organizadas na pasta [`/fontes`](./fontes/) do repositório. E os arquivos PDF 

---

## Engenharia de Prompts e "Cicatrizes"

### Metodologia de Teste

Para cada tema, foram testados dois tipos de prompts:

1. **🟡 Prompt Simples**: Pergunta direta, sem contexto ou grounding
2. **🟢 Prompt Estruturado (com Grounding)**: Instrução detalhada com fontes carregadas

### Testes Realizados

#### Tema 1: IA Generativa e Copilot

| Tipo | Prompt | Resposta | Avaliação |
|------|--------|----------|-----------|
| 🟡 Simples | *"O que é IA Generativa?"* | **Resposta obtida:** "IA Generativa é um tipo de inteligência artificial que pode criar conteúdo novo, como texto, imagens e áudio, baseado em padrões aprendidos de dados existentes. Exemplos incluem ChatGPT, DALL-E e Copilot." | Resposta genérica, superficial. Não menciona aplicações práticas ou ferramentas específicas. |
| 🟢 Estruturado | *"Atue como especialista em IA Generativa. Com base nas fontes carregadas sobre Microsoft Copilot, explique o que é IA Generativa, seus princípios de funcionamento e 3 aplicações práticas no ambiente corporativo. Cite trechos das fontes para embasar sua resposta."* | **Resposta obtida:** "Com base nas fontes fornecidas pela Microsoft, IA Generativa é uma tecnologia que utiliza modelos de linguagem de grande escala (LLMs) para gerar conteúdo. O Microsoft Copilot, conforme a documentação oficial, integra essa tecnologia ao Microsoft 365 para aumentar a produtividade. Aplicações práticas incluem: 1) Geração de relatórios automáticos no Word, 2) Análise de dados com sugestões de fórmulas no Excel, 3) Criação de apresentações no PowerPoint a partir de resumos. (Fonte: Microsoft Copilot Hub)" | ✅ Resposta detalhada, fundamentada e com citações |

#### Tema 2: Automação de Processos (RPA)

| Tipo | Prompt | Resposta | Avaliação |
|------|--------|----------|-----------|
| 🟡 Simples | *"Explique RPA"* | **Resposta obtida:** "RPA é Robotic Process Automation, uma tecnologia que usa robôs de software para automatizar tarefas repetitivas." | Resposta muito rasa, sem exemplos ou ferramentas. |
| 🟢 Estruturado | *"Com base nas fontes fornecidas sobre RPA (UiPath, Automation Anywhere, IBM), crie um guia prático com: definição, 5 exemplos de aplicação, principais ferramentas e passo a passo para implementação. Cite trechos das fontes."* | **Resposta obtida:** "Com base nas fontes carregadas, RPA é definido pela UiPath como 'software robots that handle repetitive, rule-based tasks'. A Automation Anywhere complementa que RPA 'mimics human actions in interacting with screens and systems'. Exemplos de aplicação: 1) Processamento de faturas, 2) Atendimento ao cliente, 3) Folha de pagamento, 4) Geração de relatórios, 5) Migração de dados. Ferramentas principais: UiPath, Automation Anywhere, IBM RPA. (Fonte: UiPath, Automation Anywhere, IBM)" | ✅ Guia completo e prático |

#### Tema 3: IA na Análise de Dados

| Tipo | Prompt | Resposta | Avaliação |
|------|--------|----------|-----------|
| 🟡 Simples | *"Como usar IA em dados?"* | **Resposta obtida:** "IA pode ser usada para analisar dados, fazer previsões e encontrar padrões." | Resposta vaga e sem aplicações concretas. |
| 🟢 Estruturado | *"Baseado nas fontes carregadas (IBM e AWS), crie um roteiro de como a IA pode apoiar a análise de dados em 5 etapas, desde a coleta até a visualização. Inclua ferramentas específicas e exemplos práticos. Cite trechos das fontes."* | **Resposta obtida:** "Conforme a IBM, a ciência de dados envolve 'ingestão de dados, armazenamento, análise e comunicação'. A AWS complementa com 'machine learning e data analytics'. Roteiro em 5 etapas: 1) Coleta de dados (APIs, web scraping), 2) Armazenamento (Data Lakes), 3) Limpeza e preparação (Pandas, Python), 4) Análise e modelagem (Machine Learning, Scikit-learn), 5) Visualização (Power BI, Tableau). (Fonte: IBM, AWS)" | ✅ Roteiro prático e aplicável |

###  "Cicatrizes" (Troubleshooting)

Documentação dos desafios encontrados e como foram resolvidos:

| Desafio | Tentativa de Solução | Resultado | Aprendizado |
|---------|----------------------|-----------|-------------|
| Respostas muito genéricas | Adicionei instrução "baseado apenas nas fontes carregadas" | ✅ Respostas mais precisas e confiáveis | O grounding é essencial para respostas de qualidade |
| Dificuldade com prompts muito longos | Dividi em prompts menores e encadeados | ✅ Melhor qualidade das respostas | Prompts encadeados funcionam melhor que um único prompt longo |
| IA "alucinando" informações | Usei o comando "cite trechos das fontes" | ✅ Respostas com citações verificáveis | Exigir citações aumenta confiabilidade |
| Dificuldade em comparar ferramentas | Adicionei "compare e contraste as ferramentas" | ✅ Respostas comparativas úteis | Especificar o tipo de análise desejado melhora os resultados |

---

## 📖 Miniguia de Estudo

### 📌 Resumos Estruturados

#### 1. IA Generativa e Microsoft Copilot

**O que é IA Generativa?**

IA Generativa é uma classe de inteligência artificial que cria conteúdo novo — textos, imagens, códigos, áudio — aprendendo a partir de padrões em grandes bases de dados. Conforme a documentação da Microsoft, "IA Generativa utiliza modelos de linguagem de grande escala (LLMs) para gerar respostas e conteúdo original".

**Princípios de Funcionamento:**

- ✅ Baseada em modelos de linguagem (LLMs) treinados em grandes volumes de dados
- ✅ Aprende padrões probabilísticos a partir de dados de treinamento
- ✅ Gera conteúdo novo baseado em prompts fornecidos pelo usuário
- ✅ Utiliza técnicas de "grounding" para reduzir alucinações

**Microsoft Copilot:**

O Microsoft Copilot é um assistente de IA generativa integrado ao Microsoft 365. Segundo a Microsoft, ele "está integrado nos produtos Microsoft para melhorar a produtividade e simplificar fluxos de trabalho". Ele oferece suporte em:

- **Word**: Geração e revisão de documentos
- **Excel**: Análise de dados e sugestão de fórmulas
- **PowerPoint**: Criação de apresentações
- **Outlook**: Redação e resposta a e-mails
- **Teams**: Transcrição e resumo de reuniões

**Aplicações Práticas no Ambiente Corporativo:**

1. **Geração de relatórios**: Criação automática de resumos executivos
2. **Análise de dados**: Sugestões de fórmulas e insights no Excel
3. **Automação de e-mails**: Redação e resposta a e-mails com base em contexto

---

#### 2. Automação de Processos com RPA

**Definição:**

RPA (Robotic Process Automation) é uma tecnologia que utiliza robôs de software para automatizar tarefas repetitivas e baseadas em regras. A UiPath define RPA como "software robots that handle repetitive, rule-based tasks like data entry and system integration. It mimics human actions in digital systems to work quickly and accurately."

**Benefícios:**

- ✅ **Redução de erros**: Elimina erros de entrada manual de dados
- ✅ **Aumento de produtividade**: Robôs operam 24/7 sem interrupção
- ✅ **Liberação de equipes**: Funcionários focam em atividades estratégicas
- ✅ **Escalabilidade**: Robôs podem ser adicionados rapidamente para atender demanda

**Exemplos de Aplicação:**

| Setor | Exemplo de Uso |
|-------|----------------|
| **Finanças** | Processamento de faturas, fechamento de mês |
| **Saúde** | Gestão de dados de pacientes, agendamento |
| **Manufatura** | Gestão de estoque, relatórios de qualidade |
| **Varejo** | Processamento de pedidos, atendimento ao cliente |
| **Governo** | Processamento de benefícios, licenças |

**Ferramentas Principais:**

- **UiPath**: Líder de mercado, oferece plataforma completa
- **Automation Anywhere**: Ferramenta com foco em IA e nuvem
- **Microsoft Power Automate**: Integração com ecossistema Microsoft
- **IBM RPA**: Solução empresarial com automação inteligente

---

#### 3. IA na Análise de Dados

**Definição:**

A ciência de dados, conforme definido pela IBM, "combina matemática e estatística, programação especializada, análise de dados avançada, inteligência artificial (IA) e aprendizado de máquina com conhecimento específico do assunto para descobrir insights praticáveis ocultos nos dados de uma organização."

**Ciclo de Vida da Ciência de Dados:**

| Etapa | Descrição | Ferramentas |
|-------|-----------|-------------|
| **1. Ingestão** | Coleta de dados de múltiplas fontes | APIs, web scraping |
| **2. Armazenamento** | Organização em data warehouses ou data lakes | SQL, AWS S3, Azure |
| **3. Limpeza** | Tratamento de dados nulos e inconsistências | Pandas (Python) |
| **4. Análise** | Análise exploratória e modelagem | Python, R, Scikit-learn |
| **5. Visualização** | Criação de dashboards e relatórios | Power BI, Tableau |

**Como a IA apoia a Análise de Dados:**

| Etapa | Como a IA Ajuda | Ferramentas |
|-------|-----------------|-------------|
| **Coleta** | Automação de web scraping e ETL | Python, APIs |
| **Limpeza** | Detecção de anomalias e imputação de dados | Pandas, Scikit-learn |
| **Análise** | Identificação de padrões e correlações | Python, SQL |
| **Visualização** | Geração automática de gráficos e dashboards | Power BI, Python |
| **Predição** | Modelos de machine learning | Scikit-learn, TensorFlow |

---

### 📝 Glossário de Conceitos

| Termo | Definição |
|-------|-----------|
| **IA Generativa** | IA que cria conteúdo novo (texto, imagens, código) baseado em padrões aprendidos |
| **RPA** | Tecnologia que automatiza tarefas repetitivas com robôs de software |
| **Prompt Engineering** | Técnica de formular instruções para IA de forma estruturada para obter melhores respostas |
| **Grounding** | Técnica que limita as respostas da IA a fontes específicas, reduzindo alucinações |
| **Alucinação (IA)** | Quando a IA gera informações falsas ou inventadas |
| **LLM (Large Language Model)** | Modelo de linguagem de grande escala treinado em vastos conjuntos de dados textuais |
| **ETL (Extract, Transform, Load)** | Processo de extração, transformação e carregamento de dados |
| **Pipeline de Dados** | Conjunto de processos automatizados para fluxo de dados desde a coleta até a visualização |
| **Dashboard** | Painel visual com indicadores de desempenho e métricas-chave |
| **Microsoft Copilot** | Assistente de IA integrado ao Microsoft 365 para aumento de produtividade |
| **Intelligent Automation** | Combinação de RPA com IA para automatizar processos mais complexos |
| **Data Science** | Campo que combina estatística, programação e conhecimento de negócios para extrair insights de dados |

---

### Prompts Reutilizáveis

| # | Prompt | Uso |
|---|--------|-----|
| 1 | *"Atue como especialista em [TEMA]. Com base nas fontes carregadas, crie um resumo executivo com: conceito, aplicações, benefícios e desafios."* | Resumo rápido do tema |
| 2 | *"Com base nas fontes fornecidas, crie um roteiro de 10 passos para implementar [TEMA] em uma empresa."* | Checklist prático |
| 3 | *"Extraia das fontes os 20 termos mais importantes sobre [TEMA] e crie um glossário com definições e exemplos práticos."* | Criação de glossário |
| 4 | *"Gere 5 perguntas de estudo sobre [TEMA] e forneça respostas com citações das fontes."* | Autoavaliação e fixação |
| 5 | *"Crie um tutorial passo a passo para um iniciante em [TEMA], com exemplos práticos e códigos."* | Material didático |
| 6 | *"Compare e contraste as ferramentas mencionadas nas fontes sobre [TEMA]. Crie uma tabela com prós e contras."* | Análise comparativa |
| 7 | *"Baseado nas fontes, quais são as tendências futuras para [TEMA] nos próximos 5 anos? Cite trechos das fontes."* | Pesquisa de tendências |

---

## Como Reproduzir

### Pré-requisitos

- [NotebookLM](https://notebooklm.google.com/) (gratuito)
- Conta Google
- Acesso à internet para acessar as fontes online

### Passo a Passo

1. **Acesse o NotebookLM** com sua conta Google
2. **Crie um novo caderno** e dê um nome (ex: "Miniguia - IA, RPA e Dados")
3. **Faça upload das fontes** da pasta [`/fontes`](./fontes/)
4. **Teste os prompts** documentados neste README
5. **Registre as respostas** e documente as "cicatrizes"
6. **Consolide os resumos** e o glossário

### Tecnologias Utilizadas

| Ferramenta | Finalidade |
|------------|------------|
| **NotebookLM** | Caderno temático com IA e grounding |
| **Google Docs** | Documentação colaborativa |
| **GitHub** | Versionamento e portfólio |
| **Markdown** | Formatação do README |

---

## 📂 Estrutura do Projeto
