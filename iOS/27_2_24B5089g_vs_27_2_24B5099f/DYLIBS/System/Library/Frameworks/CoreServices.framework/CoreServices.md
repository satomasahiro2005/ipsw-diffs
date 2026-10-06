## CoreServices

> `/System/Library/Frameworks/CoreServices.framework/CoreServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ceae0` | `0x1cdd7c` | **`-0xd64`** |
| `__TEXT.__cstring` | `0x29633` | `0x2944b` | **`-0x1e8`** |
| `__TEXT.__gcc_except_tab` | `0x2a3dc` | `0x2a28c` | **`-0x150`** |
| `__TEXT.__unwind_info` | `0xc7f0` | `0xc790` | **`-0x60`** |
| `__AUTH.__objc_data` | `0x33b8` | `0x3368` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x75d8` | `0x7588` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x1928` | `0x1978` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x17d60` | `0x17d20` | **`-0x40`** |
| `__TEXT.__oslogstring` | `0x16d55` | `0x16d87` | **`+0x32`** |
| `__TEXT.__objc_methlist` | `0xe334` | `0xe304` | **`-0x30`** |
| `__DATA.__bss` | `0xf40` | `0xf18` | **`-0x28`** |
| `__DATA_DIRTY.__bss` | `0x948` | `0x970` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x15760` | `0x15750` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x6608` | `0x65f8` | **`-0x10`** |
| `__DATA.__data` | `0x15c4` | `0x15bc` | **`-0x8`** |

### Other Changes

```diff

-1517.1.9.0.0
+1517.1.11.0.0

-  Functions: 9619
-  Symbols:   14321
-  CStrings:  6119
+  Functions: 9609
+  Symbols:   14307
+  CStrings:  6114
Symbols:
- -[_LSDModifyClient registerExtensionPoint:platform:declaringURL:withInfo:completionHandler:]
- -[_LSDModifyClient unregisterExtensionPoint:platform:withVersion:parentBundleUnit:completionHandler:]
- GCC_except_table132
- __LSRegisterExtensionPointClient
- __LSUnregisterExtensionPoint
- __LSUnregisterExtensionPointClient
- ___101-[_LSDModifyClient unregisterExtensionPoint:platform:withVersion:parentBundleUnit:completionHandler:]_block_invoke
- ___92-[_LSDModifyClient registerExtensionPoint:platform:declaringURL:withInfo:completionHandler:]_block_invoke
- ____LSRegisterExtensionPointClient_block_invoke
- ____LSRegisterExtensionPointClient_block_invoke_2
- ____LSUnregisterExtensionPointClient_block_invoke
- ____LSUnregisterExtensionPointClient_block_invoke_2
- ___block_descriptor_64_ea8_32s40s48bs_e42_v24?0"LSDBExecutionContext"8"NSError"16ls32l8s40l8s48l8
- ___block_descriptor_68_ea8_32s40s48s56bs_e42_v24?0"LSDBExecutionContext"8"NSError"16ls32l8s40l8s48l8s56l8
CStrings:
+ "cannot register extension points from a LS client"
- "-[_LSDModifyClient registerExtensionPoint:platform:declaringURL:withInfo:completionHandler:]"
- "-[_LSDModifyClient registerExtensionPoint:platform:declaringURL:withInfo:completionHandler:]_block_invoke"
- "-[_LSDModifyClient unregisterExtensionPoint:platform:withVersion:parentBundleUnit:completionHandler:]"
- "-[_LSDModifyClient unregisterExtensionPoint:platform:withVersion:parentBundleUnit:completionHandler:]_block_invoke"
- "invalid extensionPoint SDK dictionary"
- "invalid extensionPoint identifier"
```
