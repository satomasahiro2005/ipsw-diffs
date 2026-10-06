## CompanionSetupKit

> `/System/Library/PrivateFrameworks/CompanionSetupKit.framework/CompanionSetupKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x432af0` | `0x42e8d8` | **`-0x4218`** |
| `__TEXT.__eh_frame` | `0x37190` | `0x36c60` | **`-0x530`** |
| `__AUTH_CONST.__const` | `0x19338` | `0x19838` | **`+0x500`** |
| `__TEXT.__swift5_capture` | `0x3a68` | `0x3e80` | **`+0x418`** |
| `__TEXT.__unwind_info` | `0x12ed8` | `0x12da0` | **`-0x138`** |
| `__TEXT.__oslogstring` | `0x96c5` | `0x97b5` | **`+0xf0`** |
| `__TEXT.__const` | `0x2e7d0` | `0x2e8a0` | **`+0xd0`** |
| `__TEXT.__cstring` | `0xbe6d` | `0xbf0d` | **`+0xa0`** |
| `__DATA.__data` | `0x8db8` | `0x8d58` | **`-0x60`** |
| `__TEXT.__constg_swiftt` | `0x6b94` | `0x6b4c` | **`-0x48`** |
| `__TEXT.__swift_as_ret` | `0x1704` | `0x16c4` | **`-0x40`** |
| `__TEXT.__swift_as_cont` | `0x37f8` | `0x37c4` | **`-0x34`** |
| `__DATA_CONST.__objc_selrefs` | `0x1928` | `0x1948` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x9c0a` | `0x9bec` | **`-0x1e`** |
| `__TEXT.__swift5_fieldmd` | `0x9470` | `0x9454` | **`-0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x2610` | `0x25f8` | **`-0x18`** |
| `__TEXT.__swift_as_entry` | `0x121c` | `0x1204` | **`-0x18`** |
| `__AUTH.__data` | `0x5608` | `0x5618` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1370` | `0x1380` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x804e` | `0x805e` | **`+0x10`** |
| `__DATA.__common` | `0x3e8` | `0x3f0` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1250` | `0x1258` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xac8` | `0xac4` | **`-0x4`** |

### Other Changes

```diff

-524.10.88.0.0
+524.10.94.0.0

-  Functions: 18572
-  Symbols:   5032
-  CStrings:  2433
+  Functions: 18523
+  Symbols:   5027
+  CStrings:  2442
Symbols:
+ _OBJC_CLASS_$_AMSSyncPasswordSettingsResult
+ _OBJC_CLASS_$_AMSSyncPasswordSettingsTask
+ ___swift_closure_destructor.356Tm
+ ___swift_closure_destructor.394Tm
+ ___swift_closure_destructor.420Tm
+ ___swift_closure_destructor.422Tm
+ ___swift_closure_destructor.527Tm
+ ___swift_closure_destructor.590Tm
+ ___unnamed_9
+ _swift_release_x2
+ _swift_retain_x13
+ _symbolic ScCySo29AMSSyncPasswordSettingsResultC______pG s5ErrorP
- ___swift_closure_destructor.197Tm
- ___swift_closure_destructor.324Tm
- ___swift_closure_destructor.398Tm
- ___swift_closure_destructor.425Tm
- ___swift_closure_destructor.448Tm
- ___swift_closure_destructor.471Tm
- ___unnamed_11
- ___unnamed_36
- _swift_release_x4
- _swift_retain_x3
- _swift_unknownObjectRetain_n
- _symbolic SDySS______pG 17CompanionSetupKit7CSKStepP
- _symbolic _____ 17CompanionSetupKit17CSKStepDefinitionV11StepCreatorV
- _symbolic _____ySS______pG s18_DictionaryStorageC 17CompanionSetupKit7CSKStepP
- _symbolic _____y______pG s23_ContiguousArrayStorageC 17CompanionSetupKit7CSKStepP
- _symbolic qd__yYaYbKc
- _type_layout_string 17CompanionSetupKit17CSKStepIdentifierRzAA0D0Rd__r__lAA0D10DefinitionV11StepCreatorVyx_qd__G
CStrings:
+ "### PurchasePasswordSettings failed: no bag"
+ "### PurchasePasswordSettings sync failed: error=%@"
+ "CSKStepMisc-purchasePasswordSettingsSync"
+ "Not going forward"
+ "PurchasePasswordSettings skipped: free already set: %s"
+ "PurchasePasswordSettings skipped: no store account"
+ "PurchasePasswordSettings sync finished"
+ "PurchasePasswordSettings sync start: free=never, paid=%s"
+ "osUpdateRequiredInternal"
+ "purchasePasswordSettings"
+ "purchasePasswordSettingsSync"
+ "resolve actor: id=%s"
- "resolve actor: id=%s, created cached key=%s"
- "resolve actor: id=%s, created ephemeral"
- "resolve actor: id=%s, reusing cached key=%s"
```
