## RapidResourceDelivery

> `/System/Library/PrivateFrameworks/RapidResourceDelivery.framework/RapidResourceDelivery`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x76db8` | `0x77b1c` | **`+0xd64`** |
| `__TEXT.__eh_frame` | `0x3530` | `0x3578` | **`+0x48`** |
| `__TEXT.__cstring` | `0xc39` | `0xc09` | **`-0x30`** |
| `__TEXT.__swift5_typeref` | `0x18a4` | `0x1880` | **`-0x24`** |
| `__DATA.__data` | `0x12b8` | `0x1298` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x18c0` | `0x18e0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xd58` | `0xd60` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xa8` | `0xac` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xc8` | `0xcc` | **`+0x4`** |

### Other Changes

```diff

-3600.17.1.0.0
+3600.18.1.0.0

-  Functions: 1999
-  Symbols:   949
-  CStrings:  244
+  Functions: 1997
+  Symbols:   944
+  CStrings:  243
Symbols:
+ _swift_task_localValuePop
+ _swift_task_localValuePush
- _get_type_metadata 15Synchronization5MutexVy21RapidResourceDelivery13ConfigurationVSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVy21RapidResourceDelivery16PersistenceStateVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy21RapidResourceDelivery18URLSessionProtocol_pSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVy21RapidResourceDelivery8ManifestVSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVy3XPC11XPCListenerCSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDySi21RapidResourceDelivery17DownloadTaskStateCGG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
- "RapidResourceDelivery/RRDPeerHandler.swift"
```
