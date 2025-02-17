# Heart Disease Estimation

## Projeto para prever a presença de doenças cardíacas com base em variáveis clínicas, utilizando Machine Learning. (86% de acerto)

## Índice

Descrição

Conjunto de Dados

Pré-requisitos

Instalação

Uso

Metodologia

Resultados

Contribuição

## Descrição

O Heart Disease Estimation é um modelo de aprendizado de máquina desenvolvido para prever a presença de doenças cardíacas com base em características clínicas. O projeto envolve pré-processamento de dados, análise exploratória e modelagem preditiva.

## Conjunto de Dados

O conjunto de dados utilizado contém informações sobre pacientes e suas condições cardíacas. Algumas das principais variáveis incluem:

ChestPainType: Tipo de dor no peito (ATA, NAP, ASY, TA).

RestingBP: Pressão arterial em repouso.

FastingBS: Glicemia em jejum (0: <120 mg/dL, 1: ≥120 mg/dL).

RestingECG: Resultados do eletrocardiograma em repouso.

MaxHR: Frequência cardíaca máxima.

ExerciseAngina: Angina induzida por exercício.

Oldpeak: Depressão do segmento ST (milivolts).

ST_Slope: Inclinação do segmento ST durante esforço.

HeartDisease: (0: Sem doença, 1: Presença de doença cardíaca).

## Pré-requisitos

Python 3.x

Jupyter Notebook

Bibliotecas: numpy, pandas.

## Instalação

Clone o repositório:

git clone https://github.com/Dudusegovia/HeartDiseaseEstimation.git

Entre no diretório:

cd HeartDiseaseEstimation

Crie um ambiente virtual e ative-o:

python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

Instale as dependências:

pip install -r requirements.txt

## Uso

Para executar o notebook, use:

jupyter notebook Estimativa_cardiaca.ipynb

O notebook segue uma sequência lógica desde a importação dos dados até a avaliação do modelo.

## Metodologia

Carregamento e exploração dos dados

Tratamento de valores ausentes e transformação de variáveis

Análise exploratória com gráficos e estatísticas descritivas

Treinamento de modelos de aprendizado de máquina

Avaliação dos modelos com métricas de desempenho

## Resultados

Os resultados incluem métricas como acurácia, precisão, recall e matriz de confusão para avaliar o desempenho dos modelos aplicados ao problema de detecção de doenças cardíacas.

## Contribuição

Contribuições são bem-vindas! Para colaborar:

Faça um fork do repositório.

Crie uma branch para sua melhoria:

git checkout -b minha-melhoria

Faça commit das alterações:

git commit -m "Descrição da melhoria"

Envie para o repositório remoto:

git push origin minha-melhoria

Abra um Pull Request.
