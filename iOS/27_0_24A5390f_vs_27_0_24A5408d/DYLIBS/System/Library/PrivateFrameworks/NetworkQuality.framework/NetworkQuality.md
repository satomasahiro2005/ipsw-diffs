## NetworkQuality

> `/System/Library/PrivateFrameworks/NetworkQuality.framework/NetworkQuality`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fec0` | `0x201dc` | **`+0x31c`** |
| `__AUTH_CONST.__objc_const` | `0x4460` | `0x4550` | **`+0xf0`** |
| `__AUTH_CONST.__cfstring` | `0x1de0` | `0x1e60` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x1d10` | `0x1d88` | **`+0x78`** |
| `__TEXT.__cstring` | `0x2c3d` | `0x2c84` | **`+0x47`** |
| `__DATA_CONST.__objc_selrefs` | `0x1340` | `0x1380` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x510` | `0x524` | **`+0x14`** |
| `__TEXT.__const` | `0x198` | `0x1a8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x690` | `0x698` | **`+0x8`** |

### Other Changes

```diff

-220.0.0.0.0
+224.0.0.0.0

-  Functions: 716
-  Symbols:   1508
-  CStrings:  572
+  Functions: 726
+  Symbols:   1523
+  CStrings:  576
Symbols:
+ -[NetworkQualityConfiguration commandLineArguments]
+ -[NetworkQualityConfiguration draftVersion]
+ -[NetworkQualityConfiguration intervalDuration]
+ -[NetworkQualityConfiguration maxProbesPerSecond]
+ -[NetworkQualityConfiguration setCommandLineArguments:]
+ -[NetworkQualityConfiguration setDraftVersion:]
+ -[NetworkQualityConfiguration setIntervalDuration:]
+ -[NetworkQualityConfiguration setMaxProbesPerSecond:]
+ -[NetworkQualityResult draftVersion]
+ -[NetworkQualityResult setDraftVersion:]
+ _OBJC_IVAR_$_NetworkQualityConfiguration._commandLineArguments
+ _OBJC_IVAR_$_NetworkQualityConfiguration._draftVersion
+ _OBJC_IVAR_$_NetworkQualityConfiguration._intervalDuration
+ _OBJC_IVAR_$_NetworkQualityConfiguration._maxProbesPerSecond
+ _OBJC_IVAR_$_NetworkQualityResult._draftVersion
CStrings:
+ "commandLineArguments"
+ "draftVersion"
+ "intervalDuration"
+ "maxProbesPerSecond"
```
