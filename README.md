# **Previsão do Preço de Fechamento das Ações da Gol Linhas Aéreas: Desenvolvimento de Modelo Preditivo**

A capacidade de antecipar o movimento dos preços das ações é uma ferramenta poderosa para investidores e profissionais do mercado financeiro. A identificação prévia de tendências de valorização pode ser decisiva para a formulação de estratégias eficazes na composição de uma carteira de investimentos lucrativa. Este projeto, embora inicial, visa estabelecer uma base sólida de conceitos fundamentais para a criação de um modelo preditivo de preços de ações.

## **Sobre a Gol**

A GOL Linhas Aéreas Inteligentes S.A. é uma das principais companhias aéreas do Brasil, conhecida por sua eficiência operacional e inovação no setor. Fundada no início dos anos 2000, a GOL rapidamente expandiu sua atuação, alcançando todas as capitais brasileiras e iniciando voos internacionais. A empresa realizou sua oferta pública inicial de ações em 2004 e, desde então, tem se destacado no mercado com aquisições estratégicas, como a da Varig em 2007 e da Webjet em 2011.

A GOL é detentora da Smiles, um programa de fidelidade de destaque no mercado, e também controla a GAC Inc., focada em logística. A companhia é listada no segmento Nível 2 de governança corporativa da B3 e oferece aos investidores ações preferenciais (GOLL4), ordinárias (GOLL3) e units (GOLL11), além de estar presente no mercado fracionado (GOLL4F).

## **Objetivo do Projeto**

O principal objetivo deste trabalho é desenvolver um modelo de aprendizado de máquina capaz de realizar previsões precisas do valor de fechamento das ações da Gol Linhas Aéreas.

## **Sobre os Dados**

Os dados financeiros foram coletados utilizando-se o yfinance, uma biblioteca do Python que permite a extração de dados financeiros de várias fontes, como o Yahoo Finance, que será a fonte utilizada neste projeto. Essa ferramenta oferece acesso rápido e fácil a informações financeiras históricas detalhadas, essenciais para a criação de uma base de dados robusta e confiável, necessária para o desenvolvimento de um modelo preditivo eficiente.

## **Dicionário de Variáveis**

- Data (Date): A data correspondente às transações realizadas.
- Máxima (High): O preço máximo alcançado pelas ações durante o dia.
- Mínima (Low): O menor preço registrado para as ações no período diário.
- Abertura (Open): O preço de abertura das ações no início das negociações na bolsa de valores.
- Fechamento (Close): O preço das ações no momento do fechamento da bolsa de valores.
- Volume: O volume total de ações negociadas ao longo do dia.
- Fechamento Ajustado (Adj Close): O valor real das ações no fechamento, ajustado para contemplar eventos como distribuição de dividendos e desdobramentos de ações.
