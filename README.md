# Culturedentreprise3
Le but c'est de pouvoir creer un site web et de pouvoir le tester dans un environnement contenant mysql, apache, php, phpmyadmin et firefox.

Probleme: Coté firefox et un morceau d'apache a été mis en commentaire car firefox se lancé bien dans un contenaire mais lors de l'affichage du serveur, il affiché "403 forbidden " un probleme de permission que je n'ai pas reussi a resoudre.

Conseil d'utilisation:

1/ Récuprer tout le dossier 

2/ Mettre les pages web dans le dossier "site", pour la BD recuperer avec un export dans votre phmyadmin votre BD ((Non-fonctionnel/voir plus bas)->et la BD dans le dossier "db")

3/ Dans un terminal, se rendre dans le dossier recuperé et faire un docker-compose up

4/ Comme j'ai mis en commentaire la partie firefox qui ouvré automatiquement firefox

  Il faut: 
  
          -ouvrir votre navigateur
          
          -mettre en adresse:
          
                              "localhost" ou 172.19.0.1 pour acceder a notre site
                              
                         Ou    entre 172.19.0.2 à 172.19.0.5 pour acceder a phpmyadmin selon l'ordinateur
                         


Plus:

MYSQL_ROOT_PASSWORD: azerty

MYSQL_USER: jojo

MYSQL_PASSWORD: azerty

                         
                         
PMA_HOSTS: db

PMA_PORT: 3306
            
          
          
