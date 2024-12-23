# Fruits-classification-w-pytorch

Este repositório contém um projeto de classificação de imagens utilizando redes neurais convolucionais (CNNs) para categorizar frutas no **Fruits 360 Dataset**. O projeto foi desenvolvido como parte de um desafio acadêmico, com o objetivo de classificar três tipos de frutas e atingir uma acurácia mínima de 70%.

## Estrutura do Projeto

- **`FruitsCNN.ipynb`**: Notebook contendo o código completo do projeto.
- **`README.md`**: Este arquivo de documentação.

## Descrição do Problema
O objetivo é criar um modelo de rede neural simples capaz de classificar imagens de frutas em três categorias distintas. Para isso, utilizamos o conjunto de dados **Fruits 360**, disponível no Kaggle:

[Link para o dataset no Kaggle](https://www.kaggle.com/datasets/moltean/fruits)

### Requisitos do Projeto
- **Pré-processamento**: Realizar transformações nas imagens para garantir compatibilidade com os modelos de redes neurais.
- **Modelo**: Implementar uma CNN personalizada e avaliar também o uso de uma rede ResNet pré-treinada.
- **Predições**: Exibir as predições para um subconjunto de imagens de teste.
- **Acurácia Mínima**: Garantir pelo menos 70% de acurácia no conjunto de validação.

## Configuração do Ambiente

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/fruits-classification.git
   cd fruits-classification
   ```

2. Instale os pacotes necessários:
   ```bash
   pip install -r requirements.txt
   ```

3. Baixe o **Fruits 360 Dataset** do Kaggle e extraia-o na pasta `data/` do repositório.

## Estrutura do Dataset
O dataset está organizado em duas pastas principais:
- **`Training/`**: Contém as imagens de treino organizadas por subpastas (uma para cada classe).
- **`Test/`**: Contém as imagens de teste, também organizadas por subpastas.

## Modelos Implementados

### 1. CNN Personalizada
A CNN personalizada foi projetada com as seguintes camadas principais:
- Camadas convolucionais com ReLU e MaxPooling.
- Camadas totalmente conectadas para classificação final.

### 2. ResNet Pré-treinada
Utilizamos a ResNet-18 pré-treinada do PyTorch com ajustes para classificar as três classes do problema.

## Treinamento e Avaliação
- **Critério de Otimização**: Cross-Entropy Loss.
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

## Sugestões para Melhorias
- Testar com mais classes do dataset.
- Utilizar técnicas de aumento de dados (Data Augmentation).
- Ajustar hiperparâmetros para maior eficiência.
- Implementar visualização de matrizes de confusão.

## Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo `LICENSE` para mais informações.

