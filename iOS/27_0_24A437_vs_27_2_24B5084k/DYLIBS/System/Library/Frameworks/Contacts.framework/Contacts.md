## Contacts

> `/System/Library/Frameworks/Contacts.framework/Contacts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2216f8` | `0x221d9c` | **`+0x6a4`** |
| `__TEXT.__oslogstring` | `0xf75a` | `0xf83a` | **`+0xe0`** |
| `__TEXT.__dlopen_cstrs` | `0x91e` | `0x97e` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x9211` | `0x9251` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x66f0` | `0x6728` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x1be70` | `0x1be98` | **`+0x28`** |
| `__DATA.__bss` | `0x6090` | `0x60b0` | **`+0x20`** |
| `__TEXT.__cstring` | `0xcc19` | `0xcc39` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x9d70` | `0x9d88` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x9248` | `0x9260` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x3c2c` | `0x3c3c` | **`+0x10`** |

### Other Changes

```diff

-3844.100.1.0.0
+3846.200.41.0.0

-  Functions: 14232
-  Symbols:   20167
-  CStrings:  3452
+  Functions: 14240
+  Symbols:   20175
+  CStrings:  3456
Symbols:
+ +[CNSharedProfileStateOracle shouldHideSharedProfileMenuInContacts]
+ +[_ExistingItemUpdater isRenderablePosterData:watchPosterImageData:]
+ -[_ExistingItemUpdater insertPoster:shouldBeCurrent:]
+ -[_ExistingItemUpdater updateExistingPostersWithPoster:shouldBeCurrent:]
+ _CNPosterDataPropertyDescriptionLog.cn_once_object_0
+ _CNPosterDataPropertyDescriptionLog.cn_once_token_0
+ __OBJC_$_CLASS_METHODS__ExistingItemUpdater
+ ___36-[_ExistingItemUpdater visitPoster:]_block_invoke_2
+ ___CNPosterDataPropertyDescriptionLog_block_invoke
+ ___block_descriptor_32_e38_B16?0"CNContactPosterManagedObject"8l
- -[_ExistingItemUpdater insertPoster:]
- -[_ExistingItemUpdater updateExistingPostersWithPoster:]
CStrings:
+ "Ignoring wallpaper with empty posterArchiveData for contact identifier: %{public}@ (metadata: %{public}s, sharedToMe: %{public}s, sensitive: %{public}s)"
+ "Not saving poster/image for contact identifier: %{public}@, error: %@"
+ "kMDItemRole ==\"*\" && _kMDItemIsZombie != 1"
+ "no"
+ "yes"
- "kMDItemRole ==\"*\""
```
