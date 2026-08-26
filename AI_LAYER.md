# AI Decision Layer

The AI layer is grounded in the live state of the financial model.

## Flow

```text
Current model state
      ↓
Context snapshot
      ↓
Gemini reasoning
      ↓
Analysis
      ↓
Prescriptive recommendation
```

The application builds a real-time snapshot containing the active screen, consolidated economics, client economics, risk flags and relevant pricing assumptions. That snapshot is passed as grounding context to the AI analyst.

The AI instructions explicitly require the model to use the supplied data, avoid inventing figures, focus on the active screen when relevant and provide concrete actions with estimated impact.

## Principle

**The model calculates. The AI reasons over the model state.**

Users provide their own Gemini API key locally; credentials are not stored in this repository.
