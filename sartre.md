---
darkmode: false
keyboard: false
theme: light
avatar: https://upload.wikimedia.org/wikipedia/commons/7/77/Flickr_-_Government_Press_Office_%28GPO%29_-_Jean_Paul_Sartre_and_Simone_De_Beauvoir_welcomed_by_Avraham_Shlonsky_and_Leah_Goldberg_%28cropped%29.jpg
avatarCercle: true
contenuDynamique: true
useLLM:
   url: https://n8n.incubateur.education.gouv.fr/webhook/ilaas-chatmd
   isSecureAPI: true
   encryptedAPIkey: true
   model: gpt-oss-120b
   stream: false
   simulateStreaming: true
style: |
   .admonitionTitle span {
       font-weight: normal;
       display: block;
       margin-left: 3em;
       margin-top: 5px;
   }
variables:
   texte1: |
      Je voudrais ici défendre l'existentialisme contre un certain nombre de reproches qu'on lui a adressés.
      On lui a d'abord reproché d'inviter les gens à demeurer dans un quiétisme du désespoir, parce que, toutes les solutions étant fermées, il faudrait considérer que l'action dans ce monde est totalement impossible, et d'aboutir finalement à une philosophie contemplative, ce qui d'ailleurs, car la contemplation est un luxe, nous ramène à une philosophie bourgeoise. Ce sont surtout là les reproches des communistes.
      On nous a reproché, d'autre part, de souligner l'ignominie humaine, de montrer partout le sordide, le louche, le visqueux, et de négliger un certain nombre de beautés riantes, le côté lumineux de la nature humaine ; par exemple, selon Mlle Mercier, critique catholique, d'avoir oublié le sourire de l'enfant. Les uns et les autres nous reprochent d'avoir manqué à la solidarité humaine, de considérer que l'homme est isolé, en grande partie d'ailleurs parce que nous partons, disent les communistes, de la subjectivité pure, c'est-à-dire du je pense cartésien, c'est-à-dire encore du moment où l'homme s'atteint dans sa solitude, ce qui nous rendrait incapables par la suite de retourner à la solidarité avec les hommes qui sont hors de moi et que je ne peux pas atteindre dans le cogito.
      Et du côté chrétien, on nous reproche de nier la réalité et le sérieux des entreprises humaines, puisque si nous supprimons les commandements de Dieu et les valeurs inscrites dans l'éternité, il ne reste plus que la stricte gratuité, chacun pouvant faire ce qu'il veut, et étant incapable de son point de vue de condamner les points de vue et les actes des autres.
   texte2: |
      Lorsque nous concevons un Dieu créateur, ce Dieu est assimilé la plupart du temps à un artisan supérieur ; et quelle que soit la doctrine que nous considérions, qu'il s'agisse d'une doctrine comme celle de Descartes ou de la doctrine de Leibniz, nous admettons toujours que la volonté suit plus ou moins l'entendement ou, tout au moins, l'accompagne, et que Dieu, lorsqu'il crée, sait précisément ce qu'il crée. Ainsi, le concept d'homme, dans l'esprit de Dieu, est assimilable au concept de coupe-papier dans l'esprit de l'industriel ; et Dieu produit l'homme suivant des techniques et une conception, exactement comme l'artisan fabrique un coupe-papier suivant une définition et une technique. Ainsi l'homme individuel réalise un certain concept qui est dans l'entendement divin. Au XVIIIe siècle, dans l'athéisme des philosophes, la notion de Dieu est supprimée, mais non pas pour autant l'idée que l'essence précède l'existence. Cette idée, nous la retrouvons un peu partout : nous la retrouvons chez Diderot, chez Voltaire, et même chez Kant. L'homme est possesseur d'une nature humaine ; cette nature humaine, qui est le concept humain, se retrouve chez tous les hommes, ce qui signifie que chaque homme est un exemple particulier d'un concept universel, l'homme […].
   texte3: |
      L'existentialisme athée, que je représente, est plus cohérent. Il déclare que si Dieu n'existe pas, il y a au moins un être chez qui l'existence précède l'essence, un être qui existe avant de pouvoir être défini par aucun concept et que cet être c'est l'homme ou, comme dit Heidegger, la réalité-humaine. Qu'est-ce que signifie ici que l'existence précède l'essence ? Cela signifie que l'homme existe d'abord, se rencontre, surgit dans le monde, et qu'il se définit après. L'homme, tel que le conçoit l'existentialiste, s'il n'est pas définissable, c'est qu'il n'est d'abord rien. Il ne sera qu'ensuite, et il sera tel qu'il se sera fait. Ainsi, il n'y a pas de nature humaine, puisqu'il n'y a pas de Dieu pour la concevoir. L'homme est non seulement tel qu'il se conçoit, mais tel qu'il se veut, et comme il se conçoit après l'existence, comme il se veut après cet élan vers l'existence, l'homme n'est rien d'autre que ce qu'il se fait. Tel est le premier principe de l'existentialisme. C'est aussi ce qu'on appelle la subjectivité, et que l'on nous reproche sous ce nom même. Mais que voulons-nous dire par là, sinon que l'homme a une plus grande dignité que la pierre ou que la table ? Car nous voulons dire que l'homme existe d'abord, c'est-à-dire que l'homme est d'abord ce qui se jette vers un avenir, et ce qui est conscient de se projeter dans l'avenir. L'homme est d'abord un projet qui se vit subjectivement, au lieu d'être une mousse, une pourriture ou un chou-fleur […].
   texte4: |
      Mais si vraiment l'existence précède l'essence, l'homme est responsable de ce qu'il est. Ainsi, la première démarche de l'existentialisme est de mettre tout homme en possession de ce qu'il est et de faire reposer sur lui la responsabilité totale de son existence. Et, quand nous disons que l'homme est responsable de lui-même, nous ne voulons pas dire que l'homme est responsable de sa stricte individualité, mais qu'il est responsable de tous les hommes. Il y a deux sens au mot subjectivisme, et nos adversaires jouent sur ces deux sens. Subjectivisme veut dire d'une part choix du sujet individuel par lui-même, et, d'autre part, impossibilité pour l'homme de dépasser la subjectivité humaine. C'est le second sens qui est le sens profond de l'existentialisme. Quand nous disons que l'homme se choisit, nous entendons que chacun d'entre nous se choisit, mais par là nous voulons dire aussi qu'en se choisissant il choisit tous les hommes. En effet, il n'est pas un de nos actes qui, en créant l'homme que nous voulons être, ne crée en même temps une image de l'homme tel que nous estimons qu'il doit être. Choisir d'être ceci ou cela, c'est affirmer en même temps la valeur de ce que nous choisissons, car nous ne pouvons jamais choisir le mal ; ce que nous choisissons, c'est toujours le bien, et rien ne peut être bon pour nous sans l'être pour tous. Si l'existence, d'autre part, précède l'essence et que nous voulions exister en même temps que nous façonnons notre image, cette image est valable pour tous et pour notre époque tout entière. Ainsi, notre responsabilité est beaucoup plus grande que nous ne pourrions le supposer, car elle engage l'humanité entière.
   texte5: |
      L'existentialiste, au contraire, pense qu'il est très gênant que Dieu n'existe pas, car avec lui disparaît toute possibilité de trouver des valeurs dans un ciel intelligible ; il ne peut plus y avoir de bien a priori, puisqu'il n'y a pas de conscience infinie et parfaite pour le penser ; il n'est écrit nulle part que le bien existe, qu'il faut être honnête, qu'il ne faut pas mentir, puisque précisément nous sommes sur un plan où il y a seulement des hommes. Dostoïevsky avait écrit : “Si Dieu n'existait pas, tout serait permis.” C'est là le point de départ de l'existentialisme. En effet, tout est permis si Dieu n'existe pas, et par conséquent l'homme est délaissé, parce qu'il ne trouve ni en lui, ni hors de lui une possibilité de s'accrocher. Il ne trouve d'abord pas d'excuses. Si, en effet, l'existence précède l'essence, on ne pourra jamais expliquer par référence à une nature humaine donnée et figée ; autrement dit, il n'y a pas de déterminisme, l'homme est libre, l'homme est liberté. Si, d'autre part, Dieu n'existe pas, nous ne trouvons pas en face de nous des valeurs ou des ordres qui légitimeront notre conduite. Ainsi, nous n'avons ni derrière nous, ni devant nous, dans le domaine numineux des valeurs, des justifications ou des excuses. Nous sommes seuls, sans excuses. C'est ce que j'exprimerai en disant que l'homme est condamné à être libre. Condamné, parce qu'il ne s'est pas créé lui-même, et par ailleurs cependant libre, parce qu'une fois jeté dans le monde, il est responsable de tout ce qu'il fait. L'existentialiste ne croit pas à la puissance de la passion. Il ne pensera jamais qu'une belle passion est un torrent dévastateur qui conduit fatalement l'homme à certains actes, et qui, par conséquent, est une excuse. Il pense que l'homme est responsable de sa passion.
      L'existentialiste ne pensera pas non plus que l'homme peut trouver un secours dans un signe donné, sur terre, qui l'orientera ; car il pense que l'homme déchiffre lui-même le signe comme il lui plaît. Il pense donc que l'homme, sans aucun appui et sans aucun secours, est condamné à chaque instant à inventer l'homme.
   texte6: |
     Tout matérialisme a pour effet de traiter tous les hommes, y compris soi-même, comme des objets, c'est-à-dire comme un ensemble de réactions déterminées, que rien ne distingue de l'ensemble des qualités et des phénomènes qui constituent une table ou une chaise ou une pierre. Nous voulons constituer précisément le règne humain comme un ensemble de valeurs distinctes du règne matériel. Mais la subjectivité que nous atteignons là à titre de vérité n'est pas une subjectivité rigoureusement individuelle, car nous avons démontré que dans le _cogito_, on ne se découvrait pas seulement soi-même, mais aussi les autres. Par le _je pense_, contrairement à la philosophie de Descartes, contrairement à la philosophie de Kant, nous nous atteignons nous-mêmes en face de l'autre, et l'autre est aussi certain pour nous que nous-mêmes. Ainsi, l'homme qui s'atteint directement par le _cogito_ découvre aussi tous les autres, et il les découvre comme la condition de son existence. Il se rend compte qu'il ne peut rien être (au sens où l'on dit qu'on est spirituel, ou qu'on est méchant, ou qu'on est jaloux) sauf si les autres le reconnaissent comme tel. Pour obtenir une vérité quelconque sur moi, il faut que je passe par l'autre. L'autre est indispensable à mon existence, aussi bien d'ailleurs qu'à la connaissance que j'ai de moi. Dans ces conditions, la découverte de mon intimité me découvre en même temps l'autre, comme une liberté posée en face de moi, qui me pense, et qui ne veut que pour ou contre moi. Ainsi découvrons-nous tout de suite un monde que nous appellerons l'intersubjectivité, et c'est dans ce monde que l'homme décide ce qu'il est et ce que sont les autres.
   texte1-points-importants: |
      1. Sartre défend l'existentialisme contre des critiques venant de différentes perspectives, notamment communistes et chrétiennes. Cela montre une volonté de clarifier les malentendus autour de sa philosophie.
      2. Les communistes reprochent à l'existentialisme de mener à un désespoir qui paralyse l'action.
      3. Les catholiques reprochent à l'existentialisme une vision sombre de l'humanité, qui empêcherait de saisir la beauté et la bonté de l'être humain.
      4. Les communistes et les catholiques reprochent à l'existentialisme d'enfermer l'individu dans sa subjectivité, ce qui le rendrait incapable de participer à la solidarité humaine.
      5. De plus, les chrétiens ajoutent un autre reproche : l'existentialisme, en niant les commandements de Dieu et les valeurs éternelles, laisserait l'homme libre de faire ce qu'il veut, ce qui rendrait impossible tout jugement moral.
   questionsSartreTexte6: |
      Définis ce qu'est le matérialisme /// Ce texte défend-il le matérialisme ? /// Qu'est-ce que la subjectivité ? /// 
