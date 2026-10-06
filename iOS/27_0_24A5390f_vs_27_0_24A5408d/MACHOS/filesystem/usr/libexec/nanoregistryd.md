## nanoregistryd

> `/usr/libexec/nanoregistryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1006b4` | `0x100784` | **`+0xd0`** |
| `__DATA_CONST.__cfstring` | `0xc040` | `0xc0a0` | **`+0x60`** |
| `__TEXT.__cstring` | `0xe0ac` | `0xe0d9` | **`+0x2d`** |
| `__DATA_CONST.__const` | `0x4ba0` | `0x4bc0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x10fe0` | `0x11000` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1cd8` | `0x1cc0` | **`-0x18`** |
| `__TEXT.__objc_methname` | `0x1c5ee` | `0x1c603` | **`+0x15`** |
| `__TEXT.__auth_stubs` | `0x1100` | `0x1110` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x5e88` | `0x5e90` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x890` | `0x898` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xdc8` | `0xdd0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xdad4` | `0xdadc` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1075.1.1.0.0
+1075.1.3.0.0

-  Functions: 5828
-  Symbols:   705
-  CStrings:  8652
+  Functions: 5830
+  Symbols:   707
+  CStrings:  8656
Symbols:
+ _MGIsQuestionValid
+ _NRDevicePropertyBiometryType
CStrings:
+ "128"
+ "NanoRegistry-1075.1.3"
+ "OysterCapability"
+ "PearlIDCapability"
+ "_currentBiometryType"
+ "touch-id"
- "72"
- "NanoRegistry-1075.1.1"
```
