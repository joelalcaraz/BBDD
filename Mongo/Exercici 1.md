### Procés per instal•lar MongoDB

1- Per començar crearem el fitxer amb la següent comanda: (he fet servir el editor VI ja que no tenia el nano instal•lat, però també funcionaria amb aquest últim)
![](https://github.com/joelalcaraz/BBDD/blob/master/ImatgesMongo/1.png)

2- Un cop dintre, haurem d’afegir tota la informació al repositori.
  ***[mongodb-org-3.4]  Name=MongoDB Repository  Baseurl=https://www.mongodb.org/static/pgp/server-3.4.asc***
    
![](https://github.com/joelalcaraz/BBDD/blob/master/ImatgesMongo/2.png)  

3- Abans de continuar, haurem d’assegurar-nos que s’ha creat el “repositori”:

![](https://github.com/joelalcaraz/BBDD/blob/master/ImatgesMongo/3.png)  
  Amb el repositori al sey lloc, ja podrem continuar la instal·lació

4- Per instal•lar farem servir la comanda Yum install mongdb-org , com es veu a continuació:
  Durant el procés, ens anirà preguntarà dues vegades si És correcte {s/N}:.El primer permets la instal•lació del paquet de MongoDB, en el segon, importes la clau GPG.
  ![](https://github.com/joelalcaraz/BBDD/blob/master/ImatgesMongo/4.png)  
  
  ![](https://github.com/joelalcaraz/BBDD/blob/master/ImatgesMongo/5.png)  

5- Un cop instal•lat, utilitzant la comanda Systemctl iniciarem el servei:

  ![](https://github.com/joelalcaraz/BBDD/blob/master/ImatgesMongo/6.png) 
  
  I per assegurar-nos que està en marxa consultarem el log del Mongo
  ![](https://github.com/joelalcaraz/BBDD/blob/master/ImatgesMongo/7.png) 
  
  Amb la última línia ens assegurem que està esperant una connexió, és a dir, que està en marxa.
  ![](https://github.com/joelalcaraz/BBDD/blob/master/ImatgesMongo/8.png) 

    

