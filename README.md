# AT&T Spam Detector Machine Learning

<img src="img/image.jpg" alt="Image" width="50%" height="50%">


## A FAIRE

- Ajouter des explications dans le notebook


## Introduction

Introduction...


## Clone du repo

Pour cloner le repo, utilisez la commande suivante :

`git clone https://github.com/Clementbroeders/spam-detector-ml.git`


## Comment ça marche ?

Pour réaliser cette étude, AT&T nous a fourni une liste de **5500 sms** déjà labellisés. Parmi ces sms, **13.4% sont des spams**.

Nous utilisons l'algorithme LSTM de deep learning pour déterminer le caractère spam ou non. Le LSTM est un type d'architecture de réseau de neurones récurrents (RNN) qui est particulièrement bien adapté pour traiter des séquences de données, comme des séquences de mots dans un texte.


# Etapes

Le notebook est entièrement automatisé et disponible à la racine du repo : `notebook.ipynb`

Une fois lancé, le modèle est créé, puis enregistré au chemin suivant : `src/model.h5`. Les métriques sont également enreigstrées au chemin suivant : `src/model_history.json`