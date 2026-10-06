## MobileAssetDaemon

> `/System/Library/PrivateFrameworks/MobileAssetDaemon.framework/MobileAssetDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x261198` | `0x261210` | **`+0x78`** |
| `__AUTH.__objc_data` | `0x918` | `0x8c8` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x2530` | `0x2580` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x33220` | `0x33240` | **`+0x20`** |
| `__DATA.__bss` | `0x580` | `0x560` | **`-0x20`** |
| `__TEXT.__cstring` | `0x3fb57` | `0x3fb77` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x5b0` | `0x5c8` | **`+0x18`** |
| `__DATA.__data` | `0x1180` | `0x1170` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0xa8` | `0xb8` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x1020` | `0x1028` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xb018` | `0xb020` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-2215.40.18.0.0
+2215.40.19.0.0

-  CStrings:  11063
+  CStrings:  11064
Functions:
~ -[MAAutoAssetMigrationManager preInstalledRelocateAutoAssets] : 5728 -> 5832
~ ____isAssetTypeAllowlisted_block_invoke : 632 -> 648
CStrings:
+ "Loaded built-in MobileAssetDaemon_Framework Sep 13 2026 20:55:11"
+ "com.apple.MobileAsset.RawCamera.MLModel"
- "Loaded built-in MobileAssetDaemon_Framework Sep  4 2026 20:59:10"
```
