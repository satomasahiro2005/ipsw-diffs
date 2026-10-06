## AutoUnlockDaemon

> `/System/Library/PrivateFrameworks/AutoUnlockDaemon.framework/AutoUnlockDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c21a8` | `0x1c3304` | **`+0x115c`** |
| `__TEXT.__cstring` | `0x700b` | `0x70db` | **`+0xd0`** |
| `__TEXT.__eh_frame` | `0xa938` | `0xa9e0` | **`+0xa8`** |
| `__TEXT.__const` | `0xe688` | `0xe6b8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x5088` | `0x50a8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x13d0` | `0x13b8` | **`-0x18`** |
| `__TEXT.__oslogstring` | `0x835a` | `0x836a` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1528` | `0x1530` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x456a` | `0x456c` | **`+0x2`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-2131.20.71.0.0
+2131.21.21.0.0

-  Functions: 7852
+  Functions: 7861

-  CStrings:  1439
+  CStrings:  1442
Symbols:
+ _symbolic ______p____________p________________ptc 16AutoUnlockDaemon34AuthenticationPairingLockInterfaceP 10Foundation4UUIDV AA11SDIDSDeviceP AD4DataV AA20SDAuthenticationTypeO So0L18AKSManagerProtocolP
- _symbolic ______p____________pSS___________ptc 16AutoUnlockDaemon34AuthenticationPairingLockInterfaceP 10Foundation4UUIDV AA11SDIDSDeviceP AA20SDAuthenticationTypeO So0K18AKSManagerProtocolP
CStrings:
+ "Failed to externalize passcode as ACM context: %{public}@"
+ "Invalid previous context for confirmation, message may be replayed"
+ "Invalid previous context for request, message may be replayed"
+ "Invalid previous context for response, message may be replayed"
+ "Missing passcode ref (exists: %@)"
- "Could not convert passcode data to string"
- "Missing passcode (exists: %@)"
```
