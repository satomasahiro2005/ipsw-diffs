## AVSystemRouting

> `/System/Library/Frameworks/AVSystemRouting.framework/AVSystemRouting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21010` | `0x211cc` | **`+0x1bc`** |
| `__TEXT.__oslogstring` | `0x5c1` | `0x635` | **`+0x74`** |
| `__AUTH_CONST.__objc_const` | `0x2068` | `0x2088` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x758` | `0x770` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x210` | `0x218` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xc68` | `0xc60` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xa8` | `0xac` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-360.58.1.0.0
+360.63.1.11.2

-  Symbols:   889
-  CStrings:  125
+  Symbols:   891
+  CStrings:  126
Symbols:
+ _OBJC_CLASS_$_NSMutableSet
+ _OBJC_IVAR_$_AVCustomRoutingSystemControllerSystemCastingImpl.mDeviceIDs
Functions:
~ +[AVSystemRouteController isSupportedExtensionAvailable] : 432 -> 692
~ -[AVSystemRouteSession _invalidate] : 312 -> 308
~ -[AVSystemRoutePlaybackControl _registerForMediaSourceObservation] : 260 -> 256
~ -[AVSystemRoutePlaybackControl _unregisterFromMediaSourceObservation] : 248 -> 244
~ -[AVSystemMediaSourceExtensionImpl _updateMediaSourceData:] : 328 -> 324
~ -[AVSystemMediaSourceExtensionImpl segments] : 308 -> 304
~ -[AVSystemMediaSourceExtensionImpl seekableTimeRanges] : 360 -> 356
~ -[AVSystemMediaSourceExtensionImpl audioOptions] : 308 -> 304
~ -[AVSystemMediaSourceExtensionImpl legibleOptions] : 308 -> 304
~ -[AVSRSerializationHelper metadataFromDictionary:] : 504 -> 500
~ -[AVSRSerializationHelper dictionaryFromError:] : 900 -> 896
~ -[AVSRSerializationHelper errorFromDictionary:] : 700 -> 696
~ -[AVCustomRoutingSystemControllerSystemCastingImpl routeSymbolName] : 260 -> 256
~ -[AVCustomRoutingSystemControllerSystemCastingImpl routeDisplayName] : 260 -> 256
~ -[AVCustomRoutingSystemControllerSystemCastingImpl protocolType] : 260 -> 256
~ -[AVCustomRoutingSystemControllerSystemCastingImpl initWithParentController:] : 1184 -> 1180
~ -[AVCustomRoutingSystemControllerSystemCastingImpl dealloc] : 160 -> 168
~ _OUTLINED_FUNCTION_10 : 12 -> 16
~ _OUTLINED_FUNCTION_12 : 44 -> 20
~ _OUTLINED_FUNCTION_13 : 44 -> 12
~ _OUTLINED_FUNCTION_14 : 16 -> 44
~ _OUTLINED_FUNCTION_15 : 24 -> 44
~ _OUTLINED_FUNCTION_16 : 12 -> 24
~ _OUTLINED_FUNCTION_17 : 32 -> 24
~ _OUTLINED_FUNCTION_18 : 32 -> 12
~ _OUTLINED_FUNCTION_20 : 24 -> 32
~ sub_23cfe72b8 -> sub_23e15c37c : 1296 -> 1292
~ sub_23cfeadb8 -> sub_23e15fe78 : 4472 -> 4532
~ sub_23cfebf30 -> sub_23e16102c : 796 -> 780
~ sub_23cfefbf8 -> sub_23e164ce4 : 700 -> 696
~ sub_23cff0594 -> sub_23e16567c : 700 -> 696
~ sub_23cff3810 -> sub_23e1688f4 : 764 -> 760
~ sub_23cff408c -> sub_23e16916c : 956 -> 964
~ sub_23cff8aec -> sub_23e16dbd4 : 580 -> 592
~ sub_23cff8d30 -> sub_23e16de24 : 176 -> 188
~ sub_23cff8de0 -> sub_23e16dee0 : 540 -> 552
~ ___swift_closure_destructor : 140 -> 148
~ sub_23cffb080 -> sub_23e170194 : 228 -> 232
~ sub_23cfff678 -> sub_23e174790 : 412 -> 388
~ sub_23cfff814 -> sub_23e174914 : 256 -> 276
~ -[AVCustomRoutingSystemControllerSystemCastingImpl _sendEvent:] : 324 -> 332
~ -[AVCustomRoutingSystemControllerSystemCastingImpl _updateSystemRoutingState] : 1192 -> 1392
~ -[AVCustomRoutingSystemControllerSystemCastingImpl setMediaSourceData:forKey:] : 252 -> 244
~ -[AVCustomRoutingSystemControllerSystemCastingImpl mediaSourceDataForKeys:completionHandler:] : 332 -> 324
~ -[AVCustomRoutingSystemControllerSystemCastingImpl didReceiveData:forApplicationID:] : 424 -> 396
~ -[AVCustomRoutingSystemControllerSystemCastingImpl didReceiveMediaSourceUpdate:] : 424 -> 428
CStrings:
+ "-AVCustomRoutingSystemController- %s: Underlying routes changed (protocolChanged=%d, devicesChanged=%d). Sending deactivate for old route and activate for new route."
+ "-AVSystemRouteController- %s: unexpected error: MDESupportsUniversalURLPlayback is not an NSNumber"
- "-AVCustomRoutingSystemController- %s: ProtocolID changed from %{public}@ to %{public}@. Sending deactivate for old route and activate for new route."
```
