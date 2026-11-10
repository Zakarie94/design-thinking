# design-thinking

Une plateforme web participative de fact-checking, avec une IA entraînée sur des sources vérifiées et croisées, pour s'informer de façon fiable et pluraliste.

Équipe : Zakarie · Yaya · Hedy 

1. Contexte et problème
Contexte : les infos qui circulent, surtout sur les réseaux sociaux, ne sont pas toujours sourcées ni vérifiées.
Problème : même une source sérieuse peut être détournée pour en tirer des conclusions qu'elle ne contient pas, ou pour servir un agenda politique. Le lecteur est alors orienté vers un narratif.
Utilisateurs cibles :
Hervé, 50 ans : s'informe par la télé et TikTok, et perd confiance dans les médias traditionnels. Il veut une information pluraliste.
Hawa, 37 ans, journaliste : fait des recherches documentaires en permanence, aime partager ses fact-checks et craint que tout le monde tombe dans la désinformation.
Hiba, 21 ans : va voter pour la première fois à la présidentielle sans vraiment comprendre les enjeux. Elle veut un outil pour s'informer sur les candidats et les sujets politiques.
Questions « Comment pourrions-nous… » :
Comment pourrions-nous aider Hiba à s'informer sur les candidats à l'élection présidentielle ?
Comment faire pour qu'Hervé ait de nouveau confiance dans l'information ?
Principe clé : les données doivent être challengées, vérifiées et neutres pour que l'information soit fiable.

➡️ Détails : docs/01-comprendre.md

2. Idéation
Méthode : Crazy 8 (8 idées chacun), vote silencieux à 3 points par personne, puis matrice impact / effort.
Pistes explorées : formats médias (TikTok, YouTube, JT, podcast, journal papier), actions terrain (affiches, flyers, conférences), partenariats (influenceurs, ARCOM, CNRS, INSEE, OCDE) et outils numériques (site web, IA, contribution participative).
Idées retenues au vote :
Une IA entraînée sur nos données validées et sourcées
Un site web pour centraliser les infos
Un modèle participatif, à la Wikipédia
Concept final : combiner les trois en une seule plateforme.

➡️ Détails : docs/02-ideer.md · Photos : docs/img/

3. Proposition de valeur

[Nom du projet] propose une plateforme web participative, où une IA répond à partir de sources vérifiées et croisées (INSEE, CNRS, OCDE…), aux citoyens qui veulent s'informer, comme Hiba ou Hervé. Elle leur permet de vérifier une info et de comprendre les enjeux politiques de façon fiable et pluraliste, contrairement aux réseaux sociaux et aux médias traditionnels, où les sources sont rarement croisées ou vérifiables.

Ce que la solution apporte : des réponses sourcées en langage naturel, des sources croisées, et une communauté qui contribue au fact-checking et vote pour mettre en avant les sujets.
Différence avec l'existant : …
Indicateurs de succès : …

➡️ Détails : docs/03-valeur.md

4. Démarche data (CRISP-DM)
Étape	Ce qu'on a fait
Compréhension métier	…
Compréhension des données	…
Préparation des données	…
Modélisation	…
Évaluation	…
Déploiement	…

➡️ Détails : docs/04-crisp-dm.md

5. MVP
Périmètre : ce que fait le MVP (et ce qu'il ne fait pas encore)
Outils / technologies : …
Démo / captures : …
Prochaines étapes : …

➡️ Détails : docs/05-mvp.md · Présentation : docs/deck.pdf

6. Usage de l'IA et organisation
Usage de l'IA : à quelles étapes, pour quoi faire, avec quelles limites. Journal complet dans PROMPTS.md
Répartition du travail : qui a fait quoi
Ce qu'on a appris : …
Structure du dépôt
nom-du-projet/
├── README.md          
├── PROMPTS.md         
└── docs/
    ├── 01-comprendre.md
    ├── 02-ideer.md
    ├── 03-valeur.md
    ├── 04-crisp-dm.md
    ├── 05-mvp.md
    ├── deck.pdf       
    └── img/           
