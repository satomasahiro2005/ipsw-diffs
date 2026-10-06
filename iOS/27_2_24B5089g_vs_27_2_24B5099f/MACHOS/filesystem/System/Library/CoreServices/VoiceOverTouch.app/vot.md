## vot

> `/System/Library/CoreServices/VoiceOverTouch.app/vot`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x184584` | `0x185ad0` | **`+0x154c`** |
| `__DATA.__bss` | `0x1dc0` | `0x20c0` | **`+0x300`** |
| `__TEXT.__objc_methname` | `0x38cd8` | `0x38ec7` | **`+0x1ef`** |
| `__TEXT.__oslogstring` | `0xa5e7` | `0xa7d1` | **`+0x1ea`** |
| `__TEXT.__const` | `0x1e60` | `0x2010` | **`+0x1b0`** |
| `__TEXT.__objc_stubs` | `0x2a9e0` | `0x2ab60` | **`+0x180`** |
| `__TEXT.__auth_stubs` | `0x3d90` | `0x3e50` | **`+0xc0`** |
| `__DATA_CONST.__cfstring` | `0xea60` | `0xeb00` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x1014d` | `0x101db` | **`+0x8e`** |
| `__TEXT.__objc_methlist` | `0x117dc` | `0x11854` | **`+0x78`** |
| `__DATA.__objc_const` | `0x147f0` | `0x14860` | **`+0x70`** |
| `__DATA.__objc_selrefs` | `0xca80` | `0xcae8` | **`+0x68`** |
| `__DATA_CONST.__auth_got` | `0x1ed8` | `0x1f38` | **`+0x60`** |
| `__DATA.__data` | `0x21b8` | `0x2208` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x5d40` | `0x5d90` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0xbe8` | `0xc34` | **`+0x4c`** |
| `__TEXT.__swift5_assocty` | `0x108` | `0x138` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x2ed0` | `0x2ea4` | **`-0x2c`** |
| `__TEXT.__constg_swiftt` | `0xbcc` | `0xbf4` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x26e8` | `0x2708` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x4b20` | `0x4b40` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x640` | `0x65c` | **`+0x1c`** |
| `__TEXT.__swift5_proto` | `0xa8` | `0xc0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0xdc` | `0xf0` | **`+0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x430` | `0x440` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x7a8` | `0x7b8` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x50e7` | `0x50f5` | **`+0xe`** |
| `__DATA.__objc_ivar` | `0x1560` | `0x156c` | **`+0xc`** |
| `__DATA.__objc_data` | `0x2d08` | `0x2d10` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x84` | `0x88` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2482.13.1.0.0
+2482.13.3.0.0

-  Functions: 7263
-  Symbols:   2349
-  CStrings:  12551
+  Functions: 7286
+  Symbols:   2365
+  CStrings:  12581
Symbols:
+ _$s10Foundation17URLResourceValuesV22UniformTypeIdentifiersE07contentE0AD6UTTypeVSgvg
+ _$s10Foundation17URLResourceValuesVMa
+ _$s10Foundation3URLV14resourceValues7forKeysAA011URLResourceD0VShySo16NSURLResourceKeyaG_tKF
+ _$s10Foundation4DataV10contentsOf7optionsAcA3URLVh_So20NSDataReadingOptionsVtKcfC
+ _$s10Foundation4DataV19_bridgeToObjectiveCSo6NSDataCyF
+ _$s10Foundation4DataV36_unconditionallyBridgeFromObjectiveCyACSo6NSDataCSgFZ
+ _$s22UniformTypeIdentifiers6UTTypeV5imageACvgZ
+ _$s22UniformTypeIdentifiers6UTTypeV8conforms2toSbAC_tF
+ _$s22UniformTypeIdentifiers6UTTypeVMn
+ _$s23AXImageExplorerServices0aB16PresentationTypeO4datayAC10Foundation4DataVcACmFWC
+ _$sSS9UTF16ViewV5countSivg
+ _$ss11_SetStorageC8allocate8capacityAByxGSi_tFZ
+ _NSURLContentTypeKey
+ _OBJC_CLASS_$_AXLiveRecognitionAskParameters
+ _swift_retain
+ _swift_retain_x2
CStrings:
+ "Camera scene description failed: %@"
+ "CameraDescriptionUnavailable"
+ "FOCUS-LINK-TARGET-OFFSCREEN"
+ "Passthrough down at %@, contexts: %@, contextless: %d, fingerType: %ld"
+ "Passthrough drag at {%.1f, %.1f}, contexts: %lu"
+ "Refusing focus: %{public}@ has Dynamic Island content and this element is outside the Island: %@"
+ "SCREEN-CHANGE-RENAMED-IN-PLACE"
+ "Screen is locked. Requesting an unlock alongside the home button press."
+ "Td,N,V_lastUserLinkNavigationTime"
+ "_armScreenChangeDeferralWithPreviousLabel:"
+ "_dispatchBrailleDidPanWithSuccess:elementToken:appToken:direction:lineOffset:displayToken:"
+ "_elementIsInJindoAppOutsideJindoRegion:"
+ "_holdAppOrientationForHostingDisplay:"
+ "_isUserLinkNavigationInFlight"
+ "_lastUserInitiatedFocusTime"
+ "_lastUserLinkNavigationTime"
+ "_panCameFromPlanarDisplay:"
+ "_planarDisplayTokens"
+ "_screenChangeDeferredElementPreviousLabel"
+ "alive=%d"
+ "braille pan direction: %@, success: %@, lineoffset: %@, display: %@"
+ "current"
+ "handleBrailleDidPanLeft:elementToken:appToken:lineOffset:displayToken:"
+ "handleBrailleDidPanRight:elementToken:appToken:lineOffset:displayToken:"
+ "initWithData:"
+ "isAskOnly"
+ "lastUserLinkNavigationTime"
+ "setLastUserLinkNavigationTime:"
+ "setLiveRecognitionAskSessionUsesActivity:"
+ "setRotationCapabilityEnabled:forDisplayID:"
+ "updateElementVisuals drawing cursor for %{public}@ frame %{public}@"
+ "updateElementVisuals skipped. currentElement: %{public}@ explorerElement: %{public}@"
+ "v24@0:8B16I20"
+ "v32@?0@\"NSString\"8@\"NSString\"16@\"NSError\"24"
+ "volumeButtonRecaptureEnabled"
+ "was='%@'"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xb1"
- "PassThroughHandler"
- "_dispatchBrailleDidPanWithSuccess:elementToken:appToken:direction:lineOffset:"
- "braille pan direction: %@, success: %@, lineoffset: %@"
- "handleBrailleDidPanLeft:elementToken:appToken:lineOffset:"
- "handleBrailleDidPanRight:elementToken:appToken:lineOffset:"
- "liveRecognitionVolumeButtonRecaptureEnabled"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xa1"
```
