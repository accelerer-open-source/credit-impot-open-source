# Bénéficier du CIR et du CII pour un projet open source

Des dispositifs fiscaux existent pour encourager les entreprises de toutes tailles à poursuivre des travaux de recherche et développement et d'innovation, notamment le [Crédit Impôt Recherche](https://www.enseignementsup-recherche.gouv.fr/fr/credit-impot-recherche-cir-50180) et le [Crédit Impôt Innovation](https://entreprendre.service-public.fr/vosdroits/F35494).

Ce document s'efforce de donner quelques pistes pour bénéficier des tels crédits d'impôts dans le contexte d'un développement open source,  et d'éviter les écueils courants dans l'interprétation de l'éligibilité d'un projet open source à ces dispositifs.

Vous pouvez contribuer à ce document via les outils de collaborations fournis par GitHub.

## Caveat

- Il ne s'agit pas d'un conseil juridique, ce document n'est pas rédigé par des juristes ou avocats.
- Ces recommandations sont fondées sur les expériences des auteurs, leur mise en œuvre ne garantit pas l'éligibilité d'un dossier.
- Ces recommandations ne traduisent en aucun cas un positionnement de l'administration fiscale.
- Les dispositifs de financement de l'innovation sont complexes, il est conseillé de vous faire assister par des experts du domaine, a minima pour une relecture de vos dossiers.
- Vous êtes seuls responsables des déclarations que vous faites à l'administration fiscale, y compris lorsque vous êtes accompagnés par une entreprise de conseil.

## Open source vs R&D

### Ressources

Le [Bulletin Officiel des Finances Publiques](https://bofip.impots.gouv.fr/bofip/6486-PGP.html) définit les activités éligibles au CIR. Il s'appuie pour cela sur le [Manuel de Frascati](https://www.oecd.org/fr/innovation/inno/manueldefrascatimethodetypeproposeepourlesenquetessurlarechercheetledeveloppementexperimental6emeedition.htm).

### Écueil courant : rendre un code public ne suffit pas à justifier un apport de connaissance

Le caractère open source ne suffit pas à justifier d'une contribution à l'état des connaissances académiques et industrielles. Il faut aussi que la solution open source crée des connaissances nouvelles.

Exemple: je crée un algorithme de résolution d'équations et je le publie en open source, dans un domaine où il n'existe qu'une implémentation commerciale. Mais j'ai utilisé une technique mathématique connue depuis longtemps, et qui a fonctionné sans problèmes particuliers. La création de connaissance est limitée, le caractère open source ne suffit pas à prouver une contribution à la littérature.

Même pour un projet open source qui n'a pas d'équivalent public, il faut donc revenir aux critères usuels pour caractériser un travail considéré comme R&D, le caractère public ne suffit pas.

On note par contre que l'existence d'implémentations privées n'empêche pas un projet open source d'être éligible, car les implémentations privées ne font pas à proprement parler partie de l'état de l'art accessible aux entreprises. Contrairement aux publications de recherche académique, aux brevets et aux autres projets open source qui font partie de l'état de l'art public et doivent être comparés à votre propre travail.

### Apport de l'open source en tant que tel pour justifier le caractère R&D

Comme expliqué précédemment, le caractère open source justifie difficilement à lui seul le caractère R&D ou innovant d'un projet. Il peut néanmoins contribuer à justifier l'éligibilité d'un projet, en complément d'autres arguments.

Pour la R&D, la publication de code open source peut constituer un indicateur de recherche, notamment en ce qu'elle favorise la reproductibilité des travaux de l'entreprise et permet à d'autres acteurs d'étudier l'implémentation proposée. 

Dans une certaine mesure si le projet est effectivement exploité par des tiers, cela peut être interprété comme une forme de validation par les pairs (au moins au niveau industriel).

## Open source vs innovation

### Ressources

Le [Manuel d'Oslo](https://www.oecd.org/fr/sti/inno/2367554.pdf) définit la notion d'innovation.

### Ecueil courant : créer une alternative publique à une implémentation privée ne suffit pas à justifier d'une innovation

Le caractère open source ne suffit pas à justifier d'une innovation par rapport à une solution privée. Il faut que la solution open source présente une supériorité par rapport à l'existant, incluant les autres solutions libres mais aussi les solutions commerciales privées. 

Il faut inclure les solutions privées dans l'étude de la concurrence, même s'il est souvent difficile d'étudier leur fonctionnement précis. On peut s'appuyer sur leur documentation publique ou encore sur des études de cabinets de conseil.

Exemple: je crée une alternative open source à Microsoft Word. Le caractère libre ne suffit pas à justifier d'une innovation. Il faut présenter des fonctionnalités innovantes qui n'existent pas dans Microsoft Word, par exemple : le support automatique de la coloration syntactique pour les éléments de code inclus dans le texte ; l'intégration d'une IA générative pour reformuler des paragraphes...

### Apport de l'open source pour justifier le caractère innovant

Le caractère open source peut parfois générer des bénéfices techniques, par exemple permettre un nouvel usage qui n'est pas possible avec une base de code privée.

Exemple: la possibilité de recompiler le code d'un algorithme pour l'inclure dans des systèmes embarqués spécifiques, non supportés par les équivalents privés, donne une supériorité à la solution open source qui pourrait permettre de la considérer comme une innovation.

Il peut être difficile d'identifier ce type d'apport, s'appuyer sur d'autres avantages que le caractère open source est souvent souhaitable pour prouver qu'une solution est innovante.

## Pour aller plus loin

Les dispositifs fiscaux CIR, CII et Jeune Entreprise Innovante ne permettent qu'un financement indirect de l'open source, qui n'est pas valorisé pour lui-même.

Certains projets qui ne génèrent ni nouvelles connaissances académiques, ni supériorité face aux implémentations privées, ne seront pas éligibles à ces dispositifs. 

Le CIR et le CII ne permettent pas de valoriser les travaux open source au niveau de "l'infrastructure", c'est-à-dire la conception de solutions libres via des techniques d'ingénierie classique pour résoudre des problèmes communs. Ces travaux sont pourtant utiles au bon fonctionnement de nombreux systèmes, notamment d'autres systèmes innovants et d'autres travaux de recherche.

Le dépôt [lettres-open-source](https://github.com/accelerer-open-source/lettres-open-source) fournit des modèles de lettres à transmettre à vos représentants pour les informer de cette problématique.
