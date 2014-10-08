mag-programmez-2014
===================

Analyse des logs applicatifs avec ELK - Dossier DevOps - Programmez 2014

Vous devez installer les programmes suivant:
* Virtual Box
* Vagrant

La VM Vagrant est provisionnée par le fichier bootstrap.sh
Il configure l’ensemble de la stack, notamment :
* OS Debian 7.6 64-Bits
* Sun JDK 8 64-Bits
* Elasticsearch 1.3.4
* Logstash 1.4.2
* Kibana 3.1.0
* NGiNX 1.2.1

Lancement de la VM:
    
    vagrant up
    open http://localhost:19200
    open http://localhost:10080/kibana

Status de la VM:

    vagrant status


Connexion SSH à la VM:

    vagrant ssh


Stopper la VM:

    vagrant halt


Supprimer la VM:

    vagrant destroy


