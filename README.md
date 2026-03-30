# Miniguia de Estudos: Fundamentos de Educação Financeira com NotebookLM

Este repositório contém o projeto desenvolvido para o desafio da plataforma **DIO (Digital Innovation One)**, focado no uso do **Google NotebookLM** como ferramenta de aprendizagem ativa e curadoria de conhecimento.

O objetivo aqui é transformar informações brutas de fontes financeiras em um guia de estudos estruturado, utilizando Engenharia de Prompts para extrair o melhor da Inteligência Artificial.

---

##  Contexto e Objetivos

O tema escolhido para este caderno temático é **Educação Financeira Introdutória e Gestão de Patrimônio**. 

**Objetivos de estudo:**
* Compreender os conceitos básicos de juros compostos e inflação.
* Diferenciar tipos de investimentos de renda fixa e renda variável.
* Criar um método de revisão rápida para consultas futuras através do NotebookLM.

---

## Curadoria de Fontes

Para alimentar o NotebookLM, foram selecionadas as seguintes fontes abertas (PDF/Texto):

1.  **Guia de Educação Financeira (CVM):** Base conceitual sobre o mercado de valores mobiliários.
2.  **Estratégias de Renda Fixa:** Artigos técnicos sobre Tesouro Direto e CDBs.
3.  **Introdução à Renda Variável:** Guia básico sobre o funcionamento da bolsa de valores (B3).
4.  **Princípios de Planejamento Financeiro:** Documento sobre a regra 50-30-20 e reserva de emergência.

---

##  Engenharia de Prompts e "Cicatrizes"

Abaixo, registro o processo de refinamento das perguntas para obter respostas mais precisas da IA.

### Perguntas Estratégicas Testadas:
* *"Explique o que é IPCA como se eu fosse um iniciante, citando exemplos das fontes fornecidas."*
* *"Compare as vantagens do Tesouro Selic vs. CDB de liquidez diária com base nos documentos."*

### O Processo de Refinamento (Troubleshooting):
> **Dificuldade Encontrada:** Inicialmente, a IA trazia definições genéricas da internet.
>
> **Solução (A "Cicatriz"):** Ajustei o prompt para: *"Responda estritamente com base nas fontes carregadas. Se o documento não mencionar a taxa de administração, diga que a informação não consta na fonte."* Isso aumentou a confiabilidade das respostas e evitou alucinações.

---

## Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados
* **Reserva de Emergência:** O primeiro passo indispensável, devendo cobrir de 3 a 6 meses de custo de vida.
* **Tripé dos Investimentos:** A relação entre Segurança, Liquidez e Rentabilidade (raramente se consegue os três ao mesmo tempo).

### 2. Glossário de Conceitos
* **Selic:** A taxa básica de juros da economia brasileira.
* **Liquidez:** A facilidade/velocidade com que você transforma um investimento em dinheiro na mão.
* **Diversificação:** Estratégia de "não colocar todos os ovos na mesma cesta" para reduzir riscos.

### 3. Prompts Reutilizáveis para Revisão
* `"Resuma os pontos principais do Documento [X] em 5 bullet points."`
* `"Crie um quiz de 3 perguntas de múltipla escolha sobre o conceito de Juros Compostos com base no texto."`

---

##  Links Úteis
* [Acessar meu NotebookLM](https://notebooklm.google.com/notebook/e0dd56f4-8614-44ee-82eb-db52fbb9d651)
* [Perfil na DIO]([https://www.dio.me/](https://web.dio.me/users/wendel_ripper_diego?tab=achievements))

---
Desenvolvido por Wendel Diego Taveri, como parte do desafio de IA da DIO.
