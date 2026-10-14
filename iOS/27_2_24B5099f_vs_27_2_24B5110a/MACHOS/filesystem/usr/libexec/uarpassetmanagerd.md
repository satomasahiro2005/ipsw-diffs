## uarpassetmanagerd

> `/usr/libexec/uarpassetmanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x2c30` | `0x2cc0` | **`+0x90`** |
| `__TEXT.__cstring` | `0x30e3` | `0x312d` | **`+0x4a`** |
| `__DATA_CONST.__cfstring` | `0x2fe0` | `0x3020` | **`+0x40`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   1736
-  CStrings:  1254
+  Symbols:   1738
+  CStrings:  1256
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetManagerServiceInstance-fdd856eacdde535b824d3c8583f53dbe.o
+ _MA_PALLAS_AUDIENCE_CUSTOMER_HOMEACCESSORY
+ _MA_PALLAS_AUDIENCE_CUSTOMER_HOMEACCESSORY_GENERIC
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetManagerServiceInstance-0024640bd6a6b2c39203943f42ce0f60.o
CStrings:
+ "9adbf9f2-0adf-4a37-9ecc-bee59e9a19eb"
+ "bebc09db-45a4-43df-a45c-47a4f832c7e7"
```
