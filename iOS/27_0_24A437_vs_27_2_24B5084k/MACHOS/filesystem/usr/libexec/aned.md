## aned

> `/usr/libexec/aned`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7d2fc` | `0x7d36c` | **`+0x70`** |
| `__TEXT.__objc_methname` | `0x3ea7` | `0x3e6b` | **`-0x3c`** |
| `__DATA.__objc_const` | `0x1cb8` | `0x1c98` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x2b48` | `0x2b68` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x34a0` | `0x3480` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x1ba0` | `0x1bb8` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x6cd0` | `0x6ce5` | **`+0x15`** |
| `__DATA.__bss` | `0x98` | `0xa8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xf70` | `0xf80` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xfc0` | `0xfb8` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x7d0` | `0x7d8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x3c0` | `0x3c8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1184` | `0x117c` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xe8` | `0xe4` | **`-0x4`** |
| `__TEXT.__gcc_except_tab` | `0x619c` | `0x61a0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-382.15.1.0.0
+382.100.2.0.0

-  Symbols:   4173
-  CStrings:  1758
+  Symbols:   4176
+  CStrings:  1755
Symbols:
+ GCC_except_table21
+ GCC_except_table59
+ __32-[_ANEServer maxModelMemorySize]_block_invoke
+ __ZZ32-[_ANEServer maxModelMemorySize]E19sMaxModelMemorySize
+ __ZZ32-[_ANEServer maxModelMemorySize]E9onceToken
+ ___32-[_ANEServer maxModelMemorySize]_block_invoke
+ _kANEFModelMutableClusterIndexKey
+ _usleep
- -[_ANEServer setMaxModelMemorySize:]
- GCC_except_table44
- GCC_except_table55
- OBJC_IVAR_$__ANEServer._maxModelMemorySize
- _objc_msgSend$setMaxModelMemorySize:
CStrings:
+ "TQ,R,N"
+ "maxModelMemorySize: 0x%llx"
+ "maxModelMemorySize: non-internal build, using 0"
+ "maxModelMemorySize: unable to connect to ANE device"
+ "maxModelMemorySize: unable to create device controller"
- "Maximum model memory size: %llu"
- "TQ,V_maxModelMemorySize"
- "Unable to connect to ANE device."
- "Unable to create device controller"
- "_maxModelMemorySize"
- "set maxModelMemorySize to 0"
- "set maxModelMemorySize to 0x%llx"
- "setMaxModelMemorySize:"
```
