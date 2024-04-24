# devoir
## MYSQL
Télécharger la source: https://dev.mysql.org

Décompresser le paquet avec la commande :
```bash
$tar -zxvf  *tar.gz
```

Création d’un nouveau dossier 

Entrer dans le nouveau dossier 

Recensement des dépendances dans ce nouveau dossier : 
```bash
$cmake..
``` 

### On constate différentes erreurs :

-Erreur : Openssl 

--Résolution : Installer openssl avec la commande : 
```bash
#apt-get install libssl-dev openssl 
```
-Erreur : ncurses5

--Résolution : Installation à partir code source :
```bash
#apt-get libncurses5-dev
```
-Erreur : libxml2

--Résolution :
```bash
#apt-get install libxml2-dev
```
-Erreur : zlib

--Résolution: 
```bash
#apt-get install zlib1g-dev
```

```bash
#cmake
```

Exécution et compilation du contenu du fichier makefile : 
```bash
#make
```

Partager et copier les sources à travers l’arborescence ,installer les fichiers dérivés de la commande make avec la commande 
```bash
#make install
```

```bash
$echo export PATH=$PATH:/usr/local/mysql/bin >> ~/.bashrc
```



## APACHE
Télécharger la source: https://httpd.apache.org 

Décompresser le paquet avec la commande : 
```bash
$tar -zxvf *tar.gz
```

Recensement des dépendances à partir du commande:
```bash
$./configure
```

### Les différentes erreurs :

-Erreur : inexistance de bibliothèque

--Résolution : 
```bash
#apt-get install libapr1-dev
```

-Erreur : APR-util not found 

--Résolution :
```bash
#apt-get install libaprutil1-dev
``` 

-Erreur : pcre(2)config for libpcre not found 

--Résolution : 
```bash
#apt-get install libpcre2-dev
```

```bash
#./configure
```

Exécution et compilation du contenu du fichier makefile :
```bash
#make
```

Partager et copier les sources à travers l’arborescence ,installer les fichiers dérivés de la commande make avec la commande
```bash
#make install
```

```bash
$echo export PATH=$PATH:/usr/local/apache/bin >> ~/.bashrc
```

## PHP
Télécharger la source: https://php.net

Décompresser et désarchiver le paquet: 
```bash
$tar -zxvf *tar.gz
```

Recensement des dépendances à partir du commande:
```bash
$./configure
```

### L’erreur :

-Erreur : sqlite3

--Résolution : 
```bash
#apt-get install libsqlite3-dev
```

```bash
#./configure
```

Exécution et compilation du contenu du fichier makefile :
```bash
#make
```

Partager et copier les sources à travers l’arborescence ,installer les fichiers dérivés de la commande make avec la commande 
```bash
#make install 
```
