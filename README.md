# Classificador de Folhas de Uva

Este é um classificador de folhas de uva baseado em aprendizado profundo (deep learning) usando a biblioteca PyTorch. O classificador é capaz de identificar diferentes tipos de folhas de uva com base em imagens fornecidas como entrada.

## Arquitetura da Rede Neural

O classificador utiliza uma rede neural convolucional (CNN) com as seguintes camadas:

- Camada de Convolução (Conv2d): A primeira camada convolucional com 64 filtros e ativação ReLU.
- Camada de Convolução (Conv2d): A segunda camada convolucional com 64 filtros e ativação ReLU.
- Camada de Normalização por Batch (BatchNorm2d): Aplicada após cada camada convolucional.
- Camada de Max Pooling (MaxPool2d): Reduz o tamanho da imagem após as camadas convolucionais.
- Camada de Linear (Linear): Duas camadas densas (fully connected) com ativação ReLU.
- Camada de Saída (Linear): A camada de saída com 5 unidades, representando as classes de folhas de uva.

## Dados de Treinamento

Este classificador foi treinado com um conjunto de dados contendo imagens de folhas de uva de diferentes variedades. O modelo é capaz de classificar as folhas em cinco classes diferentes: 'Ak', 'Ala_Idris', 'Buzgulu', 'Dimnit', e 'Nazli'.

## Classificação

O classificador é capaz de identificar as seguintes classes de folhas de uva:

1. 'Ak'
2. 'Ala_Idris'
3. 'Buzgulu'
4. 'Dimnit'
5. 'Nazli'

Quando uma imagem de folha de uva é classificada, o modelo atribui uma das acima como resultado com base nas características da folha na imagem.


## Requisitos

- Python
- PyTorch
- PIL (Pillow)
- Numpy

## Autor

[João Pedro Araujo Queiroz Barbosa]

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) e solicitações de pull (pull requests) para melhorar este projeto.

© 2023 [João Pedro Araujo Queiroz Barbosa]
