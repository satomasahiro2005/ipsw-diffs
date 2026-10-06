## MessagesCloudSync

> `/System/Library/PrivateFrameworks/MessagesCloudSync.framework/MessagesCloudSync`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfb1e0` | `0xfc370` | **`+0x1190`** |
| `__TEXT.__oslogstring` | `0x5583` | `0x5703` | **`+0x180`** |
| `__TEXT.__eh_frame` | `0x9c9c` | `0x9d94` | **`+0xf8`** |
| `__TEXT.__unwind_info` | `0x3700` | `0x3738` | **`+0x38`** |
| `__TEXT.__swift_as_cont` | `0x958` | `0x96c` | **`+0x14`** |
| `__TEXT.__const` | `0x98a0` | `0x98b0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x10d0` | `0x10d8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xff0` | `0xff8` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x2bf8` | `0x2c00` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x4c0` | `0x4c8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x428` | `0x42c` | **`+0x4`** |

### Other Changes

```diff

-1481.100.29.2.9
+1483.100.10.2.4

-  Functions: 3812
+  Functions: 3822

-  CStrings:  856
+  CStrings:  860
CStrings:
+ "[ScheduledMessage] DaemonCoreBridge unavailable, cannot notify coordinator for %s: %s"
+ "[ScheduledMessage] Notifying coordinator that scheduled message %s was imported via CloudKit; service=%s, fireDate=%s"
+ "[ScheduledMessage] Skipping coordinator notify for %s: missing fireDate"
+ "[ScheduledMessage] Skipping coordinator notify for %s: missing service"
```
