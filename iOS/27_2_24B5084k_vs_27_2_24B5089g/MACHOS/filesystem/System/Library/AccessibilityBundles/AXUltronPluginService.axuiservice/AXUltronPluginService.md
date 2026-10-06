## AXUltronPluginService

> `/System/Library/AccessibilityBundles/AXUltronPluginService.axuiservice/AXUltronPluginService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43e8` | `0x4850` | **`+0x468`** |
| `__TEXT.__objc_methname` | `0x106e` | `0x11bf` | **`+0x151`** |
| `__DATA.__objc_const` | `0x568` | `0x5e8` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x769` | `0x7e1` | **`+0x78`** |
| `__TEXT.__gcc_except_tab` | `0x144` | `0x1a8` | **`+0x64`** |
| `__TEXT.__objc_stubs` | `0xba0` | `0xc00` | **`+0x60`** |
| `__DATA_CONST.__cfstring` | `0x120` | `0x160` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x404` | `0x441` | **`+0x3d`** |
| `__DATA.__objc_selrefs` | `0x480` | `0x4b8` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x4fc` | `0x52c` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x630` | `0x650` | **`+0x20`** |
| `__TEXT.__cstring` | `0xef` | `0x10a` | **`+0x1b`** |
| `__DATA_CONST.__auth_got` | `0x328` | `0x338` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x24` | `0x30` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x130` | `0x138` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1b8` | `0x1c0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3245.7.1.0.0
+3245.8.2.0.0

-  Functions: 108
-  Symbols:   161
-  CStrings:  275
+  Functions: 112
+  Symbols:   164
+  CStrings:  292
Symbols:
+ _OBJC_CLASS_$_NSMutableSet
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
CStrings:
+ "(unchanged)"
+ "@\"NSMutableSet\""
+ "T@\"NSMutableDictionary\",&,N,V_watchCanDetectState"
+ "T@\"NSMutableSet\",&,N,V_syncedCompanionNRIdentifiers"
+ "UPDATING watch state for device %@: onWrist=%@, canDetect=%@"
+ "Watch SR: nearby on-wrist watch cannot currently detect (Low Power Mode / Water Lock) — iPhone taking over"
+ "_syncedCompanionNRIdentifiers"
+ "_watchCanDetectState"
+ "_watchStateLock"
+ "containsObject:"
+ "invalidateCompanionSyncSnapshot"
+ "set"
+ "setSyncedCompanionNRIdentifiers:"
+ "setWatchCanDetectState:"
+ "syncedCompanionNRIdentifiers"
+ "watchCanDetect"
+ "watchCanDetectState"
+ "{os_unfair_lock_s=\"_os_unfair_lock_opaque\"I}"
- "UPDATING: _watchActiveWristState: %@, deviceID:%@"
```
