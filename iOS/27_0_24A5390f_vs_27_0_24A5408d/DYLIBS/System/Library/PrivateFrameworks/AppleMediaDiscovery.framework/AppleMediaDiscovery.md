## AppleMediaDiscovery

> `/System/Library/PrivateFrameworks/AppleMediaDiscovery.framework/AppleMediaDiscovery`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf3928` | `0xf3b94` | **`+0x26c`** |
| `__AUTH_CONST.__cfstring` | `0xda80` | `0xdaa0` | **`+0x20`** |
| `__TEXT.__cstring` | `0xac48` | `0xac68` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x46d7` | `0x46f7` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x28d8` | `0x28f0` | **`+0x18`** |
| `__DATA_CONST.__const` | `0xda0` | `0xda8` | **`+0x8`** |

### Other Changes

```diff

-1.5.4.0.0
+1.5.6.0.0

+  - /usr/lib/swift/libswiftCompression.dylib

-  Symbols:   2802
-  CStrings:  2390
+  Symbols:   2804
+  CStrings:  2394
Symbols:
+ ___block_descriptor_89_e8_32s40s48s56s64r72r_e5_v8?0ls32l8r64l8s40l8s48l8s56l8r72l8
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCompression_$_AppleMediaDiscovery
- ___block_descriptor_80_e8_32s40s48s56r64r_e5_v8?0lr56l8s32l8s40l8s48l8r64l8
Functions:
~ +[AMDSQLite insertRowsInternal:usingSchema:error:] : 2364 -> 2712
~ -[AMDSQLite insertRows:usingSchema:skipValidation:error:] : 2780 -> 2932
~ ___57-[AMDSQLite insertRows:usingSchema:skipValidation:error:]_block_invoke : 2100 -> 2220
CStrings:
+ "BEGIN TRANSACTION"
+ "COMMIT"
+ "SQLITE Bulk insert: %s"
+ "bulkInsert"
```
