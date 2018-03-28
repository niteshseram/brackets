| Name | Description |
| ---- | ----------- |
| `hasHints*` | `CodeHintManager` uses this mandatory hook to query whether this particular hint provider can provide hint in the current context.|
| `getHints*` | `CodeHintManager` uses this mandatory hook to fetch hint list in the current context if this provider is selected to be the code hint provider for the current hinting session.|
| `insertHint*` | `CodeHintManager` uses this mandatory hook to let the active hint provider handle the selected token insertion.|