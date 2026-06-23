# Metodologia

## Objetivo

Analisar o perfil dos estudantes e os fatores relacionados à evasão em um curso de Especialização em Geoprocessamento.

## Extração

- Leitura das bases dos editais de 2023 e 2024
- Consolidação em uma única base analítica

## Tratamento LGPD

- Remoção de identificadores pessoais
- Anonimização dos CPFs utilizando SHA-256
- Criação do identificador único `ìd_aluno`

## Limpeza e Padronização

- Padronização de categorias de raça
- Padronização de necessidades especiais
- Conversão de datas
- Tratamento de inconsistências

## Regras de Negócio

- Identificação da matrícula mais recente
- Cálculo da carga horária exigidapor edital
- Cálculo do percentual de conclusão

## Engenharia de Atributos

- idade_ingresso
- faixa_etaria
- perfil_evasao
- meses_ate_evasao
- UF_ Mapa

## Visualização

Os dados tratados foram consumidos pelo Power BI para construção de dashboards voltados para coordenação e docentes