## mobilerepaird

> `/usr/libexec/mobilerepaird`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe088` | `0xe1c8` | **`+0x140`** |
| `__DATA_CONST.__cfstring` | `0x2300` | `0x2380` | **`+0x80`** |
| `__TEXT.__cstring` | `0x23b9` | `0x242b` | **`+0x72`** |
| `__TEXT.__oslogstring` | `0xb2c` | `0xac6` | **`-0x66`** |
| `__DATA_CONST.__const` | `0x478` | `0x458` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x1c00` | `0x1c20` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x3d0` | `0x3e8` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0x212c` | `0x2140` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0x8d8` | `0x8e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1307.0.26.502.1
+1307.0.46.0.0

-  CStrings:  821
+  CStrings:  824
CStrings:
+ "FINISH_TOUCHID_REPAIR_DESC"
+ "FINISH_VB_REPAIR_DESC_IPAD"
+ "Processing EIC strobe notification - posting DisplayTCON hardware failure status (%@)"
+ "Received EIC strobe daemon notification - marking DisplayTCON as failed (%@)"
+ "Successfully unregistered exclave notification listener(s)"
+ "com.apple.medina.1.hw.failure"
+ "com.apple.medina.1.hw.success"
+ "handleExclaveNotification:"
+ "supportHarvestMesa"
- "Exclave notification handler already registered"
- "Exclave notification handler not registered, nothing to unregister"
- "Processing EIC strobe notification - posting DisplayTCON hardware failure status"
- "Received EIC strobe daemon notification - marking DisplayTCON as failed"
- "Successfully unregistered exclave notification listener"
- "handleExclaveNotification"
```
