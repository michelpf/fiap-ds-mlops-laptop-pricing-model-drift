# Análise de devios de dados e modelo

A precisão e a eficácia dos modelos são essenciais para garantir o sucesso das aplicações. No entanto, é crucial reconhecer que os dados subjacentes aos modelos podem sofrer alterações ao longo do tempo, resultando em desvios tanto nos dados de entrada quanto na relação entre entradas e saídas do modelo. Esses desvios podem ser causados por uma variedade de fatores, como mudanças nos padrões do mundo real, falhas nos processos de coleta de dados ou evolução dos requisitos da aplicação. Portanto, compreender e gerenciar adequadamente esses desvios é fundamental para manter a relevância e a precisão dos modelos de machine learning em ambientes dinâmicos.

Neste [notebook]() realizamos um estudo de devio de modelo e dados.

## Componentes utilizados:

* [Evidently](https://www.evidentlyai.com/)

## Uso

Estes estudos podem ser realizados ad-hoc ou empregados em batch jobs com uma certa frequência para detecção antecipada dos desvios. O uso de relatórios baseados em JSON proporcionam este tipo de integração fácil com ferramentas de alertas como o AWS Cloudwatch.