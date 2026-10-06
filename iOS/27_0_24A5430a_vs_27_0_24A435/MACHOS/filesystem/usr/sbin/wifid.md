## wifid

> `/usr/sbin/wifid`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c38bc` | `0x1c3d90` | **`+0x4d4`** |
| `__TEXT.__cstring` | `0x75aae` | `0x75c31` | **`+0x183`** |
| `__TEXT.__objc_stubs` | `0x14fc0` | `0x15040` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x1b3bb` | `0x1b3fd` | **`+0x42`** |
| `__DATA_CONST.__cfstring` | `0x1c8e0` | `0x1c920` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x6398` | `0x63b8` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x7c28` | `0x7c48` | **`+0x20`** |
| `__TEXT.__const` | `0xe5b` | `0xe6b` | **`+0x10`** |
| `__DATA.__common` | `0x60` | `0x68` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x45a8` | `0x45b0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Functions: 8810
+  Functions: 8814

-  CStrings:  17360
+  CStrings:  17375
Symbols:
+ _OBJC_CLASS_$_CMAngleManager
- _kWAMessageKeyPrivateMacHomeNetwork
CStrings:
+ "%s: AB mode state updated to stateA"
+ "%s: AB mode state updated to stateB"
+ "%s: AB mode state updated to unknown"
+ "%s: WiFiManager Device AB mode callback initialization failed"
+ "%s: WiFiManager Device AB mode callback initialized"
+ "WiFiDeviceManagerSetDeviceABModeState"
+ "WiFiManager-2027.32 Aug 27 2026 20:53:32"
+ "WiFiManager-2027.32 Aug 27 2026 20:54:22"
+ "WiFiManagerScheduleWithQueue_block_invoke_18"
+ "WiFiManagerScheduleWithQueue_block_invoke_19"
+ "__WiFiManagerDeviceABModeStateChangeCallback"
+ "iPad12,1"
+ "iPad12,2"
+ "isAngleValid"
+ "isAvailable"
+ "setUnderlyingQueue:"
+ "startAngleUpdatesToQueue:handler:"
+ "stopAngleUpdates"
+ "v16@?0@\"CMAngle\"8"
- "WiFiManager-2027.32 Aug 27 2026 20:51:42"
- "WiFiManager-2027.32 Aug 27 2026 20:52:31"
- "WiFiManagerScheduleWithQueue_block_invoke_17"
- "setPrivateMacNetworkTypeHome:"
```
