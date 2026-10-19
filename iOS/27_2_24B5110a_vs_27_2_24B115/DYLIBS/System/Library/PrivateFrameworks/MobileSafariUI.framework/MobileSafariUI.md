## MobileSafariUI

> `/System/Library/PrivateFrameworks/MobileSafariUI.framework/MobileSafariUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3204ec` | `0x32028c` | **`-0x260`** |
| `__TEXT.__gcc_except_tab` | `0x1f7e4` | `0x1f764` | **`-0x80`** |
| `__DATA_CONST.__const` | `0x9ae0` | `0x9a90` | **`-0x50`** |
| `__TEXT.__cstring` | `0x117c4` | `0x11794` | **`-0x30`** |
| `__AUTH_CONST.__cfstring` | `0xddc0` | `0xdda0` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0x33ae0` | `0x33ac0` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x189e0` | `0x189d8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x11598` | `0x115a0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x20f4` | `0x20f0` | **`-0x4`** |

### Other Changes

```diff

-625.2.8.10.4
+625.2.8.10.6

-  Functions: 17659
+  Functions: 17661

-  CStrings:  3389
+  CStrings:  3388
Symbols:
+ GCC_except_table354
+ GCC_except_table385
+ ___43-[URLCompletionProvider _historyDidChange:]_block_invoke
+ ___45-[StartPageController _resumeBrowsingSection]_block_invoke_10
+ ___45-[URLCompletionProvider _bookmarksDidChange:]_block_invoke
+ ___75+[TabMenuProvider menuForClusterWithID:title:tabCount:location:dataSource:]_block_invoke_9
+ ___block_descriptor_64_ea8_32s40s48s56r_e5_v8?0ls32l8s40l8r56l8s48l8
- GCC_except_table530
- _OBJC_IVAR_$_URLCompletionProvider._cfCompletionQueue
- ___44-[URLCompletionProvider setQueryToComplete:]_block_invoke_2
- ___78-[TabController _updateContextKitSuggestionsForTabGroupWithCompletionHandler:]_block_invoke_4
- ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s56l8s48l8
- ___block_descriptor_72_ea8_32s40s48s56s64r_e5_v8?0lr64l8s32l8s40l8s48l8s56l8
- ___block_descriptor_81_ea8_32s40s48s56r64r_e5_v8?0ls32l8s40l8r56l8s48l8r64l8
CStrings:
- "com.apple.mobilesafari.URLCompletionProvider.cf.%p"
```
