# 📅 IA25_P02_G03: Análise Exploratória de Dados (EDA) - Jogos Olímpicos
**Grupo:** G03 | **Unidade Curricular:** IA25

## Objetivos
1. Análise demográfica e temporal dos atletas.
2. Correlação entre atributos físicos e sucesso (medalhas).
3. **Feature Engineering:** Preparação de dados para regressão (Previsão de Medalhas por País).
## ⚙️ Tecnologias Utilizadas

O projeto é desenvolvido em Python e utiliza a seguinte biblioteca:

| Tecnologia | Descrição |
| :--- | :--- |
| **Python** | Linguagem de programação principal. |
| **`matplotlib`** | Biblioteca utilizada para visualizações interativas no python. |
| **`seaborn`** |Para visualização estatistica do matplotlib. |
| **Jupyter/Colab** | Ambiente de desenvolvimento e execução do código. |

## 🚀 Como Executar o Projeto

Para executar o projeto, siga os passos abaixo no ambiente do Google Colab ou em um ambiente Jupyter local:

### 1. Instalação de Dependências

A primeira célula do notebook instala automaticamente a biblioteca necessária:

```bash
%pip install pandas numpy matplotlib seaborn
```

## 🚀 Carregamento de Dados

O notebook necessita o upload prévio do arquivo de dados de entrada (`athlete_events.csv` ou similar)`.

1.  Carregar arquivo `athlete_events.csv`
2.  Abra o arquivo `IA_P02_G03.ipynb`.
3.  Execute a célula de instalação.
4.  Execute as células subsequentes para carregar os dados e construir o modelo.

### Conclusão
Este dataset preparado (`country_performance`) pode agora ser usado para treinar modelos de Regressão Linear ou Random Forest Regressors, usando features como o histórico de medalhas, tamanho da delegação (que pode ser calculado do dataset original) e década.

## 🧑‍💻 Autor

* **Grupo:** G03
* **Contexto:** IA25_P01_G03
* **Trabalho:** TRAB 2 cadeira de AI
