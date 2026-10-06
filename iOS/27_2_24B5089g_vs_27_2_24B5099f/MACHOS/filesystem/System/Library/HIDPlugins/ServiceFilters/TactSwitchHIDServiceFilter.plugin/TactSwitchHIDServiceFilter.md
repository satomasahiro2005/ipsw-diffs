## TactSwitchHIDServiceFilter

> `/System/Library/HIDPlugins/ServiceFilters/TactSwitchHIDServiceFilter.plugin/TactSwitchHIDServiceFilter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b6c` | `0x2bf0` | **`+0x84`** |
| `__TEXT.__oslogstring` | `0x482` | `0x4c8` | **`+0x46`** |
| `__DATA_CONST.__cfstring` | `0x360` | `0x3a0` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x720` | `0x740` | **`+0x20`** |
| `__TEXT.__cstring` | `0x38a` | `0x3a3` | **`+0x19`** |
| `__TEXT.__objc_methname` | `0x99c` | `0x9a8` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x328` | `0x330` | **`+0x8`** |

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

-  Symbols:   276
-  CStrings:  269
+  Symbols:   277
+  CStrings:  272
Symbols:
+ _objc_msgSend$boolForKey:
Functions:
~ -[TactSwitchHIDServiceFilter createUserDevice] : 476 -> 608
CStrings:
+ "MTDisableDebugUserDevice"
+ "MTDisableDebugUserDevice set; skipping debug HID user device creation"
+ "boolForKey:"
```
