# Ambiente 

## Instalando Pacotes

No diretório raiz (/) execute o comando abaixo:

```
$ pip install -r requirements.txt
```

### Pacotes Instalados

```
$ pip install accelerate
$ pip install bitsandbytes
$ pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
```

* O modelo BERT foi criando utlizando CUDA, para acelerar o treinamento e classificação. 

# Execução

## Execução do Notebook

Primeiramente devemos criar o dataset [preview.ipynb](https://github.com/charlesluizmendes/Classifier/blob/main/preview.ipynb):

- Menu 'Arquivo'
- Clicar em 'Fazer upload do notebook'
- Menu 'Ambiente de execução'
- Clicar em 'Executar tudo'

Após criar o dataset, basta executar o notebook [processing.ipynb](https://github.com/charlesluizmendes/Classifier/blob/main/processing.ipynb):

- Menu 'Arquivo'
- Clicar em 'Fazer upload do notebook'
- Menu 'Ambiente de execução'
- Clicar em 'Executar tudo'

Caso queira executar o notebook no VSCode bastar:

Primeiramente criar o dataset [preview.ipynb](https://github.com/charlesluizmendes/Classifier/blob/main/preview.ipynb):

- Clicar em 'Run All'

- Abrir o notebook [processing.ipynb](https://github.com/charlesluizmendes/Classifier/blob/main/processing.ipynb):

- Clicar em 'Run All'