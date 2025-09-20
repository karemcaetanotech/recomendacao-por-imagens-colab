# recomendacao-por-imagens-colab
# Sistema de Recomendação por Imagens (Colab)

Este notebook monta um recomendador por **similaridade visual**:
- Extrai embeddings com **MobileNetV2 (ImageNet)**.
- Indexa com **NearestNeighbors (cosseno)**.
- Retorna o **Top-K** de imagens mais parecidas da pasta do Google Drive.

## Como usar (Colab)
1. Abra o notebook no Colab.
2. Monte o Drive e ajuste `DATA_DIR` para `MyDrive/dataset_recomendacao`.
3. Rode todas as células. Troque `q = img_paths[0]` para testar outras consultas.

## Dataset
Imagens pessoais em `dataset_recomendacao/` (Google Drive).

## Resultados
Veja prints em `/images`.

<!-- Badge opcional: troque <seu-usuario>/<seu-repo> -->
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<seu-usuario>/<seu-repo>/blob/main/notebook.ipynb)
