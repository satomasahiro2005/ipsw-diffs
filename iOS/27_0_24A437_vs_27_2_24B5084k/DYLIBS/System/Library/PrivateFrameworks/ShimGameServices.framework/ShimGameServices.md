## ShimGameServices

> `/System/Library/PrivateFrameworks/ShimGameServices.framework/ShimGameServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x381f8` | `0x3b1bc` | **`+0x2fc4`** |
| `__TEXT.__eh_frame` | `0x3b40` | `0x3f68` | **`+0x428`** |
| `__TEXT.__unwind_info` | `0x11b8` | `0x12b8` | **`+0x100`** |
| `__TEXT.__swift5_typeref` | `0xbec` | `0xccc` | **`+0xe0`** |
| `__AUTH_CONST.__const` | `0xd70` | `0xe10` | **`+0xa0`** |
| `__TEXT.__const` | `0x15c0` | `0x1640` | **`+0x80`** |
| `__DATA.__data` | `0x8d0` | `0x930` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x104` | `0x164` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x8f8` | `0x948` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x398` | `0x3e4` | **`+0x4c`** |
| `__TEXT.__cstring` | `0x70a` | `0x74a` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x148` | `0x188` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x298` | `0x2cc` | **`+0x34`** |
| `__DATA_CONST.__objc_selrefs` | `0x980` | `0x998` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x270` | `0x288` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x2a8` | `0x298` | **`-0x10`** |

### Other Changes

```diff

-821.0.25.0.0
+821.1.8.0.0

-  Functions: 1395
-  Symbols:   653
-  CStrings:  47
+  Functions: 1466
+  Symbols:   666
+  CStrings:  50
Symbols:
+ ___swift_closure_destructor.33Tm
+ _swift_retain_x8
+ _swift_task_create
+ _symbolic SS_So21GKAchievementInternalCt
+ _symbolic ScA_pSg
+ _symbolic ScPSg
+ _symbolic Scgyyt______pG s5ErrorP
+ _symbolic So16GKPlayerInternalC
+ _symbolic _____3key_yp5valuet s11AnyHashableV
+ _symbolic _____yS2SG s18_DictionaryStorageC
+ _symbolic _____ySSSo21GKAchievementInternalCG s18_DictionaryStorageC
+ _symbolic _____ySS_So21GKAchievementInternalCtG s23_ContiguousArrayStorageC
+ _symbolic _____y______pG______pIeghHnzo_ 12GameServices3RefV AA0A0P s5ErrorP
+ _symbolic _____y_____y______pGSDySSSo21GKAchievementInternalCGG s17_NativeDictionaryV 12GameServices3RefV AC0C0P
- _symbolic _____y_____y______pGSaySo21GKAchievementInternalCGG s17_NativeDictionaryV 12GameServices3RefV AC0C0P
CStrings:
+ "Failed to create an achievement image ref: %@"
+ "Failed to refresh achievements for %s: %@"
+ "This achievement operation requires a local player"
```
