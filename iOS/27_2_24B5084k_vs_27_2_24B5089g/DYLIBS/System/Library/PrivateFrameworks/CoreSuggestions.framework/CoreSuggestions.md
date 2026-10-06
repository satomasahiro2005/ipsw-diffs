## CoreSuggestions

> `/System/Library/PrivateFrameworks/CoreSuggestions.framework/CoreSuggestions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x1210` | `0x10` | **`-0x1200`** |
| `__DATA_DIRTY.__data` | `0x100` | `0x1300` | **`+0x1200`** |
| `__TEXT.__text` | `0x8e538` | `0x8ec08` | **`+0x6d0`** |
| `__AUTH.__objc_data` | `0x1e0` | `—` | **`-0x1e0`** |
| `__DATA_DIRTY.__objc_data` | `0x2ee0` | `0x30c0` | **`+0x1e0`** |
| `__TEXT.__oslogstring` | `0x273d` | `0x27fc` | **`+0xbf`** |
| `__AUTH_CONST.__cfstring` | `0xa7a0` | `0xa7e0` | **`+0x40`** |
| `__TEXT.__const` | `0x858` | `0x878` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x720` | `0x730` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2240` | `0x2250` | **`+0x10`** |

### Other Changes

```diff

-1351.0.0.0.0
+1352.0.1.0.0

-  Functions: 3433
-  Symbols:   6415
-  CStrings:  1661
+  Functions: 3441
+  Symbols:   6425
+  CStrings:  1664
Symbols:
+ GCC_except_table2308
+ GCC_except_table2334
+ GCC_except_table2336
+ GCC_except_table2372
+ GCC_except_table2427
+ GCC_except_table2828
+ GCC_except_table3332
+ GCC_except_table3349
+ GCC_except_table3356
+ GCC_except_table3370
+ _CFPreferencesAppSynchronize
+ _CFPreferencesAppValueIsForced
+ _SGAppCanBeSuggested
+ _SGAppSuggestionsShowOnHomeScreen
+ _SGAppSuggestionsShowOnLockScreen
+ _SGMigrateSiriSettings
+ _SGSetAppCanBeSuggested
+ _SGSetAppSuggestionsShowOnHomeScreen
+ _SGSetAppSuggestionsShowOnLockScreen
+ _SGTransfer
- GCC_except_table2300
- GCC_except_table2326
- GCC_except_table2328
- GCC_except_table2364
- GCC_except_table2419
- GCC_except_table2820
- GCC_except_table3324
- GCC_except_table3341
- GCC_except_table3348
- GCC_except_table3362
CStrings:
+ "App replacement: migrated Siri settings (changed:%{public}d)"
+ "App replacement: not migrating managed %{public}@"
+ "App replacement: refusing to migrate Siri settings for %{public}@ -> %{public}@"
```
