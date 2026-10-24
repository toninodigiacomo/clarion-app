# 5. Budget

Menu **Budget**. Utilisable **avec ou sans compte**.

## Remplir

- **Partir d'une grille type** propose les postes habituels en Suisse (loyer, LAMal, impôts, Serafe…), montants à zéro. Supprimez ce qui ne vous concerne pas avec **×**.
- **+ Ajouter une ligne** dans Revenus ou Dépenses : libellé, catégorie, montant, périodicité.
- Périodicité **Unique** : un montant payé une fois, réparti sur le nombre de mois indiqué.

En haut : revenus, dépenses, **solde** et **taux d'épargne**, en vue **Mensuel** ou **Annuel**. À droite : la répartition des dépenses par catégorie.

## Avec un compte

- **Ajouter mes contrats** reprend la prime de chaque fiche contrat (marquée « contrat »). Relancé plus tard, il met à jour les montants qui ont changé, sans doublon.
- **Enregistrer** chiffre le budget et le range dans la collection choisie.

## Sans compte

Rien n'est envoyé ni conservé : **Exporter JSON** ou **Exporter CSV** pour garder votre travail, puis **Importer…** pour le reprendre.

Le CSV s'ouvre directement dans Excel ou Numbers (séparateur « ; »). Pour en préparer un à la main, les colonnes sont :

```
type;categorie;libelle;montant;periodicite;etalement_mois
revenu;salary;Salaire net;6200;mois;
depense;housing;Loyer;1850;mois;
depense;transport;Garantie voiture;1800;unique;24
```

Périodicités : `mois`, `trimestre`, `semestre`, `an`, `unique`.

→ Suite : [6. Lettres](06-lettres.md)
