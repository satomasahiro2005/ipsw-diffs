## DistributedSensing

> `/System/Library/PrivateFrameworks/DistributedSensing.framework/DistributedSensing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16920` | `0x169b4` | **`+0x94`** |
| `__AUTH_CONST.__objc_intobj` | `0x18` | `0x48` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x644` | `0x654` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1a8` | `0x1b0` | **`+0x8`** |
| `__TEXT.__cstring` | `0x932` | `0x934` | **`+0x2`** |

### Other Changes

```diff

-2.3.0.0.0
+2.4.0.0.0

-  Symbols:   1069
-  CStrings:  360
+  Symbols:   1067
+  CStrings:  361
Symbols:
+ _RPOptionStatusFlags
- ___49-[DSListener startMotionDataListenerWithOptions:]_block_invoke_4
- ___49-[DSListener startMotionDataListenerWithOptions:]_block_invoke_5
- ___49-[DSProvider startMotionDataProviderWithOptions:]_block_invoke_3
Functions:
~ -[DSProvider startMotionDataProviderWithOptions:] : 1796 -> 1872
~ -[DSListener startMotionDataListenerWithOptions:] : 1176 -> 1248
CStrings:
+ "Q"
```
