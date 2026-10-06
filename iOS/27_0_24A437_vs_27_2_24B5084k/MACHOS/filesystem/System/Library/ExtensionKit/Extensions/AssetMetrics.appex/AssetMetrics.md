## AssetMetrics

> `/System/Library/ExtensionKit/Extensions/AssetMetrics.appex/AssetMetrics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c7c` | `0x513c` | **`+0x14c0`** |
| `__DATA.__bss` | `0x500` | `0x780` | **`+0x280`** |
| `__TEXT.__auth_stubs` | `0x590` | `0x7e0` | **`+0x250`** |
| `__TEXT.__const` | `0x3ca` | `0x52a` | **`+0x160`** |
| `__DATA_CONST.__auth_got` | `0x2c8` | `0x3f8` | **`+0x130`** |
| `__TEXT.__oslogstring` | `0xea` | `0x205` | **`+0x11b`** |
| `__DATA_CONST.__const` | `0x258` | `0x370` | **`+0x118`** |
| `__TEXT.__eh_frame` | `0x290` | `0x370` | **`+0xe0`** |
| `__DATA.__objc_const` | `0x90` | `0x168` | **`+0xd8`** |
| `__DATA.__data` | `0x1d8` | `0x2a8` | **`+0xd0`** |
| `__TEXT.__objc_stubs` | `—` | `0xa0` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x1f8` | `0x288` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0xd0` | `0x130` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x142` | `0x1a0` | **`+0x5e`** |
| `__TEXT.__cstring` | `0xa2` | `0xfd` | **`+0x5b`** |
| `__DATA_CONST.__auth_ptr` | `0x190` | `0x1e8` | **`+0x58`** |
| `__TEXT.__objc_methname` | `—` | `0x53` | **`+0x53`** |
| `__TEXT.__objc_classname` | `0x2e` | `0x7e` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0xb0` | `0xf4` | **`+0x44`** |
| `__TEXT.__swift5_reflstr` | `0x68` | `0xa6` | **`+0x3e`** |
| `__DATA_CONST.__got` | `0x70` | `0xa0` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x2c` | `0x4c` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x18` | `0x30` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x2c` | `0x40` | **`+0x14`** |
| `__TEXT.__objc_methtype` | `—` | `0xa` | **`+0xa`** |
| `__DATA_CONST.__objc_classlist` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x1c` | `0x20` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-3600.6.1.0.0
+3605.12.1.0.0

+  - /System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices

-  Functions: 126
-  Symbols:   89
-  CStrings:  13
+  Functions: 179
+  Symbols:   109
+  CStrings:  27
Symbols:
+ _AFIsHorseman
+ _OBJC_CLASS_$_NSLock
+ _OBJC_CLASS_$_NSProcessInfo
+ __Block_copy
+ __Block_release
+ __NSConcreteStackBlock
+ __swift_stdlib_bridgeErrorToNSError
+ _dispatch_semaphore_create
+ _objc_msgSend
+ _objc_release_x21
+ _objc_release_x23
+ _objc_retainAutoreleasedReturnValue
+ _objc_retain_x20
+ _objc_retain_x23
+ _objc_retain_x8
+ _swift_allocBox
+ _swift_release_x19
+ _swift_release_x20
+ _swift_retain
+ _swift_retain_x2
+ _swift_retain_x27
- _objc_release_x26
CStrings:
+ "#AssetMetricsEntry: RunningBoard is expiring the AssetMetrics activity"
+ "AssetMetrics AND Assistant/dictation are enabled. Continuing."
+ "Hourly task running on HomePod. Not continuing for resource reasons."
+ "Siri Assistant or Dictation disabled. Not continuing."
+ "_TtC12AssetMetricsP33_CFE025F5F3C0D62108C1EA1F858D47D911RunOnceGate"
+ "claimed"
+ "com.apple.siri.AssetMetrics metrics run"
+ "dependenciesUnavailableError"
+ "init"
+ "lock"
+ "performExpiringActivityWithReason:usingBlock:"
+ "processInfo"
+ "unexpected error throws: %@"
+ "unlock"
+ "v12@?0B8"
- "AssetMetrics are disabled"
```
