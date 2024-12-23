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

Ambos os modelos atingiram uma acurácia acima de 70%, com melhorias incrementais após ajustes nos hiperparâmetros.

## Visualização de Predições
Para atender ao requisito de exibição de predições, adicionamos uma função para selecionar um subconjunto de imagens de teste, exibir as imagens e suas predições. Consulte o código na seção **"Predições"** do notebook.

## Execução

1. Execute o notebook `FruitsCNN.ipynb` para treinar o modelo e gerar os resultados.
2. As predições para imagens de teste serão exibidas automaticamente ao final.

## Resultados
- **CNN Personalizada**: Acurácia de X% (ajustar com os resultados reais).
- **ResNet Pré-treinada**: Acurácia de X% (ajustar com os resultados reais).



