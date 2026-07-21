# Fiche 31 — Data 2 : lire un A/B test sans se mentir

- **Type :** 🧠 Théorie · **Nature :** ⏳ Intemporel · **Durée :** ~1 h · **Prérequis :** Fiche 30
- **Terrain :** —

## Objectifs

1. Comprendre pourquoi la plupart des « tests » de petit compte ne prouvent rien.
2. Connaître les 4 pièges statistiques qui te font tirer de fausses conclusions.
3. Savoir quand une différence est un signal vs du bruit.

## 1. Le principe d'un A/B test

Tu changes **une** variable (le hook, la miniature, le prix, le CTA) entre deux versions et tu
mesures laquelle performe mieux sur *une* métrique actionnable (fiche 30). But : remplacer l'opinion
(« je pense que ce hook est meilleur ») par la preuve (« A convertit mieux que B »).

Règle d'or : **une seule variable à la fois.** Si tu changes le hook *et* le visuel *et* l'heure, tu
ne sauras jamais ce qui a causé la différence. La discipline de l'isolement est ce qui sépare un test
d'une impression.

## 2. Le problème n°1 du solo : la taille d'échantillon

Une différence sur **petit volume ne prouve rien.** « Version A : 3 ventes, version B : 1 vente » ne
veut *rien* dire — c'est dans le bruit du hasard. Il faut assez d'observations pour que la différence
soit peu susceptible d'être due à la chance (c'est la **significativité statistique**).

Sans faire de maths lourdes, retiens l'intuition :
- Plus l'effet est petit, plus il faut d'échantillon pour le détecter.
- Sur 20 ou 50 événements, seules des différences **énormes** sont crédibles ; les petites sont du
  bruit.
- En petit budget, tu testeras souvent des choses à **fort effet** (un hook radicalement différent),
  justement parce que tu ne peux pas détecter les petits effets. C'est une stratégie, pas un défaut.

## 3. Les 4 pièges qui te font mentir

1. **Survivorship bias.** Tu étudies les gagnants (les vidéos virales, les comptes à succès) et tu
   copies leurs traits — en ignorant les milliers qui ont fait pareil et échoué. Le trait « visible »
   n'est peut-être pas la cause. Antidote : demande « qu'ont fait ceux qui ont *échoué* en faisant
   pareil ? ».
2. **Cherry-picking.** Tu retiens le test qui confirme ton idée et tu oublies les autres. Antidote :
   décide *à l'avance* de la métrique et du critère de succès, avant de voir les résultats.
3. **Corrélation ≠ causalité.** « J'ai posté à 18 h et ça a marché » → ce n'est peut-être pas
   l'heure, mais le contenu, le sujet, un partage chanceux. Antidote : ne change qu'une variable,
   répète.
4. **Regression to the mean.** Après un post exceptionnel (haut ou bas), le suivant tend à revenir
   vers ta moyenne — pas parce que tu as « perdu la main » ou « trouvé la formule », mais par simple
   statistique. Antidote : juge sur des séries, pas sur un pic.

## 4. Quand agir malgré l'incertitude

Tu n'auras presque jamais de certitude statistique parfaite en solo. La bonne posture :
- Cherche des **effets gros et répétés**, pas des micro-différences.
- Fais des **paris révisables** : décide, mesure, garde ou jette — vite et souvent (fiche 34,
  testing créatif).
- Accepte que beaucoup de « victoires » soient du bruit. L'humilité statistique est une compétence,
  pas une faiblesse : elle t'évite de construire sur du sable.

## Explique-moi (Feynman)

Explique à voix haute pourquoi « Version A a fait 3 ventes, Version B en a fait 1, donc A est
meilleure » est probablement faux, avec le mot « hasard ».

## Quiz génératif

1. Pourquoi ne changer qu'une variable à la fois ? Que perds-tu si tu en changes trois ?
2. Un compte viral fait « du contenu brut authentique ». Quel biais te guette si tu copies ça
   aveuglément, et quelle question corrige le tir ?
3. Tu postes ton meilleur contenu de l'année, le suivant fait moins bien. Deux explications : « j'ai
   perdu la main » ou la statistique. Laquelle et pourquoi ?
4. Sur 30 ventes, tu vois +1 vente pour le prix à 24 € vs 19 €. Conclusion raisonnable ?

## Cartes de rappel → `revision-espacee.md`

- Une seule variable par test ; petit volume = pas de preuve (bruit).
- 4 pièges : survivorship, cherry-picking, corrélation≠causalité, régression vers la moyenne.
- En solo : tester des effets gros, faire des paris révisables, accepter que beaucoup de « wins » soient du bruit.
