## destinationd

> `/System/Library/PrivateFrameworks/MapsSuggestions.framework/destinationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a7c8` | `0x4c2fc` | **`+0x1b34`** |
| `__TEXT.__oslogstring` | `0x46a4` | `0x4d04` | **`+0x660`** |
| `__TEXT.__gcc_except_tab` | `0x3e14` | `0x402c` | **`+0x218`** |
| `__TEXT.__cstring` | `0x6da4` | `0x6fa4` | **`+0x200`** |
| `__TEXT.__objc_methname` | `0x59ec` | `0x5abc` | **`+0xd0`** |
| `__TEXT.__objc_stubs` | `0x49a0` | `0x4a40` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x1e38` | `0x1ea8` | **`+0x70`** |
| `__DATA_CONST.__cfstring` | `0x1ca0` | `0x1d00` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x27f4` | `0x283c` | **`+0x48`** |
| `__TEXT.__objc_methtype` | `0x18be` | `0x18fe` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1838` | `0x1878` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x1818` | `0x1850` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x1310` | `0x1340` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x1a8` | `0x1d8` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x1b4` | `0x1d8` | **`+0x24`** |
| `__TEXT.__const` | `0x418` | `0x438` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x9a0` | `0x9b8` | **`+0x18`** |
| `__DATA.__objc_const` | `0x56f0` | `0x5700` | **`+0x10`** |
| `__DATA.__objc_data` | `0x14b0` | `0x14c0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x6c0` | `0x6d0` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x34c` | `0x35c` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x49d` | `0x4a3` | **`+0x6`** |
| `__TEXT.__swift_as_cont` | `0xc` | `0x10` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0xc` | `0x10` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x8` | `0xc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-2966.30.5.15.8
+2970.30.6.5.7

-  Functions: 1282
-  Symbols:   586
-  CStrings:  2217
+  Functions: 1298
+  Symbols:   591
+  CStrings:  2258
Symbols:
+ _$s16MapsIntelligence0aB30TransportModePredictionManagerC17debugForceRetrain14minimumSamplesySiSg_tYaF
+ _$s16MapsIntelligence0aB30TransportModePredictionManagerC17debugForceRetrain14minimumSamplesySiSg_tYaFTu
+ _$s16MapsIntelligence0aB30TransportModePredictionManagerC32debugPrintPersonalizationMetricsyyF
+ _$sSo13os_log_type_ta0A0E4infoABvgZ
+ _NSLocalizedDescriptionKey
CStrings:
+ "-[MapsSuggestionsPredictionsXPCPeer debugForceRetrainTransportModeModel:]"
+ "-[MapsSuggestionsPredictionsXPCPeer debugForceRetrainTransportModeModel:]_block_invoke"
+ "-[MapsSuggestionsPredictionsXPCPeer debugPrintTransportModePersonalizationMetrics:]"
+ "-[MapsSuggestionsPredictionsXPCPeer debugPrintTransportModePersonalizationMetrics:]_block_invoke"
+ "22:48:57"
+ "Cannot force retrain - manager not initialized"
+ "Cannot print metrics - manager not initialized"
+ "Debug: Forcing retrain from Objective-C wrapper"
+ "Failed to initialize MapsIntelligence transport mode manager"
+ "Jun 15 2026"
+ "Personalization metrics have been printed to the console. Check destinationd logs."
+ "PredictionsServer: Added peer to _peers array, count: %lu"
+ "PredictionsServer: Connection details - pid: %d, euid: %d, egid: %d"
+ "PredictionsServer: Connection resumed successfully"
+ "PredictionsServer: Created exported interface: %@"
+ "PredictionsServer: Created peer: %@"
+ "PredictionsServer: Resuming connection"
+ "PredictionsServer: Returning YES to accept connection"
+ "PredictionsServer: Set exported interface and object on connection"
+ "PredictionsServer: shouldAcceptNewConnection called for connection: %@"
+ "PredictionsXPCPeer: debugForceRetrainTransportModeModel called from connection: %@"
+ "PredictionsXPCPeer: debugPrintTransportModePersonalizationMetrics called from connection: %@"
+ "PredictionsXPCPeer{%@}: Calling debugForceRetrain on tmpManager"
+ "PredictionsXPCPeer{%@}: Calling debugPrintPersonalizationMetrics on tmpManager"
+ "PredictionsXPCPeer{%@}: Creating MITransportModePredictionManager"
+ "PredictionsXPCPeer{%@}: Debug force retrain completed successfully, calling handler"
+ "PredictionsXPCPeer{%@}: Failed to initialize MapsIntelligence transport mode manager"
+ "PredictionsXPCPeer{%@}: Failed to initialize MapsIntelligence transport mode manager: %@"
+ "PredictionsXPCPeer{%@}: Handler called"
+ "PredictionsXPCPeer{%@}: MITransportModePredictionManager created: %@"
+ "PredictionsXPCPeer{%@}: On queue, processing debugPrintTransportModePersonalizationMetrics"
+ "PredictionsXPCPeer{%@}: debugPrintPersonalizationMetrics returned"
+ "Unable to capture strongSelf while trying to print personalization metrics."
+ "com.apple.maps.intelligence"
+ "debugForceRetrain"
+ "debugForceRetrainTransportModeModel:"
+ "debugPrintPersonalizationMetrics"
+ "debugPrintTransportModePersonalizationMetrics:"
+ "effectiveGroupIdentifier"
+ "effectiveUserIdentifier"
+ "processIdentifier"
+ "v24@0:8@?<v@?@\"NSError\">16"
+ "v24@0:8@?<v@?@\"NSString\"@\"NSError\">16"
- "04:14:56"
- "May 28 2026"
```
