# Análise de Criminalidade no Rio de Janeiro (2003-2024)

Projeto de análise de dados sobre a evolução da criminalidade no estado do Rio de Janeiro ao longo de duas décadas, com foco em entender o que está por trás da queda nos crimes violentos observada nos últimos anos.

## O que motivou esse projeto

É comum ver a queda em crimes violentos sendo tratada como sinônimo de melhora geral de segurança pública. Este projeto nasceu de uma dúvida simples: será que essa leitura conta a história toda, ou será que parte da criminalidade só está mudando de forma?

## O que foi feito

- Separação das ocorrências registradas em duas categorias: crimes violentos (roubo, letalidade violenta, sequestro, estupro, entre outros) e crimes não-violentos (furto, estelionato)
- Construção de série histórica anual para identificar padrões de longo prazo
- Cruzamento da série com marcos históricos de segurança pública no estado (UPPs, Copa do Mundo, Olimpíadas, Intervenção Federal)
- Comparação regional entre dois períodos (2015-2017 e 2021-2023) para checar se o padrão encontrado é local ou estadual

## Principal achado

A partir de 2022, crimes não-violentos ultrapassam os violentos pela primeira vez em toda a série histórica, um padrão que se repete em todas as regiões do estado. Isso sugere que a queda na violência não conta a história completa: parte da criminalidade parece estar se reorganizando em formas menos visíveis, não desaparecendo.

## Fonte de dados

Base de evolução mensal de ocorrências por CISP, disponibilizada pelo [ISP-RJ](https://www.ispdados.rj.gov.br/).

## Ferramentas

Python, Pandas, Matplotlib

## Limitações

A análise não estabelece relação de causa e efeito entre políticas públicas e os números observados. Fatores como subnotificação e mudanças de metodologia de registro ao longo dos anos também podem influenciar os resultados. Detalhes completos estão no notebook.
