## ShortcutsDiagnosticExtension

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/ShortcutsDiagnosticExtension.appex/ShortcutsDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77c` | `0x8d4` | **`+0x158`** |
| `__TEXT.__cstring` | `0xc2` | `0x119` | **`+0x57`** |
| `__TEXT.__oslogstring` | `0x136` | `0x166` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x1ee` | `0x211` | **`+0x23`** |
| `__DATA_CONST.__cfstring` | `0x80` | `0xa0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x280` | `0x2a0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2c` | `0x38` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0xa8` | `0xb0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-5025.0.25.103.0
+5028.0.21.0.0

-  Functions: 5
+  Functions: 6

-  CStrings:  40
+  CStrings:  44
Functions:
~ sub_10000140c : 152 -> 308
CStrings:
+ "%s Coherence context database not reachable: %@"
+ "-[ShortcutsDiagnosticExtension exportedCoherenceContextAttachment]"
+ "CoherenceContext.db"
+ "exportedCoherenceContextAttachment"
```
