# Fiche 21 — Construire ton workflow IA-humain 🛠️

- **Type :** 🛠️ Pratique · **Nature :** ⚡ (l'outillage bouge) + ⏳ (le principe) · **Durée :** ~1 h · **Prérequis :** Fiches 19, 20
- **Terrain :** Les deux

## L'exercice

Tu construis **ton** processus reproductible de création de contenu IA-humain, puis tu le testes sur
un vrai contenu. Objectif : un workflow que tu pourrais suivre chaque semaine sans réfléchir.

### Livrable 1 — Le workflow documenté

Écris ta chaîne en étapes numérotées, en précisant **à chaque étape qui fait quoi (toi / IA)** et
**le garde-fou**. Il doit inclure, au minimum :
1. Choix de l'angle + insight vécu → **toi**.
2. Divergence (générer N options) → **IA** (colle ton prompt réel).
3. Convergence (choisir/trancher) → **toi**.
4. Rédaction/déroulé → IA assistée.
5. Passe de « désIAisation » (exemple réel, voix, aspérité) → **toi**.
6. Fact-check → **toi** (liste ce que tu vérifies).
7. Adaptation multi-format (fiche 25) → IA + ta relecture.

Inclure **le(s) prompt(s) system** que tu utiliseras vraiment (un pour générer des hooks, un pour
critiquer, un pour repurposer). Un bon prompt contient : ton contexte (qui, pour qui, ta voix), la
tâche précise, les contraintes (fiche 03/07), et le format de sortie.

### Livrable 2 — Un test réel

Fais tourner ton workflow sur **un** contenu (ex. un post InvoiceLab) et colle : la sortie brute de
l'IA **et** ta version finale après désIAisation. L'écart entre les deux est la preuve que ton
garde-fou humain sert à quelque chose.

## Grille de notation (/20)

| Axe | Ce que je regarde |
|---|---|
| **Spécificité** | Prompts concrets et réutilisables (pas « fais-moi un bon post ») ? Garde-fous précis ? |
| **Mécanique** | Divergence IA / convergence humaine bien séparées ; désIAisation + fact-check présents ? |
| **Clarté** | Le workflow est suivable par un toi pressé un lundi matin ? |
| **Adéquation** | La version finale a une vraie voix + un insight réel absent de la sortie brute ? |

Colle les 2 livrables dans `journal-de-progression.md`. Je note surtout **l'écart brut → final** :
s'il est faible, ton garde-fou humain est décoratif et tu publies de la moyenne (fiche 19).

## Anti-triche

- Le test doit montrer une **vraie** différence entre la sortie IA et ta version. Si elles sont
  quasi identiques, tu n'as pas fait le travail humain — c'est précisément le piège de la fiche 19.
- Ne colle pas un prompt « théorique » : colle celui que tu utiliserais *vraiment*, avec ton contexte.

## Explique-moi (Feynman)

Montre ton écart brut → final et explique en une phrase *ce que ta main humaine a ajouté* que l'IA ne
pouvait pas. Si tu ne trouves pas, refais la passe de désIAisation.

## Cartes de rappel → `revision-espacee.md`

- Workflow = toi (angle/choix/voix/fact-check) + IA (volume/déroulé/formats).
- Le prompt system contient : contexte + voix + tâche + contraintes + format.
- Test de validité : l'écart entre la sortie brute et ta version finale doit être net.
