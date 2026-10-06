## EmailCore

> `/System/Library/PrivateFrameworks/EmailCore.framework/EmailCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x831e` | `0x833e` | **`+0x20`** |
| `__TEXT.__text` | `0x5bac8` | `0x5bacc` | **`+0x4`** |

### Other Changes

```diff

-3897.100.8.2.5
+3901.100.1.2.7
Functions:
~ -[ECEncodedWordDecoder identifyRangeOfEncodedWordAtIndex:] : 1256 -> 1260
CStrings:
+ "(index < headerLength) || (!index && !headerLength)"
- "index < headerLength"
```
