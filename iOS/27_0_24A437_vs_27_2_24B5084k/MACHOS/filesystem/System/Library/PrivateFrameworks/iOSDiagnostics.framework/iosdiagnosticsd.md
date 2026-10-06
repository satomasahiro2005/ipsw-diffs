## iosdiagnosticsd

> `/System/Library/PrivateFrameworks/iOSDiagnostics.framework/iosdiagnosticsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xc88` | `0xcad` | **`+0x25`** |
| `__DATA_CONST.__cfstring` | `0xd60` | `0xd80` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2600` | `0x25e0` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x3609` | `0x35ef` | **`-0x1a`** |
| `__DATA_CONST.__got` | `0x288` | `0x278` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0xd88` | `0xd80` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1374.2.2.0.0
+1374.40.35.0.0

-  - /System/Library/PrivateFrameworks/NanoRegistry.framework/NanoRegistry
+  - /System/Library/PrivateFrameworks/PairedDeviceRegistry.framework/PairedDeviceRegistry

-  Symbols:   195
+  Symbols:   193
Symbols:
+ _OBJC_CLASS_$_PDRDevice
- _NRDevicePropertyIsPaired
- _OBJC_CLASS_$_NRDevice
- _OBJC_CLASS_$_NRPairedDeviceRegistry
CStrings:
+ "00000000-0000-0000-0000-000000000000"
+ "bluetoothIdentifier"
+ "isEqualToPDRDevice:"
+ "isPaired"
- "deviceIDForNRDevice:"
- "isEqualToNRDevice:"
- "isEqualToNumber:"
- "valueForProperty:"
```
