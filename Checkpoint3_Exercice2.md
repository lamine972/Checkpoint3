## Q.2.1.1
Il suffit de faire un `adduser lamine` dans mon cas.

## Q.2.1.2
Je propose de l'ajouter au groupe au groupe sudo avce un `usermod -aG usermod lamine`

## Q.2.2.1

![ex2](./images/ex2_1.png)

## Q.2.2.2

Il faut rajouter la ligne suivante au fichier `AllowUsers lamine`.


## Q.2.2.3

![ex2](./images/ex2_2.png)

Il suffit juste de faire `PubkeyAuthentication yes` et `PasswordAuthentication no` 

## Q.2.3.1

![ex2](./images/ex3_3.png)


## Q.2.3.2


![ex2](./images/ex2_4.png)


## Q.2.4.1
Bareos-dir gère la configuration de l'ensemble du système.Bareos-sd gère le stocakge physique des sauvegardes.Bareos-fd est insatllé sur une machine à sauvegarder,il doit lire les fichiers à sauvegarder et les envoyer a storage daemon.


## Q.2.5.1

![ex2](./images/ex2_6.png)


## Q.2.5.2

Le port ssh(port 22),le protocole de ping ipv4 et ipv6 sont autorisés.


## Q.2.5.3
 Les connexions non reconnues et non établies par la machine ne sont pas autorisées

 ## Q.2.5.4


![ex2](./images/ex2_7.png)
 


