## SiriUIBridge

> `/System/Library/PrivateFrameworks/SiriUIBridge.framework/SiriUIBridge`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d560` | `0x2d664` | **`+0x104`** |
| `__AUTH_CONST.__objc_const` | `0x5210` | `0x5280` | **`+0x70`** |
| `__TEXT.__cstring` | `0x1fda` | `0x202a` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x250c` | `0x2544` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x980` | `0x9a8` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0xcc0` | `0xce0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xa40` | `0xa48` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x250` | `0x258` | **`+0x8`** |

### Other Changes

```diff

-3600.27.4.0.0
+3605.2.1.0.0

-  Functions: 1759
-  Symbols:   1825
-  CStrings:  242
+  Functions: 1762
+  Symbols:   1830
+  CStrings:  243
Symbols:
+ -[SUIBActionRepresentation mayStartLiveActivity]
+ -[SUIBActionRepresentationMutation mayStartLiveActivity]
+ -[SUIBActionRepresentationMutation setMayStartLiveActivity:]
+ _OBJC_IVAR_$_SUIBActionRepresentation._mayStartLiveActivity
+ _OBJC_IVAR_$_SUIBActionRepresentationMutation._mayStartLiveActivity
+ ___block_descriptor_72_e8_32s40s48s56s64s_e42_v16?0"SUIBActionRepresentationMutation"8ls32l8s40l8s48l8s56l8s64l8
- ___block_descriptor_64_e8_32s40s48s56s_e42_v16?0"SUIBActionRepresentationMutation"8ls32l8s40l8s48l8s56l8
CStrings:
+ "SUIBActionRepresentation toolID: %@, applicationIdentifier: %@, schema: %@, executionStatistic: %@, mayStartLiveActivity: %@"
+ "SUIBActionRepresentation::mayStartLiveActivity"
- "SUIBActionRepresentation toolID: %@, applicationIdentifier: %@, schema: %@, executionStatistic: %@"
```
