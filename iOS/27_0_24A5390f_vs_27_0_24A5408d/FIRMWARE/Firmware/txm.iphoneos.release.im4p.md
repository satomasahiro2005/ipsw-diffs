## txm.iphoneos.release.im4p

> `Firmware/txm.iphoneos.release.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0xff88` | `0x12338` | **`+0x23b0`** |
| `__DATA_CONST.__const` | `0xd198` | `0xd5a0` | **`+0x408`** |
| `__TEXT_EXEC.__text` | `0x49238` | `0x49358` | **`+0x120`** |
| `__TEXT.__cstring` | `0x64ca` | `0x6516` | **`+0x4c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__TEXT.__chain_starts`
- `__TEXT_BOOT_EXEC.__bootcode`
- `__TEXT_BOOT_EXEC.__text`

### Other Changes

```diff

-217.0.1.0.0
-  Functions: 1090
+217.0.2.0.0
+  Functions: 1091

-  CStrings:  734
+  CStrings:  736
CStrings:
+ "2f319679-66b9-44cf-9cf0-723471de0db9"
+ "@(#)VERSION:Code Signing Monitor Image4 Module Version 7.0.0: Mon Aug  3 20:13:58 PDT 2026; root:AppleImage4_txm-374~6843/libimage4_TXM/RELEASE_ARM64E"
+ "Code Signing Monitor Image4 Module Version 7.0.0: Mon Aug  3 20:13:58 PDT 2026; root:AppleImage4_txm-374~6843/libimage4_TXM/RELEASE_ARM64E"
+ "adaea588-c074-4b87-b8ea-26cb685b3443"
+ "txm.iphoneos.release.TrustedExecutionMonitor_Guarded-217.0.2"
- "@(#)VERSION:Code Signing Monitor Image4 Module Version 7.0.0: Fri Jul 10 21:20:27 PDT 2026; root:AppleImage4_txm-374~3979/libimage4_TXM/RELEASE_ARM64E"
- "Code Signing Monitor Image4 Module Version 7.0.0: Fri Jul 10 21:20:27 PDT 2026; root:AppleImage4_txm-374~3979/libimage4_TXM/RELEASE_ARM64E"
- "txm.iphoneos.release.TrustedExecutionMonitor_Guarded-217.0.1"
```
