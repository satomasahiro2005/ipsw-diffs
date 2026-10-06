## CoreServices

> `/System/Library/Frameworks/CoreServices.framework/CoreServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c6f38` | `0x1c7980` | **`+0xa48`** |
| `__TEXT.__oslogstring` | `0x1650f` | `0x1667b` | **`+0x16c`** |
| `__TEXT.__gcc_except_tab` | `0x2955c` | `0x29618` | **`+0xbc`** |
| `__DATA_CONST.__const` | `0x7418` | `0x7478` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0xc5d0` | `0xc628` | **`+0x58`** |
| `__TEXT.__cstring` | `0x28cce` | `0x28c7d` | **`-0x51`** |
| `__TEXT.__objc_methlist` | `0xe1d4` | `0xe1fc` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x17a00` | `0x17a20` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x3b90` | `0x3bb0` | **`+0x20`** |
| `__DATA.__bss` | `0xf30` | `0xf40` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x156e0` | `0x156e8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x6540` | `0x6548` | **`+0x8`** |

### Other Changes

```diff

-1512.0.0.0.0
+1517.0.1.0.0

-  Functions: 9533
-  Symbols:   14229
-  CStrings:  6034
+  Functions: 9545
+  Symbols:   14243
+  CStrings:  6048
Symbols:
+ -[FSMimic bundleInfoDictionaryWithError:]
+ -[FSMimicPopulator populateBundleInfoDictionaryWithError:]
+ __LSBundleCopyNodeWithCheckStyle
+ __ZL19_LSBundleCreateNodeP11_LSDatabasej24LSBundleCheckUpdateStylePbPU15__autoreleasingP7NSError
+ __ZL24_LSBundleCopyOrCheckNodeP11_LSDatabasejj24LSBundleCheckUpdateStylePU8__strongP6FSNode
+ __ZL25_LSBundleApplyCheckUpdate24LSBundleCheckUpdateStylePKcU13block_pointerFvP9LSContextE
+ __ZZL31_LSBundleCheckUpdateClientQueuevE5queue
+ __ZZL31_LSBundleCheckUpdateClientQueuevE9onceToken
+ ____ZL24_LSBundleCopyOrCheckNodeP11_LSDatabasejj24LSBundleCheckUpdateStylePU8__strongP6FSNode_block_invoke
+ ____ZL25_LSBundleApplyCheckUpdate24LSBundleCheckUpdateStylePKcU13block_pointerFvP9LSContextE_block_invoke
+ ____ZL31_LSBundleCheckUpdateClientQueuev_block_invoke
+ ____ZN14LaunchServices10ContainersL7displayEP9LSContextjjP29CSStoreAttributedStringWriter_block_invoke
+ ___block_descriptor_40_ea8_32s_e21_v16?0^{LSContext=}8ls32l8
+ ___block_descriptor_48_ea8_32bs_e9_v16?0r*8ls32l8
+ __kLSURLIsHiddenBySystemChangedNotificationsKey
+ __kLSURLIsHiddenBySystemKey
- __ZL19_LSBundleCreateNodeP11_LSDatabasejbPbPU15__autoreleasingP7NSError
- __ZL24_LSBundleCopyOrCheckNodeP11_LSDatabasejjhPU8__strongP6FSNode
CStrings:
+ "%{public}s: finished %{public}s database update (%{public}s)"
+ "%{public}s: performing synchronous (client) database update (%{public}s)"
+ "%{public}s: performing synchronous (server) database update (%{public}s)"
+ "%{public}s: scheduling asynchronous (client) database update (%{public}s)"
+ "%{public}s: scheduling asynchronous (server) database update (%{public}s)"
+ "-[FSMimic bundleInfoDictionaryWithError:]"
+ "Failed to get keys remotely, but keeping original error. Remote error info: %@ %ld"
+ "InstallBuildVersion"
+ "OriginalInstallDate"
+ "_LSBundleApplyCheckUpdate"
+ "_LSBundleCopyOrCheckNode_block_invoke"
+ "asynchronous (client)"
+ "asynchronous (server)"
+ "bundleInfoDictionary"
+ "com.apple.LaunchServices.bundle-check-update"
+ "registering changed bundle"
+ "synchronous (client)"
+ "synchronous (server)"
+ "v16@?0r*8"
- "+[_LSDisplayNameConstructor(ConstructForAnyFile) displayNameConstructorWithContextIfNeeded:bundle:bundleClass:node:preferredLocalizations:error:]"
- "+[_LSDisplayNameConstructor(ConstructForAnyFile) displayNameConstructorsWithContextIfNeeded:bundle:bundleClass:node:error:]"
- "Failed to get keys remotely, but keeping original error. Remote error: %@"
- "node had unregistered bundle type but can't issue IO to localize its name"
- "node had unregistered personality but cannot do IO to localize its name"
```
