## mediaanalysisd

> `/System/Library/PrivateFrameworks/MediaAnalysis.framework/mediaanalysisd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2315f8` | `0x239804` | **`+0x820c`** |
| `__TEXT.__gcc_except_tab` | `0x37060` | `0x37f6c` | **`+0xf0c`** |
| `__TEXT.__cstring` | `0x13d44` | `0x14134` | **`+0x3f0`** |
| `__TEXT.__unwind_info` | `0x8760` | `0x8aa8` | **`+0x348`** |
| `__DATA_CONST.__const` | `0x8690` | `0x8438` | **`-0x258`** |
| `__DATA_CONST.__cfstring` | `0x9f20` | `0xa0c0` | **`+0x1a0`** |
| `__TEXT.__objc_stubs` | `0x18f60` | `0x190a0` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0xb700` | `0xb7e8` | **`+0xe8`** |
| `__TEXT.__objc_methname` | `0x21d35` | `0x21df5` | **`+0xc0`** |
| `__DATA.__objc_selrefs` | `0x6ba0` | `0x6bf0` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x30b01` | `0x30b41` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x38d0` | `0x38f0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1c80` | `0x1c90` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2978` | `0x2980` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 7007
-  Symbols:   2339
-  CStrings:  10620
+  Functions: 7076
+  Symbols:   2342
+  CStrings:  10645
Symbols:
+ _NSSelectorFromString
+ _OBJC_CLASS_$_NSInvocation
+ __os_crash
CStrings:
+ "%@: %@"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Background/MADPhotosFaceFastPassProcessingTask.mm"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADProgressReporterProcessingTask.mm"
+ "Add MAD_WATCHDOG_CRASH_CALLBACK_METHOD to your class - %@"
+ "Biome appears to be hung. Reported: %s. Began operation at %@"
+ "Compilation of the text encoder. Reported: %s. Began operation at %@"
+ "Compilation of the visual encoder. Reported: %s. Began operation at %@"
+ "Daemon appears to be hung (%@); self-terminating"
+ "Dlib appears to be hung. Began operation at %@"
+ "Latest Watchdog petting at %s[%d]"
+ "MAD_PET_SHARED_WATCHDOG_WITH_CALLBACK object deallocated - %@"
+ "Model initialization appears to be hung. Reported: %s. Began preheat at %@"
+ "Person promoting appears to be hung. Reported: %s. Began operation at %@"
+ "Photos appears to be hung. Reported: %s. Began operation at %@"
+ "TextUnderstanding appears to be hung. Reported: %s. Began operation at %@"
+ "Watchdog Timeout"
+ "captureCrashWithKnownTimeoutRisk:"
+ "currentTimeoutRiskAndStartTime:"
+ "dumpBreadcrumps"
+ "invocationWithMethodSignature:"
+ "invoke"
+ "methodSignatureForSelector:"
+ "setArgument:atIndex:"
+ "setSelector:"
+ "setTarget:"
+ "timeoutCrashWithMessage:"
- "Daemon appears to be hung; self-terminating"
```
