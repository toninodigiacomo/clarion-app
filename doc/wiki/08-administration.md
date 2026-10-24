# 8. Administration

Menu **Administration**, réservé aux administrateurs. L'administrateur gère les comptes, **jamais les données** : il ne peut ni lire ni récupérer le contenu d'un coffre.

| Onglet | Usage |
|---|---|
| Aperçu | nombre de comptes, demandes d'accès en attente, état de la messagerie |
| Comptes | **inviter** une personne (lien valable 72 h), traiter les **demandes d'accès**, **réinitialiser la double authentification** d'un membre qui a perdu téléphone et codes, supprimer un compte |
| Messagerie | serveur d'envoi (SMTP) : hôte, port, chiffrement, identifiant et mot de passe. Pour Gmail, utilisez un **mot de passe d'application**. **Envoyer un e-mail de test** pour vérifier. |
| Modèles | textes des e-mails (invitation, rappel, alerte de sécurité…). Variables entre `{{ }}`, aperçu avec des valeurs d'exemple, **Rétablir** pour revenir au texte d'origine. |
| Annonces | envoyer une annonce (nouveautés, risque de sécurité, évolution) à tous, aux membres ou aux administrateurs. Le désabonnement est respecté, sauf pour les alertes de sécurité. |

Les e-mails partent par une file d'attente traitée chaque minute : un envoi peut prendre jusqu'à une minute.

← Retour au [sommaire](README.md)
