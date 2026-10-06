## nanoprefsyncd

> `/System/Library/PrivateFrameworks/NanoPreferencesSync.framework/nanoprefsyncd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x3cf4` | `0x3d8f` | **`+0x9b`** |
| `__TEXT.__text` | `0x26034` | `0x260a4` | **`+0x70`** |
| `__DATA.__objc_const` | `0x3068` | `0x3048` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x4b8` | `0x4d8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x778` | `0x770` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x254` | `0x250` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-332.0.0.0.0
+334.0.0.0.0

-  Functions: 732
-  Symbols:   330
-  CStrings:  1298
+  Functions: 733
+  Symbols:   334
+  CStrings:  1300
Symbols:
+ _MCFeatureKeyboardMathSolvingAllowed
+ _MCFeatureMathPaperSolvingAllowed
+ _MCFeatureSiriReduceSensitiveContentForced
+ _MCFeatureWritingToolsAllowed
CStrings:
+ "Launching; \"NanoPreferencesSyncDaemon-334\" \"51\""
+ "No cache path for domain: (%@); isPerGizmo: (%d). Cache not written."
+ "No cache path for domain: (%@); isPerGizmo: (%d). Not updating timestamps for %lu keys."
- "Launching; \"NanoPreferencesSyncDaemon-332\" \"2800\""
```
