## servicesintelligenced

> `/System/Library/PrivateFrameworks/ServicesIntelligence.framework/servicesintelligenced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd5e0` | `0xea00` | **`+0x1420`** |
| `__TEXT.__oslogstring` | `0x69c` | `0x8ac` | **`+0x210`** |
| `__TEXT.__eh_frame` | `0xa60` | `0xb80` | **`+0x120`** |
| `__DATA_CONST.__const` | `0x510` | `0x628` | **`+0x118`** |
| `__TEXT.__cstring` | `0x4a8` | `0x5b8` | **`+0x110`** |
| `__TEXT.__swift5_capture` | `0x114` | `0x170` | **`+0x5c`** |
| `__TEXT.__unwind_info` | `0x3a8` | `0x400` | **`+0x58`** |
| `__TEXT.__objc_stubs` | `0x1c0` | `0x200` | **`+0x40`** |
| `__TEXT.__const` | `0x26a` | `0x29a` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0xad0` | `0xaf0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x347` | `0x367` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x110` | `0x120` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x570` | `0x580` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xa8` | `0xb8` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x68` | `0x74` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x150` | `0x158` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x3c` | `0x44` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x173` | `0x177` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-1.53.0.0.0
+1.60.0.0.0

+  - /System/Library/Frameworks/HealthKit.framework/HealthKit

-  Functions: 202
-  Symbols:   255
-  CStrings:  122
+  Functions: 230
+  Symbols:   258
+  CStrings:  135
Symbols:
+ _OBJC_CLASS_$_NSProcessInfo
+ _objc_retain_x25
+ _objc_retain_x8
+ _swift_retain_x23
+ _swift_retain_x28
- _objc_release_x28
- _objc_retain_x26
CStrings:
+ ".computeSemanticProfile"
+ ".refreshTopicMappings"
+ "[Daemon][listenForLaunchEvents] Registering handler for semantic profile post-install bg task"
+ "[Daemon][semantic-profile-postinstall] *** COMPLETED *** (system uptime: %lds, elapsed: %lds)"
+ "[Daemon][semantic-profile-postinstall] *** EXPIRED BY DAS — 24hr semantic-profile task remains as fallback ***"
+ "[Daemon][semantic-profile-postinstall] *** POST-INSTALL TASK FIRED *** (system uptime: %lds)"
+ "[Daemon][semantic-profile-postinstall] Starting semantic profile computation (post-OS-update one-shot)"
+ "com.apple.servicesintelligenced.launchevents.semanticProfilePostInstall"
+ "com.apple.servicesintelligenced.semantic-profile.postinstall"
+ "processInfo"
+ "semantic-profile"
+ "semantic-profile-postinstall"
+ "semantic-profile-postinstall.afterWrapUp"
+ "semantic-profile-postinstall.start"
+ "systemUptime"
- "semantic-profile.computeSemanticProfile"
- "semantic-profile.refreshTopicMappings"
```
