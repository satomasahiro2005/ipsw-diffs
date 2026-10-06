## geocorrectiond

> `/System/Library/PrivateFrameworks/MapsSupport.framework/geocorrectiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe014` | `0xe7d4` | **`+0x7c0`** |
| `__DATA_CONST.__const` | `0x1570` | `0x1688` | **`+0x118`** |
| `__TEXT.__objc_stubs` | `0x2d00` | `0x2d80` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x344a` | `0x34b4` | **`+0x6a`** |
| `__TEXT.__cstring` | `0xfd4` | `0x101b` | **`+0x47`** |
| `__DATA_CONST.__cfstring` | `0xe20` | `0xe60` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xd34` | `0xd74` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x460` | `0x498` | **`+0x38`** |
| `__TEXT.__oslogstring` | `0x1458` | `0x1486` | **`+0x2e`** |
| `__DATA.__objc_const` | `0x1b30` | `0x1b50` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xdf8` | `0xe18` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x7d0` | `0x7f0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x3f8` | `0x408` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x220` | `0x230` | **`+0x10`** |
| `__DATA.__bss` | `0xc8` | `0xd0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1e8` | `0x1f0` | **`+0x8`** |
| `__TEXT.__const` | `0x138` | `0x140` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x13c` | `0x140` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-2966.30.5.15.8
+2970.30.6.5.7

-  Functions: 323
-  Symbols:   199
-  CStrings:  959
+  Functions: 339
+  Symbols:   202
+  CStrings:  968
Symbols:
+ _GEO_DISPATCH_TIME_FOREVER
+ _dispatch_source_cancel
+ _geo_dispatch_timer_create_on_queue
+ _xpc_transaction_exit_clean
- _objc_retain_x25
CStrings:
+ "@\"NSNumber\"16@?0@\"NSNumber\"8"
+ "MCPOIBusynessProcessor timer fired, giving up"
+ "POIBusynessLocationTimer"
+ "_cancelTimerOnQueue"
+ "_checkIsFinishedOnQueue"
+ "_finishedOnQueue"
+ "_isWaitingForLocation"
+ "_isWaitingForVisit"
+ "_timer"
+ "_timerFiredOnQueue"
+ "geocorrectiond"
+ "shutdown"
- "_isWaiting"
- "_waitGroup"
- "finished"
```
