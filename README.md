# Uso de IA Generativa para Fins Escolares entre Crianças e Adolescentes de 9 a 14 Anos

Projeto da disciplina de Inteligência Artificial (7º CC) – Universidade Presbiteriana Mackenzie.
**Autor:** Kauã Paixão (RA 10418548) – Turma 7º N.

## Objetivo
Identificar fatores associados ao uso de IA generativa para fins escolares entre estudantes de 9 a 14 anos, com modelos de classificação treinados nos **microdados públicos e anonimizados** do TIC Kids Online Brasil 2025 (Cetic.br). Indicadores agregados do Saeb/Ideb (Inep) servem apenas de contexto.

## Estrutura do repositório
```
artigo/            artigo parcial (PDF e fonte)
dados/             descrição do dataset (README_dados.md) e dicionário de variáveis
notebooks/         notebooks Python da análise exploratória e seus resultados
```

## Dataset
- **Fonte:** Cetic.br/NIC.br – TIC Kids Online Brasil 2025 (microdados desidentificados): https://cetic.br/en/microdados/
- **Unidade de análise:** respondente (criança/adolescente de 9 a 17 anos; recorte de 9 a 14 anos para este projeto).
- **Dados pessoais:** não há identificação individual; nenhuma tentativa de reidentificação é feita.
- **Observação:** confira os termos de uso do Cetic.br antes de republicar os arquivos de dados neste repositório; caso não seja permitido, mantenha apenas a descrição e o link de download.

## Como reproduzir
1. Baixe os microdados e o dicionário no portal do Cetic.br.
2. Abra `notebooks/01_descoberta_tic_kids_2025.ipynb` no Google Colab, envie o arquivo da base e execute.

## Convenção dos arquivos-fonte
Cada arquivo traz um cabeçalho com identificação dos membros, síntese do conteúdo e histórico de alterações (data, autor, descrição).

## Uso de IA generativa
A ferramenta Claude foi usada como apoio à redação e à organização do texto e do código; o autor revisou e assume a responsabilidade pelo conteúdo.
