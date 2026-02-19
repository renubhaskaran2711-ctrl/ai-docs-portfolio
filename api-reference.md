# API Reference

## POST /generate-reply

Generates a customer support reply based on ticket input.

### Request Body

| Field        | Type   | Required | Description |
|--------------|--------|----------|------------|
| ticket_text  | string | Yes      | Customer support message |
| tone         | string | No       | Response tone (empathetic, formal, friendly) |

### Example Request

```json
{
  "ticket_text": "My order is delayed.",
  "tone": "empathetic"
}
```

### Example Response

```json
{
  "reply": "I apologize for the delay. Let me check the status for you."
}
```
