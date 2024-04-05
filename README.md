<h1 align='center'>VIDA EN VERDE 🚗🚦</h1><BR>

<h2>MODELO DE DETECCION DE ESTADO DE SEMAFOROS PARA AYUDAR A PERSONAS INVIDENTES</h2>
<div align="center">
  <img alt="Modelo de deteccion de estado de semaforos para ayudar a personas invidentes" src="https://github.com/cesenro2801/PROYECTO_IA/blob/main/IMG/VIDA EN VERDE.png"  />

</div>
<br>
<h3>INTEGRANTES</h3>

<p>Cesar Enrique Rojas Hernandez - 2191952

Santiago Andres Delgado Quiceno - 211799

Mariana Robayo Nieto - 2195092</p>

<h2>PLANTEAMIENTO DEL PROBLEMA </h2>
<br>
<p>El problema de autonomia con el que cuentan muchas personas invidentes al momento de estar fuera de sus casas es que se les hace dificil movilizarse por las calles de manera autonoma debido p que los conductores no son concientes y en los pasos de sebra no suelen ceder el paso a las personas invidentes al igual que es muy complicado saber el estado de los semaforos para pasar con mas seguridad, debido a la poca inclusion que hay para estos casos no se cuentan con ayudas o sistemas especializados que permitan mejorar estos casos en pro de mejorar estas situaciones</p>

<h2>OBJETIVOS</h2>
<h3>OBJETIVO GENERAL</h3><br>
<p>Mejorar la autonomía y seguridad de las personas invidentes al cruzar las calles, mediante el desarrollo de un sistema de IA basado en modelos de aprendizaje que detecten el estado de los semáforos y proporcione indicaciones precisas.</p>

<h3>OBJETIVOS ESPECIFICOS</h3>

<ul>
  <li>Recopilar y etiquetar un conjunto de datos diverso y representativo de imágenes de semáforos peatonales en diferentes condiciones de iluminación y ángulos de visión.</li><br>
  <li>Entrenar y comparar varios modelos supervisados y no supervisados, para determinar cual es el más efectivo en el reconocimiento del estado de los semáforos.</li><br>
</ul>

<h3>DATASET</h3>
<p>Peatones-Traffic-Lights (PTL) es un conjunto de datos de imágenes de alta calidad de intersecciones de calles, creado para la detección de semáforos para peatones y pasos de cebra. Las imágenes tienen variaciones en el clima, la posición y la orientación en relación con el semáforo</p>
<p>las imagenes se encuantran divididas, el dataset origianl con las imagenes a maxima resolución y las recortadas que son las que se utilizaron</p>

<p>
  Original
  <a href='https://dl.orangedox.com/KrVSsK' >Parte 1</a>,
  <a href='https://dl.orangedox.com/CMjgtX'>parte 2</a>.<br>
  Recortado
  <a href='https://drive.google.com/drive/folders/1qmkmT19F9kIjHz9BfVIA1UfixMP2YzqZ?usp=drive_link' >aquí</a>
</p>

<h3>MODELOS PROBADS</h3>

<ul>
  <li>GAUSSIAN NAIVE BAYES:</li><br>
  <p>Es una técnica de clasificación utilizada en Machine Learning (ML) basada en el enfoque probabilístico y la distribución gaussiana.</p>
  <p>Accuracy:  0.58</p>
  <img alt="Modelo de deteccion de estado de semaforos para ayudar a personas invidentes" src="https://github.com/cesenro2801/PROYECTO_IA/blob/main/IMG/GNB.jpeg" width="500" /><br><br>

  <li>RANDOM FOREST CLASSIFIER:</li><br>
  <p>Random forest es un  algoritmo de aprendizaje automático construye árboles de decisión en diferentes muestras y toma su voto mayoritario 
  para la clasificación y el promedio en caso de regresión.</p>
  <p>Accuracy:  0.66</p>
  <img alt="Modelo de deteccion de estado de semaforos para ayudar a personas invidentes" src="https://github.com/cesenro2801/PROYECTO_IA/blob/main/IMG/RFC.jpeg" width="500" /><br><br>

  <li>SUPPORT VECTOR MACHINE:</li><br>
  <p>El objetivo del algoritmo de la máquina de vectores de soporte es encontrar un hiperplano en un espacio N-dimensional (N: el número de características) que      clasifique claramente los puntos de datos. Para separar las dos clases de puntos de datos, se pueden elegir muchos hiperplanos posibles.</p>
  <p>Accuracy:  0.64</p>
  <img alt="Modelo de deteccion de estado de semaforos para ayudar a personas invidentes" src="https://github.com/cesenro2801/PROYECTO_IA/blob/main/IMG/SVC.jpeg" width="500" /><br><br>

  <li>REDES NEURONALES</li><br>
  <p>Es un método de la inteligencia artificial que enseña a las computadoras a procesar datos de una manera que está inspirada en la forma en que lo hace el         cerebro humano. Se trata de un tipo de proceso de machine learning llamado aprendizaje profundo, que utiliza los nodos o las neuronas interconectados en una        estructura de capas que se parece al cerebro humano. </p>
  <p>Accuracy:  0.95652 </p>
  <img alt="Modelo de deteccion de estado de semaforos para ayudar a personas invidentes" src="https://github.com/cesenro2801/PROYECTO_IA/blob/main/IMG/CNN.jpg" width="500" /><br><br>
  
</ul>


<h3>CONCLUSIONES</h3>

<ul>
  <li>En el desarrollo inicial del proyecto se plantea la construcción de un modelo de inteligencia artificial para detectar semáforos, tras la construcción de varios modelos con diferentes métodos se logra obtener un modelo funcional que ofrece entre un 95% a un 97% de accuracy el cual se puede considerar una exactitud bastante buena teniendo en cuenta que este es un modelo enfocado en ayudar a personas y el fallar puede implicar jugar con la vida de quienes lo utilicen.</li>
  <li>Durante el desarrollo se evidencio como en un principio con pocos datos los modelos como el GNB, RFC, SVC obtuvieron resultados de mas del 70% de exactitud pero al aumentar los datos estos empezaron a fallar mas y el modelo que mejoro significativamente fueron las redes neuronales, por lo que fue el modelo que se escogió para terminar de mejorar y obtener los resultados de exactitud mas altos.</li>
</ul>

<h3>ENLACES</h3>
<p>
  <a href='https://colab.research.google.com/drive/1-8hAYrW866cpjIFQPyUtU1sqMh48sdpx?usp=sharing' >CODIGO</a>,
  <a href='https://youtu.be/rQr6DRAEhRA'>VIDEO</a>,
  <a href='https://www.canva.com/design/DAForT5t3OM/RJqN-cI_buh3y-lzolcFWA/watch?utm_content=DAForT5t3OM&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink'>PRESENTACION</a>.<br>
</p>



