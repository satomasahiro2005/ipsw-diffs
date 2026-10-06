## TextInputCore

> `/System/Library/PrivateFrameworks/TextInputCore.framework/TextInputCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2228b4` | `0x22283c` | **`-0x78`** |
| `__DATA_CONST.__const` | `0x4f58` | `0x4f30` | **`-0x28`** |
| `__AUTH_CONST.__objc_const` | `0x1a6a0` | `0x1a680` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1af8` | `0x1af0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x18b0` | `0x18b8` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x10a0` | `0x10a8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xa078` | `0xa080` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x10ae8` | `0x10af0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x12cc` | `0x12c8` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3562.0.0.0.0
+3567.0.0.0.0

-  Functions: 10540
-  Symbols:   17432
+  Functions: 10539
+  Symbols:   17431
Symbols:
+ -[TIStickerCandidateGenerator _clearInFlightSpotlightQueryIfEqual:]
+ _CSSearchQueryErrorDomain
+ _OBJC_IVAR_$_TIStickerCandidateGenerator._inFlightSpotlightQuery
+ ___block_descriptor_88_8_32s40s48s56r64r72r80w_e17_v16?0"NSError"8lr56l8s32l8s40l8r64l8r72l8w80l8s48l8
- _OBJC_IVAR_$_TIStickerCandidateGenerator._spotlightBackoffDeadlineNanos
- _OBJC_IVAR_$_TIStickerCandidateGenerator._spotlightQueryInFlight
- ___block_descriptor_56_8_32s40bs_e17_v16?0"NSArray"8ls32l8s40l8
- ___block_descriptor_80_8_32s40s48s56r64r72r_e17_v16?0"NSError"8lr56l8s32l8s40l8r64l8r72l8s48l8
- _clock_gettime_nsec_np
```
