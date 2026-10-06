## uarpassetmanagerd

> `/usr/libexec/uarpassetmanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28d6c` | `0x2a6e4` | **`+0x1978`** |
| `__TEXT.__objc_stubs` | `0x2520` | `0x26e0` | **`+0x1c0`** |
| `__DATA_CONST.__const` | `0x2710` | `0x27d0` | **`+0xc0`** |
| `__DATA_CONST.__cfstring` | `0x2b80` | `0x2bc0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x2c41` | `0x2c7e` | **`+0x3d`** |
| `__TEXT.__objc_methname` | `0x2c20` | `0x2c59` | **`+0x39`** |
| `__TEXT.__objc_methlist` | `0x12a4` | `0x12bc` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0xba0` | `0xbb0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x390` | `0x3a0` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1576.0.0.0.0
+1587.0.3.0.3

-  Functions: 453
-  Symbols:   1578
-  CStrings:  1164
+  Functions: 458
+  Symbols:   1600
+  CStrings:  1169
Symbols:
+ -[UARPSettingsAccessory copyAssetLocationSettings:]
+ -[UARPSettingsAccessory isAssetLocationSettingsEqual:]
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetManagerServiceInstance-66c0fcf2e523785dc7e763a7403edba6.o
+ _MA_KNOX_URL_OVERRIDE_DEFAULT_KEY
+ _MA_WKMS_URL_OVERRIDE_DEFAULT_KEY
+ ___54-[UARPSettingsAccessory isAssetLocationSettingsEqual:]_block_invoke
+ ___block_descriptor_32_e28_"NSString"16?0"NSString"8l
+ _correctAssetSettingsForGroup
+ _isDefaultAssetConfiguration
+ _objc_msgSend$copyAssetLocationSettings:
+ _objc_msgSend$isAssetLocationSettingsEqual:
+ _objc_msgSend$otaDisabled
+ _objc_msgSend$pallasSupportEnabled
+ _objc_msgSend$setCustomBuild:
+ _objc_msgSend$setCustomTrain:
+ _objc_msgSend$setOtaDisabled:
+ _objc_msgSend$setPallasAudienceOverride:
+ _objc_msgSend$setSupplementalAssetLocation:
+ _objc_msgSend$setSupplementalCustomBuild:
+ _objc_msgSend$setSupplementalCustomTrain:
+ _objc_msgSend$supplementalAssetLocation
+ _objc_msgSend$supplementalCustomBuild
+ _objc_msgSend$supplementalCustomTrain
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetManagerServiceInstance-a71aca054c97db48723ddd9df5a05595.o
CStrings:
+ "@\"NSString\"16@?0@\"NSString\"8"
+ "KnoxURLOverride"
+ "WKMSURLOverride"
+ "copyAssetLocationSettings:"
+ "isAssetLocationSettingsEqual:"
```
