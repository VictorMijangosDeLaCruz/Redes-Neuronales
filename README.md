# Redes Neuronales

Este repositorio contiene material del curso de Redes neuronales, en la Facultad de Ciencias, UNAM. Y ha sido desarrollado por varios contribuidores bajo el proyecto PAPIME PE102723.
Las redes neuronales artificiales son modelo de aprendizaje estadístico que buscan emular la forma en que una neurona procesa información. Tradicionalmente se enfocan a tareas de clasificación, pero también pueden resolver otras tareas como regresión o, incluso, tareas no supervisadas o generativas.

## Objetivo del curso: 
El curso comprenderá el modelo matemático de la red neuronal que da pie a las redes neuronales artificiales y su generalización. Se revisarán los temas más prominentes sobre redes neuronales: su modelación, el concepto de arquitectura y el proceso de aprendizaje que conllevan.
Asimismo, se profundizará en algoritmos específicos de la familia de redes neuronales, como es el Perceptrón, las redes FeedForward, las redes recurrentes, entre otras. Dentro de esto, se buscará comprender los diferentes problemas que corresponden a cada uno de estos modelos (problemas secuenciales, de clasificación, de regresión, de estimación probabilística).
También se profundizará en la implementación de las redes neuronales, tanto la programación de los módulos básicos, como el uso de paquetería especializada en estos (tensorflow, pytorch).
Además de los algoritmos típicos dentro de la familia de redes neuronales, se impulsará la creación de nuevas arquitecturas que respondan a problemas específicos. Se abordará también la teoría de aprendizaje geométrico profundo que plantea un marco matemático para el planteamiento de diferentes arquitecturas a problemas estructurados.

## Temas

1. Introducción
- &nbsp; 1.1. [Teoría de aprendizaje estadístico](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/Introduccion/00AprendizajeMaquina.html)
- &nbsp; 1.2. [Representación de datos](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/Introduccion/01RepresentacionDatos.html)
- &nbsp; 1.3. [Modelo biológico de la neurona](https://github.com/VictorMijangosDeLaCruz/Redes_Neuronales/blob/main/Notebooks/00%20Modelo%20de%20Hudgkin-Huxley)
3. Modelos de una neurona
- &nbsp; 3.1. [Regresión lineal](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/neuronas/02Linear_regression.html)
- &nbsp; 3.2. [Perceptrón](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/neuronas/03Perceptron.html)
- &nbsp; 3.3. [Límites de una neurona (Problema XOR)](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/neuronas/04SolucionXOR.html)
4. Redes FeedForward
- &nbsp; 4.1. [Ejemplo de regresión con feedforward](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/ffw/01FFWRegression.html)
- &nbsp; 4.2. [Redes neuronales como aproximadores universales](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/ffw/02AproximadorUniversal.html)
5. Aprendizaje en redes multicapa
- &nbsp; 5.1. [Vectorización hacia adelante y atrás](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/aprendizaje/01Vectorizacion.html)
- &nbsp; 5.2. [Descenso por gradiente](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/aprendizaje/02GD.html)
- &nbsp; 5.3. [Desvsanecimiento del gradiente](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/aprendizaje/03Desvanecimiento.html)
- &nbsp; 5.4. [Lotes](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/aprendizaje/04Batches.html)
- &nbsp; 5.5. [Optimizadores basados en descendo por grandiente](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/aprendizaje/05Optimizadores.html)
- &nbsp; 5.6. [Backpropagtion](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/aprendizaje/06Backprop.html)
- &nbsp; 5.7. [Implementación de backprop con gráficas computacionales](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/aprendizaje/07BackPropGraph.html)
6. Regularización
  - &nbsp; 6.1. [Aprendizaje multitarea](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/regularizacion/01Multitarea.html)
  - &nbsp; 6.2. [Early Stopping](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/regularizacion/02EarlyStopping.html)
  - &nbsp; 6.3. [Dropout](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/regularizacion/03Dropout.html)
6. Redes neuronales recurrentes
- &nbsp; 6.1. [Redes recurrentes](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/rnn/01RNN.html)
- &nbsp; 6.2. [LSTMs](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/rnn/02LSTM.html)
7. Redes convolucionales
- &nbsp; 7.1. [Convoluciones y correlación cruzada](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/conv/01Convolucion.html)
- &nbsp; 7.2. [Redes convolucionales](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/conv/02ConvolutionalNetworks.html)
8. Redes atencionales
- &nbsp; 8.1. [Atención](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/att/01Attention.html)
- &nbsp; 8.2. [Transformadores](https://victormijangosdelacruz.github.io/Redes-Neuronales/html/att/02Transformer.html)

### Frameworks para redes neuronales
  1. [Noteboks en PyTorch](https://github.com/VictorMijangosDeLaCruz/Redes-Neuronales/tree/main/Notebooks/Torch)
  2. [Notebooks en TensroFlow](https://github.com/VictorMijangosDeLaCruz/Redes-Neuronales/tree/main/Notebooks/tensorflow)

## Colaboradores

[@veroarriola](https://github.com/veroarriola)

[@milmor](https://github.com/milmor)

[@VictorMijangosDeLaCruz](https://github.com/VictorMijangosDeLaCruz)


---------------------------------------------------------------------------------
<div style="text-align: right">Proyecto PAPIME PE102723</div>
