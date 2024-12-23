# Fruits-classification-w-pytorch

Este repositório contém um projeto de classificação de imagens utilizando redes neurais convolucionais (CNNs) para classificar frutas no **Fruits 360 Dataset** entre 3 categorias diferentes, foram escolhidas: Maçã, Tomate e Banana.

## Estrutura do Projeto

- **`FruitsCNN.ipynb`**: Notebook contendo o código completo do projeto.
- **`README.md`**: Este arquivo de documentação.
- **`Fruits360`**: Arquivo filtrado com somente as 3 classes de frutas.

Para executar o projeto é necessário: 

- Verificar se todas bibliotecasa utilizadas estão baixadas no seu computador.  
- Baixar o **Fruits360.zip.

## Estrutura do Dataset
O dataset está organizado em duas pastas principais:
- **`Training/`**: Contém as imagens de treino organizadas por subpastas (uma para cada classe).
- **`Test/`**: Contém as imagens de teste, também organizadas por subpastas.

## Modelos Implementados

### 1. CNN Personalizada
### 2. ResNet Pré-treinada

## Treinamento e Avaliação

- **Loss Function**: Cross-Entropy Loss.
- **Otimizador**: Adam.
- **Métrica**: Acurácia no conjunto de validação.


## Resultados
- **CNN Personalizada**: Acurácia de 100%.
- **ResNet Pré-treinada**: Acurácia de 100%.

Ambos os modelos conseguiram atingir uma improvável acurácia de 100%, isso só foi possível devido ao fato de estarmos trabalhando com apenas 3 classes diferentes, reduzindo bastante a complexidade do problema.



