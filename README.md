# Decision Tree - Pinguins

Projeto de aprendizagem de máquina utilizando árvore de decisão para prever a espécie de pinguins do Arquipélago Palmer (Antártica).

## Dataset

O dataset **Palmer Archipelago Penguins** contém dados de três espécies de pinguins:

- **Adelie**
- **Chinstrap**
- **Gentoo**

### Variáveis

| Coluna | Descrição |
|---|---|
| `species` | Espécie do pinguim (target) |
| `island` | Ilha onde foi observado |
| `bill_length_mm` | Comprimento do bico (mm) |
| `bill_depth_mm` | Profundidade do bico (mm) |
| `flipper_length_mm` | Comprimento da nadadeira (mm) |
| `body_mass_g` | Massa corporal (g) |
| `sex` | Gênero |
| `year` | Ano de coleta |

## Etapas do Projeto

1. Carregamento e exploração do dataset
2. Análise de valores nulos
3. Visualizações (distribuição por gênero e por ilha)
4. Pré-processamento: remoção de colunas irrelevantes, one-hot encoding e label encoding
5. Divisão em treino/teste (`test_size=0.2`)
6. Treinamento de `DecisionTreeClassifier` com `max_depth=3`
7. Avaliação com accuracy e F1-score
8. Visualização da árvore de decisão

## Tecnologias

- Python
- pandas
- scikit-learn
- matplotlib

## Como executar

Abra o notebook `decision-tree-penguins.ipynb` no Jupyter ou Google Colab e execute as células em ordem.

> Projeto desenvolvido em 2024 no contexto da disciplina de Linguagem de Programacao III (LP3) - Universidade do Estado da Bahia.