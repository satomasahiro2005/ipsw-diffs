## DiagnosticExtensionsDaemon

> `/System/Library/PrivateFrameworks/DiagnosticExtensionsDaemon.framework/DiagnosticExtensionsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x13b30` | `0x13ad0` | **`-0x60`** |
| `__TEXT.__text` | `0x75f8c` | `0x75fe8` | **`+0x5c`** |
| `__DATA_DIRTY.__objc_data` | `0x18e0` | `0x1890` | **`-0x50`** |
| `__TEXT.__oslogstring` | `0x9908` | `0x98c8` | **`-0x40`** |
| `__AUTH_CONST.__cfstring` | `0x5040` | `0x5020` | **`-0x20`** |
| `__AUTH_CONST.__const` | `0xc20` | `0xc40` | **`+0x20`** |
| `__DATA.__bss` | `0x1d0` | `0x1f0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x2188` | `0x2198` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x6e8` | `0x6d8` | **`-0x10`** |
| `__TEXT.__cstring` | `0x56f0` | `0x56e0` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x7054` | `0x7044` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1cc8` | `0x1cd8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x278` | `0x270` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3bc8` | `0x3bc0` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x5f4` | `0x5f8` | **`+0x4`** |

### Other Changes

```diff

-224.0.0.0.0
+225.0.0.0.0

-  Functions: 2932
-  Symbols:   4297
-  CStrings:  1791
+  Functions: 2934
+  Symbols:   4299
+  CStrings:  1787
Symbols:
+ +[DEDSeedingFinisher(SecurityResearchDevice) isERMCommPageCheckCompiledIn]
+ -[DEDConfiguration protectedDefaults]
+ -[DEDPersistence discardLegacyStoreKeys]
+ -[DEDPersistence protectedDefaults]
+ -[DEDPersistence setProtectedDefaults:]
+ GCC_except_table134
+ _DEDDeferredExtensionUserDefaultsKey
+ _DEDGroupContainerName
+ _OBJC_IVAR_$_DEDPersistence._protectedDefaults
+ __OBJC_$_CLASS_METHODS_DEDSeedingFinisher(SecurityResearchDevice)
+ ___37-[DEDConfiguration protectedDefaults]_block_invoke
+ ___73-[DEDSeedingFinisher(SecurityResearchDevice) isSecurityResearchDeviceERM]_block_invoke
+ _isSecurityResearchDeviceERM.ermEnabled
+ _isSecurityResearchDeviceERM.onceToken
+ _protectedDefaults.onceToken
+ _protectedDefaults.protectedDefaults
- +[DEDDirectoriesCleanup didRun]
- +[DEDDirectoriesCleanup isDryRun]
- +[DEDDirectoriesCleanup run]
- +[DEDDirectoriesCleanup shouldRun]
- -[DEDController upgradeToClassCDataProtectionIfNeeded]
- GCC_except_table138
- _NSURLFileProtectionCompleteUntilFirstUserAuthentication
- _OBJC_CLASS_$_DEDDirectoriesCleanup
- _OBJC_METACLASS_$_DEDDirectoriesCleanup
- __OBJC_$_CLASS_METHODS_DEDDirectoriesCleanup
- __OBJC_$_CLASS_METHODS_DEDSeedingFinisher
- __OBJC_CLASS_RO_$_DEDDirectoriesCleanup
- __OBJC_METACLASS_RO_$_DEDDirectoriesCleanup
- ___54-[DEDController upgradeToClassCDataProtectionIfNeeded]_block_invoke
CStrings:
+ "bugsession:"
+ "discarded [%lu] legacy keys"
+ "failed to archive bug session [%{public}@], not updating the store: [%{public}@]"
+ "group.com.apple.diagnosticextensionsd"
+ "no group container for [%{public}@]; protected defaults will not be protected"
+ "overrideDevice"
- "%@.c-data-class-upgrade"
- "DEDUpgradedToClassC"
- "Error setting file protection key: %@"
- "Upgrading: [%{public}@]"
- "directoriesCleanupDone"
- "directoriesCleanupDryRun"
- "failed to archive bug session with error: [%{public}@]"
- "upgradeToClassCDataProtectionIfNeeded already done"
- "upgradeToClassCDataProtectionIfNeeded end"
- "upgradeToClassCDataProtectionIfNeeded start"
```
