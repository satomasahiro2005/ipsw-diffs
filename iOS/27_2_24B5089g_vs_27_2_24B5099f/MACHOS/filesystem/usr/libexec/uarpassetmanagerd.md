## uarpassetmanagerd

> `/usr/libexec/uarpassetmanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ef84` | `0x2f0d8` | **`+0x154`** |
| `__DATA_CONST.__cfstring` | `0x2fc0` | `0x2fe0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x30db` | `0x30e3` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1587.40.28.0.0
+1587.40.33.0.0

-  Functions: 507
-  Symbols:   1735
-  CStrings:  1253
+  Functions: 508
+  Symbols:   1736
+  CStrings:  1254
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetManagerServiceInstance-0024640bd6a6b2c39203943f42ce0f60.o
+ _mobileAssetMatchesSigning
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetManagerServiceInstance-5c571b8fe790d123b77cfbebb245e0c0.o
Functions:
+ _mobileAssetMatchesSigning
~ _assetWithMaxVersion : 664 -> 680
CStrings:
+ "Signing"
```
