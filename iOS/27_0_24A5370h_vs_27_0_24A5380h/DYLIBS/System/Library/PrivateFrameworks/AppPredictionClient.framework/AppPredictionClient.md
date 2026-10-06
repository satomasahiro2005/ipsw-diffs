## AppPredictionClient

> `/System/Library/PrivateFrameworks/AppPredictionClient.framework/AppPredictionClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x3ca0` | `0x4740` | **`+0xaa0`** |
| `__DATA_DIRTY.__objc_data` | `0x51e0` | `0x4740` | **`-0xaa0`** |
| `__TEXT.__text` | `0x18c1b0` | `0x18c128` | **`-0x88`** |
| `__TEXT.__cstring` | `0x1c2fe` | `0x1c35a` | **`+0x5c`** |
| `__TEXT.__oslogstring` | `0x17966` | `0x179bc` | **`+0x56`** |
| `__AUTH_CONST.__cfstring` | `0x15500` | `0x15520` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x18f1c` | `0x18f2c` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xa0d0` | `0xa0d8` | **`+0x8`** |

### Other Changes

```diff

-661.0.7.0.0
+664.0.2.1.0

-  Functions: 10917
-  Symbols:   16823
-  CStrings:  4814
+  Functions: 10919
+  Symbols:   16824
+  CStrings:  4817
Symbols:
+ +[ATXAppDirectoryCategory categorizationVersion]
Functions:
~ _ATXSlotSetsDeserialize : 1556 -> 1544
+ +[ATXAppDirectoryCategory categorizationVersion]
~ _PPZipUnarchive : 1720 -> 1728
~ -[ATXDefaultHomeScreenItemProducer _initializeCachedWidgetPersonalityToAppScoreCache] : 860 -> 596
+ -[ATXDefaultHomeScreenItemProducer _initializeCachedWidgetPersonalityToAppScoreCache].cold.1
CStrings:
+ "%s: _appLaunchCounts is %@; widget ranking will fall back to no launch-history signal"
+ "-[ATXDefaultHomeScreenItemProducer _initializeCachedWidgetPersonalityToAppScoreCache]"
+ "empty"
```
