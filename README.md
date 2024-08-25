# PetFinder Exploratory Data Analysis (EDA)

## Overview

Este projeto realiza uma Análise Exploratória de Dados (EDA) nos dados do [PetFinder](https://www.petfinder.com/), um serviço que ajuda na adoção de animais de estimação. O objetivo da análise é entender as características dos animais listados para adoção, identificar padrões e tendências, e preparar os dados para futuros modelos preditivos.

## Table of Contents

- [Overview](#overview)
- [Data Description](#data-description)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Results](#results)
- [Future Steps](#future-steps)
- [Contributing](#contributing)
- [License](#license)

## Data Description

Os dados utilizados neste projeto foram fornecidos pelo PetFinder e contêm informações sobre os animais listados para adoção, incluindo:

- **Animal ID**: Identificador único do animal
- **Name**: Nome do animal
- **Type**: Tipo de animal (cão, gato, etc.)
- **Age**: Idade do animal
- **Breed**: Raça do animal
- **Color**: Cor do animal
- **Health**: Condições de saúde
- **AdoptionSpeed**: Velocidade de adoção (classificada de 0 a 4)

## Installation

Para reproduzir esta análise em sua máquina local, siga os passos abaixo:

1. Clone o repositório:
   ```bash
   git clone https://github.com/milenoepifanio/EAD_ExploracaoPetFinder.git```
2. Navegue até o diretório do projeto:
   ```bash
   cd EAD_ExploracaoPetFinder```
3. Crie um ambiente virtual e ative-o:
    ```bash
    python -m venv venv
    source venv/bin/activate```  # No Windows: venv\Scripts\activate
4. Instale as dependências:
    ```bash
    pip install -r requirements.txt```

## Project Structure

```plaintext
EAD_ExploracaoPetFinder/
│
├── Análise Exploratória/
│   └── AED - PetFinder.ipynb  # Jupyter notebook contendo a análise exploratória
├── data/                      # Diretório para armazenar os dados (não incluído)
├── images/                    # Imagens usadas na análise ou README
└── README.md                  # Documento atual

## Usage

Para executar a análise exploratória:

1. Abra o notebook `AED - PetFinder.ipynb` no Jupyter Notebook ou JupyterLab:

   ```bash
   jupyter notebook```
2. Execute as células sequencialmente para reproduzir a análise.

## Results

Nesta análise, foram explorados vários aspectos dos dados do PetFinder, incluindo distribuições de características dos animais e correlações entre elas. A seguir estão alguns insights chave:

- A maioria dos animais listados para adoção são cães.
- A velocidade de adoção tende a ser mais rápida para animais mais jovens.
- Certas raças e cores têm maior probabilidade de serem adotadas rapidamente.

Gráficos e visualizações adicionais estão disponíveis no notebook.

## Future Steps

Para aprofundar a análise e refinar a compreensão dos padrões de adoção, os próximos passos sugeridos incluem:

- **Remoção de Outliers**: Realizar uma nova análise exploratória após a remoção de outliers identificados nos dados. Isso pode revelar padrões de comportamento de adoção mais consistentes, que podem estar ocultos devido à presença de valores atípicos.
- **Modelagem Preditiva**: Desenvolver modelos preditivos para estimar a velocidade de adoção com base nas características dos animais.
- **Análise Temporal**: Explorar tendências temporais, como a variação na velocidade de adoção ao longo do tempo.

## Contributing

Contribuições são bem-vindas! Se você deseja contribuir, por favor, abra uma [issue](https://github.com/milenoepifanio/EAD_ExploracaoPetFinder/issues) ou envie um [pull request](https://github.com/milenoepifanio/EAD_ExploracaoPetFinder/pulls).

## License

Este projeto está licenciado sob a [MIT License](LICENSE).