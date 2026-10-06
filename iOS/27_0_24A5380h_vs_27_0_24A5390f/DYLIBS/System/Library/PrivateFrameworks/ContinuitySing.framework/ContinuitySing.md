## ContinuitySing

> `/System/Library/PrivateFrameworks/ContinuitySing.framework/ContinuitySing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5d484` | `0x5dc58` | **`+0x7d4`** |
| `__AUTH_CONST.__objc_const` | `0x7260` | `0x7320` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x35d4` | `0x3694` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x60e9` | `0x6169` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x32b9` | `0x3329` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a90` | `0x2af8` | **`+0x68`** |
| `__DATA.__data` | `0x968` | `0x9c8` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x16a8` | `0x16d0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1870` | `0x1888` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x478` | `0x484` | **`+0xc`** |
| `__DATA_CONST.__objc_protolist` | `0x80` | `0x88` | **`+0x8`** |

### Other Changes

```diff

-758.0.0.122.2
+761.0.0.0.3

-  Functions: 1904
-  Symbols:   3021
-  CStrings:  937
+  Functions: 1915
+  Symbols:   3041
+  CStrings:  943
Symbols:
+ -[CSPlaybackManager beginScrubbing]
+ -[CSPlaybackManager isSeekable]
+ -[CSPlaybackManager seekToValue:]
+ -[CSPlaybackManager updateScrubbingValue:]
+ -[CSQueuePlaybackControlsView _updateTimelineInteractivity]
+ -[CSQueuePlaybackControlsView mediaTimelineControl:didChangeValue:]
+ -[CSQueuePlaybackControlsView mediaTimelineControlDidEndChanging:]
+ -[CSQueuePlaybackControlsView mediaTimelineControlWillBeginChanging:]
+ _CSRapportDeviceStatusPairedFlags
+ _OBJC_IVAR_$_CSPlaybackManager._pendingSeekActive
+ _OBJC_IVAR_$_CSPlaybackManager._pendingSeekValue
+ _OBJC_IVAR_$_CSQueuePlaybackControlsView._lastScrubValue
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AVMediaTimelineControlDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_AVMediaTimelineControlDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AVMediaTimelineControlDelegate
+ __OBJC_$_PROTOCOL_REFS_AVMediaTimelineControlDelegate
+ __OBJC_LABEL_PROTOCOL_$_AVMediaTimelineControlDelegate
+ __OBJC_PROTOCOL_$_AVMediaTimelineControlDelegate
+ ___33-[CSPlaybackManager seekToValue:]_block_invoke
+ ___block_descriptor_48_e8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
CStrings:
+ "%s: Requesting seek to %f"
+ "%s: Seek request completed. Request: %@"
+ "%s: error performing seek request: %@ error: %@"
+ "-[CSPlaybackManager seekToValue:]"
+ "-[CSPlaybackManager seekToValue:]_block_invoke"
+ "-[CSPlaybackManager seekToValue:]_block_invoke_2"
```
