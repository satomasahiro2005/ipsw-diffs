## MMCSServices

> `/System/Library/PrivateFrameworks/MMCSServices.framework/MMCSServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x85e8` | `0x88e0` | **`+0x2f8`** |
| `__AUTH_CONST.__objc_const` | `0xa50` | `0xab0` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x126a` | `0x12c2` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x548` | `0x578` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x3b8` | `0x3e0` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x568` | `0x578` | **`+0x10`** |
| `__TEXT.__cstring` | `0x281` | `0x28f` | **`+0xe`** |
| `__DATA.__objc_ivar` | `0x98` | `0xa0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xa14` | `0xa1c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x390` | `0x398` | **`+0x8`** |

### Other Changes

```diff

-1491.100.1.2.25
+1491.200.63.2.1

-  Functions: 154
-  Symbols:   151
-  CStrings:  138
+  Functions: 159
+  Symbols:   159
+  CStrings:  139
Symbols:
+ __dispatch_source_type_timer
+ _dispatch_activate
+ _dispatch_source_cancel
+ _dispatch_source_create
+ _dispatch_source_set_event_handler
+ _dispatch_source_set_timer
+ _dispatch_time
+ _kMMCSRequestOptionPriority
+ _objc_loadWeakRetained
+ _objc_release
- _OBJC_CLASS_$_NSTimer
- _objc_loadWeak
CStrings:
+ "Could not create power assertion timer, assertion will be held until transfers complete"
+ "[%@: guid: %@  item id: %qx  path: %@  fd: %d token: %@   requestor ID: %@  request url: %@ signature: %@  progress: %f file size: %llu priority: %ld]"
- "[%@: guid: %@  item id: %qx  path: %@  fd: %d token: %@   requestor ID: %@  request url: %@ signature: %@  progress: %f file size: %llu]"
```
