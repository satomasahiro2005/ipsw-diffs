## appleaccountd

> `/usr/libexec/appleaccountd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3eaeac` | `0x3edc54` | **`+0x2da8`** |
| `__TEXT.__oslogstring` | `0x204fd` | `0x2081d` | **`+0x320`** |
| `__DATA.__bss` | `0x13700` | `0x13a00` | **`+0x300`** |
| `__TEXT.__const` | `0x13070` | `0x13230` | **`+0x1c0`** |
| `__TEXT.__eh_frame` | `0x1451c` | `0x1464c` | **`+0x130`** |
| `__DATA_CONST.__const` | `0x13ca8` | `0x13d28` | **`+0x80`** |
| `__TEXT.__cstring` | `0x4519` | `0x4579` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x76a5` | `0x7705` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x8430` | `0x8480` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0xc4b0` | `0xc4f8` | **`+0x48`** |
| `__TEXT.__objc_stubs` | `0x4c80` | `0x4cc0` | **`+0x40`** |
| `__DATA.__data` | `0x141d0` | `0x14200` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x920` | `0x950` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x7869` | `0x7893` | **`+0x2a`** |
| `__TEXT.__swift5_fieldmd` | `0x6590` | `0x65b8` | **`+0x28`** |
| `__DATA.__objc_const` | `0x1dce8` | `0x1dd08` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x6665` | `0x6685` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0xc54` | `0xc6c` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x119c` | `0x11b4` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x2a8` | `0x2bc` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0x16f0` | `0x1700` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x37c0` | `0x37d0` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x6510` | `0x6520` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x860` | `0x86c` | **`+0xc`** |
| `__TEXT.__objc_methtype` | `0x201e` | `0x2014` | **`-0xa`** |
| `__DATA_CONST.__auth_got` | `0x1be8` | `0x1bf0` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x65c` | `0x664` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x62c` | `0x630` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-1061.0.0.0.0
+1063.1.0.0.0

-  Functions: 10179
-  Symbols:   1813
-  CStrings:  4138
+  Functions: 10200
+  Symbols:   1814
+  CStrings:  4152
Symbols:
+ _$sSD10FoundationE34_conditionallyBridgeFromObjectiveC_6resultSbSo12NSDictionaryC_SDyxq_GSgztFZ
+ _OBJC_CLASS_$_ACDataclassAction
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "AccountUpdatePerformer - Failed to save account with dataclass actions:%s with error: %@"
+ "AccountUpdatePerformer - No account on disk for altDSID; skipping save with dataclass actions."
+ "AccountUpdatePerformer - No dataclass actions to save (nil or empty); skipping save."
+ "Custodian handleFailedSetup failed for custodianID: %s, error: %@"
+ "Custodian not tearing down setup; teardownActionEnabled is false for custodianID: %s"
+ "DaemonAccountStore - Failed to bridge ACDataclassActions to [ACAccount.Dataclass: ACDataclassAction]."
+ "Owner handleFailedSetup failed for custodianID: %s, error: %@"
+ "Owner not tearing down setup; teardownActionEnabled is false for custodianID: %s"
+ "aa_sanitizeError:"
+ "aa_updateAccountWithProvisioningResponse:"
+ "cleanupOrphanedCustodiansV2"
+ "ownerSetupGracePeriodV2InSeconds"
+ "retainedProvider"
+ "saveAccount:withDataclassActions:completion:"
+ "teardownActionEnabled"
+ "🔔 Internal build: %s override is set to: %{bool}d"
- "aa_updateWithProvisioningResponse:"
- "cleanupOrphanedCustodians"
```
