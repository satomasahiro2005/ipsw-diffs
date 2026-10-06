## PhotosFileProvider

> `/System/Library/ExtensionKit/Extensions/PhotosFileProvider.appex/PhotosFileProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24c4` | `0x27ac` | **`+0x2e8`** |
| `__TEXT.__oslogstring` | `0x564` | `0x64f` | **`+0xeb`** |
| `__TEXT.__objc_stubs` | `0x9c0` | `0xaa0` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x9d8` | `0xa7e` | **`+0xa6`** |
| `__DATA.__objc_selrefs` | `0x2a0` | `0x2d8` | **`+0x38`** |
| `__TEXT.__cstring` | `0x265` | `0x296` | **`+0x31`** |
| `__DATA_CONST.__const` | `0xe0` | `0x108` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x2e0` | `0x300` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x300` | `0x320` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x188` | `0x198` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x100` | `0x110` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-910.21.101.0.0
+910.27.103.0.0

-  Symbols:   90
-  CStrings:  166
+  Symbols:   94
+  CStrings:  176
Symbols:
+ _OBJC_CLASS_$_NSArray
+ _OBJC_CLASS_$_PHFetchOptions
+ _objc_retain_x25
+ _objc_retain_x26
Functions:
~ sub_1000017d0 : 2032 -> 2092
~ sub_100001fc0 -> sub_100001ffc : 40 -> 724
CStrings:
+ "Adjustment timestamp changed during export for asset %{public}@: expected %{public}@, current %{public}@"
+ "Asset adjustment timestamp changed during export"
+ "Nil result refetching asset %{public}@, may have been expunged during export, but after the share action, will proceed with share"
+ "arrayWithObjects:count:"
+ "fetchAssetsWithLocalIdentifiers:options:"
+ "firstObject"
+ "setIncludeGuestAssets:"
+ "setIncludeHiddenAssets:"
+ "setIncludeTrashedAssets:"
+ "setPhotoLibrary:"
```
