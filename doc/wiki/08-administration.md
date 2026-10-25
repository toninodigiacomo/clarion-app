# 8. Administration

Menu **Administration**, réservé aux administrateurs. L'administrateur gère les comptes, **jamais les données** : il ne peut ni lire ni récupérer le contenu d'un coffre.

| Onglet | Usage |
|---|---|
| Aperçu | nombre de comptes, demandes d'accès en attente, état de la messagerie |
| Comptes | **inviter** une personne (lien valable 72 h), traiter les **demandes d'accès**, **réinitialiser la double authentification** d'un membre qui a perdu téléphone et codes, supprimer un compte |
| Messagerie | serveur d'envoi (SMTP) : hôte, port, chiffrement, identifiant et mot de passe. Pour Gmail, utilisez un **mot de passe d'application**. **Envoyer un e-mail de test** pour vérifier. |
| Modèles | textes des e-mails (invitation, rappel, alerte de sécurité…). Variables entre `{{ }}`, aperçu avec des valeurs d'exemple, **Rétablir** pour revenir au texte d'origine. |
| Annonces | envoyer une annonce (nouveautés, risque de sécurité, évolution) à tous, aux membres ou aux administrateurs. Le désabonnement est respecté, sauf pour les alertes de sécurité. |
| IA | la liste des **modèles recommandés** par fournisseur (un par ligne, `identifiant \| libellé`). Aucune clé n'est stockée ici : chaque membre utilise la sienne. |
| Journaux | **Sécurité** : connexions, échecs, changements de compte, actions sur les coffres (jamais leur contenu), filtrables par catégorie et par e-mail ou IP ; conservé un an. **E-mails** : envoyés, en attente ou en échec, avec la cause de l'échec et un bouton **Relancer**. **Erreurs serveur** : la cause technique des « Erreur interne » vues par les membres ; conservées 90 jours. Un compteur rouge sur l'onglet signale les erreurs des dernières 24 h et les e-mails en échec. |

Les e-mails partent par une file d'attente traitée chaque minute : un envoi peut prendre jusqu'à une minute.

→ Suite : [9. Assistant IA](09-assistant-ia.md)
