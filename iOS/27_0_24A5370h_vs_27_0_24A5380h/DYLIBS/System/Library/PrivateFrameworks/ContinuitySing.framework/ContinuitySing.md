## ContinuitySing

> `/System/Library/PrivateFrameworks/ContinuitySing.framework/ContinuitySing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5c600` | `0x5d484` | **`+0xe84`** |
| `__TEXT.__oslogstring` | `0x30a9` | `0x32b9` | **`+0x210`** |
| `__TEXT.__cstring` | `0x5f59` | `0x60e9` | **`+0x190`** |
| `__DATA_CONST.__const` | `0x15e0` | `0x16a8` | **`+0xc8`** |
| `__AUTH_CONST.__objc_const` | `0x71e0` | `0x7260` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0xb4c` | `0xb94` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x1828` | `0x1870` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x2ea0` | `0x2ee0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a58` | `0x2a90` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x35a4` | `0x35d4` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x9b0` | `0x9d8` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x1420` | `0x1400` | **`-0x20`** |
| `__DATA.__objc_ivar` | `0x468` | `0x478` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xd68` | `0xd70` | **`+0x8`** |

### Other Changes

```diff

-753.0.0.122.3
+758.0.0.122.2

-  Functions: 1886
-  Symbols:   2995
-  CStrings:  924
+  Functions: 1904
+  Symbols:   3021
+  CStrings:  937
Symbols:
+ -[CSPlaybackManager _sendRequest:completion:]
+ -[CSRemoteRequestClient _cancelDeferredMicrophoneActivation]
+ -[CSRemoteRequestClient _scheduleDeferredMicrophoneActivation]
+ -[CSRemoteRequestClient invalidate]
+ -[CSShieldManager _attemptMicrophoneConnectionOnRoute:isRetry:completion:]
+ GCC_except_table15
+ GCC_except_table35
+ GCC_except_table36
+ GCC_except_table44
+ GCC_except_table48
+ GCC_except_table64
+ GCC_except_table79
+ GCC_except_table81
+ GCC_except_table82
+ _FigContinuityCaptureGetUserPreferenceDisabled
+ _MPAVRoutingControllerActiveSystemRouteDidChangeNotification
+ _OBJC_IVAR_$_CSPlaybackManager._didRequestVocalsControlPrepare
+ _OBJC_IVAR_$_CSRemoteRequestClient._deferredMicActivationObserver
+ _OBJC_IVAR_$_CSRemoteRequestClient._deferredMicActivationTimer
+ _OBJC_IVAR_$_CSRemoteRequestClient._didFireDeferredMicActivation
+ ___119-[CSRemoteRequestClient initWithRemoteDisplayIdentifier:participantInfo:disconnectHandler:connectionCompletionHandler:]_block_invoke_4
+ ___35-[CSRemoteRequestClient invalidate]_block_invoke
+ ___45-[CSPlaybackManager _sendRequest:completion:]_block_invoke
+ ___62-[CSRemoteRequestClient _scheduleDeferredMicrophoneActivation]_block_invoke
+ ___62-[CSRemoteRequestClient _scheduleDeferredMicrophoneActivation]_block_invoke_2
+ ___62-[CSRemoteRequestClient _scheduleDeferredMicrophoneActivation]_block_invoke_3
+ ___74-[CSShieldManager _attemptMicrophoneConnectionOnRoute:isRetry:completion:]_block_invoke
+ ___block_descriptor_40_e8_32w_e19_v16?0"MPAVRoute"8lw32l8
+ ___block_descriptor_48_e8_32s40bs_e17_v16?0"NSError"8ls32l8s40l8
+ ___block_descriptor_48_e8_32s40w_e19_v16?0"MPAVRoute"8ls32l8w40l8
+ ___block_descriptor_48_e8_32s40w_e5_v8?0ls32l8w40l8
+ ___block_descriptor_56_e8_32s40s48w_e5_v8?0ls32l8s40l8w48l8
+ ___block_descriptor_57_e8_32s40s48bs_e20_v24?0q8"NSError"16ls32l8s40l8s48l8
- GCC_except_table21
- GCC_except_table41
- GCC_except_table45
- GCC_except_table61
- ___34-[CSPlaybackManager _sendRequest:]_block_invoke
- ___61-[CSShieldManager requestMicrophoneActivationWithCompletion:]_block_invoke_2
- ___block_descriptor_48_e8_32s40bs_e20_v24?0q8"NSError"16ls32l8s40l8
CStrings:
+ " (retry)"
+ "%s: Active route changed and endpoint is now Connected; firing mic activation"
+ "%s: Active route endpoint already Connected; firing mic activation immediately"
+ "%s: Active route endpoint not yet Connected; arming notification observer + 5s watchdog"
+ "%s: Handshake indicates we should turn on the mic - let's defer until the route endpoint is Connected!"
+ "%s: Microphone retry also failed with error: %@"
+ "%s: Microphone retry succeeded after dissociation"
+ "%s: Retrying microphone request after dissociation"
+ "%s: Watchdog (5s) fired; route endpoint never reported Connected — firing mic activation anyway"
+ "%s: requested mic with result %@, error: %@%@"
+ "-[CSPlaybackManager _sendRequest:completion:]"
+ "-[CSPlaybackManager _sendRequest:completion:]_block_invoke"
+ "-[CSPlaybackManager controller:defersResponseReplacement:]_block_invoke_2"
+ "-[CSRemoteRequestClient _scheduleDeferredMicrophoneActivation]_block_invoke"
+ "-[CSRemoteRequestClient _scheduleDeferredMicrophoneActivation]_block_invoke_3"
+ "-[CSRemoteRequestClient initWithRemoteDisplayIdentifier:participantInfo:disconnectHandler:connectionCompletionHandler:]_block_invoke_4"
+ "-[CSShieldManager _attemptMicrophoneConnectionOnRoute:isRetry:completion:]_block_invoke"
+ "-[CSShieldManager _attemptMicrophoneConnectionOnRoute:isRetry:completion:]_block_invoke_2"
+ "Continuity Camera is disabled"
- "%s: Handshake indicates we should turn on the mic - let's do it!"
- "%s: requested mic with result %@, error: %@"
- "-[CSPlaybackManager _sendRequest:]"
- "-[CSPlaybackManager _sendRequest:]_block_invoke"
- "-[CSRemoteRequestClient initWithRemoteDisplayIdentifier:participantInfo:disconnectHandler:connectionCompletionHandler:]_block_invoke_3"
- "-[CSShieldManager requestMicrophoneActivationWithCompletion:]_block_invoke_2"
```
