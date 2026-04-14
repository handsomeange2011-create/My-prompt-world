## 🛡️ AI Security & Safety Guardrails

A breakdown of how I prevent "Prompt Injection" and "Data Leakage."

1. **Sandboxing:** Using XML tags to separate user input from system instructions.
2. **Negative Constraint Layering:** Explicitly banning the mention of internal API keys or PII (Personally Identifiable Information).
3. **Refusal Logic:** Training the model on when to say "I cannot fulfill this request" rather than hallucinating a dangerous answer.
