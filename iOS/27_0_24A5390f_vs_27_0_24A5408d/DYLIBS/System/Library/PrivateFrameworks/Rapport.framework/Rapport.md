## Rapport

> `/System/Library/PrivateFrameworks/Rapport.framework/Rapport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd93f8` | `0xd962c` | **`+0x234`** |
| `__TEXT.__oslogstring` | `0x238d` | `0x242d` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x6080` | `0x60a0` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x2638` | `0x2658` | **`+0x20`** |
| `__DATA.__bss` | `0x2e90` | `0x2ea0` | **`+0x10`** |
| `__TEXT.__cstring` | `0x1449c` | `0x144ac` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x9f38` | `0x9f48` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x44d8` | `0x44e0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2ec8` | `0x2ed0` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0xc4` | `0xc8` | **`+0x4`** |

### Other Changes

```diff

-747.100.2.0.0
+751.100.2.0.0

-  Functions: 5742
-  Symbols:   6757
-  CStrings:  3007
+  Functions: 5746
+  Symbols:   6761
+  CStrings:  3009
Symbols:
+ -[RPCompanionLinkClient checkForStatusFlagsForMsg:options:]
+ GCC_except_table100
+ GCC_except_table147
+ GCC_except_table53
+ GCC_except_table58
+ GCC_except_table61
+ GCC_except_table65
+ GCC_except_table80
+ ___59-[RPCompanionLinkClient checkForStatusFlagsForMsg:options:]_block_invoke
+ _checkForStatusFlagsForMsg:options:.onceToken
+ _checkForStatusFlagsForMsg:options:.statusFlagsLog
- GCC_except_table145
- GCC_except_table50
- GCC_except_table51
- GCC_except_table55
- GCC_except_table63
- GCC_except_table78
- GCC_except_table98
CStrings:
+ "### Specifying the trust flags using RPOptionStatusFlags for registering message '%@' is required. Please file a radar in 'Rapport | All' to get more information."
+ "StatusFlagsLog"
+ "_ff"
+ "soundanalysisd"
- "MockA2DPActivity"
- "UltronApp"
```
