## AssistantIsland

> `/System/Library/PrivateFrameworks/AssistantIsland.framework/AssistantIsland`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8b608` | `0x8e928` | **`+0x3320`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x2e60` | **`+0x2e60`** |
| `__AUTH.__objc_data` | `0x3ac8` | `0xce8` | **`-0x2de0`** |
| `__DATA_DIRTY.__data` | `—` | `0x2268` | **`+0x2268`** |
| `__AUTH.__data` | `0x1848` | `0x150` | **`-0x16f8`** |
| `__DATA.__bss` | `0x3260` | `0x2960` | **`-0x900`** |
| `__DATA_DIRTY.__bss` | `—` | `0x900` | **`+0x900`** |
| `__DATA.__data` | `0x2470` | `0x1c18` | **`-0x858`** |
| `__TEXT.__cstring` | `0x1ae7` | `0x1db7` | **`+0x2d0`** |
| `__AUTH_CONST.__objc_const` | `0x6570` | `0x66d0` | **`+0x160`** |
| `__TEXT.__swift5_reflstr` | `0x2bdc` | `0x2d2c` | **`+0x150`** |
| `__DATA.__common` | `0x190` | `0x80` | **`-0x110`** |
| `__DATA_DIRTY.__common` | `—` | `0x110` | **`+0x110`** |
| `__TEXT.__oslogstring` | `0x18cc` | `0x17fc` | **`-0xd0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1a48` | `0x1ad8` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x2bd4` | `0x2c4c` | **`+0x78`** |
| `__TEXT.__swift5_fieldmd` | `0x20fc` | `0x2174` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0x2648` | `0x26b0` | **`+0x68`** |
| `__AUTH_CONST.__auth_got` | `0x1320` | `0x1360` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x1b90` | `0x1bd0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x2168` | `0x2138` | **`-0x30`** |
| `__AUTH_CONST.__const` | `0x5de0` | `0x5e08` | **`+0x28`** |
| `__DATA_CONST.__got` | `0xaf0` | `0xb10` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x1604` | `0x1624` | **`+0x20`** |
| `__TEXT.__const` | `0x3e68` | `0x3e80` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x1f75` | `0x1f73` | **`-0x2`** |

### Other Changes

```diff

-67.4.100.0.0
+73.0.5.102.0

-  Functions: 4007
-  Symbols:   2195
-  CStrings:  306
+  Functions: 4051
+  Symbols:   2207
+  CStrings:  324
Symbols:
+ _CGAffineTransformMakeTranslation
+ _CGAffineTransformScale
+ _CGRectIsEmpty
+ _OBJC_CLASS_$_CALayer
+ _OBJC_CLASS_$_CASDFFillEffect
+ _OUTLINED_FUNCTION_200
+ _OUTLINED_FUNCTION_201
+ _OUTLINED_FUNCTION_202
+ _OUTLINED_FUNCTION_203
+ _OUTLINED_FUNCTION_204
+ _OUTLINED_FUNCTION_205
+ ___swift_closure_destructor.395Tm
+ ___swift_closure_destructor.699Tm
+ ___swift_memcpy5_1
+ _kCAFilterDestIn
+ _objc_retain_x11
+ _swift_release_x9
+ _symbolic So10CASDFLayerC
- ___swift_closure_destructor.393Tm
- ___swift_closure_destructor.697Tm
- _get_type_metadata 15AssistantIsland17StageHapticPlayerVSg noncopyable
- _get_type_metadata 15Synchronization5MutexVy15AssistantIsland20WorkspaceEnvironmentC4Peer33_401913C9EB585487E72B1639036E51DELLC13StateSyncInfoVG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDy10Foundation4UUIDVScS12ContinuationVySo27AIWorkspaceEnvironmentStateC_GGG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "%s suppressing transient canvas (drivingFocus=%{bool}d ambient=%{bool}d)"
+ "Siri"
+ "SiriIsland.Appear"
+ "SiriIsland.FirstLayout"
+ "SiriIsland.State.Listening"
+ "SiriIsland.State.Response"
+ "SiriIsland.State.Thinking"
+ "SiriWave.DisplayLinkCreated"
+ "SiriWave.DisplayLinkStarted"
+ "SiriWave.FirstLayout.listeningThinking"
+ "SiriWave.FirstLayout.response"
+ "SiriWave.FirstNonZeroOpacity.listeningThinking"
+ "SiriWave.FirstNonZeroOpacity.response"
+ "SiriWave.FirstTick"
+ "SiriWave.Install.listeningThinking"
+ "SiriWave.Install.response"
+ "SiriWave.TimeToFirstFrame"
+ "SiriWave.Uninstall.listeningThinking"
+ "SiriWave.Uninstall.response"
+ "Standby"
+ "assistant-island-bubble"
+ "assistant-island-pill"
+ "isMapsOnLockScreen"
+ "stage %s latency string update ignored (drivingFocus=%{bool}d ambient=%{bool}d)"
- "%s suppressing transient canvas in driving focus mode"
- "SiriWave: listeningThinkingWaveView - Installed"
- "SiriWave: listeningThinkingWaveView - Uninstalled"
- "SiriWave: responseWaveView - Installed (aboveGlass: %{bool}d)"
- "SiriWave: responseWaveView - Uninstalled"
- "stage %s latency string update ignored — driving focus mode active"
```
