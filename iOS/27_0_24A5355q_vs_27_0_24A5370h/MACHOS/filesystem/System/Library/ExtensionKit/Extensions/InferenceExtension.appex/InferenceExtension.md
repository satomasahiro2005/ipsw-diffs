## InferenceExtension

> `/System/Library/ExtensionKit/Extensions/InferenceExtension.appex/InferenceExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8750` | `0x92d8` | **`+0xb88`** |
| `__TEXT.__auth_stubs` | `0x6f0` | `0x740` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x1f9` | `0x229` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x380` | `0x3a8` | **`+0x28`** |
| `__DATA.__data` | `0x158` | `0x160` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x148` | `0x150` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.32.1.0.0
+3600.40.1.0.0

-  Symbols:   497
-  CStrings:  29
+  Symbols:   503
+  CStrings:  30
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/PostSiriEngagement/install/TempContent/Objects/PostSiriEngagement.build/InferenceExtension.build/Objects-normal/arm64e/InferenceExtension-7a2c2492b148cc8e8b8c1f5f6d46c560.o
+ _$s18InferenceExtensionAAC6doWork7context20LighthouseBackground12MLHostResultCAE0hB7ContextC_tYaFTQ10_
+ _$sS2cEs5ErrorsWL
+ _$sS2cEycfC
+ _$sScEs5ErrorsMc
+ _objc_retain_x24
+ _swift_allocError
+ _swift_release_x8
+ _swift_willThrow
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/PostSiriEngagement/install/TempContent/Objects/PostSiriEngagement.build/InferenceExtension.build/Objects-normal/arm64e/InferenceExtension-859f3c64bee4f51cfe6f5b2c5a0bd3e7.o
- _$s18InferenceExtensionAAC011runOnDeviceA033_7486101AE976CDEF82411786A6A08A1BLL14taskParametersSb010LighthouseA00maB6ConfigV_tYaKFTf4nnd_nTQ5_
- _$s19LighthouseInference0B5StateO25evaluatorSessionCompletedyA2CmFWC
CStrings:
+ "MLHost Task failed: TaskId: %s, TaskName: %s"
```
