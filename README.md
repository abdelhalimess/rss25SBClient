# Projet RSS25 – Convertisseur et Uploadeur de flux RSS vers rss25SB

Ce projet permet de :

- Télécharger un flux RSS classique (ex : Le Monde)
- Le convertir au **format rss25SB**
- L’**envoyer** à un serveur Spring Boot déployé sur CleverCloud




## 🚀 Lancer les applications

- Ouvrez un terminal 


### `Rss25ConverterApp`

Application en ligne de commande qui **convertit un flux RSS classique vers rss25SB**.

Éxecutez la commande :

java -jar Rss25ConverterApp-jar-with-dependencies.jar


* Tapez un des choix des sources proposées (ex: lemonde)
* Le fichier `.xml` est généré dans le dossier courant



### `Rss25UploaderApp`

Application Swing qui **envoie un fichier rss25SB** au serveur.


Éxecutez la commande :

java -jar Rss25UploaderApp-jar-with-dependencies.jar


* Sélectionnez un fichier converti (ou conforme au format rss25)
* Il sera envoyé via HTTP POST au backend Spring (https://rss25sb-esselami.cleverapps.io/rss25/insert)

P.S : Remplacez le lien. 



## `RssConverterSwingApp`

Application Swing avec une interface graphique conviviale **convertit un flux RSS classique vers rss25SB**.

Éxecutez la commande :

java -jar Rss25SwingApp-jar-with-dependencies.jar


Fonctionnalités :

* Choix d’un flux RSS prédéfini
* Conversion vers rss25SB




## Abdelhalim ESSELAMI / Mohamed BENGUERAR – Étudiants en Master 1 GIL – Université de Rouen
