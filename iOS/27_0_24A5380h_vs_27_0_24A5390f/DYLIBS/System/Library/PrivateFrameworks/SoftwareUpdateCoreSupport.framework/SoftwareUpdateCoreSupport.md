## SoftwareUpdateCoreSupport

> `/System/Library/PrivateFrameworks/SoftwareUpdateCoreSupport.framework/SoftwareUpdateCoreSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x8280` | `0x8360` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x82e7` | `0x83ba` | **`+0xd3`** |
| `__TEXT.__text` | `0x33c90` | `0x33ce8` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x1348` | `0x1378` | **`+0x30`** |

### Other Changes

```diff

-2718.0.5.0.0
+2718.0.12.0.0

-  Symbols:   2220
-  CStrings:  1304
+  Symbols:   2226
+  CStrings:  1311
Symbols:
+ _kSUCoreControllerPreSUStagingOptionalCountKey
+ _kSUCoreControllerPreSUStagingOptionalStagedCountKey
+ _kSUCoreControllerPreSUStagingOptionalStagedSizeKey
+ _kSUCoreControllerPreSUStagingRequiredCountKey
+ _kSUCoreControllerPreSUStagingRequiredStagedCountKey
+ _kSUCoreControllerPreSUStagingRequiredStagedSizeKey
CStrings:
+ "failed to fsync persistence file"
+ "preSUStagingOptionalCount"
+ "preSUStagingOptionalStagedCount"
+ "preSUStagingOptionalStagedSize"
+ "preSUStagingRequiredCount"
+ "preSUStagingRequiredStagedCount"
+ "preSUStagingRequiredStagedSize"
```
