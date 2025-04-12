# Deep Learning - Trabalho final

Este trabalho foi desenvolvido no âmbito do módulo de Deep Learning, inserido no programa da pós-graduação em Data Science e Business Intelligence no ano letivo de 2024/2025.

O principal objectivo deste trabalho é desenvolver o espírito crítico na construção de um modelo de Deep Learning. Iterando sobre as diferentes vertentes pelas quais se pode ir controlando o _overfitting_ que pode acontecer durante o treino e compreender de que forma podemos ultrapssar.

O dataset escolhido é o [DeepWeeds](https://www.tensorflow.org/datasets/catalog/deep_weeds?hl=pt-br), trabalho que foi desenvolvido para classificar um conjunto de imagens como contendo 1 de 8 espécies de ervas daninhas em solo australiano.
O notebook foi corrido em Google Collab com os recursos standards.

O trabalho está estruturado da seguinte forma:
1. Recolha de dados (através das funcionalidades disponibilizadas pelo package tensorflow-datasets);
2. Análise Exploratória de dados (algo breve, verificação do número de classes em cada _split_ do dataset original);
3. Pré-processamento (normalização da imagem e redimensionamento para facilitar o treino);
4. Criação dos modelos de baseline;
5. Complexificação do modelo;
6. Introdução de regulararização (_dropout_ e normalização L2);
7. Modelo final;
8. Avaliação do modelo;
9. Trabalho futuro.

O artigo que deu origem ao dataset é o seguinte:
1. Olsen, A., Konovalov, D.A., Philippa, B. et al. DeepWeeds: A Multiclass Weed Species Image Dataset for Deep Learning. Sci Rep 9, 2058 (2019). https://doi.org/10.1038/s41598-018-38343-3
