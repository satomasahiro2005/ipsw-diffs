## MarketplaceKit

> `/System/Library/Frameworks/MarketplaceKit.framework/MarketplaceKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9f7b8` | `0x9f880` | **`+0xc8`** |
| `__TEXT.__cstring` | `0x1bf4` | `0x1c94` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0xab48` | `0xabd8` | **`+0x90`** |
| `__TEXT.__const` | `0x142e4` | `0x14314` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x3138` | `0x3154` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0xb58` | `0xb68` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x3ea4` | `0x3eb4` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x35d0` | `0x35d8` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x3c30` | `0x3c36` | **`+0x6`** |
| `__TEXT.__swift5_types` | `0x534` | `0x538` | **`+0x4`** |

### Other Changes

```diff

-4.0.30.0.0
+4.0.33.0.0

+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 4945
-  Symbols:   1962
-  CStrings:  230
+  Functions: 4950
+  Symbols:   1965
+  CStrings:  232
Symbols:
+ _MobileGestalt_get_current_device
+ _MobileGestalt_get_isVirtualDevice
+ _symbolic _____ 14MarketplaceKit30VirtualMachineUnsupportedAlertO
CStrings:
+ "Alternative distribution is not supported in VMs.\n\nPlease use a physical device.\n\n[Internal Only]"
+ "Can't Install in a Virtual Machine"
```
