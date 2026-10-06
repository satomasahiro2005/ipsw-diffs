## NewsPersonalization

> `/System/Library/PrivateFrameworks/NewsPersonalization.framework/NewsPersonalization`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24a040` | `0x24a734` | **`+0x6f4`** |
| `__DATA.__bss` | `0x21610` | `0x21790` | **`+0x180`** |
| `__TEXT.__cstring` | `0x10ea1` | `0x10fd1` | **`+0x130`** |
| `__TEXT.__const` | `0x19d50` | `0x19e10` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0xbb88` | `0xbc18` | **`+0x90`** |
| `__DATA.__data` | `0x4c98` | `0x4d08` | **`+0x70`** |
| `__DATA_DIRTY.__data` | `0xa048` | `0xa008` | **`-0x40`** |
| `__TEXT.__swift5_reflstr` | `0x5015` | `0x5045` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x2e68` | `0x2e88` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x54ac` | `0x54c8` | **`+0x1c`** |
| `__TEXT.__swift5_fieldmd` | `0x5fbc` | `0x5fd8` | **`+0x1c`** |
| `__TEXT.__unwind_info` | `0x85e0` | `0x85f8` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x4585` | `0x4593` | **`+0xe`** |
| `__TEXT.__swift5_proto` | `0x1498` | `0x14a4` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x6b4` | `0x6b8` | **`+0x4`** |
| `__TEXT.__oslogstring` | `0x30e` | `0x30d` | **`-0x1`** |

### Other Changes

```diff

-5926.0.0.0.0
+5934.2.0.0.0

-  Functions: 11564
-  Symbols:   2714
-  CStrings:  1173
+  Functions: 11570
+  Symbols:   2716
+  CStrings:  1177
Symbols:
+ _associated conformance 19NewsPersonalization28GroupFormationBestOfProviderC6ErrorsOSHAASQ
+ _symbolic _____ 19NewsPersonalization28GroupFormationBestOfProviderC6ErrorsO
CStrings:
+ "Failed to extract embedding feature: unexpected feature encoding: %{public}@"
+ "groupFormation.titleEmbedding"
+ "groupFormation.topicIDs"
+ "groupFormation.topicIDs.contentRatings"
+ "groupFormation.topicIDs.relevanceRatings"
+ "groupFormation: WARNING title embeddings substituted with zero vectors — decodeFailures=%ld dimMismatch=%ld of %ld (expected %ld bytes, dim=%ld)"
- "Failed to extract embedding feature: %{public}@"
- "Failed to get features for keys %{public}@"
```
