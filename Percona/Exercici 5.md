### 5.	Crea un usuari anomenat asix en el sistema operatiu i en SGBD de tal manera que aquest usuari del sistema operatiu no hagi d'introduir l'usuari i password cada vegada que cridem al client mysql?

1- Creem l'usuari en el sistema:

![](https://github.com/joelalcaraz/BBDD/blob/master/Imatges/14.png)

2- Creem l'usuari dintre del mysql

![](https://github.com/joelalcaraz/BBDD/blob/master/Imatges/15.png)

3- Automatitzem el log in:
  Amb les opcions: 
  ***[client]
  user=asix
  password=patata
  #database=database_name***
![](https://github.com/joelalcaraz/BBDD/blob/master/Imatges/16.png)

4- Comprovem que ho faci bé

![](https://github.com/joelalcaraz/BBDD/blob/master/Imatges/17.png)


