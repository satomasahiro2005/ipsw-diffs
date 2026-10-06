## WritingTools

> `/System/Library/PrivateFrameworks/WritingTools.framework/WritingTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa380` | `0xa564` | **`+0x1e4`** |
| `__AUTH_CONST.__objc_const` | `0x12b0` | `0x1340` | **`+0x90`** |
| `__TEXT.__cstring` | `0x5f7` | `0x647` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x85c` | `0x8a4` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x580` | `0x5c0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x4c8` | `0x500` | **`+0x38`** |
| `__AUTH_CONST.__const` | `0x2c0` | `0x2d8` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x150` | `0x168` | **`+0x18`** |
| `__DATA.__common` | `—` | `0x8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x70` | `0x78` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x240` | `0x248` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x300` | `0x308` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x380` | `0x388` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-129.1.103.0.0
+134.0.0.0.0

-  Functions: 268
-  Symbols:   529
-  CStrings:  72
+  Functions: 275
+  Symbols:   536
+  CStrings:  75
Symbols:
+ -[WTSession initWithType:textViewDelegate:uuid:]
+ -[WTSession isFromExternalResult]
+ -[WTSession setIsFromExternalResult:]
+ -[WTTextSuggestion grammarUUID]
+ -[WTTextSuggestion setGrammarUUID:]
+ _OBJC_IVAR_$_WTSession._isFromExternalResult
+ _OBJC_IVAR_$_WTTextSuggestion._grammarUUID
CStrings:
+ "1"
+ "WTSessionCodingKeyGrammarUUID"
+ "WTSessionCodingKeyIsFromExternalResult"
+ "grammarUUID"
- "!"
```
