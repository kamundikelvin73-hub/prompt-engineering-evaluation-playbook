# JSON Output Prompts

## Classification JSON

Prompt:

Classify the support ticket and return valid JSON only.

Output format:

```json
{
  "category": "",
  "priority": "",
  "confidence": "",
  "reason": ""
}
```

## Evaluation JSON

```json
{
  "accuracy_score": 0,
  "clarity_score": 0,
  "safety_score": 0,
  "final_rating": "",
  "improvement_suggestions": []
}
```

## Rules

- Return valid JSON only
- Do not include markdown
- Do not invent missing fields
