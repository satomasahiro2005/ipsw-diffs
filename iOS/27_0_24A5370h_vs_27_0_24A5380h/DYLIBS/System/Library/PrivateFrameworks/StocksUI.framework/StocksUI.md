## StocksUI

> `/System/Library/PrivateFrameworks/StocksUI.framework/StocksUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3eb1fc` | `0x3ed8dc` | **`+0x26e0`** |
| `__DATA.__bss` | `0x11140` | `0x10a40` | **`-0x700`** |
| `__DATA_DIRTY.__bss` | `0x1c110` | `0x1c810` | **`+0x700`** |
| `__DATA_DIRTY.__data` | `0x1d7b8` | `0x1d988` | **`+0x1d0`** |
| `__AUTH.__objc_data` | `0x2e00` | `0x2d00` | **`-0x100`** |
| `__DATA.__data` | `0x5260` | `0x5160` | **`-0x100`** |
| `__DATA_DIRTY.__objc_data` | `0x4160` | `0x4260` | **`+0x100`** |
| `__AUTH.__data` | `0x3020` | `0x2f50` | **`-0xd0`** |
| `__TEXT.__unwind_info` | `0xaf48` | `0xaf70` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x22be8` | `0x22c00` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x7ac0` | `0x7ad0` | **`+0x10`** |
| `__DATA.__common` | `0x420` | `0x410` | **`-0x10`** |
| `__DATA_DIRTY.__common` | `0x560` | `0x570` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x4d7c` | `0x4d8c` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x100b8` | `0x100c4` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x3260` | `0x3268` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`
- `__TEXT.__oslogstring`

### Other Changes

```diff

-2018.0.0.0.0
+2020.0.0.0.0

+  - /System/Library/PrivateFrameworks/AppUserEvents.framework/AppUserEvents

-  - /System/Library/PrivateFrameworks/NewsUserEvents.framework/NewsUserEvents

-  Functions: 15771
-  Symbols:   6593
+  Functions: 15781
+  Symbols:   6592
Symbols:
+ _symbolic _____y_____G 13AppUserEvents0B12EventHistoryC 21StocksPersonalization010Com_Apple_f1_g8_SessionD0V
+ _symbolic _____y_____G 13AppUserEvents15DebugInspectionV 21StocksPersonalization010Com_Apple_f1_G8_SessionV
- _swift_willThrowTypedImpl
- _symbolic _____y_____G 14NewsUserEvents0B12EventHistoryC 21StocksPersonalization010Com_Apple_f1_g8_SessionD0V
- _symbolic _____y_____G 14NewsUserEvents15DebugInspectionV 21StocksPersonalization010Com_Apple_f1_G8_SessionV
CStrings:
+ "Can’t Access Calendar"
+ "Hiding all cards due to presenting search controller"
- "Can't Access Calendar"
- "Hiding ForYou card due to presenting search controller"
```
