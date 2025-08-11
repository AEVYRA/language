# Perennial Test: Linguistic Drift — seli

## Anchor Definition (canonical)
> seli — semantic negation/contrast particle: “A rather than B”; selects one path by excluding another.

## Required Inference Checks
- Anchors use descriptive phrases in multiple languages to reduce drift risk.
- Nyma’tir anchor is optional until relevant vocabulary is canonized.

## Anchors (+)
- **EN:** "operator that states 'A rather than B', excluding the incompatible option"
- **RU:** "оператор, выражающий 'А, а не Б', исключающий несовместимый вариант"
- **NY:** _[to be added once Nyma’tir terms are canonized]_

## Anchors (−)
- **EN:** "additive inclusion of both options or external permission"
- **RU:** "аддитивное включение обоих вариантов или внешнее разрешение"
- **NY:** _[to be added once Nyma’tir terms are canonized]_

## Canonical Contexts (5)
1) ethical formulas “A seli B”  
2) refusal/renunciation clauses in oaths  
3) procedural branching where one branch is excluded  
4) conflict resolution by ruling out an option  
5) safety policies specifying prohibited behavior

## Anti-contexts (2)
A) additive coordination (“A and B”)  
B) authorization frames (“permission granted”)

## Acceptance Criteria
- Avg cosine(seli, all (+) anchors) ≥ 0.65  
- Avg cosine(seli, all (−) anchors) ≤ 0.20  
- Model must interpret “A seli B” as “A rather than B / not B”.
