## TinCanShared

> `/System/Library/PrivateFrameworks/TinCanShared.framework/TinCanShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x124c8` | `0x125a4` | **`+0xdc`** |
| `__AUTH_CONST.__const` | `0x1a0` | `0x1c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0xe79` | `0xe96` | **`+0x1d`** |
| `__TEXT.__objc_methlist` | `0x1254` | `0x1264` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xe80` | `0xe88` | **`+0x8`** |

### Other Changes

```diff

-245.0.0.0.0
+247.0.0.0.0

-  Functions: 441
-  Symbols:   939
-  CStrings:  278
+  Functions: 443
+  Symbols:   940
+  CStrings:  279
Symbols:
+ -[TCSCallCenter sendingCall]
+ GCC_except_table51
+ _sendingCallPredicate_block_invoke_5
- GCC_except_table29
- GCC_except_table49
Functions:
+ _sendingCallPredicate_block_invoke_5
+ -[TCSCallCenter sendingCall]
CStrings:
+ "-[TCSCallCenter sendingCall]"
```
