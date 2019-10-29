# Applied Deep Learning Project

### Project type: Bring your own method
The focus of this project type is to build or re-implement a neural network
architecture that operates on an existing dataset that is already publicly available.
Your method should reflect the state of the art, so it is fine to use an existing
implementation but you should alter it and attempt to find ways how you can improve the results.
You will get bonus points if you can improve the state of the art.

### Project Topic: Generative Adversarial Network (GAN)
#### Project Description
As the number of Pokemon in its universe is expanding with every new game, with its newest upcoming iteration being "Sword" and "Shield", coming up
with new designs is becoming increasingly more difficult for the creators. Our friendly neighbourhood newspaper for free [HEUTE](https://www.heute.at/s/-es-wird-immer-schwerer-neue-pokemon-zu-erfinden--46204996) conducted an interview
with one of their creators comfirming this assumption.
Ideas for new design usually are based of already something existing ones. For instance a lot of existing pokemon are based of on either
animals or plants and believe it or not this even includes things such as [gears](https://www.pokewiki.de/Klikk), [candles](https://www.pokewiki.de/Lichtel) and lamps.
As such using that line of thinking what if there is a way to create new Pokemon based on existing Pokemon?

The goal of this project is to use an existing dataset (refer "Possible Dataset") of pokemon images, training a GAN model that
creates new "Pokemons". This model will then be implemented and deployed as a very simple web application providing the user the possibility to generate new Pokemon
and assigning a name for the newly generated monster based one the existing names.

#### Extra features
After the main goal can be done before the given amount of time, the feautures listed below will be tackeled.
* Providing the user to generate a pokemon based on preferred type e.g. fire type pokemon

## Possible Dataset
* [Kaggle-Pokemon Image Dataset - labeled](https://www.kaggle.com/vishalsubbiah/pokemon-images-and-types#pokemon.csv)
* [Kaggle-Pokemon Image Dataset - unlabeled](https://www.kaggle.com/kvpratama/pokemon-images-dataset)

## Relevant Literature/Papers
* [Towards the Automatic Anime Characters Creation with Generative Adversarial Networks](https://arxiv.org/abs/1708.05509)
* [Improved Techniques for Training GANs](https://arxiv.org/abs/1606.03498)
* [How to Develop a Conditional GAN (cGAN) From Scratch](https://machinelearningmastery.com/how-to-develop-a-conditional-generative-adversarial-network-from-scratch/)

## Project Plan
### Preparing (3 Weeks estimate)
Studying the concept of GAN, different architectures and state of the art in DETAIL; adapting the available data set to my needs;  
### Testing (3 Weeks estimate)
Checking out possibilites and limitation, what kind of model e.g. styleGAN or other GANs can be used based on available resources. Development enviroment will
be GOOGLE COLAB (internet dependened), doing prototyping. 
### Implement (2 Weeks estimate)
Implement project properly
### Deploy (3 Weeks estimate)
Checking out how to create a web application and integrate it with the trained model.
### Reporting (1 Week)
Create Report and Presentation
