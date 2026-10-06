## VoiceMemos

> `/System/Library/PrivateFrameworks/VoiceMemos.framework/VoiceMemos`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x47e60` | `0x47a6c` | **`-0x3f4`** |
| `__TEXT.__cstring` | `0x68b8` | `0x6833` | **`-0x85`** |
| `__AUTH_CONST.__cfstring` | `0x32e0` | `0x3280` | **`-0x60`** |
| `__AUTH_CONST.__const` | `0xa40` | `0x9e0` | **`-0x60`** |
| `__DATA.__bss` | `0x22c` | `0x1fc` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x1a78` | `0x1a48` | **`-0x30`** |
| `__TEXT.__oslogstring` | `0x2f36` | `0x2f62` | **`+0x2c`** |

### Other Changes

```diff

-1433.0.0.0.0
+1435.0.0.0.0

-  Functions: 2010
-  Symbols:   3298
-  CStrings:  929
+  Functions: 1998
+  Symbols:   3286
+  CStrings:  925
Symbols:
- _RCApplicationAssetRecoveryDirectoryURL
- _RCApplicationAssetRecoveryDirectoryURL.onceToken
- _RCApplicationAssetRecoveryDirectoryURL.url
- _RCApplicationAssetsDirectoryURL
- _RCApplicationAssetsDirectoryURL.onceToken
- _RCApplicationAssetsDirectoryURL.url
- _RCMixDownRecoveryDirectoryURL
- _RCMixDownRecoveryDirectoryURL.onceToken
- _RCMixDownRecoveryDirectoryURL.url
- ___RCApplicationAssetRecoveryDirectoryURL_block_invoke
- ___RCApplicationAssetsDirectoryURL_block_invoke
- ___RCMixDownRecoveryDirectoryURL_block_invoke
CStrings:
+ "%s -- Fragments consolidated for file at %@"
+ "+[FragmentConsolidator consolidateMovieFragmentsForFileAt:error:]"
- "ApplicationAssetRecovery"
- "ApplicationAssets"
- "MixDownRecovery"
- "RCApplicationAssetRecoveryDirectoryURL_block_invoke"
- "RCApplicationAssetsDirectoryURL_block_invoke"
- "RCMixDownRecoveryDirectoryURL_block_invoke"
```
