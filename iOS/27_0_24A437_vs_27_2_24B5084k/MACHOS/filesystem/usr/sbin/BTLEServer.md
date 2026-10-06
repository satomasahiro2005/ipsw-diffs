## BTLEServer

> `/usr/sbin/BTLEServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7f8ec` | `0x7f9e4` | **`+0xf8`** |
| `__DATA_CONST.__cfstring` | `0x4ca0` | `0x4d00` | **`+0x60`** |
| `__TEXT.__cstring` | `0x363c` | `0x3694` | **`+0x58`** |
| `__TEXT.__objc_methname` | `0x13364` | `0x133bc` | **`+0x58`** |
| `__TEXT.__objc_stubs` | `0xcf80` | `0xcfc0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x7e94` | `0x7ec4` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x42f0` | `0x4308` | **`+0x18`** |
| `__DATA.__objc_const` | `0xfcb8` | `0xfcc8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x10f0` | `0x1100` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x890` | `0x898` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2700.39.0.0.0
+2701.2.0.0.0

-  Functions: 3167
-  Symbols:   572
-  CStrings:  5257
+  Functions: 3168
+  Symbols:   573
+  CStrings:  5265
Symbols:
+ _MGGetStringAnswer
CStrings:
+ "DeviceClass"
+ "DeviceSupportsApplePencil"
+ "ExperimentalUSBPencilSupport"
+ "PencilPairing"
+ "deviceInactivityTimeout:"
+ "deviceNoFirmwareUpdateAvailable:"
+ "iPhone"
+ "usesModifiedNominalParameters"
```
