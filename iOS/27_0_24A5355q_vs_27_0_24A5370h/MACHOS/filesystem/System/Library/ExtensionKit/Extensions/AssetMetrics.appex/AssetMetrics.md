## AssetMetrics

> `/System/Library/ExtensionKit/Extensions/AssetMetrics.appex/AssetMetrics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3984` | `0x48ec` | **`+0xf68`** |
| `__TEXT.__eh_frame` | `0x240` | `0x340` | **`+0x100`** |
| `__TEXT.__auth_stubs` | `0x610` | `0x6f0` | **`+0xe0`** |
| `__DATA_CONST.__auth_got` | `0x308` | `0x378` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x2d0` | `0x320` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x218` | `0x268` | **`+0x50`** |
| `__TEXT.__const` | `0x4ca` | `0x4fa` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x144` | `0x172` | **`+0x2e`** |
| `__TEXT.__swift5_capture` | `—` | `0x2c` | **`+0x2c`** |
| `__TEXT.__cstring` | `0xad` | `0xcd` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x1d0` | `0x1e8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x70` | `0x88` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x14` | `0x20` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x14` | `0x20` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x14` | `0x20` | **`+0xc`** |
| `__DATA.__data` | `0x1f8` | `0x200` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0xf4` | `0xec` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3600.2.1.0.0
+3600.3.1.0.0

-  - /System/Library/PrivateFrameworks/AssetMetricsCore.framework/AssetMetricsCore
+  - /System/Library/PrivateFrameworks/AssetMetricsCoreV2.framework/AssetMetricsCoreV2

+  - /System/Library/PrivateFrameworks/DeepThoughtBiomeFoundation.framework/DeepThoughtBiomeFoundation

-  Functions: 147
-  Symbols:   85
-  CStrings:  16
+  Functions: 168
+  Symbols:   93
+  CStrings:  17
Symbols:
+ _objc_release_x8
+ _objc_retain_x26
+ _swift_continuation_await
+ _swift_continuation_init
+ _swift_deallocObject
+ _swift_release_x8
+ _swift_task_create
+ _swift_unknownObjectRelease
CStrings:
+ "doWork(context:)"
```
