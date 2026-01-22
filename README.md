Este script tem como objetivo realizar a análise de viabilidade econômico-financeira de empreendimentos a partir de séries históricas de fluxo de caixa, armazenadas em banco de dados relacional.

A partir da leitura estruturada dos dados financeiros, o código consolida os fluxos por empreendimento, setor e cenário, respeitando a ordem temporal definida pelo ano de referência. Em seguida, são calculados indicadores clássicos de avaliação de investimentos, como a Taxa Interna de Retorno (TIR) e a Taxa Interna de Retorno Modificada (TIRM), além do fluxo de caixa total de cada projeto.

O processamento foi desenvolvido em Python, utilizando bibliotecas amplamente consolidadas para análise financeira e manipulação de dados, permitindo a automatização dos cálculos, maior rastreabilidade dos resultados e integração direta com o banco de dados institucional.

Ao final da execução, os projetos são classificados conforme a existência ou não de TIR calculável, possibilitando a identificação de casos financeiramente consistentes e daqueles que demandam análise complementar.
