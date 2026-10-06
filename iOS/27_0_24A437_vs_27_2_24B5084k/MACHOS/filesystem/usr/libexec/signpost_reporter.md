## signpost_reporter

> `/usr/libexec/signpost_reporter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaee0` | `0xaa18` | **`-0x4c8`** |
| `__TEXT.__oslogstring` | `0xc26` | `0x99d` | **`-0x289`** |
| `__TEXT.__cstring` | `0x12b6` | `0x1216` | **`-0xa0`** |
| `__TEXT.__objc_stubs` | `0x1800` | `0x1780` | **`-0x80`** |
| `__TEXT.__objc_methname` | `0x1ab3` | `0x1a63` | **`-0x50`** |
| `__DATA_CONST.__cfstring` | `0x1700` | `0x16c0` | **`-0x40`** |
| `__TEXT.__auth_stubs` | `0x910` | `0x8d0` | **`-0x40`** |
| `__TEXT.__gcc_except_tab` | `0x3f8` | `0x3cc` | **`-0x2c`** |
| `__DATA_CONST.__const` | `0x6e8` | `0x6c0` | **`-0x28`** |
| `__DATA_CONST.__auth_got` | `0x498` | `0x478` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x650` | `0x638` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x150` | `0x148` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x310` | `0x308` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-203.0.0.0.0
+205.0.0.0.0

-  Functions: 266
-  Symbols:   210
-  CStrings:  596
+  Functions: 265
+  Symbols:   205
+  CStrings:  580
Symbols:
+ _objc_retain_x27
- _OBJC_CLASS_$_AnalyticsConfigurationObserver
- _dispatch_semaphore_create
- _dispatch_semaphore_signal
- _dispatch_semaphore_wait
- _dispatch_time
- _os_variant_has_internal_diagnostics
Functions:
~ sub_100004b9c : 3352 -> 2852
- sub_100007938
CStrings:
+ "Reporting based on being a customer seed build."
- "Not reporting based on not being tasked-on by CoreAnalytics ('%@' is false)"
- "Not reporting based on not being tasked-on by CoreAnalytics (Non-NSDictionary configuration object)"
- "Not reporting based on not being tasked-on by CoreAnalytics (Timeout waiting for config)"
- "Not reporting based on not being tasked-on by CoreAnalytics (nil configuration object)"
- "Not reporting based on not being tasked-on by CoreAnalytics (unexpected type string: '%@')"
- "Not reporting since is not tasked-on by CoreAnalytics (nil value for %@ key)"
- "Not reporting since not tasked-on by CoreAnalytics (Wrong value class for class for %@)"
- "Reporting based on being tasked-on by CoreAnalytics"
- "Reporting based on os_variant result"
- "TaskedOn"
- "boolValue"
- "com.apple.performance.signpost_reporter_tasking"
- "com.apple.signpost"
- "setConfigurationObserverDelegate:queue:"
- "signpost_reporter configuration observing queue"
- "startObservingConfigurationType:"
- "v24@?0@\"NSObject\"8@\"NSString\"16"
```
