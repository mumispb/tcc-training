# Código de treinamento do TCC

Neste repositório, você encontrará apenas um arquivo Main.ipynb que contém
o código para o treinamento de um modelo de classificação de imagens utilizando
a biblioteca Keras.

É necessário instalar as bibliotecas que o código utiliza.

Recomenda-se o uso de Docker para que o ambiente de desenvolvimento seja
reproduzível e não haja problemas com dependências. Como referência de como fazer isso, veja: https://www.tensorflow.org/install/docker.

O código está divido em várias seções que devem ser executadas apenas se
necessário. Comentários breves foram deixados em cada seção para explicar
um pouco o que está sendo feito naquela seção.

Por exemplo, existem algumas inicializações do banco de dados para realizar um
treinamento utilizando 3 conjunto de dados: treinamento, validação e teste, mas também possui uma seção para realizar o treinamento utilizando validação
cruzada k-fold.
