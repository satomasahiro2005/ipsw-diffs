## PhoneAppIntents

> `/System/Library/PrivateFrameworks/PhoneAppIntents.framework/PhoneAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38088` | `0x385ec` | **`+0x564`** |
| `__TEXT.__oslogstring` | `0x465` | `0x4e5` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x1a00` | `0x1a48` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x1b08` | `0x1b42` | **`+0x3a`** |
| `__TEXT.__const` | `0x5ab4` | `0x5ae4` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x898` | `0x8c8` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x14cc` | `0x14f4` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x40` | `0x50` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x8f4` | `0x904` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1538` | `0x1548` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x4ec` | `0x4f0` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x4` | `0x8` | **`+0x4`** |

### Other Changes

```diff

-1626.200.65.0.0
+1626.200.84.0.0

-  Functions: 1757
-  Symbols:   993
-  CStrings:  118
+  Functions: 1761
+  Symbols:   995
+  CStrings:  119
Symbols:
+ _symbolic $s15PhoneAppIntents19AudioRouteMatchableP
+ _symbolic SaySo7TURouteCG
CStrings:
+ "entities(for:) retrieved CallAudioRoutes for %s: %s"
+ "entities(matching:) no name/attribute match for %s, falling back to uniqueIdentifier search"
+ "entities(matching:) retrieved CallAudioRoutes matching %s: %s"
- "Retrieved CallAudioRoutes for %s: %s"
- "Retrieved CallAudioRoutes matching %s: %s"
```
