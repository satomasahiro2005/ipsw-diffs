## TextToSpeech

> `/System/Library/PrivateFrameworks/TextToSpeech.framework/TextToSpeech`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30c5d4` | `0x31394c` | **`+0x7378`** |
| `__TEXT.__eh_frame` | `0x16db8` | `0x17100` | **`+0x348`** |
| `__TEXT.__oslogstring` | `0x28f4` | `0x2a64` | **`+0x170`** |
| `__TEXT.__unwind_info` | `0xc518` | `0xc5f0` | **`+0xd8`** |
| `__AUTH_CONST.__const` | `0x15d10` | `0x15c48` | **`-0xc8`** |
| `__TEXT.__const` | `0x3e889` | `0x3e949` | **`+0xc0`** |
| `__AUTH.__data` | `0x4140` | `0x41d0` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x7202` | `0x726e` | **`+0x6c`** |
| `__TEXT.__cstring` | `0x78ae` | `0x78fe` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x3cc0` | `0x3d08` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x5c2c` | `0x5c6c` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x2910` | `0x2948` | **`+0x38`** |
| `__AUTH.__objc_data` | `0x2d50` | `0x2d30` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0xa520` | `0xa500` | **`-0x20`** |
| `__DATA.__bss` | `0x25258` | `0x25278` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x7b10` | `0x7b30` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x4830` | `0x4810` | **`-0x20`** |
| `__TEXT.__swift5_capture` | `0x2ff4` | `0x2fd8` | **`-0x1c`** |
| `__DATA_CONST.__const` | `0x18f8` | `0x1910` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x28a0` | `0x28b0` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x1278` | `0x1284` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x724` | `0x72c` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xd14` | `0xd0c` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0xc2c` | `0xc28` | **`-0x4`** |

### Other Changes

```diff

-713.1.0.0.0
+716.0.0.0.0

-  Functions: 15444
+  Functions: 15491

-  CStrings:  1564
+  CStrings:  1570
CStrings:
+ "%s: rejecting replacement at range overlapping a prior replacement"
+ "(?i)\\b(a\\.?m\\.?|p\\.?m\\.?)\\b"
+ "applyReplacements: skipping markup replacement overlapping prior accepted range"
+ "applyReplacements: skipping markup replacement with range outside source text"
+ "applyReplacements: skipping markup replacement, computed offset %ld length %ld out of bounds for transformed utf8 length %ld"
+ "assetOrThrow(voice:onlyInstalled:)"
+ "transformedAsync"
- "assetOrThrow(voice:)"
```
