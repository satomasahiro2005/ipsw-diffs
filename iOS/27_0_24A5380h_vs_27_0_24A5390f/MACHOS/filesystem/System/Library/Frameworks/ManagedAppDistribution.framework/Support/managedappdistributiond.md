## managedappdistributiond

> `/System/Library/Frameworks/ManagedAppDistribution.framework/Support/managedappdistributiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6df1ac` | `0x6e5e34` | **`+0x6c88`** |
| `__TEXT.__eh_frame` | `0x39c20` | `0x3a178` | **`+0x558`** |
| `__TEXT.__unwind_info` | `0x128e0` | `0x12520` | **`-0x3c0`** |
| `__DATA.__data` | `0x10d48` | `0x11038` | **`+0x2f0`** |
| `__TEXT.__const` | `0x3fc10` | `0x3fe60` | **`+0x250`** |
| `__DATA.__bss` | `0x2ea50` | `0x2ec50` | **`+0x200`** |
| `__DATA.__objc_const` | `0x8460` | `0x8600` | **`+0x1a0`** |
| `__TEXT.__constg_swiftt` | `0x7468` | `0x7578` | **`+0x110`** |
| `__TEXT.__oslogstring` | `0x16002` | `0x160f2` | **`+0xf0`** |
| `__TEXT.__cstring` | `0xf915` | `0xf9cd` | **`+0xb8`** |
| `__TEXT.__objc_classname` | `0x1ee6` | `0x1f76` | **`+0x90`** |
| `__DATA.__objc_data` | `0x23f8` | `0x2448` | **`+0x50`** |
| `__DATA_CONST.__auth_ptr` | `0x5eb0` | `0x5e60` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x2f458` | `0x2f4a8` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x74e0` | `0x7520` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x8575` | `0x85b5` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x652a` | `0x6560` | **`+0x36`** |
| `__TEXT.__swift_as_cont` | `0x3524` | `0x3558` | **`+0x34`** |
| `__TEXT.__swift_as_ret` | `0x19b4` | `0x19d8` | **`+0x24`** |
| `__DATA_CONST.__auth_got` | `0x3a80` | `0x3aa0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1fb8` | `0x1fd8` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0xc20` | `0xc38` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0xa64` | `0xa78` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x380` | `0x390` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x19c8` | `0x19d8` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x1ebf` | `0x1ec5` | **`+0x6`** |

### Same-size Content Changes

- `__DATA.__objc_ivar`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-4.0.37.0.0
+4.0.39.0.0

-  Functions: 16856
-  Symbols:   3339
-  CStrings:  4572
+  Functions: 16941
+  Symbols:   3348
+  CStrings:  4583
Symbols:
+ _$s15Synchronization19AtomicRepresentableP06decodeB14Representationyx0bE0QznFZTj
+ _$s15Synchronization19AtomicRepresentableTL
+ _$s20AtomicRepresentation15Synchronization0A13RepresentablePTl
+ _$s22ManagedAppDistribution08InternalaB14InstallRequestV6ResultV6StatusO6deniedyA2GmFWC
+ _$s22ManagedAppDistribution08InternalaB14InstallRequestV6ResultV6StatusO6failedyA2GmFWC
+ _$s22ManagedAppDistribution08InternalaB14InstallRequestV6ResultV6StatusO7allowedyA2GmFWC
+ _$s22ManagedAppDistribution08InternalaB14InstallRequestV6ResultV6StatusOMa
+ _$s22ManagedAppDistribution08InternalaB14InstallRequestV6ResultV6statusA2E6StatusO_tcfC
+ _$s22ManagedAppDistribution08InternalaB14InstallRequestV6ResultVMn
+ _$sScCMa
- _$s22ManagedAppDistribution19MessageRegistrationOs23CustomStringConvertibleAAMc
CStrings:
+ "AsyncBufferedPipe:read"
+ "Installation already in progress"
+ "ManagedAppDistributionDaemon/AsyncBufferedPipe.swift"
+ "[%@] Declaration already pinned for installation"
+ "[%@] Retried installation but it was already in progress"
+ "[%@] Updating backoff date for declaration %{public}s also encountered an error: %{public}@"
+ "[%@][EnterpriseUpdates] Installation of '%{public}s' is already in progress"
+ "_TtC28ManagedAppDistributionDaemon12BufferedPipe"
+ "_TtC28ManagedAppDistributionDaemon17AsyncBufferedPipe"
+ "buffer"
+ "nextPendingID"
+ "underestimatedLimit"
- "[%@] Client %s not found in registry for registration: %s"
```
