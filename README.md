# Tratamento e Análise Exploratória de Dados de Telecomunicações

## Objetivo

Este projeto tem como objetivo realizar a **exploração e o tratamento de dados** de uma base de clientes de uma empresa de telecomunicações, com ênfase na variável **Churn** (evasão de clientes). 

Apesar de não haver modelagem preditiva nesse estudo, as etapas foram realizadas com foco na preparação dos dados para esse possível uso futuro. O projeto contém a limpeza e padronização dos dados, além de uma análise exploratória. A proposta incluiu a identificação de inconsistências, padrões e potenciais insights que possam embasar decisões estratégicas e o desenvolvimento de modelos de machine learning.

## Bibliotecas Utilizadas

- `pandas`
- `matplotlib`
- `seaborn`

## Conclusões

- A grande maioria dos clientes contratam o serviço de telefonia.
- Há uma quantidade equilibrada de clientes femininos e masculinos, e o gênero não apresenta influência no churn.
- O valor mensal cobrado pelos serviços também não tem impacto direto no churn.
- A maioria dos clientes tem menos de 60 anos, mas os clientes acima dessa faixa etária mostram maior tendência ao churn.
- Clientes com menor tempo de contrato apresentam maior porcentagem de churn.
- Clientes com contrato mensal têm maior tendência ao churn.

## Próximos Passos Sugeridos

- Aplicar técnicas de balanceamento da variável alvo na base de treino (como SMOTE)
- Criar e avaliar modelos preditivos de classificação  
- Desenvolver dashboards e visualizações interativas para comunicar os resultados obtidos

## Arquivos

1. **`telecomunicacao_tratamento_dados.ipynb`**  
   Etapas realizadas:
   - Identificação e tratamento de valores nulos  
   - Correção de inconsistências  
   - Padronização e limpeza de variáveis  
   - Preparação da base para futuras análises

2. **`telecomunicacao_analise_exploratoria.ipynb`**  
   Etapas realizadas:
   - Análise univariada e bivariada  
   - Visualização da distribuição das variáveis  
   - Identificação de desequilíbrios e possíveis vieses  
   - Extração de insights iniciais sobre o comportamento de churn

## Autoria

**Graciela Rozza** - Projeto desenvolvido como parte dos estudos em **Ciência de Dados**, com foco em **visualização e exploração de dados com Python**.

## Licença

MIT