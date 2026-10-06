## HealthStoragePlugin

> `/System/Library/PreferenceBundles/StoragePlugins/HealthStoragePlugin.bundle/HealthStoragePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x2f1` | `0x345` | **`+0x54`** |
| `__DATA_CONST.__cfstring` | `0x300` | `0x340` | **`+0x40`** |
| `__TEXT.__text` | `0x29f4` | `0x2a1c` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x960` | `0x980` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x7cc` | `0x7e0` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0x290` | `0x298` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  CStrings:  144
+  CStrings:  147
Functions:
~ sub_1d4c : 208 -> 220
~ sub_2954 -> sub_2960 : 256 -> 268
~ sub_2c2c -> sub_2c44 : 304 -> 320
CStrings:
+ "HKStoragePlugin:_buildDataSourceSection"
+ "HKStoragePlugin:_hkTypeCountsQueryOperation"
+ "setDebugIdentifier:"
```
