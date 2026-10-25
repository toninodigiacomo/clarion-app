# 9. Assistant IA

L'assistant lit une police en PDF et propose les champs de la fiche. **Vous validez chaque champ** : rien n'est rempli sans votre accord.

Clarion ne fournit pas d'IA : vous utilisez **vos propres clés** (Google Gemini, Anthropic Claude ou OpenAI). Les appels partent **directement de votre navigateur** vers le fournisseur ; le serveur Clarion ne voit ni la clé, ni le texte, ni la réponse.

## Configurer une clé

**Compte → Assistant IA**

1. Créez une clé chez le fournisseur (lien **Obtenir une clé**). Google propose une offre gratuite.
2. Collez la clé, cochez le fournisseur, choisissez un **modèle** : ceux recommandés par l'administrateur, ou **Charger les modèles de ce fournisseur**.
3. **Tester la clé**, puis **Enregistrer**. Les clés sont chiffrées dans votre coffre.

Avec plusieurs clés, l'ordre (flèches ↑ ↓) fixe la priorité. Si un fournisseur échoue (clé refusée, quota épuisé, panne), Clarion essaie le suivant et vous dit lequel a répondu. Une clé refusée est marquée **clé à vérifier**.

## Analyser une police

1. **Coffre → Documents** : déposez la police (PDF), puis **Analyser avec l'IA**.
2. Clarion lit le PDF dans votre navigateur et **masque vos données personnelles** (nom, adresse, n° AVS, IBAN, n° de police, téléphone, e-mail) par des marqueurs. **Voir le texte exact qui sera envoyé** permet de le vérifier ; **Masquer aussi** ajoute d'autres termes.
3. **Lancer l'analyse**. Les vraies valeurs sont remises dans la réponse, chez vous.
4. Cochez les champs et couvertures que vous retenez (vous pouvez corriger le fournisseur, la référence et l'objet), choisissez **une nouvelle fiche** ou une fiche existante, puis **Ouvrir la fiche avec ces champs**.
5. Vérifiez la fiche et **Enregistrez**. La police y est liée automatiquement.

## Limites

- Les **PDF scannés** (images sans texte) ne sont pas encore lus : saisissez la fiche à la main.
- Le masquage est un filet de sécurité, pas une garantie : jetez un œil à l'aperçu pour un document sensible.
- Seuls les 60 000 premiers caractères sont envoyés (environ 20 pages).

→ Suite : [10. Comparer à garanties égales](10-comparateur.md)
