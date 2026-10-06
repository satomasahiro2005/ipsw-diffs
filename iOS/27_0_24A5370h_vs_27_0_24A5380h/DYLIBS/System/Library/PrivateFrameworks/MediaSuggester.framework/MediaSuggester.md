## MediaSuggester

> `/System/Library/PrivateFrameworks/MediaSuggester.framework/MediaSuggester`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80c4c` | `0x8313c` | **`+0x24f0`** |
| `__TEXT.__eh_frame` | `0x3674` | `0x3834` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x2004` | `0x21a4` | **`+0x1a0`** |
| `__DATA.__bss` | `0x3880` | `0x3a00` | **`+0x180`** |
| `__TEXT.__const` | `0x3790` | `0x3890` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x239c` | `0x247c` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x1f38` | `0x1fc0` | **`+0x88`** |
| `__AUTH_CONST.__const` | `0x59c0` | `0x5a28` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0xb88` | `0xbc8` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x183c` | `0x1874` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0xe58` | `0xe84` | **`+0x2c`** |
| `__DATA.__data` | `0xf38` | `0xf58` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1616` | `0x1636` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x608` | `0x620` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x191a` | `0x192e` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x264` | `0x278` | **`+0x14`** |
| `__AUTH.__data` | `0x1d00` | `0x1cf0` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x1c0` | `0x1cc` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x148` | `0x154` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x14c` | `0x154` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x1c54` | `0x1c58` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x108` | `0x10c` | **`+0x4`** |

### Other Changes

```diff

-87.0.1.0.0
+90.0.0.0.0

-  Functions: 3796
-  Symbols:   340
-  CStrings:  391
+  Functions: 3850
+  Symbols:   343
+  CStrings:  405
Symbols:
+ _OBJC_CLASS_$_LNActionParameterMetadata
+ _OBJC_CLASS_$_LNAssistantContext
+ _OBJC_CLASS_$_LNSystemContext
CStrings:
+ "AlgorithmicRadioStationEntity"
+ "AlgorithmicStationSiriEntity"
+ "ArtistSiriEntity"
+ "ConnectToSpeaker: completed for %s"
+ "ConnectToSpeaker: no action metadata for %s/%s"
+ "ConnectToSpeaker: routing %s to outputDeviceUIDs=%s session=%s"
+ "ConnectToSpeakerIntent"
+ "MediaControlsDevice"
+ "PlaylistSiriEntity"
+ "Translating donated entity type '%s' -> '%s' for %s fallback"
+ "com.apple.MediaRemoteAppIntentsExtension"
+ "connect(toOutputDeviceUIDs:applicationBundleID:sessionIdentifier:requestIdentifier:)"
+ "execute(outputDeviceUIDs:)"
+ "executeWithStoredBundleID(_:outputDeviceUIDs:)"
```
