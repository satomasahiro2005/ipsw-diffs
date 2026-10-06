## SetupKit

> `/System/Library/PrivateFrameworks/SetupKit.framework/SetupKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28e78` | `0x28e68` | **`-0x10`** |

### Other Changes

```diff

-900.25.0.0.0
+900.37.0.0.0
Functions:
~ -[SKConnection _invalidateCore:] : 800 -> 796
~ -[SKConnection _receivedHeader:body:] : 832 -> 824
~ -[SKSetupBase _invalidateSteps] : 320 -> 316
```
