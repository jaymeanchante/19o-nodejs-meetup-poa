# 19o-nodejs-meetup-poa

Repository containing presentation + code for my talk in the [19º Node.js Meetup](https://github.com/jayme-anchante/19o-nodejs-meetup-poa)

## abstract

Title: Artificial intelligence and data science in the JavaScript ecosystem  
By: Jayme Anchante  
Description: What is artificial intelligence. What is the difference between machine learning, deep learning. Main Node.js libraries: tensorflow, brainjs, scikit-learn. Livecoding training an algorithm in JavaScript

## resumo

Título: Inteligência artificial e ciência de dados no ecossistema JavaScript  
Por: Jayme Anchante  
Descrição: O que é inteligência artificial. Qual a diferença para aprendizado de máquina, aprendizado profundo. Principais bibliotecas de nodejs: tensorflow, brain, scikit-learn entre outros. Livecoding treinando um algoritmo em JavaScript

# presentation

In order to compile the presentation you need [sent](https://tools.suckless.org/sent/). Please make sure you have all dependencies installed in your system, then:

```
mkdir -p sent &&
cd sent &&
wget https://dl.suckless.org/tools/sent-1.tar.gz &&
tar -xvzf sent-1.tar.gz &&
make &&
sudo make install &&
cd .. &&
rm -r sent &&
sent presentation
```

# case

The [iris dataset](https://en.wikipedia.org/wiki/Iris_flower_data_set) is a canonical dataset which includes 150 samples containing 50 samples of each of the 3 classes: setosa, virginica e versicolor. This is a simple implementation containing a train pipeline in [Python](https://www.python.org/) which transpiles a JavaScript model file, which is then used by the frontend. The code is hosted [here](https://github.com/jayme-anchante/iris-prediction)

The presentation explaining the model inner workings can be found [here](https://github.com/jayme-anchante/iris-prediction)
