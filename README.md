# Sentinela-de-pragas
Projeto: [Sentinela de pragas]
1. Identificação do Grupo
Instituição: Faculdade Engenheiro Salvador Arena
Curso: [Inteligência Artificial]
Grupo: A
Integrantes: * [Antônio Jack s. Monte] - RA: [062220002]
[José de Jesus Amaral] - RA: [062220033]
[Jackson Gomes Cerqueira] - RA: [062220030]
---
2. Área Problema Selecionada
Selecione a trilha tecnológica do projeto (marque com um [x]):
[ ] Saúde 4.0: Robótica Assistiva (Controladores Inteligentes/Fuzzy)
[ ] Smart Grid: Eficiência Energética e Descarbonização
[x] Agtech: Automação de Precisão e Visão Computacional
[ ] Logística Autônoma: Coordenação de AGVs e Otimização de Rotas
---
3. Diagnóstico e Definição do Agente
Nesta seção, descrevemos o cenário de atuação e a modelagem do agente inteligente.
Contexto: [Agronegócios].
Problema: [Detecção de pragas na lavoura].
Impacto: [Redução de custos ].
Modelagem PEAS (Agente Inteligente)
Componente	Descrição
Performance (P)	Critérios de sucesso (ex: precisão de acerto, kWh economizados).
Ambiente (E)	Onde o agente opera (ex: armazém simulado, rede elétrica).
Atuadores (A)	Como o agente age (ex: acionamento de motores, válvulas).
**Sensores (S) **	Como o agente percebe o ambiente (ex: câmeras, sensores de carga).
---
4. Arquitetura de Dados e IA
Definição das fontes de dados e da inteligência por trás da solução.
Origem dos Dados: [Link para dataset no Kaggle/UCI ou descrição da fonte].
Lógica de IA: [Técnica utilizada: ex: Redes Neurais, Lógica Fuzzy, Busca A*].
Justificativa: Por que essa técnica é ideal para este problema específico?
---
5. Plano de Tratamento de Dados (ETL)
O fluxo de processamento dos dados segue estas etapas:
Extração: Coleta de dados via arquivos [CSV/JSON] ou simulação.
Transformação: Limpeza de nulos, normalização e engenharia de atributos.
Carga: Disponibilização dos dados para o treinamento do modelo de IA.
---
6. Estrutura do Repositório
Organização simplificada para o Milestone 1:
`/data`: Arquivos de dados originais (raw) e tratados (processed).
`/notebooks`: Experimentos iniciais e análise exploratória.
`/scripts`: Códigos Python (.py) contendo a lógica do agente e do ETL.
`requirements.txt`: Lista de bibliotecas para rodar o projeto.
`README.md`: Documentação atual do projeto.
---
7. Instruções para Execução
Para reproduzir o ambiente e testar o diagnóstico:
Clone este repositório.
Instale as dependências:
```bash
   pip install -r requirements.txt
