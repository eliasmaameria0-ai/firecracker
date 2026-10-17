# Stratégie : Order Blocks 5 étoiles

Source : vidéo « les 4 secrets des order blocks » (Casper). Méthode retenue par l'utilisateur.

## Définition
- **Order block (OB)** : la fin de l'accumulation et le début de l'expansion. C'est la **dernière bougie inverse** avant un mouvement violent.
  - OB haussier = dernière bougie baissière avant le rally haussier → zone d'**achat** au retour du prix.
  - OB baissier = dernière bougie haussière avant le rally baissier → zone de **vente** au retour du prix.
- Les OB existent sur toutes les unités de temps (1 min, 5 min, 15 min, 1h, 4h) : le marché est fractal.

## Les 5 étoiles (un OB ne se trade qu'à 5/5)
1. ★ **OB valide** : accumulation puis mouvement violent qui casse la structure.
2. ★ **Tendance** (secret 1, le plus important) : l'OB est dans le sens de la structure de marché.
   On n'achète pas en structure baissière et on ne vend pas en structure haussière. Toujours identifier la tendance **avant** de chercher un OB.
3. ★ **Imbalance** (secret 2) : le mouvement après l'OB libère un FVG net, pas une petite imbalance.
   En haussier, le haut de la bougie 1 ne touche pas le bas de la bougie 3. Cela prouve que la smart money est entrée.
4. ★ **Non mitigé** (secret 3) : la zone est vierge. Dès que le prix l'a touchée une fois, on ne la trade plus : les ordres ont déjà été fermés.
5. ★ **Liquidité** (secret 4) : l'OB a pris de la liquidité avant de partir (equal lows/highs, swing précédent chassé).
   Une poche de liquidité intacte juste au-dessus ou au-dessous de l'OB = risque de se faire stopper.

## Exécution
- Entrée au premier retour du prix dans un OB 5★.
- Stop juste derrière l'OB.
- Risque fixe par trade (1 % conseillé, jamais plus de 2 %).
- Take profit selon un ratio R:R (2R à 3R par défaut), éventuellement partiels.
- Journaliser chaque trade avec son nombre d'étoiles pour mesurer le vrai taux de réussite.

## Outils
- Indicateur TradingView : `order_blocks_5_etoiles.pine` (même dossier).
- Assistant web (analyse de capture, checklist, calcul de position, journal) : https://claude.ai/artifact/RZU2aojDsb9SoWofAn5wLB
