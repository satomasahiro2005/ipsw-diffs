## SpotlightServices

> `/System/Library/PrivateFrameworks/SpotlightServices.framework/SpotlightServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15fe28` | `0x15ff68` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0x18190` | `0x181c0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xe5f8` | `0xe610` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x8d88` | `0x8d98` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x31f0` | `0x31f8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x15b0` | `0x15b4` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-2451.1.101.0.0
+2454.100.0.0.0

-  Functions: 6456
-  Symbols:   11499
+  Functions: 6458
+  Symbols:   11502
Symbols:
+ -[SearchToolQUSignalsPerTool containingFolderTokensFromQU]
+ -[SearchToolQUSignalsPerTool setContainingFolderTokensFromQU:]
+ _OBJC_IVAR_$_SearchToolQUSignalsPerTool._containingFolderTokensFromQU
+ _kTCCServiceSiriAccess
- _kTCCServiceSiri
Functions:
~ _OUTLINED_FUNCTION_3 : 12 -> 24
+ -[SearchToolQUSignalsPerTool setParsedArgLocationTermsFromQU:]
+ -[SearchToolQUSignalsPerTool uniquePersonsFromLLMQU]
~ -[SearchToolQUSignalsPerTool .cxx_destruct] : 272 -> 284
~ _OUTLINED_FUNCTION_4 : 24 -> 28
~ _OUTLINED_FUNCTION_6 : 28 -> 12
~ _SSGetDisabledBundleSet : 656 -> 928
~ -[SSBullseyeTopHitsManager bullseyeResultSetForTopHit:checkForTopHit:boostSafari:thresholdCounter:existingResults:allowMultipleTopHits:] : 6956 -> 6972
```
