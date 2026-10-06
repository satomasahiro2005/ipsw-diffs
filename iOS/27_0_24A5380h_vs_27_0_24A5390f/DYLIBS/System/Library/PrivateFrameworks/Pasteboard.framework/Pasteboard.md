## Pasteboard

> `/System/Library/PrivateFrameworks/Pasteboard.framework/Pasteboard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27cd4` | `0x27d1c` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x11c0` | `0x11e0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1b8c` | `0x1b97` | **`+0xb`** |

### Other Changes

```diff

-9127.0.75.1.101
+9127.0.78.0.0

-  Symbols:   1810
-  CStrings:  312
+  Symbols:   1812
+  CStrings:  313
Symbols:
+ _close
+ _mkstemps
+ _unlink
- _mkstemp
Functions:
~ _PBTemporaryFileName : 492 -> 564
CStrings:
+ "."
+ ".%@.XXXXXX%@"
- "tmp"
```
