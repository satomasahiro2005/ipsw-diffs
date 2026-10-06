## uarpassetmanagerd

> `/usr/libexec/uarpassetmanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x2c40` | `0x2bb0` | **`-0x90`** |
| `__TEXT.__cstring` | `0x2fe3` | `0x2f99` | **`-0x4a`** |
| `__DATA_CONST.__cfstring` | `0x2f40` | `0x2f00` | **`-0x40`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1587.0.21.0.0
+1587.0.27.0.0

-  Symbols:   1712
-  CStrings:  1235
+  Symbols:   1710
+  CStrings:  1233
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetManagerServiceInstance-b3842435c2c82172377d4b0b45f2a480.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetManagerServiceInstance-4b0ed6e1656d20a748062c3f582e7535.o
- _MA_PALLAS_AUDIENCE_CUSTOMER_SEASHIP
- _MA_PALLAS_AUDIENCE_INTERNAL_SEASHIP
CStrings:
- "cd060049-2465-43e3-bbb5-d769a66da2d7"
- "ffc25f86-b83c-4139-b8ad-91131d0e5429"
```
