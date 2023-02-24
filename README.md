# Estudos com transfer Learning do Google:

Com base nos estudos do Curso de Machine Learning do curso DIO, comecei a trabalher em cima deste notebook.
Fazendo algumas mudanças, atualmente esta parado por eu utilizar Colab gratuito, e este notebook por vezes excede o uso diario.. 

.. 

Este repositório contém um exemplo de aplicação de Transfer Learning utilizando a biblioteca Keras com a base de dados Caltech-101.

A técnica de Transfer Learning é utilizada em Machine Learning quando se utiliza um modelo pré-treinado em uma tarefa específica para ser ajustado em uma nova tarefa, ao invés de se iniciar o treinamento do zero. Dessa forma, o modelo já tem um conhecimento prévio que pode ser utilizado para melhorar o desempenho na nova tarefa.

O conjunto de dados Caltech-101 é composto por imagens de 101 objetos diferentes, com cada objeto contendo em média 50 imagens. Para a aplicação do Transfer Learning, utilizamos um modelo pré-treinado da família VGG, que já foi treinado com milhares de imagens em uma tarefa de classificação de objetos.

O código contém os seguintes passos:

Download e extração da base de dados Caltech-101;
Pré-processamento dos dados, normalizando as imagens e convertendo as labels para one-hot vectors;
Criação do modelo utilizando a técnica de Transfer Learning, onde é adicionada uma camada densa no topo da arquitetura do modelo pré-treinado;
Treinamento do modelo utilizando os dados de treinamento e validação;
Avaliação do modelo utilizando os dados de teste.
O modelo treinado obteve uma acurácia de X% na tarefa de classificação dos objetos na base de dados Caltech-101. O código também contém funções para visualização dos resultados e para predição de classes de novas imagens.

Para executar o código, é necessário ter instalado as bibliotecas Keras, TensorFlow e Matplotlib. 
Além disso, é necessário baixar e extrair a base de dados Caltech-101. 
O caminho para a base de dados esta ser especificado no código.