## GAXClient

> `/System/Library/AccessibilityBundles/GAXClient.bundle/GAXClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa810` | `0xa880` | **`+0x70`** |
| `__TEXT.__cstring` | `0x2c51` | `0x2c8c` | **`+0x3b`** |
| `__DATA_CONST.__cfstring` | `0x2b40` | `0x2b60` | **`+0x20`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1067.3.1.0.0
+1067.3.3.0.0

-  Functions: 262
-  Symbols:   476
-  CStrings:  776
+  Functions: 264
+  Symbols:   478
+  CStrings:  777
Symbols:
+ _GAXBackboardStateAllowsAllTouchByOverride
+ _GAXBackboardStateAllowsAllTouchForTransientSystemUI
CStrings:
+ "  overrideAllowsAllTouchAuthenticatingWithBiometrics: %ld\n"
```
