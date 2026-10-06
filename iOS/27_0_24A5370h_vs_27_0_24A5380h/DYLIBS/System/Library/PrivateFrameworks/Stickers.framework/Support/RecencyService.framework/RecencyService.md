## RecencyService

> `/System/Library/PrivateFrameworks/Stickers.framework/Support/RecencyService.framework/RecencyService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22d34` | `0x25374` | **`+0x2640`** |
| `__AUTH.__data` | `0x568` | `0x750` | **`+0x1e8`** |
| `__AUTH_CONST.__objc_const` | `0xab8` | `0xc80` | **`+0x1c8`** |
| `__TEXT.__const` | `0x24f8` | `0x2628` | **`+0x130`** |
| `__TEXT.__eh_frame` | `0x1368` | `0x1470` | **`+0x108`** |
| `__AUTH_CONST.__const` | `0xe48` | `0xf40` | **`+0xf8`** |
| `__TEXT.__oslogstring` | `0x32f` | `0x41f` | **`+0xf0`** |
| `__TEXT.__constg_swiftt` | `0x788` | `0x870` | **`+0xe8`** |
| `__TEXT.__swift5_fieldmd` | `0x904` | `0x9ec` | **`+0xe8`** |
| `__TEXT.__cstring` | `0x589` | `0x659` | **`+0xd0`** |
| `__TEXT.__swift5_reflstr` | `0x674` | `0x724` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x7ca` | `0x874` | **`+0xaa`** |
| `__DATA.__data` | `0x3e0` | `0x478` | **`+0x98`** |
| `__AUTH_CONST.__auth_got` | `0x6f8` | `0x788` | **`+0x90`** |
| `__DATA.__bss` | `0x1e00` | `0x1e80` | **`+0x80`** |
| `__AUTH.__objc_data` | `0x1e0` | `0x230` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xa58` | `0xa98` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x9c` | `0xd4` | **`+0x38`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x58` | `0x68` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0xc30` | `0xc40` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xa4` | `0xb4` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xf8` | `0x108` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x88` | `0x90` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x200` | `0x204` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x64` | `0x68` | **`+0x4`** |

### Other Changes

```diff

-85.0.0.0.0
+87.0.0.0.0

+  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

-  Functions: 807
-  Symbols:   403
-  CStrings:  48
+  Functions: 851
+  Symbols:   435
+  CStrings:  58
Symbols:
+ _CFPreferencesAppSynchronize
+ _CFPreferencesSetAppValue
+ __DATA__TtC14RecencyService26RecencyGenerationPublisher
+ __DATA__TtCV14RecencyService17ActivityDebouncerP33_0530339A9596E209C808FEE3EDAF792214DebouncerActor
+ __IVARS__TtC14RecencyService26RecencyGenerationPublisher
+ __IVARS__TtCV14RecencyService17ActivityDebouncerP33_0530339A9596E209C808FEE3EDAF792214DebouncerActor
+ __METACLASS_DATA__TtC14RecencyService26RecencyGenerationPublisher
+ __METACLASS_DATA__TtCV14RecencyService17ActivityDebouncerP33_0530339A9596E209C808FEE3EDAF792214DebouncerActor
+ ___swift_memcpy4_4
+ _objc_release_x28
+ _objc_retain_x19
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_deletedAsyncMethodErrorTu
+ _swift_getForeignTypeMetadata
+ _swift_release_n
+ _swift_release_x28
+ _swift_retain_x26
+ _swift_retain_x27
+ _symbolic Si
+ _symbolic SiSaySSGIeghyg_
+ _symbolic _____ 14RecencyService0A19GenerationPublisherC
+ _symbolic _____ 14RecencyService17ActivityDebouncerV
+ _symbolic _____ 14RecencyService17ActivityDebouncerV0D5Actor33_0530339A9596E209C808FEE3EDAF7922LLC
+ _symbolic _____ So16os_unfair_lock_sV
+ _symbolic _____ s6UInt32V
+ _symbolic _____ySSG s23_ContiguousArrayStorageC
+ _symbolic _____ySi10generation_SaySSG9orderKeystG 2os21OSAllocatedUnfairLockV
+ _symbolic _____ySi10generation_SaySSG9orderKeyst_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _symbolic ySi_SaySSGtYbc
+ _symbolic yyYaYbc
+ _type_layout_string So16os_unfair_lock_sV
CStrings:
+ "Debounce task did execute"
+ "Debounce task will execute"
+ "Debounce timer fired"
+ "Recents generation write: generation=%ld orderCount=%ld set=%lluus synchronize=%lluus"
+ "Sending activity signal. Restarting timer."
+ "com.apple.EmojiPreferences"
+ "com.apple.stickers.recency.generation"
+ "com.apple.stickers.recency.order"
+ "com.apple.stickersd.stickersDebouncerQueue"
+ "recency-generation-publisher"
```
