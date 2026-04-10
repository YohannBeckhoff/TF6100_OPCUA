# Exemple OPC UA sous TwinCAT (Mode Local)

Ce projet est une démonstration simple de communication OPC UA en environnement TwinCAT, exécutée en mode local.

##  Configuration

### Serveur OPC UA
- **Utilisateur** : "ym"
- **Mot de passe** : "12345"

##  Clients

### Client PLC
- Communication OPC UA depuis le PLC TwinCAT via les IO

### Client TwinCAT HMI (ADS)
- Communication via protocole ADS (Automation Device Specification)

### Client TwinCAT HMI (OPC UA)
- Communication directe via OPC UA

##  Objectif

Ce projet a pour but d'illustrer :
- La mise en place d’un serveur OPC UA local sous TwinCAT
- La connexion de différents clients (PLC et HMI)
- La comparaison entre communication ADS et OPC UA

##  Remarques

- Configuration destinée à un environnement de test/local
- Adapter les identifiants pour un usage en production
