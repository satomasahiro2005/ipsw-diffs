## ReplicatorEngine

> `/System/Library/PrivateFrameworks/ReplicatorEngine.framework/ReplicatorEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a5a80` | `0x1a8304` | **`+0x2884`** |
| `__AUTH_CONST.__const` | `0xa2c0` | `0xa358` | **`+0x98`** |
| `__TEXT.__oslogstring` | `0x7e8d` | `0x7f0d` | **`+0x80`** |
| `__TEXT.__const` | `0xb858` | `0xb8c8` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x299f` | `0x29ef` | **`+0x50`** |
| `__DATA.__data` | `0x2b00` | `0x2b38` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x3478` | `0x34ac` | **`+0x34`** |
| `__AUTH.__data` | `0x4c38` | `0x4c08` | **`-0x30`** |
| `__TEXT.__swift5_typeref` | `0x3a92` | `0x3ac2` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x4288` | `0x42b0` | **`+0x28`** |
| `__TEXT.__cstring` | `0x1ada` | `0x1aba` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1610` | `0x1628` | **`+0x18`** |
| `__TEXT.__eh_frame` | `0x55a8` | `0x5598` | **`-0x10`** |
| `__TEXT.__constg_swiftt` | `0x416c` | `0x4168` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x390` | `0x394` | **`+0x4`** |

### Other Changes

```diff

-164.0.0.0.0
+168.0.0.0.0

-  Functions: 6564
-  Symbols:   1912
-  CStrings:  665
+  Functions: 6604
+  Symbols:   1916
+  CStrings:  667
Symbols:
+ ___swift_closure_destructor.23Tm
+ ___swift_closure_destructor.490Tm
+ ___swift_closure_destructor.496Tm
+ ___swift_closure_destructor.512Tm
+ ___swift_closure_destructor.529Tm
+ ___swift_closure_destructor.578Tm
+ ___swift_closure_destructor.622Tm
+ ___swift_closure_destructor.628Tm
+ ___swift_closure_destructor.735Tm
+ _symbolic $s16ReplicatorEngine18PersonaIntroducingP
+ _symbolic SDySSShySSGG
+ _symbolic _____ 16ReplicatorEngine21RelationshipValidatorV
+ _symbolic _____ 16ReplicatorEngine21RelationshipValidatorV17ValidationContextV
+ _symbolic _____ySSSay_____GG s18_DictionaryStorageC 10Foundation4UUIDV
+ _symbolic _____ySSShySSGG s18_DictionaryStorageC
+ _type_layout_string 16ReplicatorEngine21RelationshipValidatorV17ValidationContextV
- ___swift_closure_destructor.25Tm
- ___swift_closure_destructor.493Tm
- ___swift_closure_destructor.499Tm
- ___swift_closure_destructor.515Tm
- ___swift_closure_destructor.532Tm
- ___swift_closure_destructor.581Tm
- ___swift_closure_destructor.625Tm
- ___swift_closure_destructor.631Tm
- ___swift_closure_destructor.738Tm
- _symbolic $s16ReplicatorEngine17ReplicationPolicyP
- _symbolic _____ 16ReplicatorEngine27UnfilteredReplicationPolicyV
- _symbolic ______p 16ReplicatorEngine17ReplicationPolicyP
CStrings:
+ "Device %{public}s (%s) became available for persona %{public}s"
+ "Found colliding persona relationships: %{public}s"
+ "Found illegal relationships: %{public}s"
+ "Found incompatible relationships: %{public}s"
+ "Removing invalid relationship: %{public}s"
- "(%{public}s) Replication policy prevents record from syncing: %{public}s"
- "Device %{public}s became available for persona %{public}s"
- "availableDeviceIDs"
```
