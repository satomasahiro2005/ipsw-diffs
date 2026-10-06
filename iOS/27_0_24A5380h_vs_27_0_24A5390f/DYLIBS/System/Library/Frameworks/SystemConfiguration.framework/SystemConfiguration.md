## SystemConfiguration

> `/System/Library/Frameworks/SystemConfiguration.framework/SystemConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x79760` | `0x7981c` | **`+0xbc`** |
| `__AUTH_CONST.__auth_got` | `0xf88` | `0xf90` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xd20` | `0xd28` | **`+0x8`** |

### Other Changes

```diff

-1441.0.0.0.0
+1444.0.0.0.0

-  Functions: 1309
-  Symbols:   2370
+  Functions: 1310
+  Symbols:   2372
Symbols:
+ ___SCNetworkReachabilityPathUsesCellular
+ _nw_interface_copy_delegate_interface
Functions:
~ ___SCNetworkReachabilityGetFlagsFromPath : 1316 -> 1304
+ ___SCNetworkReachabilityPathUsesCellular
```
