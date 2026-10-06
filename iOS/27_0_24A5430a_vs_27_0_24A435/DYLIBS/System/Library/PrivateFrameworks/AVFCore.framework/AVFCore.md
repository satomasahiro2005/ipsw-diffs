## AVFCore

> `/System/Library/PrivateFrameworks/AVFCore.framework/AVFCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c9db4` | `0x1c9de0` | **`+0x2c`** |
| `__AUTH_CONST.__auth_got` | `0x2048` | `0x2040` | **`-0x8`** |

### Other Changes

```diff

-  Symbols:   23941
+  Symbols:   23940
Symbols:
- _swift_release_x9
Functions:
~ -[AVTelemetryMonitor incrementBucketCount:executionTime:] : 420 -> 424
~ sub_196817580 -> sub_19690d584 : 748 -> 756
~ sub_196817d58 -> sub_19690dd64 : 404 -> 408
~ sub_196818564 -> sub_19690e574 : 748 -> 756
~ sub_196818b40 -> sub_19690eb58 : 404 -> 408
~ sub_19681b1fc -> sub_196911218 : 748 -> 756
~ sub_19681b9f4 -> sub_196911a18 : 404 -> 408
~ sub_19681cc70 -> sub_196912c98 : 748 -> 756
~ sub_19681d258 -> sub_196913288 : 404 -> 408
~ -[AVSampleBufferRenderSynchronizer dealloc] : 728 -> 736
~ -[AVSampleBufferRenderSynchronizer setRate:] : 400 -> 392
~ -[AVSampleBufferRenderSynchronizer setRate:time:] : 388 -> 380
~ -[AVSampleBufferRenderSynchronizer setRate:time:atHostTime:error:] : 492 -> 484
~ -[AVSampleBufferRenderSynchronizer(AVSampleBufferRenderSynchronizerRendererManagement) removeRenderer:atTime:completionHandler:] : 692 -> 700
```
