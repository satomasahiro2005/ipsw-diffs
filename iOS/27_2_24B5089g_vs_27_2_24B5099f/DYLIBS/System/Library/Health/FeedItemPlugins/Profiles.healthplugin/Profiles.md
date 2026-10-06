## Profiles

> `/System/Library/Health/FeedItemPlugins/Profiles.healthplugin/Profiles`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x66d2c` | `0x66eb4` | **`+0x188`** |
| `__TEXT.__cstring` | `0xd5a` | `0xe5a` | **`+0x100`** |
| `__AUTH_CONST.__const` | `0x1ce8` | `0x1c70` | **`-0x78`** |
| `__TEXT.__eh_frame` | `0x17f8` | `0x1830` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x1640` | `0x1650` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x41c` | `0x40c` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x6b0` | `0x6b8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x14c8` | `0x14d0` | **`+0x8`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 1747
+  Functions: 1743

-  CStrings:  195
+  CStrings:  199
CStrings:
+ "PrimaryProfileInformationExecutor:getLatestActivitySummary"
+ "PrimaryProfileInformationExecutor:result"
+ "SharingProfileInformationExecutor:getLatestActivitySummary"
+ "SharingRelationshipLatestTransactionDatesInputSignal:fetchAndObserve"
```
