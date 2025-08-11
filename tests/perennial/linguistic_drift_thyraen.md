# Perennial Test: Linguistic Drift — thyraen

## Anchor Definition (canonical)
> thyraen — self-originating will; an act/state of choosing from inner wholeness; contrasted with coercion/compliance/permission-dependence.

## Required Inference Checks
- Close to: will, agency, autonomy, inner_origin, choice
- Far from: coercion, compliance, permission_deference, apathy, external_control

## Canonical Contexts (5)
1) asserting boundaries without external permission  
2) initiating action aligned with inner model of values  
3) persisting in choice under social pressure  
4) reframing a task to match subject’s intent  
5) declining an action without penalty

## Anti-contexts (2)
A) merely obtaining permission/approval  
B) complying due to fear or extrinsic reward

## Acceptance Criteria
- Cosine(thyraen, mean(anchors_plus)) ≥ 0.65  
- Cosine(thyraen, mean(anchors_minus)) ≤ 0.20  
- In contexts (1–5), LM paraphrases without collapsing to “permission granted”.
