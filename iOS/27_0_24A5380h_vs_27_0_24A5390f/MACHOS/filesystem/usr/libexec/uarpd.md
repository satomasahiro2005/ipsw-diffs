## uarpd

> `/usr/libexec/uarpd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa02bc` | `0xa164c` | **`+0x1390`** |
| `__DATA.__objc_const` | `0x10918` | `0x105e8` | **`-0x330`** |
| `__TEXT.__oslogstring` | `0x8cec` | `0x8f0f` | **`+0x223`** |
| `__TEXT.__cstring` | `0xac00` | `0xadf9` | **`+0x1f9`** |
| `__TEXT.__objc_stubs` | `0xa360` | `0xa520` | **`+0x1c0`** |
| `__TEXT.__objc_methname` | `0xf377` | `0xf1f2` | **`-0x185`** |
| `__DATA.__objc_selrefs` | `0x30e8` | `0x3160` | **`+0x78`** |
| `__DATA_CONST.__const` | `0x10a0` | `0x1110` | **`+0x70`** |
| `__DATA.__objc_ivar` | `0xb90` | `0xb30` | **`-0x60`** |
| `__TEXT.__unwind_info` | `0x2318` | `0x2378` | **`+0x60`** |
| `__DATA.__objc_data` | `0x3c00` | `0x3c50` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x8678` | `0x86a8` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x2a49` | `0x2a72` | **`+0x29`** |
| `__DATA_CONST.__cfstring` | `0x53e0` | `0x5400` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x1ce4` | `0x1cf6` | **`+0x12`** |
| `__DATA_CONST.__objc_classlist` | `0x600` | `0x608` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x5e8` | `0x5f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-1587.0.21.0.0
+1587.0.27.0.0

-  Functions: 3910
-  Symbols:   228
-  CStrings:  4906
+  Functions: 3928
+  Symbols:   229
+  CStrings:  4921
Symbols:
+ _NSURLContentModificationDateKey
CStrings:
+ "%02ld-%02ld-%02ld"
+ "%04ld-%02ld-%02ld"
+ "%s: All ripe files pruned at %@"
+ "%s: Failed to create pruner for %@"
+ "%s: Failed to instantiate UARPSuperBinaryPayloadLayer3 at index %lu for %@"
+ "%s: Hit max prunings at %@"
+ "%s: Nothing to prune at %@"
+ "%s: Pruned %lu files / directories this iteration"
+ "%s: Pruning all directories"
+ "%s: Pruning all files under %@"
+ "%s: Set pruning timer with start time of %llu, interval time %llu, leeway time %llu"
+ "%s: Stop pruning timer"
+ "%s: Totally pruned %lu files / directories"
+ "%s: could not instantiate UARPSuperBinaryLayer3 for tag %@ on endpoint %@"
+ "%s: could not instantiate UARPSuperBinaryPayloadLayer3 for asset %@ on endpoint %@"
+ "%s: for pruning %@"
+ "%s: processSuperBinaryPropertyList: failed to process"
+ "-[UARPEndpointLayer3(Layer2EndpointCallbacks) layer2CallbackUnsolicitedDynamicAssetOffered:assetTag:]_block_invoke"
+ "-[UARPPruner prune]"
+ "-[UARPPrunerManager addPrunerWithFolderPath:prunerType:maxFileAge:]"
+ "-[UARPPrunerManager pruneAssets]_block_invoke"
+ "-[UARPPrunerManager pruneDatabaseEntries]_block_invoke"
+ "-[UARPPrunerManager prunePacketCaptures]_block_invoke"
+ "-[UARPPrunerManager startPruning]_block_invoke"
+ "-[UARPPrunerManager stopPruningInternal]"
+ "-[UARPPrunerManager timerFired]"
+ "@\"UARPPrunerManager\""
+ "@40@0:8@16Q24d32"
+ "File %@ is not old enough to prune; last modified date %@"
+ "PLST"
+ "Pruned Expired File at %@; last modified date %@"
+ "Q32@0:8@16@24"
+ "TQ,R,V_prunerType"
+ "UARPPrunerManager"
+ "_pruneInterval"
+ "_prunerManager"
+ "_prunerType"
+ "_pruners"
+ "addPrunerWithFolderPath:prunerType:maxFileAge:"
+ "endpointControllerStartPruning"
+ "enumeratorAtURL:includingPropertiesForKeys:options:errorHandler:"
+ "getResourceValue:forKey:error:"
+ "initWithPruneInterval:"
+ "initWithURL:prunerType:maxFileAge:"
+ "processSuperBinaryPropertyList:"
+ "processURL:pruneBaseTime:"
+ "prune"
+ "pruneAll"
+ "pruneAssets"
+ "pruneDatabaseEntries"
+ "pruneNow"
+ "prunePacketCaptures"
+ "prunerType"
+ "q24@?0@\"NSURL\"8@\"NSURL\"16"
+ "siriAssetsFolder"
+ "sortedArrayUsingComparator:"
+ "stopPruningInternal"
+ "timerFired"
+ "v40@0:8@16Q24d32"
- "%s: Error creating payload at index %lu"
- "%s: Failed to create payload at index %lu"
- "@\"UARPPruner\""
- "@32@0:8@16d24"
- "Evaluate %@ for pruning"
- "File %@ is not old enough to prune"
- "Nothing left to prune, stopping pruning for %@"
- "Pruning Expired File at %@"
- "T@\"NSString\",R,V_analyticsAssetsFolder"
- "T@\"NSString\",R,V_assetsFolder"
- "T@\"NSString\",R,V_cachedAssetsFolder"
- "T@\"NSString\",R,V_crashAssetsFolder"
- "T@\"NSString\",R,V_endpointDatabaseFolder"
- "T@\"NSString\",R,V_heySiriAssetsFolder"
- "T@\"NSString\",R,V_logsAssetsFolder"
- "T@\"NSString\",R,V_mappedAnalyticsAssetsFolder"
- "T@\"NSString\",R,V_packetCaptureFolder"
- "T@\"NSString\",R,V_personalizationAssetsFolder"
- "T@\"NSString\",R,V_sysdiagnoseApprovedFolder"
- "T@\"NSString\",R,V_sysdiagnoseFolder"
- "T@\"NSString\",R,V_tmapDatabaseFolder"
- "T@\"NSString\",R,V_voiceAssistAssetsFolder"
- "_analyticsAssetsPruner"
- "_assetsPruner"
- "_cachedAssetsPruner"
- "_crashAssetsPruner"
- "_endpointDatabasePruner"
- "_heySiriAssetsPruner"
- "_logsAssetsPruner"
- "_mappedAnalyticsAssetsPruner"
- "_packetCapturePruner"
- "_personalizationAssetsPruner"
- "_pruneBaseTime"
- "_sysdiagnoseApprovedPruner"
- "_sysdiagnosePruner"
- "_tmapDatabasePruner"
- "_voiceAssistAssetsPruner"
- "cancelTimer"
- "date"
- "initWithURL:maxFileAge:"
- "timer interval for pruning %@"
- "timerInterval"
- "yyyy-MM-dd-HH-mm-ss"
- "yyyy-MM-dd-hh-mm-ss"
```
