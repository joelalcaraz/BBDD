### Accedim a MongoDB

1-	Per entrar a la Shell de MongoDB, escriurem simplement mongo:

![](https://github.com/joelalcaraz/BBDD/blob/master/ImatgesMongo/9.png)

2-	En cas que ens surti un avis dient el següent haurem de sortir del promt de mongo utlitzant exit, seguir els passos següents i tornar a entrar a mongo, un cop finalitzats:
    Haurem de modificar el número de processos que fa, editant el fitxer: 
    
![](https://github.com/joelalcaraz/BBDD/blob/master/ImatgesMongo/10.png)

    ***/etc/security/límits.d/20-nproc.conf ***
    
    I afegint al final de l’arxiu:
    
    ***Mongod soft nproc 32000***
    
    Un cop guardem i sortim de l’arxiu, utilitzant la comanda *systemctl*:
    
    ***Systemctl restart mongod***
    
3-	Per veure que estem dintre del mongo, escriurem db.help()

![](https://github.com/joelalcaraz/BBDD/blob/master/ImatgesMongo/11.png)

4-	Per acabar, ens assegurarem que  MongoDB s’inicïi amb el sistema. Per fer-ho utilitzarem la comanda systemctl


![](https://github.com/joelalcaraz/BBDD/blob/master/ImatgesMongo/12.png)


    Amb una resposta de 0, ens assegurem que el dimoni (servei) està activat, que és el que volem.
    En cas contrari, que surti un 1, utilitzarem la següent comanda:
    
    
![](https://github.com/joelalcaraz/BBDD/blob/master/ImatgesMongo/13.png)

    
    
