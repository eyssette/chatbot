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

## Texte 1 - tester sa compréhension

!Keyboard: true

Je vais te proposer une question pour tester ta compréhension du texte 1 (attends un peu, je dois réfléchir avant).



<div class="question-texte1" markdown>

`!useLLM`

Pose une question sur l'un des points importants du texte suivant de Sartre pour voir si j'ai bien compris le texte.
La question ne doit pas être formulée de manière trop compliquée.

### Types de questions possibles
- Demander une définition d'un terme ou d'une notion
- Demander une explication d'une idée ou d'un passage du texte
- Demander un exemple concret pour illustrer une idée du texte
- Demander une comparaison entre deux idées du texte

### Texte de Sartre

@{texte1}

### Points importants du texte
@{texte1-points-importants}

### Instructions

- Tire au hasard un des points importants du texte sur lequel poser une question
- S'il y a une question précédente, change de thème : la question ne doit pas porter sur les mêmes notions et le même point important que la question précédente
   - Question précédente : `@SELECTOR[".question-texte1"]`
- Formule une question claire et concise sur ce point important, en utilisant un langage simple et compréhensible pour un élève de lycée
- La question doit être en rapport direct avec le texte et la philosophie de Sartre
- Formule la question elle-même sans syntaxe Markdown ou HTML, de manière brute

### Format attendu

:::question Question

QUESTION_POSEE_SUR_LE_TEXTE

:::

`END !useLLM`

</div>

Réponds à cette question, je vais te proposer ensuite une évaluation.

!Next: Texte 1 - tester sa compréhension - évaluation de la réponse de l'élève

## Texte 1 - tester sa compréhension - évaluation de la réponse de l'élève

:::warning Évaluation générée par une IA
Attention, cette évaluation de ta réponse est générée par une IA : garde l'esprit critique !
:::

Voici mon évaluation (attends un peu, je dois réfléchir avant).

`!useLLM`

J'ai répondu à une question sur un texte de Sartre.
Évalue ma réponse.

### Question posée
`@SELECTOR[".question-texte1"]`

### Ma réponse
`@INPUT`

### Texte de Sartre
@{texte1}

### Instructions
- Vérifie que ma réponse est correcte et complète
   - Il faut que ma réponse corresponde à la question posée et qu'elle soit en accord avec le texte et la philosophie de Sartre.
   - Il faut que ma réponse définisse bien les termes ou notions importantes dans la question posée
- Évalue ma réponse de manière claire et concise :
   - Si ma réponse est correcte, explique pourquoi elle est correcte et complète.
   - Si ma réponse est incorrecte ou incomplète, dis simplement ce qui pourrait être amélioré, mais en étant bienveillant et constructif dans la formulation (sans souligner les manques et les erreurs de manière négative).
- Rédige ton évaluation en 1 paragraphe seulement, mais en sautant une ligne entre chaque phrase pour que ce soit plus clair.

`END !useLLM`