## findmylocated

> `/usr/libexec/findmylocated`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x58cc9c` | `0x58fc7c` | **`+0x2fe0`** |
| `__TEXT.__oslogstring` | `0x18fcc` | `0x191ac` | **`+0x1e0`** |
| `__TEXT.__cstring` | `0xb922` | `0xb9b2` | **`+0x90`** |
| `__DATA.__data` | `0xf050` | `0xf080` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1d48` | `0x1d70` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x8fdc` | `0x9000` | **`+0x24`** |
| `__TEXT.__const` | `0x20988` | `0x209a8` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x7e5d` | `0x7e7d` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x18270` | `0x18288` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x72c2` | `0x72d8` | **`+0x16`** |
| `__TEXT.__auth_stubs` | `0x5cf0` | `0x5d00` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x4d74` | `0x4d84` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x43f4` | `0x4400` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x2e80` | `0x2e88` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x487f0` | `0x487e8` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x16e8` | `0x16e0` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x2864` | `0x285c` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x16358` | `0x16350` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-141.30.6.14.7
+141.30.6.14.11

-  Functions: 17533
-  Symbols:   2879
-  CStrings:  3845
+  Functions: 17535
+  Symbols:   2884
+  CStrings:  3851
Symbols:
+ _$s11SwiftSQLite3RowV3getyxAA10ExpressionVyxGKAA5ValueRzlF
+ _$s12FindMyLocate21LabelLocationResponseV5label0G2IdACSSSg_AFtcfC
+ _$s12FindMyLocate8LocationV8latitude9longitude18horizontalAccuracy08verticalH05speed8altitude5floor9timestamp9placemark12locationType19motionActivityState11customLabel7labelIdACSd_S5dSi10Foundation4DateVAA9PlaceMarkVSgAA0dP0OAA06MotionrS0OSSSgA_tcfC
+ _$s15FindMyMessaging11DestinationV0D4TypeO6deviceyA2EmFWC
+ _$s15FindMyMessaging11DestinationV0D4TypeO8apsTokenyA2EmFWC
+ _$s15FindMyMessaging11DestinationV0D4TypeO9selfTokenyA2EmFWC
+ _$s15FindMyMessaging11DestinationV0D4TypeOSQAAMc
- _$s12FindMyLocate21LabelLocationResponseV5labelACSSSg_tcfC
- _$s12FindMyLocate8LocationV8latitude9longitude18horizontalAccuracy08verticalH05speed8altitude5floor9timestamp9placemark12locationType19motionActivityState11customLabelACSd_S5dSi10Foundation4DateVAA9PlaceMarkVSgAA0dP0OAA06MotionrS0OSSSgtcfC
CStrings:
+ "NIFanout: findee captured peerDestination deviceScoped: %{bool,public}d from %{private,mask.hash}s"
+ "NIFanout: finder captured peerDestination deviceScoped: %{bool,public}d from %{private,mask.hash}s"
+ "NIFanout: sending findingConfigData deviceScoped: %{bool,public}d to %{private,mask.hash}s for handle %{private,mask.hash}s"
+ "NIFanout: sending findingToken deviceScoped: %{bool,public}d to %{private,mask.hash}s for handle %{private,mask.hash}s"
+ "locationLabelId"
+ "receiveFindingConfig(_:from:)"
+ "receivedConfigData(_:tokenData:replyHandle:peerDestination:)"
+ "respondToFindingTokenRequest(_:replyTo:)"
+ "sendConfigData(_:peerToken:peerHandle:ownerHandle:peerDestination:)"
+ "startFindeeRangingForConfigData(with:replyHandle:configData:peerDestination:)"
+ "startFinderRangingForConfigData(with:peerHandle:ownerHandle:peerDestination:)"
- "receiveFindingConfig(_:)"
- "receivedConfigData(_:tokenData:replyHandle:)"
- "respondToFindingTokenRequest(_:)"
- "sendConfigData(_:peerToken:peerHandle:ownerHandle:)"
- "startFindeeRangingForConfigData(with:replyHandle:configData:)"
```
