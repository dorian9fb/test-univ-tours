# test-univ-tours

Projet test pour montrer l'utilisation 

ce que le projet va **permettre** :

* Récupérer les messages
* Les stocker en BDD
* Les afficher
* Utiliser Node-RED
=====================================================================
Ajouter une image : 

![diode](diode.png)

====================================================================
```mermaid
flowchart TD
    mosquitto[seveur<br>mosquitto] --> |messages| Rpi[Raspberry Pi<br>Node-RED<br>documentation] 
    Rpi--> BDD
    Rpi <--> Github
```

```mermaid
flowchart TD
    github -->|git clone URL| local
    local --> |git push origin main| github
    github --> |git pull origin main| local
    local --> |edition / creation<br> fichier| local
    local --> |git add file1 file2| index
    index --> |git commit -m...| local
```
=====================================================================
Commande utile :
git init,Initialise --> un nouveau dépôt Git
git clone <url>  --> Clone un dépôt distant
git status --> Affiche l’état des fichiers (modifiés, ajoutés, etc.)