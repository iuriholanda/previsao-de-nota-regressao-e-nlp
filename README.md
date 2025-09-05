# previsao-de-nota-regressao-e-nlp

## Descrição
Tarefas de previsão da nota IMDB de filmes baseado em algoritmos de aprendizagem de máquina de regressão, além de algoritmos de classificação de gênero do filme com uso de processamento de linguagem natural (NLP). 

A previsão da nota levou em consideração a seleção de hiperparâmetros com Gridsearch e comparação e avaliação de desempenho de 4 modelos base(Regressão linear, polinomial, XGBoost e Random Forest). Já para a classificação dos gêneros, foi utilizado uma MLP(Multilayer Perceptron) de duas camadas ocultas, implementada com PyTorch, além de embeddings feitos com Word2Vec(Gensim). 
## Pré-requisitos

* [Python (versão 3.8 ou superior)](https://www.python.org/downloads/)
* [Git (para clonar o repositório)](https://git-scm.com/downloads/)
* [Jupyter Notebook](https://www.youtube.com/watch?v=HLD-Ll_-IT4) (se não tiver, o link ao lado leva para um tutorial de instalação no Windows)

## Como executar
Siga os passos abaixo para configurar o ambiente e instalar todas as dependências necessárias.

**1. Clone o Repositório**
Abra o seu terminal e clone este repositório para a sua máquina local:
```bash
git clone https://github.com/iuriholanda/previsao-de-nota-regressao-e-nlp.git
cd previsao-de-nota-regressao-e-nlp
```
**2. Crie o ambiente virtual**
```bash
python -m venv venv
```
**3. Ative o Ambiente Virtual**

No Windows:

```bash
.\venv\Scripts\activate
```
No Mac ou Linux:

```bash
source venv/bin/activate
```
**4. Instale as Dependências**

```bash
pip install -r requirements.txt
```
**5. Abrindo o Notebook Jupyter**

```bash
jupyter notebook
```
Isso irá abrir uma nova guia no seu navegador, hosteada localmente, vá até a pasta do repositório e execute os arquivos .ipynb normalmente.