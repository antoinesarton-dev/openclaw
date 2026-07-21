# Fiche 32 — Analyser un funnel & décider quoi tester 🛠️

- **Type :** 🛠️ Pratique · **Nature :** ⏳ Intemporel · **Durée :** ~1 h · **Prérequis :** Fiches 30, 31
- **Terrain :** InvoiceLab (ou boutique)

## L'exercice

Tu prends un funnel (réel si tu as des chiffres, sinon des chiffres plausibles que tu poses) et tu
fais le travail d'un vrai analyste : trouver le goulot, décider **un seul** test, et écrire son
protocole.

### Livrable 1 — Le funnel chiffré

Dessine le funnel d'InvoiceLab (ou de la boutique) avec un taux de passage à chaque étape. Ex pour
InvoiceLab :

```
Vues vidéo courte : 10 000
 → clics profil/bio : 300 (3 %)
   → visites landing : 200 (67 %)
     → essais (facture créée) : 60 (30 %)
       → passage Pro : 3 (5 %)
```

Marque **l'étape où le taux chute le plus** (le goulot). Justifie en une phrase pourquoi c'est *là*
qu'il faut agir et pas ailleurs (fiche 30).

### Livrable 2 — La décision de test

- **Une seule hypothèse**, formulée proprement : « Si je change [X], alors [métrique] passera de [a]
  à [b], parce que [raison psycho/algo] ». (X = une seule variable, fiche 31.)
- **La métrique de succès décidée à l'avance** et le seuil (pour éviter le cherry-picking).
- **La taille d'échantillon minimale** que tu attends avant de conclure (ordre de grandeur : assez
  pour que ce ne soit pas du bruit, fiche 31).
- **Ce que tu feras** si A gagne / si B gagne / si c'est trop serré.

## Grille de notation (/20)

| Axe | Ce que je regarde |
|---|---|
| **Spécificité** | Taux chiffrés, goulot identifié précisément, hypothèse concrète |
| **Mécanique** | Bon goulot (le plus gros drop) ; une seule variable ; métrique + seuil fixés *avant* |
| **Clarté** | Le protocole est exécutable tel quel |
| **Adéquation** | Le test attaque le vrai levier du projet, pas un détail cosmétique |

Colle les 2 livrables dans `journal-de-progression.md`. Je vérifie surtout que tu attaques **le bon
goulot** (l'erreur n°1 : optimiser une étape déjà bonne) et que ton test isole une variable.

## Anti-triche

- Ne choisis pas le goulot « le plus facile à corriger » : choisis **celui qui perd le plus de
  monde**. C'est tout l'enjeu.
- Fixe ta métrique de succès **avant** de fantasmer le résultat, sinon tu te prépares un
  cherry-picking (fiche 31).

## Explique-moi (Feynman)

Montre ton funnel et explique en une phrase pourquoi améliorer l'étape que tu as choisie aura plus
d'impact que d'améliorer n'importe quelle autre.

## Cartes de rappel → `revision-espacee.md`

- Trouver le goulot = la plus grosse chute de taux, pas le plus facile à corriger.
- Hypothèse = une variable + métrique + seuil décidés avant le test.
- Prévoir la décision (garder/jeter) à l'avance.
