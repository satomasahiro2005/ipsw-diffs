## CoreSuggestions

> `/System/Library/PrivateFrameworks/CoreSuggestions.framework/CoreSuggestions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8ec08` | `0x8e6e4` | **`-0x524`** |
| `__TEXT.__oslogstring` | `0x27fc` | `0x2776` | **`-0x86`** |
| `__TEXT.__cstring` | `0x7dd1` | `0x7d7c` | **`-0x55`** |
| `__AUTH_CONST.__cfstring` | `0xa7e0` | `0xa7a0` | **`-0x40`** |
| `__AUTH_CONST.__auth_got` | `0x730` | `0x710` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x750` | `0x730` | **`-0x20`** |
| `__TEXT.__const` | `0x878` | `0x868` | **`-0x10`** |

### Other Changes

```diff

-1352.0.1.0.0
+1354.0.0.0.0

-  Functions: 3441
-  Symbols:   6425
-  CStrings:  1664
+  Functions: 3439
+  Symbols:   6415
+  CStrings:  1656
Symbols:
+ GCC_except_table2305
+ GCC_except_table2331
+ GCC_except_table2333
+ GCC_except_table2369
+ GCC_except_table2424
+ GCC_except_table2825
+ GCC_except_table3329
+ GCC_except_table3346
+ GCC_except_table3353
+ GCC_except_table3367
- GCC_except_table2308
- GCC_except_table2334
- GCC_except_table2336
- GCC_except_table2372
- GCC_except_table2427
- GCC_except_table2828
- GCC_except_table3332
- GCC_except_table3349
- GCC_except_table3356
- GCC_except_table3370
- _CFBundleGetIdentifier
- _SGAllowedByAppExclusions
- _TCCAccessCopyBundleIdentifiersDisabledForService
- _TCCAccessCopyInformation
- _TCCAccessSetForBundleId
- _appExclusionsSetCanLearnFromApp
- _kTCCInfoBundle
- _kTCCInfoGranted
- _kTCCServiceSiri
- _kTCCServiceSiriAccess
CStrings:
- "'Learn from this app' was on: %@"
- "'Use with Siri' was on: %@"
- "AppExclusions"
- "IntelligenceFlow"
- "Reenabling 'Learn from this app' for %@"
- "Reenabling 'Use with Siri' for %@"
- "SiriCanLearnFromAppBlacklist"
- "SiriPerAppSiriPriorValue"
```
