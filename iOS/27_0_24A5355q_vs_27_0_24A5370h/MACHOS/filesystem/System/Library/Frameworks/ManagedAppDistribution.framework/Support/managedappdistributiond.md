## managedappdistributiond

> `/System/Library/Frameworks/ManagedAppDistribution.framework/Support/managedappdistributiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6d9588` | `0x6e041c` | **`+0x6e94`** |
| `__TEXT.__eh_frame` | `0x3a258` | `0x3a628` | **`+0x3d0`** |
| `__TEXT.__oslogstring` | `0x15dd2` | `0x16082` | **`+0x2b0`** |
| `__DATA_CONST.__const` | `0x2f5c0` | `0x2f640` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0x72d0` | `0x7350` | **`+0x80`** |
| `__TEXT.__swift_as_cont` | `0x34ec` | `0x3544` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x12e78` | `0x12ec0` | **`+0x48`** |
| `__DATA_CONST.__auth_got` | `0x3978` | `0x39b8` | **`+0x40`** |
| `__TEXT.__const` | `0x400b0` | `0x400e0` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x8575` | `0x85a5` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0x5ae0` | `0x5b00` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x19d0` | `0x19e4` | **`+0x14`** |
| `__DATA.__data` | `0x10ca8` | `0x10cb8` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x6534` | `0x6524` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0xc40` | `0xc4c` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x1ea8` | `0x1eb0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1f80` | `0x1f88` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x7470` | `0x7478` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-4.0.30.0.0
+4.0.33.0.0

+  - /System/Library/PrivateFrameworks/DMCUtilities.framework/DMCUtilities
+  - /System/Library/PrivateFrameworks/DataMigration.framework/DataMigration

-  Functions: 16888
-  Symbols:   3302
-  CStrings:  4570
+  Functions: 16930
+  Symbols:   3310
+  CStrings:  4581
Symbols:
+ _$s10Foundation23LocalizedStringResourceV13stringLiteralACSS_tcfC
+ _$s14MarketplaceKit30VirtualMachineUnsupportedAlertO5titleSSvgZ
+ _$s14MarketplaceKit30VirtualMachineUnsupportedAlertO7messageSSvgZ
+ _$s14MarketplaceKit30VirtualMachineUnsupportedAlertO8okButtonSSvgZ
+ _$s14MarketplaceKit33ADDeviceIsRunningInVirtualMachineSbyF
+ _$s29AppleMediaServicesKitInternal10BagServiceV19PermittedDataOriginV15persistenceOnlyAEvgZ
+ _DMGetUserDataDisposition
+ _OBJC_CLASS_$_DMCCodeUtilities
CStrings:
+ "Failed to load bag from persistence"
+ "[%@] Alternative distribution is unsupported in a virtual machine"
+ "[%@] Declaration state changed (expected active, found %{public}s), skipping install"
+ "[%@] Expected composed identifier but none found"
+ "[%@] Expected declaration status but none found for %{public}s"
+ "[%@] Migrating from '%{public}s' to '%{public}s'%{public}s"
+ "[%@] Migration not needed for '%{public}s'"
+ "[%@] Migration skipped for '%{public}s'"
+ "[%@] Precondition not met (expected %{public}s, found %{public}s), skipping task"
+ "[%@] Record not found for '%{public}s'"
+ "[%@] Signature invalid for '%{public}s'"
+ "[%@] Skipping declaration for %{public}s as it is not visible"
+ "[%@] ╲╭ Declaration: %{public}s (#%{public}s)"
+ "verifySignatureForPath:composedIdentifier:"
- "[%@] Migrating from '%s' to '%s'"
- "[%@] Migration not needed for '%s'"
- "[%@] ╲╭ Declaration: %{public}s (#%s)"
```
