# Quickstart Guide

This guide helps developers integrate the AI Support Assistant API in minutes.

---

## 1. Authentication

All requests require an API key.

Add the API key in the header:

Authorization: Bearer YOUR_API_KEY

---

## 2. Make Your First Request

### Using curl

```bash
curl -X POST https://api.aisupportassistant.com/v1/generate-reply \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "ticket_text": "My product arrived damaged.",
    "tone": "empathetic"
  }'
```

---

## 3. Example Response

```json
{
  "reply": "I'm very sorry your product arrived damaged. Let me arrange a replacement immediately."
}
```

---

## 4. Error Handling

| Code | Meaning |
|------|----------|
| 401  | Unauthorized |
| 429  | Rate limit exceeded |
| 500  | Server error |
