# ASCT – Abstract Structured Component Tree

ASCT is a universal, declarative JSON format for describing UI as nested, styled, and bindable component trees.

It is designed to be:
- 🔁 runtime-renderable
- 🧱 modular and composable
- 🌐 portable across web, mobile, dashboard, and builder systems
- 🎨 theme-friendly and style-token based

**Declare once. Render anywhere.**

## Example

```json
{
  "type": "section",
  "styleToken": "hero",
  "children": [
    {
      "type": "text",
      "props": { "text": "Welcome, {{user.name}}" }
    },
    {
      "type": "button",
      "props": {
        "label": "Start now",
        "action": { "type": "navigate", "target": "/dashboard" }
      }
    }
  ]
}
```

More examples, schema definition, and the first runtime renderer coming soon.
