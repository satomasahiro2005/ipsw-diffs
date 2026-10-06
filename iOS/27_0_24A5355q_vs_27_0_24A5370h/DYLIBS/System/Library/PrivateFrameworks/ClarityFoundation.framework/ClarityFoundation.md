## ClarityFoundation

> `/System/Library/PrivateFrameworks/ClarityFoundation.framework/ClarityFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7408` | `0x74c8` | **`+0xc0`** |
| `__AUTH_CONST.__cfstring` | `0xa40` | `0xa60` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xae4` | `0xafc` | **`+0x18`** |
| `__TEXT.__cstring` | `0x847` | `0x858` | **`+0x11`** |
| `__AUTH_CONST.__objc_const` | `0x1328` | `0x1338` | **`+0x10`** |
| `__DATA.__bss` | `0x448` | `0x458` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x6e0` | `0x6f0` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x30` | `0x20` | **`-0x10`** |

### Other Changes

```diff

-3229.1.6.0.0
+3232.3.0.0.0

-  Functions: 225
-  Symbols:   557
-  CStrings:  123
+  Functions: 227
+  Symbols:   559
+  CStrings:  124
Symbols:
+ -[CLFPhoneFaceTimeSettings_GeneratedCode setVoicemailEnabled:]
+ -[CLFPhoneFaceTimeSettings_GeneratedCode voicemailEnabled]
+ GCC_except_table149
+ GCC_except_table159
+ GCC_except_table163
- GCC_except_table147
- GCC_except_table155
- GCC_except_table161
CStrings:
+ "VoicemailEnabled"
```
