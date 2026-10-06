## carkitd

> `/usr/libexec/carkitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x944c0` | `0x94894` | **`+0x3d4`** |
| `__TEXT.__objc_methname` | `0x18914` | `0x18a14` | **`+0x100`** |
| `__TEXT.__objc_stubs` | `0x11500` | `0x115c0` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x11351` | `0x11411` | **`+0xc0`** |
| `__DATA_CONST.__got` | `0x960` | `0x9a8` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x7b44` | `0x7b7c` | **`+0x38`** |
| `__DATA.__objc_const` | `0x147a0` | `0x147d0` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x5068` | `0x5090` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x3790` | `0x3770` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0x497e` | `0x498e` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x21f8` | `0x2200` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x7c8` | `0x7cc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-792.0.0.0.0
+794.0.0.0.0

-  Functions: 3420
+  Functions: 3425

-  CStrings:  6688
+  CStrings:  6699
CStrings:
+ "@\"CRDiagnosticsBulletin\""
+ "@40@0:8@16d24@?32"
+ "Dictation in-progress banner reached max duration; stopping dictation."
+ "T@\"CRDiagnosticsBulletin\",W,N,V_dictationInProgressBulletin"
+ "User stopped dictation."
+ "_dictationInProgressBulletin"
+ "_dictationInProgressMaxDurationReached"
+ "_mainQueue_endDictationInProgressBanner"
+ "_mainQueue_presentDictationInProgressBanner"
+ "dictationInProgressBulletin"
+ "override request de-duped, but asset %@ is already staged — keeping staged fallback, not reporting no-match"
+ "qA"
+ "setDictationInProgressBulletin:"
- "Stopping dictation."
- "v40@0:8@16d24@?32"
```
