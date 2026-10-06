## txm.iphoneos.release.im4p

> `Firmware/txm.iphoneos.release.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x48d38` | `0x49150` | **`+0x418`** |
| `__TEXT.__cstring` | `0x63a8` | `0x63ce` | **`+0x26`** |
| `__DATA_CONST.__const` | `0xd190` | `0xd198` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__TEXT_BOOT_EXEC.__bootcode`
- `__TEXT_BOOT_EXEC.__text`

### Other Changes

```diff

-215.0.0.0.0
+217.0.0.0.0

-  CStrings:  727
+  CStrings:  728
CStrings:
+ "1cf29dc4-4f08-457d-b9a7-512c89f0e142"
+ "374"
+ "@(#)VERSION:Code Signing Monitor Image4 Module Version 7.0.0: Thu Jun 11 23:44:59 PDT 2026; root:AppleImage4_txm-374~1515/libimage4_TXM/RELEASE_ARM64E"
+ "Code Signing Monitor Image4 Module Version 7.0.0: Thu Jun 11 23:44:59 PDT 2026; root:AppleImage4_txm-374~1515/libimage4_TXM/RELEASE_ARM64E"
+ "txm.iphoneos.release.TrustedExecutionMonitor_Guarded-217"
- "372"
- "@(#)VERSION:Code Signing Monitor Image4 Module Version 7.0.0: Thu May 21 05:12:50 PDT 2026; root:AppleImage4_txm-372~203/libimage4_TXM/RELEASE_ARM64E"
- "Code Signing Monitor Image4 Module Version 7.0.0: Thu May 21 05:12:50 PDT 2026; root:AppleImage4_txm-372~203/libimage4_TXM/RELEASE_ARM64E"
- "txm.iphoneos.release.TrustedExecutionMonitor_Guarded-215"
```
