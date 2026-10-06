## SwiftTLS

> `/System/Library/PrivateFrameworks/SwiftTLS.framework/SwiftTLS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__data` | `0x560` | `—` | **`-0x560`** |
| `__DATA_DIRTY.__data` | `0x2de0` | `0x3340` | **`+0x560`** |
| `__TEXT.__text` | `0xdfd68` | `0xe0024` | **`+0x2bc`** |
| `__TEXT.__oslogstring` | `0x39de` | `0x3a6e` | **`+0x90`** |

### Other Changes

```diff

-171.40.7.0.0
+171.40.10.0.0

-  CStrings:  389
+  CStrings:  391
Functions:
~ sub_2b45e40d8 -> sub_2b492d040 : 1108 -> 1808
CStrings:
+ "alert record contained trailing bytes after a complete alert message"
+ "alert record did not contain a complete alert message"
```
