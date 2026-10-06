## MobileInBoxUpdate

> `/System/Library/PrivateFrameworks/MobileInBoxUpdate.framework/MobileInBoxUpdate`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x333dc` | `0x335c8` | **`+0x1ec`** |
| `__AUTH_CONST.__objc_intobj` | `0x1308` | `0x1338` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x1de0` | `0x1e00` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x2a48` | `0x2a68` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x3c0` | `0x3d8` | **`+0x18`** |
| `__TEXT.__cstring` | `0x18c1` | `0x18d1` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x4870` | `0x4878` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x378` | `0x380` | **`+0x8`** |

### Other Changes

```diff

-274.2.2.0.0
+274.40.15.0.0

-  Functions: 1402
-  Symbols:   1944
-  CStrings:  497
+  Functions: 1404
+  Symbols:   1945
+  CStrings:  498
Symbols:
+ _kMIBUNFCCommandSigningServerForSUKey
Functions:
~ ___39+[MIBUSerializationUtil tagTypeMapping]_block_invoke : 1468 -> 1484
~ -[MIBUNFCCommand _serializeSSUpdate] : 3584 -> 3720
+ ___36-[MIBUNFCCommand _serializeSSUpdate]_block_invoke.472
~ -[MIBUNFCCommand _deserializeSSUpdate] : 3256 -> 3364
~ -[MIBUNFCCommand _serializeSSUpdate].cold.26 : 120 -> 128
+ -[MIBUNFCCommand _serializeSSUpdate].cold.36
CStrings:
+ "SigningServerForSU"
```
