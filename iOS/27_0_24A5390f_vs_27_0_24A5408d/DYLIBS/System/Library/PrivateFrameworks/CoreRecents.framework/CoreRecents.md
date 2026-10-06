## CoreRecents

> `/System/Library/PrivateFrameworks/CoreRecents.framework/CoreRecents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc5fc` | `0xc63c` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x7e8` | `0x827` | **`+0x3f`** |
| `__AUTH_CONST.__objc_const` | `0x1800` | `0x1830` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x6c8` | `0x6f0` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x11dc` | `0x11f4` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xb88` | `0xb98` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x150` | `0x15c` | **`+0xc`** |
| `__TEXT.__const` | `0xe8` | `0xf0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xa4` | `0xa8` | **`+0x4`** |

### Other Changes

```diff

-1233.100.1.0.0
+1234.100.1.0.0

-  Functions: 405
-  Symbols:   841
-  CStrings:  184
+  Functions: 407
+  Symbols:   849
+  CStrings:  185
Symbols:
+ -[CRRecentContactsLibraryRemoteAccess initWithConnection:searchTimeout:]
+ -[CRRecentContactsLibraryRemoteAccess searchTimeout]
+ GCC_except_table10
+ GCC_except_table13
+ GCC_except_table2
+ GCC_except_table7
+ _OBJC_IVAR_$_CRRecentContactsLibraryRemoteAccess._searchTimeout
+ ___block_descriptor_56_e8_32s40r48r_e29_v24?0"NSArray"8"NSError"16lr40l8r48l8s32l8
+ _dispatch_semaphore_create
+ _dispatch_semaphore_signal
+ _dispatch_semaphore_wait
+ _dispatch_time
- GCC_except_table1
- GCC_except_table12
- GCC_except_table6
- GCC_except_table9
Functions:
- ___59-[CRRecentContactsLibraryRemoteAccess executeSearch:error:]_block_invoke.6
~ -[CRRecentContactsLibraryRemoteAccess executeSearch:error:] : 580 -> 648
~ ___59-[CRRecentContactsLibraryRemoteAccess executeSearch:error:]_block_invoke : 124 -> 156
~ -[CRRecentContactsLibraryRemoteAccess initWithConnection:] : 124 -> 8
+ -[CRRecentContactsLibraryRemoteAccess initWithConnection:searchTimeout:]
+ -[CRRecentContactsLibraryRemoteAccess searchTimeout]
+ -[CRRecentContactsLibraryRemoteAccess executeSearch:error:].cold.1
CStrings:
+ "Timed out after %.1fs waiting for recentsd to service a search"
```