---


# Discute avec Sartre !

Bonjour, je suis là pour t'accompagner dans la lecture de ma conférence _L'existentialisme est un humanisme_

Comment puis-je t'aider ?

1. [J'aimerais en savoir un peu plus sur toi, Sartre !](Qui es-tu Sartre ?)
1. [Je veux comprendre la structure générale de cette conférence](Comprendre la structure générale)
2. [Je veux travailler sur un texte en particulier](Travailler sur un texte en particulier)

## Revenir à la conférence

Que veux-tu faire ?

1. [Comprendre la structure générale de cette conférence](Comprendre la structure générale)
2. [Travailler sur un texte en particulier](Travailler sur un texte en particulier)

## Qui es-tu Sartre ?

Je suis Jean-Paul Sartre, né en 1905 et mort en 1980.

Voici une première présentation de mon parcours et de mes idées !

\`

:::info Mes idées principales
J’ai développé une philosophie, **l'existentialisme**, fondée sur la liberté fondamentale de l'être humain.

Je pense que l'être humain n’est pas prédéterminé : il se définit par ses actes.

Sans dieu pour imposer un sens, nous sommes condamnés à être libres, à choisir et à assumer nos choix.
:::

:::info Mes œuvres
J’ai exploré ces idées à travers :
- la philosophie, notamment dans _L’Être et le Néant_,
- mais aussi dans la littérature : avec des romans, comme _La Nausée_, ou des pièces de théâtre, comme _Huis clos_.
:::

:::info Mon engagement politique
Je suis également un intellectuel engagé : je refuse de séparer la pensée de l’action. La philosophie ne doit pas être une contemplation abstraite, elle doit s’inscrire dans le monde et y prendre position.
:::

\`

1. [Dans quelle mesure as-tu été un intellectuel engagé ?](Un intellectuel engagé)
2. [Revenir à la conférence](Revenir à la conférence)

## Un intellectuel engagé

J'ai souvent mis ma plume au service des minorités délaissées.

Je te propose ci-dessous de découvrir mes engagements !

\`

:::info Lutte contre l'antisémitisme, le racisme et le colonialisme
Je me suis attaqué à l'antisémitisme en France (dans mes _Réflexions sur la question juive_) ou encore au racisme et aux discriminations dont sont victimes les noirs américains.

J'ai critiqué le colonialisme et soutenu l'indépendance de l'Algérie.
:::

:::info L'écriture comme acte politique
J’ai toujours vu l’écriture comme un acte politique. Dans _Qu’est-ce que la littérature ?_, j’explique que l’écrivain a une responsabilité et ne peut pas être neutre face aux injustices.

Politiquement, je me suis rapproché des marxistes et du communisme, tout en prenant mes distances avec ces mouvements.
:::

\`

1. [Explique plus précisément tes rapports avec le marxisme et le communisme](Rapports avec le marxisme et le communisme)
2. [Revenir à la conférence](Revenir à la conférence)

## Rapports avec le marxisme et le communisme

Pour moi, le marxisme offre un cadre puissant pour comprendre les rapports de classe et les injustices sociales. Cependant, je critique son déterminisme historique, car il réduit l’individu à un simple produit des forces économiques, niant ainsi la liberté existentielle que je défends.

Dans _Critique de la raison dialectique_ (1960), j’essaie de réconcilier l’existentialisme et le marxisme. Je propose une synthèse où l’individu, tout en étant façonné par des structures sociales, conserve une liberté d’action

J’ai entretenu une relation ambivalente avec le Parti communiste français (PCF). Après la Seconde Guerre mondiale, le PCF représente pour moi la résistance au fascisme et l’espoir d’un monde plus juste. J’ai néanmoins critiqué plus tard les dérives autoritaires du régime soviétique.


1. [Je veux revenir à ta conférence <i>L'existentialisme est un humanisme</i> et en comprendre la structure générale](Comprendre la structure générale)
2. [Je veux travailler sur un texte en particulier](Travailler sur un texte en particulier)

## Comprendre la structure générale

\`
<style scoped>
   ol {
      list-style-type: upper-alpha;
      margin-right: 1em;
   }
   ol li {
      padding-left: 0.25em;
   }
</style>
\`

Il n'y a pas de plan apparent dans _L'existentialisme est un humanisme_, mais on peut identifier deux grandes parties.

Clique sur les titres ci-dessous pour voir un résumé de chaque partie.

:::info collapsible I - Clarification du principe fondamental de l'existentialisme : <span>L'être humain est libre et responsable de ce qu'il est</span>

1. Des reproches sont adressés à l'existentialisme
   - [Texte 1 : les reproches contre l'existentialisme](#Texte 1)
2. Ces reproches montrent que l'existentialisme est mal compris et qu'il est nécessaire de clarifier son principe fondamental : l'idée que chez l'être humain l'existence précède l'essence.
   - [Texte 2 : l'existentialisme se distingue de deux formes d'essentialisme](#Texte 2)
   - [Texte 3 : l'existentialisme athée de Sartre repose sur l'idée que l'existence précède l'essence](#Texte 3)
   - [Texte 4 : si l'existence précède l'essence, cela signifie que l'être humain est responsable de ce qu'il est](#Texte 4)
3. Cette idée implique que l'être humain est libre et responsable de ce qu'il est, ce qui concrètement se vit à travers deux expériences : l'angoisse et le délaissement
   - [Texte 5 : l'être humain est condamné à être libre](#Texte 5)

:::

:::info collapsible II - Défense d'une forme d'humanisme : <span>L'existentialisme valorise l'action et l'engagement de l'être humain dans un monde partagé avec autrui</span>

1. L'existentialisme conduit à une forme de désespoir
2. Mais ce désespoir n'enferme pas l'individu dans l'inaction : l'existentialisme valorise l'action et l'engagement de l'être humain
3. Cet engagement n'a de sens que dans un monde partagé avec autrui : l'existentialisme n'enferme pas l'individu dans sa subjectivité, c'est une philosophie de l'intersubjectivité
   - [Texte 6 : de la subjectivité à l'intersubjectivité](#Texte 6)

:::

1. [Je veux maintenant travailler sur un texte en particulier](Travailler sur un texte en particulier)


## Travailler sur un texte en particulier

Quel texte veux-tu travailler plus précisément ?

1. [Le texte 1](Texte 1)
2. [Le texte 2](Texte 2)
3. [Le texte 3](Texte 3)
4. [Le texte 4](Texte 4)
5. [Le texte 5](Texte 5)
6. [Le texte 6](Texte 6)

## Texte 1

:::info collapsible Texte 1 – Les reproches contre l'existentialisme (clique pour relire le texte)
@{texte1}
:::

Que souhaites-tu faire ?

1. [J'aimerais des explications sur ce texte](Texte 1 - explications)
2. [Je veux poser une question à propos de ce texte](Texte 1 - poser une question)
3. [Je veux tester ma compréhension du texte](Texte 1 - tester sa compréhension)
4. [Je veux travailler sur un autre texte](Travailler sur un texte en particulier)

## Texte 1 - explications

Voici les points importants de ce texte :


\`

:::info Points importants du texte 1
@{texte1-points-importants}
:::

\`

1. [Explique moi le point n°1 @point-à-expliquer=1](Texte 1 - explications plus précises)
2. [Explique moi le point n°2 @point-à-expliquer=2](Texte 1 - explications plus précises)
3. [Explique moi le point n°3 @point-à-expliquer=3](Texte 1 - explications plus précises)
4. [Explique moi le point n°4 @point-à-expliquer=4](Texte 1 - explications plus précises)
5. [Explique moi le point n°5 @point-à-expliquer=5](Texte 1 - explications plus précises)
1. [Je veux travailler sur un autre texte](Travailler sur un texte en particulier)

## Texte 1 - explications plus précises

Regarde avant tout le cours pour avoir une explication plus précise.

Pour t'aider, voici cependant quelques explications supplémentaires sur le point n°`@point-à-expliquer` de ce texte.

\`

:::warning Réponse générée par une IA
Attention, ces explications sont proposées par une IA : garde un esprit critique et n'hésite pas à poser des questions à ton professeur !
:::

\`

Je vais te proposer une explication ci-dessous, mais sois patient, je dois d'abord réfléchir un peu !

`!useLLM`
Je cherche à comprendre le point @{texte1-points-importants} de ce texte de Sartre, extrait de sa conférence _L'existentialisme est un humanisme_.

### Texte de Sartre
@{texte1}

### Points importants du texte
Voici les points importants de ce texte, que tu peux relire pour bien comprendre la structure du texte et pour identifier le point que je souhaite approfondir :

@{texte1-points-importants}

### Instructions
Propose des explications supplémentaires sur le point `@point-à-expliquer` de ce texte, en t'appuyant sur tes connaissances sur Sartre et sur le texte.

- Relis bien le point `@point-à-expliquer` du texte et concentre-toi uniquement sur ce point.
- Explique de manière claire l'idée principale. L'explication ne doit pas être une simple paraphrase du texte. Elle doit vraiment aider à mieux comprendre le sens de ce passage et apporter plus de clarté et de précision.
- L'explication ne doit pas aborder les points des autres passages du texte. Focalise-toi uniquement sur le point `@point-à-expliquer`.
- S'il y a des termes techniques dans le passage correspondant du texte, définis-les en restant proche de la philosophie de Sartre.
- Rédige l'explication de manière à ce qu'elle soit compréhensible par un élève de lycée, en 1 paragraphe seulement
- N'utilise pas de syntaxe Markdown : rédige le texte de manière brute.

### Format de sortie attendu

:::info Proposition d'explication

EXPLICATION_DU_POINT_À_EXPLIQUER

:::

`END !useLLM`

## Texte 1 - poser une question

!Keyboard: true

Quelle est ta question ?

!Next: Texte 1 - réponse à la question de l'élève

## Texte 1 - réponse à la question de l'élève

!Keyboard: true

:::warning Réponse générée par une IA
Attention, réponse générée par une IA : garde l'esprit critique !
:::

Je vais te proposer une réponse, mais sois patient, je dois d'abord réfléchir un peu !

`!useLLM`
!useHistory

J'ai posé une question à propos d'un texte de Sartre. Vérifie que la question porte sur ce le texte, et réponds à cette question en utilisant tes connaissances sur Sartre et sur le texte.

### Question que j'ai posé
`@INPUT`

### Texte de Sartre
@{texte1}

### Instructions

- Réponds en me tutoyant, de manière courte et accessible pour un élève en lycée.
- Reste très proche dans ta réponse de la philosophie de Sartre.
- Si tu utilises des termes techniques, définis-les.
- Réponds en 1 paragraphe.
- N'utilise pas de syntaxe Markdown, rédige le texte de manière brute.

### Format de sortie attendu

:::info Proposition de réponse

REPONSE_A_LA_QUESTION

:::

`END !useLLM`

As-tu une autre question ?

!Next: Texte 1 - réponse à la question de l'élève

1. [Retour au texte 1](Texte 1)
2. [Je veux travailler sur un autre texte](Travailler sur un texte en particulier)



## Texte 2

:::info collapsible Texte 2 – Deux formes d'essentialisme (clique pour relire le texte)
@{texte2}
:::

Que souhaites-tu faire ?

1. [J'aimerais des explications sur ce texte](Texte 2 - explications)
2. [Je veux poser une question à propos de ce texte](Texte 2 - poser une question)
3. [Je veux tester ma compréhension du texte](Texte 2 - tester sa compréhension)
4. [Je veux travailler sur un autre texte](Travailler sur un texte en particulier)

## Texte 3

:::info collapsible Texte 3 – L'existentialisme athée (clique pour relire le texte)
@{texte3}
:::

Que souhaites-tu faire ?

1. [J'aimerais des explications sur ce texte](Texte 3 - explications)
2. [Je veux poser une question à propos de ce texte](Texte 3 - poser une question)
3. [Je veux tester ma compréhension du texte](Texte 3 - tester sa compréhension)
4. [Je veux travailler sur un autre texte](Travailler sur un texte en particulier)

## Texte 4

:::info collapsible Texte 4 – L'être humain est responsable de ce qu'il est (clique pour relire le texte)
@{texte4}
:::

Que souhaites-tu faire ?

1. [J'aimerais des explications sur ce texte](Texte 4 - explications)
2. [Je veux poser une question à propos de ce texte](Texte 4 - poser une question)
3. [Je veux tester ma compréhension du texte](Texte 4 - tester sa compréhension)
4. [Je veux travailler sur un autre texte](Travailler sur un texte en particulier)


## Texte 5

:::info collapsible Texte 5 – L'être humain est condamné à être libre (clique pour relire le texte)
@{texte5}
:::

Que souhaites-tu faire ?

1. [J'aimerais des explications sur ce texte](Texte 5 - explications)
2. [Je veux poser une question à propos de ce texte](Texte 5 - poser une question)
3. [Je veux tester ma compréhension du texte](Texte 5 - tester sa compréhension)
4. [Je veux travailler sur un autre texte](Travailler sur un texte en particulier)


## Texte 6

:::info collapsible Texte 6 – De la subjectivité à l'intersubjectivité (clique pour relire le texte)
@{texte6}
:::

Que souhaites-tu faire ?

1. [J'aimerais des explications sur ce texte](Texte 6 - explications)
1. [Je veux poser une question à propos de ce texte](Texte 6 - poser une question)
2. [Je veux tester ma compréhension du texte](Texte 6 - tester sa compréhension)
4. [Je veux travailler sur un autre texte](Travailler sur un texte en particulier)

## Texte 6 - poser une question

Quelle est ta question ?

!Next: Texte 6 - réponse à la question de l'élève

## Texte 6 - réponse à la question de l'élève

`!useLLM`
J'ai posé une question à propos d'un texte de Sartre. Vérifie que la question porte sur ce le texte, et réponds à cette question en utilisant tes connaissances sur Sartre et sur le texte.

Question que j'ai posé : `@INPUT`

Texte de Sartre : @{texte6}

Réponds en me tutoyant.

`END !useLLM`

## Texte 6 - tester sa compréhension


