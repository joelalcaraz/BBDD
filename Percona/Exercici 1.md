**Primer cargarem la màquina on tenim el nostre CentOS i ens loguejem amb ella amb les credencials.**
![](https://github.com/joelalcaraz/BBDD/blob/master/Imatges/1.png)

1- Instal·lem els repositoris del Percona Server
  Per fer-ho executarem la següent comanda ***yum install http://www.percona.com/downloads/percona-release/redhat/0.1-4/percona-release-0.1-4.noarch.rpm***
![](https://github.com/joelalcaraz/BBDD/blob/master/Imatges/2.png)

2- Confirmarem que s'han instal·lat correctament els repositoris
  Ho farem amb la comanda: ***yum list | grep percona***
  
  ![](https://github.com/joelalcaraz/BBDD/blob/master/Imatges/4.png) 
  
  Aquesta comanda ens mostrarà la llista dels paquets del repositori
  
  ![](https://github.com/joelalcaraz/BBDD/blob/master/Imatges/5.png)
  
3- Un cop comprovat, podrem instal·lar els paquets del percona server
  Utilitzant la comanda: ***yum install Percona-Server-server-57***
  
  ![](https://github.com/joelalcaraz/BBDD/blob/master/Imatges/6.png)
  
  Finalment s'ens mostrarà un resum de la transacció i dels paquets que la composen incluint els dependents. (Haurem de confirmar-los)
  
  ![](https://github.com/joelalcaraz/BBDD/blob/master/Imatges/7.png)
  
  ![](https://github.com/joelalcaraz/BBDD/blob/master/Imatges/8.png)
  
  Un cop haguem confirmat, començarà la instal·lació.
  ![](https://github.com/joelalcaraz/BBDD/blob/master/Imatges/9.png)
