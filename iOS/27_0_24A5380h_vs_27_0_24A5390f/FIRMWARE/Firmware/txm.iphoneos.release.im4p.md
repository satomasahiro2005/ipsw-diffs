## txm.iphoneos.release.im4p

> `Firmware/txm.iphoneos.release.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x490b8` | `0x49238` | **`+0x180`** |
| `__TEXT.__cstring` | `0x63ce` | `0x64ca` | **`+0xfc`** |
| `__TEXT.__const` | `0xff28` | `0xff88` | **`+0x60`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT_BOOT_EXEC.__text`

### Other Changes

```diff

-217.0.0.0.0
-  Functions: 1089
+217.0.1.0.0
+  Functions: 1090

-  CStrings:  728
+  CStrings:  734
CStrings:
+ "@(#)VERSION:Code Signing Monitor Image4 Module Version 7.0.0: Fri Jul 10 21:20:27 PDT 2026; root:AppleImage4_txm-374~3979/libimage4_TXM/RELEASE_ARM64E"
+ "Code Signing Monitor Image4 Module Version 7.0.0: Fri Jul 10 21:20:27 PDT 2026; root:AppleImage4_txm-374~3979/libimage4_TXM/RELEASE_ARM64E"
+ "PlatformCode-Strict"
+ "cs-system-policy"
+ "cs-system-policy property is not a NULL terminated string"
+ "developer mode disabled due to platform code strict policy"
+ "missing data for cs-system-policy property"
+ "txm.iphoneos.release.TrustedExecutionMonitor_Guarded-217.0.1"
+ "unable to find cs-system-policy property in /chosen"
- "@(#)VERSION:Code Signing Monitor Image4 Module Version 7.0.0: Fri Jun 26 21:01:06 PDT 2026; root:AppleImage4_txm-374~2547/libimage4_TXM/RELEASE_ARM64E"
- "Code Signing Monitor Image4 Module Version 7.0.0: Fri Jun 26 21:01:06 PDT 2026; root:AppleImage4_txm-374~2547/libimage4_TXM/RELEASE_ARM64E"
- "txm.iphoneos.release.TrustedExecutionMonitor_Guarded-217"
```
