## PhotosFileProvider

> `/System/Library/ExtensionKit/Extensions/PhotosFileProvider.appex/PhotosFileProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23b0` | `0x24c4` | **`+0x114`** |
| `__TEXT.__oslogstring` | `0x4f0` | `0x564` | **`+0x74`** |
| `__TEXT.__objc_stubs` | `0x980` | `0x9c0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x22f` | `0x265` | **`+0x36`** |
| `__DATA_CONST.__cfstring` | `0x2c0` | `0x2e0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x2f0` | `0x300` | **`+0x10`** |
| `__TEXT.__const` | `0x38` | `0x48` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x9c9` | `0x9d8` | **`+0xf`** |
| `__DATA.__objc_selrefs` | `0x298` | `0x2a0` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x180` | `0x188` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

-  Symbols:   89
-  CStrings:  163
+  Symbols:   90
+  CStrings:  166
Symbols:
+ _PLFileProviderGetLog
Functions:
~ sub_100000f28 : 1696 -> 1664
~ sub_1000017f0 -> sub_1000017d0 : 1724 -> 2032
~ sub_1000022d0 -> sub_1000023e4 : 764 -> 768
~ sub_1000025cc -> sub_1000026e4 : 784 -> 792
~ sub_1000028dc -> sub_1000029fc : 364 -> 352
CStrings:
+ "Adjustment timestamp mismatch for asset %{public}@: expected %{public}@, current %{public}@"
+ "Asset adjustment timestamp does not match promise URL"
+ "Can't find possible content type with extension: %{public}@"
+ "Failed to fetch PHObject with localIdentifier: %{public}@"
+ "Unknown URL query item (name: %{public}@, value: %@)"
+ "isEqualToDate:"
- "Can't find possible content type with extension: %@"
- "Failed to fetch PHObject with localIdentifier: %@"
- "Unknown URL query item (name: %@, value: %@)"
```
