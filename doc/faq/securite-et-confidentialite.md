# Sécurité et confidentialité

### Qui peut lire mes données ?
Vous seul. Vos fiches, documents et budgets sont chiffrés **dans votre navigateur**, avec une clé dérivée de votre mot de passe, avant d'être envoyés. Le serveur ne stocke que des données illisibles. L'administrateur, l'hébergeur ou un pirate qui volerait la base ne voient que du chiffré.

### Que voit le serveur, alors ?
Le strict nécessaire au fonctionnement : votre e-mail, un journal technique des connexions, le nombre et la taille de vos documents, et les **dates** de vos rappels (sans le nom du contrat, sauf si vous activez les alertes détaillées). Ni les noms des collections, ni les montants, ni les noms de fichiers.

### Pourquoi la double authentification est-elle obligatoire ?
Parce que Clarion contient vos contrats, vos polices et votre budget. Un mot de passe seul peut fuiter (réutilisé sur un autre site, hameçonnage, logiciel espion). Avec le code du téléphone en plus, un voleur de mot de passe reste à la porte. Il n'y a aucune exception, administrateurs compris.

### Si Clarion est piraté, mes données sont-elles exposées ?
Le pirate obtiendrait des données chiffrées, inutilisables sans votre mot de passe. Il pourrait tenter de le deviner, mais chaque essai est volontairement lent (Argon2id) : un mot de passe long et unique le rend hors de portée.

### L'administrateur peut-il réinitialiser mon mot de passe ?
Non, et c'est voulu : s'il le pouvait, il pourrait aussi lire vos données. Seule votre **clé de récupération** permet de choisir un nouveau mot de passe. L'administrateur peut seulement réinitialiser votre double authentification, ce qui ne donne accès à rien.

### Le budget et les lettres sans compte envoient-ils quelque chose ?
Non. Tout est calculé dans votre navigateur ; rien n'est transmis ni conservé. C'est pourquoi il faut exporter le budget pour le reprendre plus tard.

### Qu'est-ce que « Mémoriser sur cet appareil » dans les lettres ?
Votre nom et votre adresse sont gardés dans le navigateur de **cet** appareil uniquement, pour ne pas les retaper. Décochez la case pour les effacer. Évitez-le sur un ordinateur partagé.

### Mes données sont-elles sauvegardées ?
Oui, chaque nuit, sous forme chiffrée, sur un second serveur. Les sauvegardes restent illisibles sans votre mot de passe. Après une suppression de compte, vos données disparaissent des sauvegardes au fil de leur rotation (6 mois au plus).

### Clarion me conseille-t-il ?
Non. Clarion calcule, compare et rappelle ; il ne recommande pas un produit et ne touche aucune commission. Les décisions restent les vôtres.
