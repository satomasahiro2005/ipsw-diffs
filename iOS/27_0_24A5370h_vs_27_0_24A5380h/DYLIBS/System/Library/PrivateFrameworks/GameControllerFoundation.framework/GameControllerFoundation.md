## GameControllerFoundation

> `/System/Library/PrivateFrameworks/GameControllerFoundation.framework/GameControllerFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f844` | `0x6fc24` | **`+0x3e0`** |
| `__AUTH.__objc_data` | `0x2850` | `0x2940` | **`+0xf0`** |
| `__DATA_DIRTY.__objc_data` | `0x410` | `0x320` | **`-0xf0`** |
| `__TEXT.__oslogstring` | `0x3275` | `0x32f7` | **`+0x82`** |
| `__TEXT.__objc_methlist` | `0x6b1c` | `0x6b84` | **`+0x68`** |
| `__DATA_CONST.__got` | `0x4d0` | `0x520` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x6f40` | `0x6f80` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x14988` | `0x149b8` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x1e08` | `0x1e30` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x20f8` | `0x2110` | **`+0x18`** |
| `__TEXT.__cstring` | `0x71a6` | `0x71ba` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0xa50` | `0xa58` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x33a4` | `0x33a0` | **`-0x4`** |

### Other Changes

```diff

-14.0.17.0.0
+14.0.19.0.0

-  Functions: 2952
-  Symbols:   5361
-  CStrings:  1332
+  Functions: 2957
+  Symbols:   5367
+  CStrings:  1336
Symbols:
+ +[GCIOService getService:matching:error:]
+ +[GCIOService getServices:matching:error:]
+ -[GCIOService waitQuiet:error:]
+ -[GCIOService waitQuietWithError:]
+ _IOServiceGetMatchingService
+ _modf
CStrings:
+ "<IOService> Error creating iterator for matching services: %{public}@"
+ "<IOService> Error finding matching services: %{mach.errno}d"
+ "GameControllerCategory"
+ "GameControllerSupport"
+ "dynamic"
- "GameControllerSupportedHIDDevice"
```
