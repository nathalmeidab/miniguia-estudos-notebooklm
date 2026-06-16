# Miniguia de Estudos: Data Literacy e a Era dos Agentes de IA

## 🎯 Contexto e Objetivos
Este repositório foi desenvolvido como entrega para o Desafio de Projeto da DIO, utilizando o **NotebookLM** da Google como ferramenta central de aprendizagem ativa. 

O objetivo deste caderno temático é explorar a evolução da análise de dados na era da Inteligência Artificial. Investigamos como o conceito de **Data Literacy (Letramento em Dados)** se transforma quando deixamos de apenas ler relatórios e passamos a colaborar com **Agentes de IA Autônomos** — sistemas capazes de analisar dados, executar códigos e tomar decisões de negócios com o suporte de frameworks modernos.

---

## 📚 Curadoria de Fontes
Para alimentar o NotebookLM com informações de alta qualidade e evitar alucinações, foram selecionadas as seguintes fontes de mercado e técnicas (disponíveis publicamente):

1. **Relatório McKinsey & Company:** *The economic potential of generative AI: The next productivity frontier* (Focado no impacto econômico e automação do trabalho de dados).
2. **Documentação Oficial do CrewAI / LangChain:** Seções conceituais sobre o que são agentes, ferramentas (tools) e como funciona a memória e o planejamento de um agente de IA.
3. **Artigo Gartner Trend Insight:** *Top Trends in Data and Analytics* (Explorando a transição do Business Intelligence tradicional para a tomada de decisão aumentada por IA).

---

## 🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)
O maior aprendizado deste projeto foi entender que o NotebookLM responde estritamente com base nas fontes fornecidas. Abaixo está o registro de como os prompts foram refinados para extrair o melhor resultado.

### ❌ Teste 1: Prompt Inicial (Muito Genérico)
* **Prompt enviado:** *"Me explica o que é um agente de IA e como ele usa dados."*
* **Resultado da IA:** A resposta foi correta, mas muito ampla e superficial. Ela citou conceitos gerais da internet e não aprofundou nas fontes que eu havia subido (como o relatório da McKinsey).
* **Cicatriz/Lição:** Prompts abertos fazem a IA agir de forma genérica. É preciso amarrar o contexto às fontes do caderno.

### 🧠 Teste 2: Prompt Refinado (Com Papel e Escopo)
* **Prompt enviado:** *"Atuando como um Arquiteto de Soluções de IA, analise as fontes deste caderno e explique qual é o papel dos Agentes de IA na automação de análises de dados complexas. Cite quais capacidades (como uso de ferramentas e planejamento) são mencionadas nos documentos técnicos."*
* **Resultado da IA:** Excelente. O NotebookLM estruturou a resposta dividindo em "Capacidade de Planejamento", "Uso de Ferramentas (Python/SQL)" e trouxe insights do relatório da Gartner sobre tomada de decisão.
* **Cicatriz/Lição:** Definir uma persona (ex: Arquiteto de Soluções) e delimitar as capacidades exatas que eu queria extrair mudou completamente a maturidade técnica da resposta.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 📌 Resumo Estruturado: A Nova Análise de Dados
A análise de dados tradicional sempre dependeu de um humano criando consultas SQL, tratando os dados em Python e gerando gráficos no Power BI para que gestores tomassem decisões. 

Na era dos **Agentes de IA**, o fluxo muda:
1. **O Humano (Data Literate):** Define o problema de negócio e supervisiona o processo de forma crítica.
2. **O Agente de IA:** Recebe o objetivo, planeja os passos necessários, escreve o código para analisar a base de dados, corrige os próprios erros de execução (self-healing) e entrega o insight pronto.

Isso não elimina o profissional de dados, mas exige que ele desenvolva um alto nível de **Data Literacy** para questionar os resultados da IA, validar biases e garantir a governança dos dados.

### 📕 Glossário de Conceitos-Chave
* **Data Literacy (Letramento em Dados):** A habilidade de ler, trabalhar, analisar e se comunicação com dados de forma crítica.
* **Agente de IA (AI Agent):** Um sistema de software que utiliza um Modelo de Linguagem (LLM) como "cérebro" para planejar tarefas, interagir com ferramentas externas e agir de forma autônoma para atingir um objetivo.
* **Tools (Ferramentas dos Agentes):** Funções ou APIs que o agente pode decidir usar quando necessário (ex: um executor de código Python, uma ferramenta de busca na web ou um conector de banco de dados SQL).
* **RAG (Retrieval-Augmented Generation):** Técnica usada pelo NotebookLM para buscar trechos específicos de documentos confiáveis e entregá-los à IA, garantindo que as respostas sejam baseadas em fatos reais e não em alucinações.

### 🔄 Prompts Reutilizáveis para Revisão Técnica
Estes prompts foram consolidados para serem reutilizados em futuros estudos sobre arquitetura de dados e IA:

* **Prompt para Estudo de Caso:**
  > *"Com base nos documentos do caderno, crie um estudo de caso fictício onde uma empresa tradicional de varejo implementou Agentes de IA para análise de dados. Inclua os desafios de governança de dados que eles enfrentaram e como resolveram."*
* **Prompt para Autoavaliação:**
  > *"Crie um questionário com 5 perguntas técnicas de nível intermediário sobre a diferença entre sistemas de IA tradicionais e Agentes Autônomos de dados. Não dê as respostas imediatamente; espere eu responder cada uma para me dar o feedback."*

---

## 🛠️ Como replicar este projeto no seu NotebookLM
1. Acesse o [NotebookLM](https://notebooklm.google/).
2. Crie um novo espaço de trabalho chamado "Estudos - Agentes de IA".
3. Faça o upload de relatórios da McKinsey/Gartner ou documentações do CrewAI/LangChain em PDF ou via link.
4. Utilize os prompts refinados listados neste README para iniciar suas sessões de estudo interativo.
