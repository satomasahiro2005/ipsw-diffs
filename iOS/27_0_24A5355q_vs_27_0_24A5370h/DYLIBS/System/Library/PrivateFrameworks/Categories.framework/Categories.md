## Categories

> `/System/Library/PrivateFrameworks/Categories.framework/Categories`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xadd0` | `0xb34c` | **`+0x57c`** |
| `__TEXT.__cstring` | `0x2cd2` | `0x2d54` | **`+0x82`** |
| `__AUTH_CONST.__cfstring` | `0x3660` | `0x36e0` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x5ff` | `0x676` | **`+0x77`** |
| `__TEXT.__objc_methlist` | `0x794` | `0x7c4` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x6a8` | `0x6c8` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x978` | `0x990` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0xa88` | `0xaa0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x378` | `0x388` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x428` | `0x41c` | **`-0xc`** |

### Other Changes

```diff

-53.1.0.0.0
+56.0.0.0.0

-  Functions: 205
-  Symbols:   506
-  CStrings:  498
+  Functions: 211
+  Symbols:   512
+  CStrings:  503
Symbols:
+ +[CTCategory _canonicalBundleIDFor:]
+ +[CTCategory categoryForBundleID:platform:version:withCompletionHandler:]
+ +[CTCategory categoryForBundleID:version:withCompletionHandler:]
+ +[CTCategory categoryForBundleIdentifiers:platform:version:withCompletionHandler:]
+ GCC_except_table28
+ GCC_except_table43
+ GCC_except_table48
+ GCC_except_table49
+ GCC_except_table61
+ GCC_except_table73
+ GCC_except_table90
+ ___73+[CTCategory categoryForBundleID:platform:version:withCompletionHandler:]_block_invoke
+ ___82+[CTCategory categoryForBundleIdentifiers:platform:version:withCompletionHandler:]_block_invoke
+ ___82+[CTCategory categoryForBundleIdentifiers:platform:version:withCompletionHandler:]_block_invoke_2
+ ___82+[CTCategory categoryForBundleIdentifiers:platform:version:withCompletionHandler:]_block_invoke_3
+ ___block_descriptor_56_e8_32bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8
+ __os_log_fault_impl
+ _objc_retain_x10
- GCC_except_table25
- GCC_except_table26
- GCC_except_table44
- GCC_except_table45
- GCC_except_table57
- GCC_except_table68
- GCC_except_table85
- ___74+[CTCategory categoryForBundleIdentifiers:platform:withCompletionHandler:]_block_invoke
- ___74+[CTCategory categoryForBundleIdentifiers:platform:withCompletionHandler:]_block_invoke_2
- ___74+[CTCategory categoryForBundleIdentifiers:platform:withCompletionHandler:]_block_invoke_3
- ___block_descriptor_48_e8_32bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8
- _objc_retain_x9
CStrings:
+ "CTCategory _canonicalBundleIDFor: equivalence row for %{public}@ has no ios:// entry; fix _equivalentBundleIDsMapping."
+ "com.apple.controlcenter"
+ "com.apple.internal.ScreenTimeSettingsShield"
+ "ios://com.roblox.robloxmobile"
+ "macos://com.roblox.RobloxPlayer"
```
