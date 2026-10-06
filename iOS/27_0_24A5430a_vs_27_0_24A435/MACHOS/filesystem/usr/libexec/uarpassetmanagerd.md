## uarpassetmanagerd

> `/usr/libexec/uarpassetmanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x30da` | `0x30d6` | **`-0x4`** |
| `__TEXT.__text` | `0x2ef84` | `0x2ef88` | **`+0x4`** |

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
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetManagerServiceInstance-cd28759bbba90add29bb983c22716798.o
+ ___kCFBooleanFalse
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetManagerServiceInstance-7729611873715ee4029351be2b32dc54.o
- ___kCFBooleanTrue
Functions:
~ _updateSeedEnablementForAccessory : 732 -> 736
CStrings:
+ "Rave"
- "RaveSeed"
```
