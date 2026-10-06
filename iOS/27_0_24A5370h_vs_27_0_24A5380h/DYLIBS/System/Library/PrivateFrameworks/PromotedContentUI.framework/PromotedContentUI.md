## PromotedContentUI

> `/System/Library/PrivateFrameworks/PromotedContentUI.framework/PromotedContentUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x5b98` | `0x73c0` | **`+0x1828`** |
| `__TEXT.__text` | `0x191d0c` | `0x192be4` | **`+0xed8`** |
| `__DATA.__bss` | `0xa880` | `0x9a00` | **`-0xe80`** |
| `__DATA_DIRTY.__bss` | `0x2d80` | `0x3c00` | **`+0xe80`** |
| `__AUTH.__data` | `0x2388` | `0x1628` | **`-0xd60`** |
| `__DATA.__data` | `0x3650` | `0x2b90` | **`-0xac0`** |
| `__DATA_DIRTY.__objc_data` | `0x3c18` | `0x4328` | **`+0x710`** |
| `__AUTH.__objc_data` | `0x33f8` | `0x2cf8` | **`-0x700`** |
| `__TEXT.__eh_frame` | `0x60c0` | `0x61c0` | **`+0x100`** |
| `__DATA.__common` | `0x258` | `0x178` | **`-0xe0`** |
| `__DATA_DIRTY.__common` | `0x158` | `0x238` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x7901` | `0x7971` | **`+0x70`** |
| `__TEXT.__const` | `0xe834` | `0xe874` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x5a94` | `0x5ad4` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x4b70` | `0x4b98` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0xa9f0` | `0xaa10` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x3530` | `0x3548` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x16b8` | `0x16a0` | **`-0x18`** |
| `__TEXT.__swift5_typeref` | `0x6ebc` | `0x6ea4` | **`-0x18`** |
| `__TEXT.__constg_swiftt` | `0x791c` | `0x792c` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x6428` | `0x6438` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x5858` | `0x5864` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d48` | `0x1d40` | **`-0x8`** |

### Other Changes

```diff

-557.1.21.0.0
+557.1.24.0.0

-  Functions: 6519
+  Functions: 6525

-  CStrings:  970
+  CStrings:  975
CStrings:
+ "[SLP] API received empty content array"
+ "[SLP] API response received %{public}ld ads. AdamIds: %{private}s"
+ "[SRP] Incrementality eval took %{public}f s"
+ "curate API response received %{public}ld items (%{public}ld ads). Ad adamIDs: %{private}s"
+ "curate API response received at %{public}f"
+ "curate returning %{public}ld ranked candidates, adamIDs: %{private}s"
+ "noNoiseNoAccount"
+ "noNoiseRestrictedAge"
+ "payload returned at: %{public}f"
- "Unable to determine action button height contributing to ad height using trait collection %ld."
- "Unable to determine action button placement using trait collection: %ld."
- "Unable to determine bottom margin using trait collection: %ld."
- "Unable to determine headline height using trait collection: %ld."
```
