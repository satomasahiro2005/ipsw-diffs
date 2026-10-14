## AccessibilityUI

> `/System/Library/PrivateFrameworks/AccessibilityUI.framework/AccessibilityUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4930` | `0x49b0` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x8b9` | `0x8f8` | **`+0x3f`** |
| `__TEXT.__gcc_except_tab` | `0x2a4` | `0x2b0` | **`+0xc`** |

### Other Changes

```diff

-3245.8.4.2.0
+3245.8.9.0.0

-  CStrings:  63
+  CStrings:  64
Functions:
~ -[AXUIClientConnection _processXPCReply:context:] : 2240 -> 2368
CStrings:
+ "Could not process incoming message from %{public}@: %{public}@"
```
