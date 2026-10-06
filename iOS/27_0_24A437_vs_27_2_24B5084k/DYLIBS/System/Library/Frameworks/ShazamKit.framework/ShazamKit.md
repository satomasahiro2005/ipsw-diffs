## ShazamKit

> `/System/Library/Frameworks/ShazamKit.framework/ShazamKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa68cc` | `0xa69c8` | **`+0xfc`** |
| `__TEXT.__oslogstring` | `0x1471` | `0x14e1` | **`+0x70`** |

### Other Changes

```diff

-427.0.48.0.0
+427.2.4.0.0

-  CStrings:  587
+  CStrings:  590
Functions:
~ -[SHSession matcher:didProduceResponse:] : 748 -> 1000
CStrings:
+ "SHSession: Match attempt finished with error: %@"
+ "SHSession: Match attempt was cancelled"
+ "SHSession: No Match found"
```
