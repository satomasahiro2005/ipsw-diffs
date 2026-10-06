## UIIntelligenceIntents

> `/System/Library/PrivateFrameworks/UIIntelligenceIntents.framework/UIIntelligenceIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1435` | `0x139a` | **`-0x9b`** |
| `__TEXT.__eh_frame` | `0x1bac` | `0x1c14` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x9ba` | `0xa1a` | **`+0x60`** |
| `__DATA.__common` | `0x350` | `0x300` | **`-0x50`** |
| `__DATA_CONST.__const` | `0xf8` | `0x140` | **`+0x48`** |
| `__TEXT.__text` | `0x2cf04` | `0x2cf4c` | **`+0x48`** |
| `__DATA.__data` | `0xdf8` | `0xdc0` | **`-0x38`** |
| `__DATA_CONST.__got` | `0x2c8` | `0x2e8` | **`+0x20`** |
| `__TEXT.__const` | `0x3bb8` | `0x3bd8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xe68` | `0xe78` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x9f0` | `0x9f8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x628` | `0x630` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xd4` | `0xd8` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xb8` | `0xbc` | **`+0x4`** |
| `__TEXT.__swift5_typeref` | `0x117a` | `0x1179` | **`-0x1`** |

### Other Changes

```diff

-9127.0.84.1.106
+9127.1.5.0.0

-  Functions: 1072
-  Symbols:   683
-  CStrings:  141
+  Functions: 1062
+  Symbols:   694
+  CStrings:  137
Symbols:
+ _IAPayloadKeyWritingToolsBundleID
+ _IASignalWritingToolsIntentInsertText
+ _IASignalWritingToolsIntentKeyPoints
+ _IASignalWritingToolsIntentPresentResult
+ _IASignalWritingToolsIntentProofread
+ _IASignalWritingToolsIntentRequestEditingContext
+ _IASignalWritingToolsIntentRewrite
+ _IASignalWritingToolsIntentSummarize
+ _IASignalWritingToolsIntentTransformList
+ _IASignalWritingToolsIntentTransformTable
+ _objc_retain_x27
CStrings:
+ "Writing Tools session already active on %{public}s — skipping becomeFirstResponder"
- "IntentInsertText"
- "IntentPresentResult"
- "IntentRequestEditingContext"
- "IntentTransformList"
- "IntentTransformTable"
```
