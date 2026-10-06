## SetupAssistant

> `/System/Library/PrivateFrameworks/SetupAssistant.framework/SetupAssistant`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x5a0` | `0x10e0` | **`+0xb40`** |
| `__DATA_DIRTY.__objc_data` | `0xeb0` | `0x370` | **`-0xb40`** |
| `__TEXT.__cstring` | `0x34f5` | `0x349e` | **`-0x57`** |
| `__TEXT.__objc_methlist` | `0x41ec` | `0x419c` | **`-0x50`** |
| `__TEXT.__text` | `0x443fc` | `0x443c0` | **`-0x3c`** |
| `__AUTH_CONST.__objc_const` | `0x62a0` | `0x6288` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c88` | `0x2c70` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x1340` | `0x1358` | **`+0x18`** |

### Other Changes

```diff

-5405.0.0.0.0
+5407.0.0.0.0

-  Functions: 1798
-  Symbols:   3101
-  CStrings:  1139
+  Functions: 1795
+  Symbols:   3098
+  CStrings:  1135
Symbols:
- -[BuddyFeatureFlags isNewMandatorySUFlowEnabled]
- -[BuddyFeatureFlags isNewMigrationSUFlowEnabled]
- -[BuddyFeatureFlags isNewRestoreSUFlowEnabled]
CStrings:
- "NewBuddyMandatorySUFlow"
- "NewBuddyMigrationSUFlow"
- "NewBuddyRestoreSUFlow"
- "SoftwareUpdateUI"
```
