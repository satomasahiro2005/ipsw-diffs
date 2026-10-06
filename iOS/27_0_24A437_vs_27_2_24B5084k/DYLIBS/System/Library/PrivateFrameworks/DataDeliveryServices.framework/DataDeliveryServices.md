## DataDeliveryServices

> `/System/Library/PrivateFrameworks/DataDeliveryServices.framework/DataDeliveryServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a060` | `0x2a2bc` | **`+0x25c`** |
| `__AUTH_CONST.__objc_const` | `0x8e18` | `0x8e70` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x2a7c` | `0x2ac4` | **`+0x48`** |
| `__TEXT.__cstring` | `0x16c2` | `0x16d4` | **`+0x12`** |
| `__TEXT.__oslogstring` | `0x3dfd` | `0x3e09` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x1618` | `0x1620` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xc98` | `0xca0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x22c` | `0x230` | **`+0x4`** |

### Other Changes

```diff

-115.0.0.0.0
+117.0.0.0.0

-  Functions: 1043
-  Symbols:   1939
+  Functions: 1048
+  Symbols:   1943
Symbols:
+ -[DDSUAFManager _assetsFromUAFForQuery:]
+ -[DDSUAFManager assetQueryResultsCache]
+ -[DDSUAFManager serverDidUpdateAssetsWithType:]
+ -[DDSUAFManagerStub serverDidUpdateAssetsWithType:]
+ _OBJC_IVAR_$_DDSUAFManager._assetQueryResultsCache
+ ___40-[DDSUAFManager _assetsFromUAFForQuery:]_block_invoke
- GCC_except_table23
- ___32-[DDSUAFManager assetsForQuery:]_block_invoke
CStrings:
+ "DDSUAFManagerStub: serverDidUpdateAssetsWithType called (no-op)"
+ "UAFAssetAccess"
+ "com.apple.UnifiedAssetFramework"
- "FinishTaskNow"
- "assetsForQuery: %{public}@ final result: %{public}@"
- "com.apple.common"
```
