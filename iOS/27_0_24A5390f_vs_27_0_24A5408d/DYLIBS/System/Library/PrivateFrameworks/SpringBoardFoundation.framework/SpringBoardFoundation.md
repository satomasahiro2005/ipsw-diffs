## SpringBoardFoundation

> `/System/Library/PrivateFrameworks/SpringBoardFoundation.framework/SpringBoardFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb9720` | `0xb979c` | **`+0x7c`** |
| `__TEXT.__cstring` | `0xed74` | `0xedba` | **`+0x46`** |
| `__AUTH_CONST.__cfstring` | `0xbf20` | `0xbf40` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x5a0` | `0x5b8` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x1a740` | `0x1a750` | **`+0x10`** |

### Other Changes

```diff

-4630.1.102.0.0
+4636.102.1.0.0

-  CStrings:  2543
+  CStrings:  2545
Functions:
~ _OUTLINED_FUNCTION_10 : 16 -> 8
~ _OUTLINED_FUNCTION_9 : 12 -> 28
~ _OUTLINED_FUNCTION_8 : 8 -> 12
~ _OUTLINED_FUNCTION_20 : 12 -> 20
~ _OUTLINED_FUNCTION_25 -> _OUTLINED_FUNCTION_20 : 28 -> 24
~ _OUTLINED_FUNCTION_20 : 24 -> 16
~ _OUTLINED_FUNCTION_20 -> -[SBFZStackResolver _resolveCaptureButtonFullFidelityEventRequestingScenesOfSortedParticipants:changedHandler:prevailingHandler:] : 16 -> 388
~ -[SBFZStackResolver _resolveCaptureButtonFullFidelityEventRequestingScenesOfSortedParticipants:changedHandler:prevailingHandler:] -> -[SBFZStackResolver _resolveForegroundCaptureApplicationsOfSortedParticipants:changedHandler:prevailingHandler:] : 388 -> 392
~ -[SBFZStackResolver _resolveForegroundCaptureApplicationsOfSortedParticipants:changedHandler:prevailingHandler:] -> -[SBFZStackResolver _resolveAudioCategoriesDisablingVolumeHUDOfSortedParticipants:changedHandler:prevailingHandler:] : 392 -> 432
~ -[SBFZStackResolver _resolveAudioCategoriesDisablingVolumeHUDOfSortedParticipants:changedHandler:prevailingHandler:] -> _OUTLINED_FUNCTION_19 : 432 -> 28
~ _OUTLINED_FUNCTION_11 : 28 -> 16
~ _OUTLINED_FUNCTION_21 : 20 -> 12
~ -[SBApplicationDefaults _bindAndRegisterDefaults] : 936 -> 996
~ _LibSer_SEPControl_Deserialize : 160 -> 200
~ _LibSer_SEPControlResponse_Deserialize : 64 -> 88
CStrings:
+ "SBResizingCapabilityOverrideForApps"
+ "resizingCapabilityOverrideForApps"
```
