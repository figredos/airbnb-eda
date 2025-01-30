# airbnb-eda

EDA on AirBnB data

- [airbnb-eda](#airbnb-eda)
  - [English](#english)
    - [Environment Setup](#environment-setup)
      - [Python installation](#python-installation)
      - [Creating .venv](#creating-venv)
      - [Activating .venv](#activating-venv)
      - [Installing packages](#installing-packages)
    - [Project Structure](#project-structure)
  - [Portuguese](#portuguese)
    - [Configurando ambiente](#configurando-ambiente)
      - [Instalando Python](#instalando-python)
      - [Criando .venv](#criando-venv)
      - [Activating `.venv`](#activating-venv-1)
      - [Installing packages](#installing-packages-1)
    - [Estrutura do projeto](#estrutura-do-projeto)

## English

### Environment Setup

#### Python installation

To run the files used in the EDA process, firstly install python using this [link](https://www.python.org/downloads/)

#### Creating .venv

With python created, download the files in this repository, and in the same folder, run the following command:

```bash
python3 -m venv ./.venv
```

#### Activating .venv

Once the virtual environment has been created, activate it using the following line:

```bash
source .venv/bin/activate
```

#### Installing packages

Finally to install the required packages run the following code:

```bash
pip install -r requirements.txt
```

Once these steps have been completed, you should be able to run the project seamlessly. Thank you!

### Project Structure

In the repository you can find 4 main folders:

- [dataset](./dataset/): Folder that contains the data used in the project and the data dictionary for the [listings.csv](./dataset/listings.csv) file.
- [models](./models/): Folder that contains the saved model, used to predict the price for each entry in the datasets
- [notebooks](./notebooks/): Folder that contains the notebooks used for the EDA and the modelling.
- [report](./report/): Folder that contains the reports for the findings of the EDA and modelling.

The other important file in this structure, is the [resposta.pdf](./resposta.pdf), that holds a summary of all the questions asked for the recruitment process.

## Portuguese

### Configurando ambiente

#### Instalando Python

Para rodar os arquivos usados no processo de análise exploratória, primeiramente instale o Python usando esse [link](https://www.python.org/downloads/).

#### Criando .venv

Com o python instalado na sua máquina, baixe os arquivos desse repositório, e na mesma pasta na qual os arquivos estão, abra um terminal e rode o seguinte comando:

```bash
python3 -m venv ./.venv
```

#### Activating `.venv`

Uma vez que o `.venv` foi criado, é necessário ativa-lo. Para tal, use o seguinte comando no mesmo terminal usado para criar o `.venv`

```bash
source .venv/bin/activate
```

#### Installing packages

Finalmente, para a instalação dos pacotes necessários, rode a seguinte linha no mesmo terminal:

```bash
pip install -r requirements.txt
```

Uma vez que esses comandos foram executados, você poderá rodar o projeto sem problemas. Obrigado!

### Estrutura do projeto

No repositório são encontradas 4 pastas:

- [dataset](./dataset/): pasta que contém os dados usados nos projetos, e o dicionário para o arquivo [listings.csv](./dataset/listings.csv).
- [models](./models/): pasta que contém o modelo gerado, usado para prever o preço de cada entrada no dataset.
- [notebooks](./notebooks/): pasta que contém os notebooks usados para o processo de EDA e a modelagem
  - Possui dois arquivos de modelagem, o modelo é proveniente do arquivo [improved_model](./notebooks/improved_model.ipynb).
- [report](./report/): Pasta que contém os relatórios provenientes da EDA e da modelagem.

O outro arquivo importante é o [resposta.pdf](./resposta.pdf), que contém um sumário de todas as perguntas do processo seletivo.
