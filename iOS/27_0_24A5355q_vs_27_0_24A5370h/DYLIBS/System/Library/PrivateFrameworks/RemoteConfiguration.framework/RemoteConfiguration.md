## RemoteConfiguration

> `/System/Library/PrivateFrameworks/RemoteConfiguration.framework/RemoteConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2bdd4` | `0x2bf84` | **`+0x1b0`** |
| `__AUTH_CONST.__objc_const` | `0x5808` | `0x5838` | **`+0x30`** |
| `__TEXT.__cstring` | `0x4b83` | `0x4bb3` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x2fcc` | `0x2ff4` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x22a0` | `0x22c0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b50` | `0x1b68` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x3d0` | `0x3d4` | **`+0x4`** |

### Other Changes

```diff

-421.0.0.0.0
+422.0.0.0.0

-  Functions: 1402
-  Symbols:   2317
-  CStrings:  550
+  Functions: 1405
+  Symbols:   2321
+  CStrings:  551
Symbols:
+ -[RCConfigurationSettings rc_deviceInfoDictionaryRepresentation]
+ -[RCDebugOverrides initWithDisableAbTesting:overrideSegmentSetIDs:additionalSegmentSetIDs:configurationSource:debugEnvironment:ignoreCache:enableExtraLogs:overrideDeviceClass:]
+ -[RCDebugOverrides overrideDeviceClass]
+ GCC_except_table30
+ GCC_except_table36
+ GCC_except_table40
+ GCC_except_table44
+ GCC_except_table48
+ GCC_except_table52
+ GCC_except_table56
+ GCC_except_table60
+ GCC_except_table64
+ _OBJC_IVAR_$_RCDebugOverrides._overrideDeviceClass
- GCC_except_table29
- GCC_except_table35
- GCC_except_table39
- GCC_except_table43
- GCC_except_table47
- GCC_except_table51
- GCC_except_table55
- GCC_except_table59
- GCC_except_table63
CStrings:
+ "<%@: %p; disableAbTesting: %d overrideSegmentSetIDs: %@ additionalSegmentSetIDs: %@ configurationSource: %lu debugEnvironment: %lu ignoreCache: %d enableExtraLogs: %d overrideDeviceClass: %@>"
+ "overrideDeviceClass"
- "<%@: %p; disableAbTesting: %d overrideSegmentSetIDs: %@ additionalSegmentSetIDs: %@ configurationSource: %lu debugEnvironment: %lu ignoreCache: %d enableExtraLogs: %d>"
```
