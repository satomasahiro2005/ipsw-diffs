## SiriEmergencyIntents

> `/System/Library/PrivateFrameworks/SiriEmergencyIntents.framework/SiriEmergencyIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11b1c` | `0x127e0` | **`+0xcc4`** |
| `__TEXT.__const` | `0x13e8` | `0x13f8` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x6a0` | `0x690` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x5c8` | `0x5c0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x470` | `0x478` | **`+0x8`** |

### Other Changes

```diff

-3600.8.4.0.0
+3600.12.4.1.1

-  Functions: 421
-  Symbols:   245
+  Functions: 425
+  Symbols:   244
Symbols:
+ _swift_bridgeObjectRetain_n
- _swift_release_x25
- _swift_retain_x25
CStrings:
+ "No (%s, %s) match. Expanding to any-language rows for %s."
- "No orgs found matching siriLanguageCode: %s, physicalLocationCountryCode: %s."
```
