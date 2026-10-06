## TouchSensitiveButtonHIDService

> `/System/Library/HIDPlugins/ServicePlugins/TouchSensitiveButtonHIDService.plugin/TouchSensitiveButtonHIDService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2fdc` | `0x3058` | **`+0x7c`** |
| `__TEXT.__oslogstring` | `0x4a9` | `0x4ef` | **`+0x46`** |
| `__DATA_CONST.__cfstring` | `0x2a0` | `0x2e0` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x6e0` | `0x700` | **`+0x20`** |
| `__TEXT.__cstring` | `0x336` | `0x34f` | **`+0x19`** |
| `__TEXT.__objc_methname` | `0x96d` | `0x979` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x318` | `0x320` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-10100.44.0.0.0
+10110.3.0.0.0

-  Symbols:   289
-  CStrings:  265
+  Symbols:   290
+  CStrings:  268
Symbols:
+ _objc_msgSend$boolForKey:
Functions:
~ -[TouchSensitiveButtonHIDServicePlugin createUserDevice] : 476 -> 600
CStrings:
+ "MTDisableDebugUserDevice"
+ "MTDisableDebugUserDevice set; skipping debug HID user device creation"
+ "boolForKey:"
```
