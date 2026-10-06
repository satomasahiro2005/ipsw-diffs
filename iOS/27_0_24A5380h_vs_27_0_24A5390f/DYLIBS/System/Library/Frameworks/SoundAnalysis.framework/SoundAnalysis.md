## SoundAnalysis

> `/System/Library/Frameworks/SoundAnalysis.framework/SoundAnalysis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x326d1c` | `0x341c90` | **`+0x1af74`** |
| `__DATA.__bss` | `0x5ba30` | `0x5e940` | **`+0x2f10`** |
| `__TEXT.__const` | `0x3ebd0` | `0x40550` | **`+0x1980`** |
| `__TEXT.__eh_frame` | `0x2626c` | `0x27610` | **`+0x13a4`** |
| `__AUTH_CONST.__const` | `0x2c010` | `0x2d158` | **`+0x1148`** |
| `__TEXT.__swift5_typeref` | `0x190f9` | `0x19f33` | **`+0xe3a`** |
| `__TEXT.__unwind_info` | `0x13168` | `0x13b58` | **`+0x9f0`** |
| `__DATA.__data` | `0xd288` | `0xd8b0` | **`+0x628`** |
| `__AUTH.__data` | `0x2628` | `0x2c28` | **`+0x600`** |
| `__TEXT.__swift5_fieldmd` | `0xc940` | `0xce9c` | **`+0x55c`** |
| `__TEXT.__constg_swiftt` | `0xf540` | `0xf9e0` | **`+0x4a0`** |
| `__TEXT.__swift5_reflstr` | `0x80d2` | `0x84d2` | **`+0x400`** |
| `__TEXT.__swift5_capture` | `0x55c0` | `0x5980` | **`+0x3c0`** |
| `__TEXT.__cstring` | `0xe69e` | `0xea05` | **`+0x367`** |
| `__AUTH_CONST.__objc_const` | `0x117f8` | `0x11a50` | **`+0x258`** |
| `__TEXT.__oslogstring` | `0x3bce` | `0x3d9e` | **`+0x1d0`** |
| `__TEXT.__swift5_proto` | `0x3668` | `0x37e0` | **`+0x178`** |
| `__DATA_DIRTY.__data` | `0x8c88` | `0x8d88` | **`+0x100`** |
| `__AUTH.__objc_data` | `0x1a28` | `0x1b20` | **`+0xf8`** |
| `__TEXT.__swift_as_cont` | `0xcec` | `0xdb8` | **`+0xcc`** |
| `__TEXT.__swift5_assocty` | `0x1eb8` | `0x1f60` | **`+0xa8`** |
| `__AUTH_CONST.__auth_got` | `0x2590` | `0x2620` | **`+0x90`** |
| `__TEXT.__swift5_types` | `0x12c4` | `0x133c` | **`+0x78`** |
| `__TEXT.__swift_as_ret` | `0x958` | `0x9bc` | **`+0x64`** |
| `__TEXT.__swift_as_entry` | `0x7cc` | `0x820` | **`+0x54`** |
| `__TEXT.__objc_methlist` | `0x5a7c` | `0x5ac4` | **`+0x48`** |
| `__TEXT.__swift5_builtin` | `0x49c` | `0x4d8` | **`+0x3c`** |
| `__DATA.__common` | `0x150` | `0x180` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b60` | `0x1b90` | **`+0x30`** |
| `__DATA_CONST.__got` | `0xf40` | `0xf60` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x412c` | `0x414c` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x920` | `0x938` | **`+0x18`** |
| `__DATA_DIRTY.__objc_data` | `0x4f40` | `0x4f48` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0xf8` | `0x100` | **`+0x8`** |

### Other Changes

```diff

-500.167.0.0.0
+500.185.0.0.0

-  Functions: 27252
-  Symbols:   925
-  CStrings:  1563
+  Functions: 28103
+  Symbols:   923
+  CStrings:  1591
Symbols:
+ _NSFileSize
+ _NSURLContentModificationDateKey
+ _OBJC_CLASS_$_SNFileItem
+ _OBJC_METACLASS_$_SNFileItem
- _CFDictionaryGetValueIfPresent
- _CFGetTypeID
- _CFNumberGetTypeID
- _CFNumberGetValue
- _OBJC_CLASS_$_CUFileItem
- _swift_dynamicCastUnknownClassUnconditional
CStrings:
+ " returned neither a response nor an error"
+ "/var/mobile/Library/Caches/com.apple.soundanalysisd/AudioCaptures"
+ "AudioCapture framework is available"
+ "AudioCapture framework is not available"
+ "AudioCaptureInitialize"
+ "CLAPDetectorIdentifier_"
+ "File server activated at root directory: %{public}s"
+ "FileTransferListFiles"
+ "Initialized AudioCapture framework."
+ "MM-dd-yyyy_HHmmss.SSS"
+ "MM-dd-yyyy_hhmmss.SSS a"
+ "Received file listing request for path: %s"
+ "SoundAnalysis.SNFileItem"
+ "SoundPrintDetectorIdentifier_"
+ "Starting file server at root directory: %{public}s"
+ "USoundPrintDetectorIdentifier_"
+ "[PUB] voice activity detection "
+ "[PUB] voice activity detection %s: fast heartbeat received %ld audio frames"
+ "[PUB] voice activity detection %s: slow heartbeat received %ld audio frames"
+ "[PUB] voice activity detection ("
+ "[PUB] voice activity detection periodic value ("
+ "[SNAudioCapturer] Deleted audio capture %s"
+ "[SNAudioCapturer] Failed to delete audio capture %s: %s"
+ "[SNAudioCapturer] Failed to initialize AudioCapture framework: %@"
+ "[SNAudioCapturer] Failed to read modification date for %s: %s"
+ "audioCaptureMode"
+ "bool SNAudioCaptureInitialize()"
+ "enableHomeSoundRecognitionAudioCaptures"
+ "file sharing request "
+ "getIdentities returned neither identities nor an error"
+ "homeKitIdentifier"
- "Movie Remix: Invalid type for key '%s' in dictionary."
- "Movie Remix: Missing expected key '%s' in dictionary."
- "audiomix_music"
```
