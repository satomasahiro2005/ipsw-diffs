## GenericGamepadHIDServicePlugin

> `/System/Library/HIDPlugins/ServicePlugins/GenericGamepadHIDServicePlugin.plugin/GenericGamepadHIDServicePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8800` | `0x8690` | **`-0x170`** |
| `__TEXT.__objc_methname` | `0xdd1` | `0xdfa` | **`+0x29`** |
| `__TEXT.__auth_stubs` | `0x4c0` | `0x4e0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xf40` | `0xf60` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x6e8` | `0x700` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x270` | `0x280` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x520` | `0x528` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x208` | `0x210` | **`+0x8`** |
| `__TEXT.__cstring` | `0x9ea` | `0x9f1` | **`+0x7`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-14.0.19.0.0
+14.0.21.0.0

-  Functions: 133
-  Symbols:   121
-  CStrings:  323
+  Functions: 136
+  Symbols:   123
+  CStrings:  326
Symbols:
+ _objc_getProperty
+ _objc_setProperty_atomic
CStrings:
+ "0@`"
+ "0`"
+ "_onqueue_configureRumbleWithModel:error:"
```
