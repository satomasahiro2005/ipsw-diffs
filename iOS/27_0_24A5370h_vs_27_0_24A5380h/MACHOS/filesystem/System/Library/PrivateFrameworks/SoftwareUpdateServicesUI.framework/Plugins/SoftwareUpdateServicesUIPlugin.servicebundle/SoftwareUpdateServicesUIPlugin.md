## SoftwareUpdateServicesUIPlugin

> `/System/Library/PrivateFrameworks/SoftwareUpdateServicesUI.framework/Plugins/SoftwareUpdateServicesUIPlugin.servicebundle/SoftwareUpdateServicesUIPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x410f8` | `0x41260` | **`+0x168`** |
| `__TEXT.__objc_stubs` | `0x54e0` | `0x5540` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x4878` | `0x48c5` | **`+0x4d`** |
| `__TEXT.__objc_methname` | `0x6147` | `0x6170` | **`+0x29`** |
| `__DATA_CONST.__got` | `0x450` | `0x478` | **`+0x28`** |
| `__TEXT.__cstring` | `0x3e26` | `0x3e42` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x1950` | `0x1968` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x678` | `0x690` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-302.0.0.0.0
+305.0.0.0.0

-  CStrings:  2039
+  CStrings:  2043
CStrings:
+ "%s: [DDM] Overriding start install delay, starting installing in %f seconds."
+ "Download invalidated for new updates available - Preferred: %@, Alternate: %@"
+ "alternateDescriptor"
+ "ddmDelay"
+ "doubleValue"
- "Download invalidated for new update available: %@"
```
