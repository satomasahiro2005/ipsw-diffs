## sharingd

> `/usr/libexec/sharingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6ad4c8` | `0x6adc6c` | **`+0x7a4`** |
| `__TEXT.__cstring` | `0x3ede1` | `0x3efd1` | **`+0x1f0`** |
| `__TEXT.__objc_stubs` | `0x37700` | `0x37840` | **`+0x140`** |
| `__TEXT.__objc_methname` | `0x4ebe5` | `0x4ecd5` | **`+0xf0`** |
| `__DATA_CONST.__cfstring` | `0x196c0` | `0x19740` | **`+0x80`** |
| `__DATA.__objc_const` | `0x38698` | `0x386f8` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x110e8` | `0x11138` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x1e604` | `0x1e634` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1cc98` | `0x1ccc0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x148a0` | `0x148c8` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0xbca2` | `0xbcc2` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x688c` | `0x68a8` | **`+0x1c`** |
| `__DATA.__objc_ivar` | `0x293c` | `0x2948` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x3a30` | `0x3a38` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
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

-  Functions: 26393
-  Symbols:   5017
-  CStrings:  27556
+  Functions: 26398
+  Symbols:   5018
+  CStrings:  27581
Symbols:
+ _OBJC_CLASS_$_CMDeviceStateManager
CStrings:
+ "### Device state no longer supports Handoff, cleaning up notifications\n"
+ "### Device state update error: %@\n"
+ "-[SDProxHandoffAgent _deviceStateEnsureStarted]"
+ "-[SDProxHandoffAgent _deviceStateEnsureStarted]_block_invoke"
+ "-[SDProxHandoffAgent _deviceStateEnsureStopped]"
+ "-[SDProxHandoffAgent _deviceStateUpdate:]"
+ "@\"CMDeviceStateManager\""
+ "Device state monitor start\n"
+ "Device state monitor stop\n"
+ "Device state supported: %s -> %s\n"
+ "_deviceStateEnsureStarted"
+ "_deviceStateEnsureStopped"
+ "_deviceStateMonitor"
+ "_deviceStateMonitorStarted"
+ "_deviceStateShouldStart"
+ "_deviceStateSupported"
+ "_deviceStateUpdate:"
+ "b518"
+ "b868e"
+ "b868m"
+ "com.apple.SharingServices.SDProxHandoffAgent"
+ "propertyB"
+ "startUpdatesToQueue:withHandler:"
+ "stopUpdates"
+ "v24@?0@\"CMDeviceStateEvent\"8@\"NSError\"16"
```
