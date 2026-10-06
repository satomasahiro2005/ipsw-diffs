## MusicUnderstanding

> `/System/Library/Frameworks/MusicUnderstanding.framework/MusicUnderstanding`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x102e98` | `0xfdf40` | **`-0x4f58`** |
| `__DATA.__bss` | `0xfe90` | `0xf910` | **`-0x580`** |
| `__TEXT.__eh_frame` | `0xbbf4` | `0xb674` | **`-0x580`** |
| `__TEXT.__const` | `0xceb8` | `0xc958` | **`-0x560`** |
| `__AUTH_CONST.__const` | `0x8548` | `0x89a8` | **`+0x460`** |
| `__AUTH.__data` | `0x3da8` | `0x3aa0` | **`-0x308`** |
| `__AUTH_CONST.__objc_const` | `0x3868` | `0x35c8` | **`-0x2a0`** |
| `__TEXT.__constg_swiftt` | `0x44c4` | `0x42b0` | **`-0x214`** |
| `__TEXT.__swift5_typeref` | `0x3a52` | `0x385a` | **`-0x1f8`** |
| `__TEXT.__unwind_info` | `0x5520` | `0x5330` | **`-0x1f0`** |
| `__TEXT.__oslogstring` | `0x66a` | `0x80a` | **`+0x1a0`** |
| `__AUTH_CONST.__auth_got` | `0x15e0` | `0x14b8` | **`-0x128`** |
| `__DATA.__data` | `0x3ea0` | `0x3d78` | **`-0x128`** |
| `__TEXT.__swift5_capture` | `0x63c` | `0x744` | **`+0x108`** |
| `__TEXT.__swift5_reflstr` | `0x40cc` | `0x400c` | **`-0xc0`** |
| `__AUTH.__objc_data` | `0x370` | `0x2d0` | **`-0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x3fe8` | `0x3f5c` | **`-0x8c`** |
| `__TEXT.__swift_as_entry` | `0x3bc` | `0x344` | **`-0x78`** |
| `__TEXT.__swift5_assocty` | `0xc70` | `0xc00` | **`-0x70`** |
| `__TEXT.__swift_as_cont` | `0x664` | `0x610` | **`-0x54`** |
| `__TEXT.__cstring` | `0xda1` | `0xd51` | **`-0x50`** |
| `__TEXT.__swift_as_ret` | `0x3d8` | `0x398` | **`-0x40`** |
| `__TEXT.__swift5_acfuncs` | `0x3c` | `—` | **`-0x3c`** |
| `__TEXT.__swift5_proto` | `0x874` | `0x848` | **`-0x2c`** |
| `__DATA.__common` | `0x140` | `0x128` | **`-0x18`** |
| `__DATA_CONST.__const` | `0x2c0` | `0x2b0` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x160` | `0x150` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c8` | `0x1d8` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x58` | `0x54` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x484` | `0x480` | **`-0x4`** |

### Other Changes

```diff

-12.0.0.0.0
+13.0.0.0.0

-  - /System/Library/PrivateFrameworks/XPCDistributed.framework/XPCDistributed

-  - /usr/lib/swift/libswiftDistributed.dylib

-  Functions: 7805
-  Symbols:   289
-  CStrings:  159
+  Functions: 7745
+  Symbols:   284
+  CStrings:  162
Symbols:
+ _OBJC_CLASS_$_NSProcessInfo
+ _objc_retain_x28
- _objc_release_x9
- _object_getClass
- _swift_distributedActor_remote_initialize
- _swift_distributed_actor_is_remote
- _swift_release_x9
- _swift_task_isCurrentExecutor
- _swift_task_reportUnexpectedExecutor
CStrings:
+ "KeyAnalyzer: invalid accumulate shape (classCount: %ld, accumulator: %ld)"
+ "KeyAnalyzer: invalid flush shape (pending: %ld, accumulator: %ld, classCount: %ld)"
+ "KeyAnalyzer: pendingOverlap %ld not a multiple of classCount %ld"
+ "KeyAnalyzer: prediction scalars %ld too small for %ld frames × %ld classes"
+ "MelSpectrogramConverter: invalid DFT buffer sizes for windowLength %ld (time: %ld, freq: %ld, real: %ld, imag: %ld)"
+ "TESTBOT_IDENTITY_JSON"
- "Instrument activity range processing cancelled"
- "MusicUnderstanding/MelSpectrogramModelInputProvider.swift"
- "com.apple.computationalmusicd"
```
