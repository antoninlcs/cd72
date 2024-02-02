# Rapport quotidien 

## 8/01/2024

- Redécouverte environnement de travail 
- Analyse du besoin qui va s'étendre sur la première semaine 
- Teste de l'outil vagrant 

## 9/01/2024 

- Utilisation plus appronfondie de vagrant 
- Début de la documentation 

### Problèmes 

Blocage au niveau du proxy qui empêche la vm d'accèder a certains site ou faire des apt-update 

## 10/01/2024 

- Utilisation de vagrant 
- Poursuite  de la documentation 


## 11/01/2024 

- Utilisation de vagrant 
- Fin de la documentation 

## 12/01/2024

- Début du projet donné par mon tuteur (Déployer automatiquement des Vm sur un hyperviseur avec des provisionneur selon le besoin du CD72)
- Analyse du besoin (Choix de l'hyperviseur ainsi que du provisionneur)

## 13/01/2024

- Choix de l'hyperviseur qui sera promox 
- Lecture de la documentation promox pour l'installer sur un serveur le 16/01/2024
- Choix du stockage LVM ou ZFS 

## 15/01/2024

- Analyse du besoin (Choix de l'hyperviseur ainsi que du provisionneur)
  
## 16/01/2024

- Suite a l'analyse de vendredi et lundi on a décidé de partir sur l'hyperviseur Proxmox
  
## 17/01/2024

- Installation en mode test de proxmox sur une veille machine en attendant un serveur de test qui sera mis en place 

## 18/01/2024

- Mise en place du serveur avec promox dessus 
- Configuration du stockage ( LVM-Thin ) sur proxmox

## 19/01/2024

- Manipulation du provisionner ( Terraform ) pour déployer les marchines automatiquement sur Proxmox

## 22/01/2024

Poursuite de la manipulation de Terraform. On résous des problème de syntaxe, d'accès erreur par erreur.

## 23/01/2024

Poursuite de la manipulation de Terraform. On résous des problème de syntaxe, d'accès erreur par erreur.

## 24/01/2024 

Message de l'ANSSI reçu par le département qu'il y a une fuite des données qui provienne du portail.sarthe.fr sur des blogs de hacker 
Pas de connexion de la journée le temps de résoudre le problème

## 25/01/2024

A ce jour, j'arrive a déployer une vm avec une configuration de base (Hostname, OS, IP, DNS, SSHKEY, user, password)

## 26/01/2024

Etude pour pouvoir combiné ansible + terraform. Ansible va servir a installer des services ( Apache, MariaDb) sur la vm lors de l'installation 

## 29/01/2024

Toujours entrain d'étudier ansible 

## 30/01/2024

Absent en raison de l'entretien pour intégrer le CESI