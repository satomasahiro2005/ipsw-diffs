## backupd

> `/System/Library/PrivateFrameworks/MobileBackup.framework/backupd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2471c8` | `0x247b64` | **`+0x99c`** |
| `__TEXT.__cstring` | `0x6860c` | `0x687bb` | **`+0x1af`** |
| `__TEXT.__oslogstring` | `0x31263` | `0x313eb` | **`+0x188`** |
| `__TEXT.__objc_stubs` | `0x280a0` | `0x280e0` | **`+0x40`** |
| `__DATA.__objc_const` | `0x23760` | `0x23740` | **`-0x20`** |
| `__DATA_CONST.__cfstring` | `0x1aec0` | `0x1aee0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x7da0` | `0x7dc0` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0xc88` | `0xca0` | **`+0x18`** |
| `__DATA_CONST.__objc_arrayobj` | `0x528` | `0x540` | **`+0x18`** |
| `__DATA.__bss` | `0x1928` | `0x1938` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x32b0` | `0x32a0` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x9d48` | `0x9d54` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0xb7a8` | `0xb7b0` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x1968` | `0x1960` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x61f8` | `0x6200` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x199c` | `0x1998` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3038.0.0.0.0
+3039.0.1.0.0

-  Functions: 8925
-  Symbols:   1317
-  CStrings:  18396
+  Functions: 8928
+  Symbols:   1316
+  CStrings:  18401
Symbols:
- _MBDeviceCoverGlassColor
CStrings:
+ "%@ is a local storage app domain - not removing from the disabled domains list"
+ "%s local files domains \"%{public}@\""
+ "=backoff= ServerKeySync failureCount:%lu, backoff:%G"
+ "=ckrestore-engine= Failed to remove incomplete restore directories: %@"
+ "=quota-calculation= Adding local storage domain size %@ to DocumentsApp (total: %@)"
+ "AppDomain-com.apple.DocumentsApp"
+ "Cleanup: Failed to remove incomplete restore dirs: %@"
+ "Cleanup: Removing stale incomplete restore dirs"
+ "Failed to remove incomplete restore directories: %@"
+ "ServerKeySyncFailureCount"
+ "ServerKeySyncRetryAfter"
+ "_dependentDomainsForDisabledDomains:"
+ "_shortenRetryAfterOnUnlockForFailureCountKey:retryAfterKey:"
+ "createIncompleteRestoreDirectoriesWithError:"
+ "isRetryableServerKeySyncError:"
+ "removeIncompleteRestoreDirectoriesWithError:"
+ "removeIntermediateRestoreDirectoriesWithError:"
+ "syncDisabledDomainsWithInstalledAppDomains:persona:"
- "Cleanup: Failed to remove %@ : %@"
- "Cleanup: Finished removing %@"
- "Cleanup: Removing %@"
- "DeviceCoverGlassColor"
- "T@\"NSString\",R,V_deviceCoverGlassColor"
- "_cleanupStaleRestorePath:"
- "_deviceCoverGlassColor"
- "_subdomainNamesForAppDomainNames:"
- "_syncDisabledDomainsWithAllInstalledAppDomains:persona:"
- "allDisabledDomainNames"
- "cleanupRestoreDirectoriesWithError:"
- "createRestoreDirectoriesWithError:"
- "deviceCoverGlassColor"
```
