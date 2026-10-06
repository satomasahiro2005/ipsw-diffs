## deviceaccessd

> `/usr/libexec/deviceaccessd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x91ba4` | `0x91f34` | **`+0x390`** |
| `__TEXT.__cstring` | `0x152c4` | `0x15394` | **`+0xd0`** |
| `__TEXT.__objc_stubs` | `0x7ee0` | `0x7f40` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0xa3b4` | `0xa3e4` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x21e0` | `0x2200` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x2738` | `0x2750` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x2728` | `0x2740` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1aa0` | `0x1ab0` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x78` | `0x80` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2700.30.0.0.0
+2700.34.0.0.0

-  Functions: 2515
+  Functions: 2520

-  CStrings:  3966
+  CStrings:  3973
CStrings:
+ "### _updateDeviceStateForBluetooth prox pairing device with APP Required flow"
+ "### centralManagerDidUpdateState powerState: %ld"
+ "Marking device state Activating for app-required mode: %@"
+ "_createCBCentralManager"
+ "_deviceConfirmsAuthorization:"
+ "com.apple.media-device-extension"
+ "requiresCompanionApp"
```
