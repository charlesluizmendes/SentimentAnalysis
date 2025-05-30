# Ambiente 

## Instalando Pacotes

No diretório raiz e execute o comando abaixo:

```
$ pip install -r requirements.txt
```

Ou se prefirir pode instalar manualmente os pacotes:

```
pip install python-dotenv
pip install evaluate
pip install scikit-learn
pip install transformers
pip install datasets
pip install accelerate
pip install bitsandbytes
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
```

# Execução

## Dataset

Primeiramente vamos criar o dataset com notebook:

[dataset.ipynb](https://github.com/charlesluizmendes/SentimentAnalysis/blob/feature/notebook/src/dataset.ipynb)

## Processamento

Após isso, vamos criar o modelo treinando para análise de sentimentos com o notebook:

[processing.ipynb](https://github.com/charlesluizmendes/SentimentAnalysis/blob/feature/notebook/src/processing.ipynb)