## GenericHID

> `/System/Library/ScreenReader/BrailleDrivers/GenericHID.brailledriver/GenericHID`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__objc_dictobj` | `0xf0` | `—` | **`-0xf0`** |
| `__DATA_CONST.__objc_arraydata` | `0x1c8` | `0x108` | **`-0xc0`** |
| `__TEXT.__text` | `0x4f14` | `0x4e78` | **`-0x9c`** |
| `__DATA_CONST.__objc_intobj` | `0x288` | `0x228` | **`-0x60`** |
| `__TEXT.__objc_stubs` | `0xec0` | `0xf20` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0xfd7` | `0x101c` | **`+0x45`** |
| `__DATA.__objc_selrefs` | `0x570` | `0x588` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x6a4` | `0x6bc` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x4b0` | `0x4c0` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x310` | `0x31b` | **`+0xb`** |
| `__DATA_CONST.__auth_got` | `0x260` | `0x268` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x98` | `0xa0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x118` | `0x120` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-467.3.0.0.0
+467.3.1.0.0

-  Functions: 89
-  Symbols:   105
-  CStrings:  331
+  Functions: 91
+  Symbols:   106
+  CStrings:  335
Symbols:
+ ___NSArray0__struct
+ _objc_retain_x21
+ _objc_retain_x23
- _OBJC_CLASS_$_NSConstantDictionary
- _objc_retain_x22
CStrings:
+ "@20@0:8I16"
+ "_brailleDisplayElementsWithUsage:"
+ "_releaseHIDDevice"
+ "unsignedIntValue"
```
