# projet-django
les etapes pour pouvoir creer un projet django:

1-creer un environnement virtuel
 on le cree pour isoler notre projet : python-m venv venv
 actvation de l'environnement: ./venv/Scripts/activate

2-Installation de django
avant de commencer il faut s'assurer d'avoir installer django avec la commande pip install django via le terminal

3- creer un projet
-initialisation d'un nouveau projet avec la commande django-admin startproject mon_projet dans le terminal et
-on navigue dans le repertoire avec cd nom_projet
-demarer le serveur avec python manage.py runserver

4-creer une application django
-creer une application django avec : python manage.py startapp mon_application
-ajouter l'application dans au projet : on ouvre le seeting et dans install app on met le nom de l'application

5-Configuration de la base de donneé
-django utilise un base de donneé par defaut qu'on peut le remplacer en fonction de la bd qu'on utilise et parametrer
-on peut faire la migration initial avec python manage.py migrate

6-creer des modeles dans l'application
on cree et on applique les migrations pour nos modeles avec la commande:
 python manage.py migrations
 python manage.py migrate

7-creer des vues et des urls dans l'application
-dans views.py on cree les vues 
-dans urls.py on cree les chemins pour notre vues

8-creation du templates
Configuration du seeting.py et on va dans la partie templates

9-Configuration de l'admin
avec la commande python manage.py createsuperuser

10-On 







