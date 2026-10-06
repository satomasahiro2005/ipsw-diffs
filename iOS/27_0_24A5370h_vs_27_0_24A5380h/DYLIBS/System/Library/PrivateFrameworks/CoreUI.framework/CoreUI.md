## CoreUI

> `/System/Library/PrivateFrameworks/CoreUI.framework/CoreUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe67f8` | `0xe6310` | **`-0x4e8`** |
| `__DATA.__bss` | `0x9c8` | `0x7b8` | **`-0x210`** |
| `__DATA_DIRTY.__bss` | `0x3c8` | `0x538` | **`+0x170`** |
| `__AUTH_CONST.__const` | `0x3728` | `0x3660` | **`-0xc8`** |
| `__TEXT.__const` | `0x6538` | `0x64c8` | **`-0x70`** |
| `__TEXT.__constg_swiftt` | `0x33c` | `0x2fc` | **`-0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x284` | `0x24c` | **`-0x38`** |
| `__TEXT.__unwind_info` | `0x4410` | `0x43e0` | **`-0x30`** |
| `__DATA_CONST.__got` | `0xa28` | `0xa48` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x188` | `0x168` | **`-0x20`** |
| `__TEXT.__cstring` | `0x25cd6` | `0x25cb7` | **`-0x1f`** |
| `__TEXT.__swift5_typeref` | `0x3a0` | `0x38e` | **`-0x12`** |
| `__TEXT.__swift5_reflstr` | `0x132` | `0x123` | **`-0xf`** |
| `__AUTH_CONST.__auth_got` | `0x17c0` | `0x17b8` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x60` | `0x58` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x24` | `0x20` | **`-0x4`** |
| `__DATA.__common` | `0xb` | `0x8` | **`-0x3`** |

### Other Changes

```diff

-1006.0.0.0.0
+1007.0.0.0.0

-  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

-  Functions: 5843
-  Symbols:   9217
-  CStrings:  5504
+  Functions: 5831
+  Symbols:   9211
+  CStrings:  5501
Symbols:
- ___swift_destroy_boxed_opaque_existential_0Tm
- ___swift_exist.box.addr_destructor
- _symbolic _____ 6CoreUI12FeatureFlagsO
- _symbolic _____ 6CoreUI12FeatureFlagsO3Key33_4CF804A7504C62A9106D52B93F22FFAELLV
- _symbolic _____ s12StaticStringV
- _type_layout_string 6CoreUI12FeatureFlagsO3Key33_4CF804A7504C62A9106D52B93F22FFAELLV
CStrings:
+ "CoreUI: %s couldn't create bitmapContext for (%fx%f) colorSpace:'%@' [canvasSize:%fx%f scale:%f bpc:%zd bpp:%zd bitmapInfo:%d]"
- "Calistoga"
- "CoreUI: %s couldn't create bitmapContext for %s (%fx%f) colorSpace:'%@' [pdfsize:%fx%f scale:%f bpc:%zd bpp:%zd bitmapInfo:%zd]"
- "IconServices"
- "SwiftUI"
```
