# Desafio de Projeto - Explorando IA Generativa em um Pipeline de ETL com Python

### Bootcamp - TOTVS - Fundamentos de Engenharia de Dados e Machine Learning

## 🚀 Desafio
Recriar um fluxo ETL (Extract, Transform, Load) para personalização de mensagens bancárias. 

## 💡 Adaptação e Resiliência
Devido à indisponibilidade da API original do projeto, este repositório apresenta uma solução resiliente:
- **Extract**: Substituímos o consumo da API por um arquivo `sdw_2023.json`, contendo dados de saldo e objetivos dos clientes.
- **Transform**: Utilizamos a biblioteca `google-generativeai` (modelo Gemini 2.5 Flash) para gerar mensagens de investimento personalizadas com base no **objetivo específico** de cada usuário (ex: comprar carro, viagem).
- **Load**: O resultado foi consolidado em um novo arquivo `sdw_2023_final.json`, simulando o carregamento dos dados processados.

## 🛠️ Tecnologias
- Python (Pandas)
- Google Gemini API
- Google Colab
