# test-univ-tours

Projet test pour montrer l'utilisation 

ce que le projet va \*\*permettre\*\* :

* Récupérer les messages
* Les stocker en BDD
* Les afficher
* Utiliser Node-RED

Ajouter une image : 

![diode](diode.png)

```mermaid
flowchart TD
    mosquitto[seveur<br>mosquitto] --> |messages| Rpi[Raspberry Pi<br>Node-RED<br>documentation] 
    Rpi--> BDD
    Rpi <--> Github
```