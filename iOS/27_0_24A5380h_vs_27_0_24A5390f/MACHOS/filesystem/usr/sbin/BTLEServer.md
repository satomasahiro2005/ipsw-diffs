## BTLEServer

> `/usr/sbin/BTLEServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7ee24` | `0x7f744` | **`+0x920`** |
| `__TEXT.__oslogstring` | `0xd77e` | `0xd852` | **`+0xd4`** |
| `__TEXT.__unwind_info` | `0x1bf0` | `0x1c18` | **`+0x28`** |
| `__TEXT.__objc_methname` | `0x13341` | `0x13364` | **`+0x23`** |
| `__DATA_CONST.__auth_ptr` | `0x40` | `0x20` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x10d0` | `0x10f0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xcf60` | `0xcf80` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x880` | `0x890` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x13d0` | `0x13c4` | **`-0xc`** |
| `__DATA.__objc_selrefs` | `0x42e8` | `0x42f0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x7e8c` | `0x7e94` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-2700.35.0.0.0
+2700.38.0.0.0

-  Functions: 3158
-  Symbols:   570
-  CStrings:  5251
+  Functions: 3165
+  Symbols:   572
+  CStrings:  5255
Symbols:
+ _dispatch_group_notify
+ _pthread_set_qos_class_self_np
CStrings:
+ "Input report too large (%ld bytes) for report ID 0x%02x"
+ "Peripheral \"%@\" supports deferred service \"%{public}@\" — link now encrypted"
+ "instantiateEncryptionGatedServices"
+ "instantiateEncryptionGatedServices: link not encrypted on \"%@\", nothing to do"
```
