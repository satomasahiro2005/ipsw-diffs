## SoundAnalysis

> `/System/Library/Frameworks/SoundAnalysis.framework/SoundAnalysis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x32644c` | `0x326d1c` | **`+0x8d0`** |
| `__AUTH.__data` | `0x29e8` | `0x2628` | **`-0x3c0`** |
| `__DATA_DIRTY.__data` | `0x88e0` | `0x8c88` | **`+0x3a8`** |
| `__TEXT.__eh_frame` | `0x260f4` | `0x2626c` | **`+0x178`** |
| `__DATA_CONST.__got` | `0xea8` | `0xf40` | **`+0x98`** |
| `__AUTH.__objc_data` | `0x1ab8` | `0x1a28` | **`-0x90`** |
| `__DATA_DIRTY.__objc_data` | `0x4eb0` | `0x4f40` | **`+0x90`** |
| `__DATA.__bss` | `0x5bab0` | `0x5ba30` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x2f10` | `0x2f90` | **`+0x80`** |
| `__TEXT.__cstring` | `0xe63e` | `0xe69e` | **`+0x60`** |
| `__TEXT.__const` | `0x3eb90` | `0x3ebd0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x13128` | `0x13168` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x3bae` | `0x3bce` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0xc928` | `0xc940` | **`+0x18`** |
| `__DATA.__common` | `0x160` | `0x150` | **`-0x10`** |
| `__DATA.__data` | `0xd298` | `0xd288` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x7bc` | `0x7cc` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x948` | `0x958` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2588` | `0x2590` | **`+0x8`** |
| `__AUTH_CONST.__const` | `0x2c008` | `0x2c010` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `0x208` | `0x210` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xcf0` | `0xcec` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-500.162.0.0.0
+500.167.0.0.0

-  Functions: 27241
-  Symbols:   924
-  CStrings:  1561
+  Functions: 27252
+  Symbols:   925
+  CStrings:  1563
Symbols:
+ _objc_retain_x10
+ _objc_retain_x12
- _objc_retain_x11
CStrings:
+ "Initialized uLanguageAligned detector head '%s' with activation threshold: %f, version: %s, base model: %s"
+ "com.apple.soundanalysis.detectorHead.baseModel"
+ "com.apple.soundanalysis.detectorHead.version"
- "Initialized uLanguageAligned detector head '%s' with activation threshold: %f"
```
