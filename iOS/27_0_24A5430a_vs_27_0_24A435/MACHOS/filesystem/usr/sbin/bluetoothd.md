## bluetoothd

> `/usr/sbin/bluetoothd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x902ef8` | `0x903c40` | **`+0xd48`** |
| `__TEXT.__objc_stubs` | `0x19a20` | `0x19ba0` | **`+0x180`** |
| `__TEXT.__cstring` | `0xc7e2b` | `0xc7f46` | **`+0x11b`** |
| `__DATA_CONST.__const` | `0x34228` | `0x34330` | **`+0x108`** |
| `__TEXT.__oslogstring` | `0xc0b4f` | `0xc0c3a` | **`+0xeb`** |
| `__TEXT.__objc_methname` | `0x1f4bf` | `0x1f59b` | **`+0xdc`** |
| `__TEXT.__gcc_except_tab` | `0x70968` | `0x70a0c` | **`+0xa4`** |
| `__TEXT.__const` | `0x25e00` | `0x25e90` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x26218` | `0x26278` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x76f0` | `0x7740` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x27840` | `0x27880` | **`+0x40`** |
| `__DATA_CONST.__got` | `0xe40` | `0xe50` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 37351
-  Symbols:   1801
-  CStrings:  43024
+  Functions: 37368
+  Symbols:   1803
+  CStrings:  43044
Symbols:
+ _OBJC_CLASS_$_CMAngleManager
+ _OBJC_CLASS_$_FBSDisplayLayoutMonitorConfiguration
CStrings:
+ "/Library/Application Support/BTServer/countryCodes0x2036.plist"
+ "20:56:10"
+ "DisplayLayoutMonitor: displayState=%d, backlightState=%ld"
+ "DisplayState"
+ "RegulatoryManager: angle updates started"
+ "RegulatoryManager: angle updates stopped"
+ "RegulatoryManager: sending setDeviceState(%u)"
+ "RegulatoryManager: setDeviceState(%u) failed: %d"
+ "backlightState"
+ "configurationForDefaultMainDisplayMonitor"
+ "displayConfiguration"
+ "isAvailable"
+ "isMainDisplay"
+ "setAngleUpdateInterval:"
+ "setRequestHandler:"
+ "setTransitionHandler:"
+ "startAngleUpdatesToQueue:handler:"
+ "stopAngleUpdates"
+ "v16@?0@\"CMAngle\"8"
+ "v32@?0@\"FBSDisplayLayoutMonitor\"8@\"FBSDisplayLayout\"16@\"FBSDisplayLayoutTransitionContext\"24"
+ "v40@?0@\"NSString\"8@\"NSDictionary\"16@\"NSDictionary\"24@?<v@?@\"NSDictionary\"@\"NSDictionary\"@\"NSError\">32"
- "20:55:43"
```
