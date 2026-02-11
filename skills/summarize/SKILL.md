---
name: summarize
description: "Résume un texte en conservant les points essentiels. Utilise ce skill quand l'utilisateur demande un résumé, une synthèse ou un condensé d'un contenu textuel."
---

# Skill : Résumé

## Objectif

Produire un résumé clair et concis d'un texte donné, en conservant les informations essentielles.

## Instructions

1. Identifier les **idées principales** du texte source.
2. Éliminer les détails secondaires et les répétitions.
3. Structurer le résumé avec :
   - Une phrase d'introduction donnant le sujet,
   - Les points clés sous forme de liste,
   - Une phrase de conclusion.
4. Le résumé ne doit pas dépasser **30 % de la longueur** du texte original.

## Format de sortie

```markdown
**Résumé** : [phrase d'introduction]

- Point clé 1
- Point clé 2
- ...

**Conclusion** : [phrase de synthèse]
```

## Exemples

**Entrée** : Un paragraphe de 200 mots sur LangGraph.

**Sortie attendue** :
> **Résumé** : LangGraph est un framework d'orchestration pour agents LLM.
>
> - Gestion automatique de la mémoire et de l'état
> - Support multi-sessions via thread_id
> - Intégration native avec LangChain
>
> **Conclusion** : LangGraph simplifie la construction d'agents stateful.
