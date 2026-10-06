## CoreRepairCoreXPCService

> `/System/Library/PrivateFrameworks/CoreRepairCore.framework/XPCServices/CoreRepairCoreXPCService.xpc/CoreRepairCoreXPCService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x404` | `0x72c` | **`+0x328`** |
| `__TEXT.__objc_methname` | `0x264` | `0x334` | **`+0xd0`** |
| `__TEXT.__objc_stubs` | `0x160` | `0x220` | **`+0xc0`** |
| `__TEXT.__objc_methtype` | `0x157` | `0x1c3` | **`+0x6c`** |
| `__DATA.__objc_selrefs` | `0x110` | `0x150` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x160` | `0x1a0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x174` | `0x1a4` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x58` | `0x84` | **`+0x2c`** |
| `__DATA_CONST.__auth_got` | `0xb8` | `0xd8` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x20` | `0x40` | **`+0x20`** |
| `__DATA.__objc_const` | `0x2b0` | `0x2c0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x28` | `0x38` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x70` | `0x78` | **`+0x8`** |
| `__TEXT.__cstring` | `0x63` | `0x6a` | **`+0x7`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-1291.0.0.502.1
+1307.0.16.0.0

-  Functions: 5
-  Symbols:   41
-  CStrings:  69
+  Functions: 7
+  Symbols:   47
+  CStrings:  83
Symbols:
+ _OBJC_CLASS_$_CRRepairStateSnapshot
+ _OBJC_CLASS_$_NSMutableDictionary
+ _objc_release_x23
+ _objc_release_x24
+ _objc_release_x25
+ _objc_retain_x21
CStrings:
+ "GetRepairDate"
+ "IsHardwareChangedFromOldState"
+ "UseXPC"
+ "dictionary"
+ "getRepairDate:"
+ "getRepairDate:withReply:"
+ "isHardwareChangedFromOldState:newState:options:error:"
+ "isHardwareChangedFromOldState:options:withReply:"
+ "mutableCopy"
+ "removeObjectForKey:"
+ "timeIntervalSince1970"
+ "v28@0:8i16@?<v@?q>20"
+ "v40@0:8@\"NSString\"16@\"NSDictionary\"24@?<v@?B@\"NSString\"@\"NSError\">32"
+ "v40@0:8@16@24@?32"
```
