# Classification Prompt Templates

## Text Classification

Classify the text into exactly one label.

Labels:
- Account Access
- Billing
- Technical Support
- Product Feedback
- General Inquiry

Return JSON:
{
  "label": "",
  "confidence": "",
  "reason": ""
}

## Sentiment Classification

Classify sentiment as Positive, Negative, Neutral, or Mixed.

Do not infer emotion that is not expressed.
