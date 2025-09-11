# PjTransferLearningCatandDog
Teste de base de dados (dataset) para diferenciar cachorros e gatos usando Transfer Learning.

# Classificação de Gatos e Cachorros 🐱🐶

Este projeto foi desenvolvido no google colab e implementa um classificador de imagens que diferencia gatos de cachorros utilizando **Transfer Learning** com a rede **MobileNetV2** pré-treinada no ImageNet. O modelo foi ajustado em duas etapas: primeiro com as camadas convolucionais congeladas e depois com fine-tuning nas últimas camadas.  

As imagens que usei (600 de cada classe) foram obtidas do dataset em: https://www.microsoft.com/en-us/download/details.aspx?id=54765. , selecionadas e organizadas em duas classes: `Cat/` e `Dog/`. 
O dataset usado neste projeto pode ser baixado [neste link do Google Drive]( https://drive.google.com/file/d/1PRAvEj84vg3gbSBnk0ou4vvHbxMwZQy8/view?usp=sharing).

O projeto foi desenvolvido em **Python** com **Keras/TensorFlow**, e inclui código para treinamento, avaliação e predição de novas imagens.
