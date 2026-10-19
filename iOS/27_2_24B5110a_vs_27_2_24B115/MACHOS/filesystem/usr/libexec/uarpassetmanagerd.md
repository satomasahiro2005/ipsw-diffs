## uarpassetmanagerd

> `/usr/libexec/uarpassetmanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x312d` | `0x3129` | **`-0x4`** |
| `__TEXT.__text` | `0x2f0d8` | `0x2f0dc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetManagerServiceInstance-56f11a94e2f69fa8bfc6c9236f548e4d.o
+ ___kCFBooleanFalse
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetManagerServiceInstance-fdd856eacdde535b824d3c8583f53dbe.o
- ___kCFBooleanTrue
Functions:
~ _updateSeedEnablementForAccessory : 732 -> 736
CStrings:
+ "RaveB"
- "RaveBSeed"
```
