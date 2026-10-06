## Freeform

> `/private/var/staged_system_apps/Freeform.app/Freeform`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14662e8` | `0x1468a4c` | **`+0x2764`** |
| `__TEXT.__cstring` | `0xc6955` | `0xc6b45` | **`+0x1f0`** |
| `__TEXT.__objc_methname` | `0xc9259` | `0xc9319` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x29562` | `0x29622` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x1b4cc` | `0x1b530` | **`+0x64`** |
| `__TEXT.__eh_frame` | `0x58194` | `0x5814c` | **`-0x48`** |
| `__TEXT.__constg_swiftt` | `0x38800` | `0x38840` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x6c5a0` | `0x6c5e0` | **`+0x40`** |
| `__DATA.__objc_data` | `0x4d480` | `0x4d4b8` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x43e78` | `0x43ea0` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x11e20` | `0x11dfc` | **`-0x24`** |
| `__DATA.__objc_const` | `0x9c680` | `0x9c6a0` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x24205` | `0x24225` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x37bc2` | `0x37be2` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x25470` | `0x25488` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x20788` | `0x207a0` | **`+0x18`** |
| `__DATA.__data` | `0x50478` | `0x50488` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x819c0` | `0x819d0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x10fe0` | `0x10ff0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x570e0` | `0x570f0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x8808` | `0x8810` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x145c` | `0x1454` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x1820` | `0x1818` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-656.40.5.0.0
+656.40.6.0.0

-  Functions: 91636
-  Symbols:   7833
-  CStrings:  48755
+  Functions: 91652
+  Symbols:   7834
+  CStrings:  48769
Symbols:
+ _$sSo33CKFetchRecordZoneChangesOperationC8CloudKitE26zoneAttributesChangedBlockySo08CKRecordC0CcSgvs
CStrings:
+ "#Assert *** Assertion failure #%u: %{public}s %{public}s:%d Expected at least 3 arguments.  Selector: %@"
+ "#Assert *** Assertion failure #%u: %{public}s %{public}s:%d Unexpected selector %@"
+ "An inherited share already exists and will be used for this folder item provider."
+ "Expected at least 3 arguments.  Selector: %@"
+ "Failed running upgrade code 183330305 for zone attribute refetch with error %{public}@ %@"
+ "Finished running upgrade code 183330305 for zone attribute refetch"
+ "Marked %d zones for refetch on upgrade"
+ "Running upgrade code 183330305 for zone attribute refetch"
+ "SELECT identifier FROM folders"
+ "Unexpected selector %@"
+ "aa_isManagedAppleID"
+ "capturedFixedPosition"
+ "crl_records(for:includingAssets:includingZone:qualityOfService:)"
+ "methodSignature"
+ "repairMissingZoneAttributesOnUpgrade_183330305"
- "crl_records(for:includingAssets:qualityOfService:)"
```
