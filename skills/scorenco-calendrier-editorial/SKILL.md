---
name: scorenco-calendrier-editorial
description: Construire le calendrier éditorial mensuel Score'n'co (FB/IG, LinkedIn, Meta Ads) à partir du Google Sheet existant, de la charte, des bilans de campagnes et des temps forts du sport amateur.
---

# Calendrier éditorial mensuel Score'n'co

> Copie de référence. Pour l'utiliser dans Claude, il faut l'installer depuis la carte de proposition de skill. Ce fichier ne l'installe pas.

## 1. Lire l'existant (toujours en premier)
- Google Sheet « Score'n'co - Calendrier Éditorial Social Media » (id 1Y9ztuqcvgLzDl-plb6RPakrlqE47NKf7ZfaFsQSbxtc) : l'onglet du mois cible (brouillons déjà posés), les 2 mois précédents, le même mois l'année précédente, et l'onglet « Linkedin ».
- Les commentaires client (colonne « Commentaires client ») ont valeur de règles. Exemples : convocations = matchs uniquement ; écrire « le point » plutôt que « le but » ; sourcer chaque statistique.
- Les derniers bilans (Drive, voir `sources/README.md` de ce dépôt) : ce qui a marché, les formats gagnants, les KPI de référence des campagnes.

## 2. Rechercher les temps forts du mois
Une recherche web par sujet : tours de Coupe de France (masculine et féminine), compétitions internationales, Téléthon, journées mondiales, trêves, fêtes. Noter la source de chaque date dans `sources/web.md`.

## 3. Cadence
- 3 posts FB/IG, 2 posts LinkedIn (+ un texte de repartage pour le profil), 1 campagne Meta Ads par mois. Les stories sont en option.
- Heures indicatives : FB/IG à 12h30 ou 18h30, LinkedIn à 8h30 du mardi au jeudi. Un texte qui parle du week-end se publie le jeudi.

## 4. Règles de contenu
- Un gabarit (G1 à G5) par ligne. Les 5 sont couverts sur deux mois.
- Au moins 4 sports par mois. Priorité aux sports sous-représentés dans l'historique : hockey sur glace, rink-hockey, roller-hockey, volley, et les équipes féminines.
- Ne pas reprendre l'angle d'un post du même mois l'année précédente.
- Chiffres autorisés : ceux déjà validés (avec leur année) et « plus de 3 000 clubs utilisent les widgets ». Tout le reste se met entre [CROCHETS], avec le statut « À rédiger (chiffres client) ».
- Chaque post FB/IG se termine par un appel à commenter et à taguer.
- Meta Ads : une créa par ensemble de pub (A/B test strict) ; carrousel pour la lead gen sur Meta ; visuel statique pour la pub LinkedIn ; question de qualification dans les formulaires de leads.

## 5. Livrable
Un Sheet avec ces colonnes, dans cet ordre : Date | Jour | Réseau | Gabarit | Sujet / angle | Sport · Public | Persona | Format | Heure conseillée | Proposition de texte | Texte repartage profil LinkedIn | Brief visuel | Lien / CTA | Statut | Points à valider.
Ajouter un onglet « Repères » (temps forts et sources, cadence, contrôle de diversité, enseignements de l'historique, points à trancher), et un résumé dans `calendriers/AAAA-MM.md`.

## 6. Vérifier avant de livrer
Relire les jours de la semaine, compter les gabarits et les sports, puis lister dans la réponse les points que le client doit trancher.
