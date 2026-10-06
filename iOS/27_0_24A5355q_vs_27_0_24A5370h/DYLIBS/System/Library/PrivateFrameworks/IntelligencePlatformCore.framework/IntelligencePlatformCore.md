## IntelligencePlatformCore

> `/System/Library/PrivateFrameworks/IntelligencePlatformCore.framework/IntelligencePlatformCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb3c6a0` | `0xb3ffb4` | **`+0x3914`** |
| `__TEXT.__const` | `0x7d5f0` | `0x7d6f0` | **`+0x100`** |
| `__TEXT.__eh_frame` | `0x605d4` | `0x604d8` | **`-0xfc`** |
| `__TEXT.__unwind_info` | `0x28eb8` | `0x28e50` | **`-0x68`** |
| `__TEXT.__cstring` | `0x312df` | `0x3133f` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x2657f` | `0x2658f` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x5880` | `0x5888` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x13bc` | `0x13c4` | **`+0x8`** |

### Other Changes

```diff

-184.0.1.0.0
+185.0.0.0.0

-  Functions: 67465
-  Symbols:   1004
-  CStrings:  5838
+  Functions: 67590
+  Symbols:   1005
+  CStrings:  5840
Symbols:
+ _swift_release_x11
CStrings:
+ "    SELECT startDate AS occurredAt,\n    type AS type,\n    durationSeconds AS durationSeconds,\n    bundleId AS bundleId,\n    rowId AS interactionRowid,\n    isLocal AS isLocal,\n    devicePlatform AS devicePlatform,\n    remoteDeviceId AS remoteDeviceId,\n    isDonatedBySiri AS isDonatedBySiri\n    FROM interactions\n    WHERE (id = ?)"
+ "CreateDraftMessage"
+ "com.apple.facetime"
+ "com.apple.mobilephone"
- "    SELECT startDate AS occurredAt,\n    type AS type,\n    durationSeconds AS durationSeconds,\n    bundleId AS bundleId,\n    rowId AS interactionRowid,\n    isLocal AS isLocal,\n    devicePlatform AS devicePlatform,\n    remoteDeviceId AS remoteDeviceId\n    FROM interactions\n    WHERE (id = ?)"
- "SendMessageIntent"
```
