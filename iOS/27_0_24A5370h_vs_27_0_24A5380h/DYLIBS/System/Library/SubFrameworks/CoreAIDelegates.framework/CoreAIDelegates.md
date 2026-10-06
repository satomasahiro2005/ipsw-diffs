## CoreAIDelegates

> `/System/Library/SubFrameworks/CoreAIDelegates.framework/CoreAIDelegates`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d990` | `0x30100` | **`+0x2770`** |
| `__TEXT.__cstring` | `0x11ad` | `0x13cd` | **`+0x220`** |
| `__TEXT.__eh_frame` | `0x1600` | `0x16f0` | **`+0xf0`** |
| `__AUTH.__data` | `0x330` | `0x3b0` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x5ef` | `0x63e` | **`+0x4f`** |
| `__TEXT.__const` | `0x18b0` | `0x18fc` | **`+0x4c`** |
| `__TEXT.__unwind_info` | `0x938` | `0x980` | **`+0x48`** |
| `__DATA.__data` | `0x5f8` | `0x630` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x6dc` | `0x710` | **`+0x34`** |
| `__AUTH_CONST.__auth_got` | `0xc48` | `0xc70` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x428` | `0x450` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x542` | `0x558` | **`+0x16`** |
| `__DATA_CONST.__got` | `0x2a8` | `0x2b0` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0xc4` | `0xbf` | **`-0x5`** |
| `__TEXT.__swift5_types` | `0x6c` | `0x70` | **`+0x4`** |

### Other Changes

```diff

-3600.73.1.0.0
+3600.75.3.0.0

-  Functions: 758
-  Symbols:   156
-  CStrings:  136
+  Functions: 773
+  Symbols:   155
+  CStrings:  146
Symbols:
- _swift_willThrowTypedImpl
CStrings:
+ " to asset for model at "
+ " to resources for model at "
+ ". Please try specializing again."
+ "An invalid specialized asset was found when applying purgeability settings for "
+ "Could not apply purge conditions "
+ "Encountered unexpected error with specialized asset for "
+ "Failed to apply purge conditions for model at "
+ "Failed to persist external delegate resources"
+ "Failed to remove resource on behalf of "
+ "Unable to apply PurgeConditions as no specialized asset found for "
+ "Updating purgeability settings to "
- " at staging location: "
```
