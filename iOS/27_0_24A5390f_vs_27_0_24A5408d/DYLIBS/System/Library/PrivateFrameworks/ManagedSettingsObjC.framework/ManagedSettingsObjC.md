## ManagedSettingsObjC

> `/System/Library/PrivateFrameworks/ManagedSettingsObjC.framework/ManagedSettingsObjC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x33b30` | `0x33ca4` | **`+0x174`** |
| `__AUTH_CONST.__cfstring` | `0x25e0` | `0x2600` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x9640` | `0x9660` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x48ac` | `0x48cc` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1cc0` | `0x1cd8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1238` | `0x1250` | **`+0x18`** |
| `__TEXT.__cstring` | `0x17ec` | `0x1801` | **`+0x15`** |
| `__DATA.__bss` | `0x8e0` | `0x8f0` | **`+0x10`** |
| `__TEXT.__const` | `0x90` | `0x98` | **`+0x8`** |

### Other Changes

```diff

-304.0.0.0.0
+304.2.6.0.0

-  Functions: 1620
-  Symbols:   3418
-  CStrings:  409
+  Functions: 1624
+  Symbols:   3424
+  CStrings:  410
Symbols:
+ +[MOIntelligenceSettingsGroup denyAccessibilityAskMetadata]
+ -[MOIntelligenceSettingsGroup denyAccessibilityAsk]
+ -[MOIntelligenceSettingsGroup setDenyAccessibilityAsk:]
+ ___59+[MOIntelligenceSettingsGroup denyAccessibilityAskMetadata]_block_invoke
+ _denyAccessibilityAskMetadata.metadata
+ _denyAccessibilityAskMetadata.onceToken
CStrings:
+ "denyAccessibilityAsk"
```
