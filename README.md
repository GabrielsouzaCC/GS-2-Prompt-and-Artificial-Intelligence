# Citizen Assist AI — Assistente Digital de Orientação ao Cidadão

**Global Solution — Prompt and Artificial Intelligence**

**Integrantes:**
- Rafael Sá — RM 569223
- João Melo — RM 571116
- Gabriel Souza — RM 571583

## Sobre o projeto

Assistente digital que responde perguntas sobre documentos pessoais (RG, CPF, título de eleitor, carteira de trabalho, certidões e CNH), usando como única fonte de verdade as 7 fichas de referência da Central do Cidadão de Aurora (fictícia), fornecidas no desafio.

Tudo está em um único notebook: o agente (LangChain + Gemini), o golden dataset de 26 mensagens, o pipeline de LLM as a Judge, a comparação antes/depois de uma melhoria aplicada, o roteiro de testes com usuários e as justificativas e limitações do projeto.

## Como rodar

1. Abra `Citizen_Assist_AI.ipynb` no Google Colab.
2. Suba a pasta `fichas/` (ou todo este repositório) para o ambiente do Colab.
3. Crie um secret no Colab chamado `KEY-GS` com uma chave gerada em [aistudio.google.com/apikey](https://aistudio.google.com/apikey), e ative o acesso ao notebook.
4. Rode o notebook do início ao fim.

## Estrutura

- `Citizen_Assist_AI.ipynb` — notebook principal (agente, golden dataset, juiz, comparação, testes com usuários, justificativas, limitações).
- `fichas/` — as 7 fichas de referência (`FC-01` a `FC-07`) fornecidas no enunciado, fonte única de verdade do assistente.
