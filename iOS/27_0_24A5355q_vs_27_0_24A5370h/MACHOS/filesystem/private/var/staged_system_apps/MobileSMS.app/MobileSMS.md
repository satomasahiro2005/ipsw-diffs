## MobileSMS

> `/private/var/staged_system_apps/MobileSMS.app/MobileSMS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0x3e80` | `0x3ee0` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x4e3f` | `0x4e94` | **`+0x55`** |
| `__TEXT.__text` | `0x1c3e8` | `0x1c408` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1510` | `0x1528` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x8f0` | `0x8e0` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0xf3c` | `0xf4c` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x488` | `0x480` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x530` | `0x538` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1481.100.29.2.9
+1483.100.10.2.4

-  Functions: 514
+  Functions: 515

-  CStrings:  1307
+  CStrings:  1310
Symbols:
+ _CKDefaultsKeyDisableNewComposeAutomaticKeyboardPresentation
+ _CKDefaultsKeyForceUnknownSenderForTesting
- _IMSCSensitivityAnalysisPrepareContentPolicy
- _OBJC_CLASS_$_IMFeatureFlags
CStrings:
+ "_updateKnownSenderStateForChatUnderTestWithOptions:"
+ "boolForKey:"
+ "im_boolForKey:defaultValue:"
+ "messagesAppDomain"
+ "updateIsFiltered:"
- "isSCABasedSafetyEnabled"
- "sharedFeatureFlags"
```
