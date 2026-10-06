## UserDomainConceptsSupport

> `/System/Library/PrivateFrameworks/UserDomainConceptsSupport.framework/UserDomainConceptsSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xccbc` | `0x1318c` | **`+0x64d0`** |
| `__TEXT.__eh_frame` | `0x148` | `0x630` | **`+0x4e8`** |
| `__AUTH_CONST.__const` | `0xab0` | `0x940` | **`-0x170`** |
| `__TEXT.__unwind_info` | `0x3d8` | `0x528` | **`+0x150`** |
| `__TEXT.__const` | `0x450` | `0x592` | **`+0x142`** |
| `__DATA.__data` | `0x240` | `0x370` | **`+0x130`** |
| `__AUTH.__data` | `—` | `0x118` | **`+0x118`** |
| `__TEXT.__constg_swiftt` | `0x210` | `0x2e4` | **`+0xd4`** |
| `__DATA_DIRTY.__data` | `0x450` | `0x380` | **`-0xd0`** |
| `__TEXT.__cstring` | `0x151` | `0x211` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x3ec` | `0x48a` | **`+0x9e`** |
| `__TEXT.__swift5_fieldmd` | `0x22c` | `0x2b8` | **`+0x8c`** |
| `__AUTH_CONST.__auth_got` | `0x620` | `0x6a0` | **`+0x80`** |
| `__AUTH_CONST.__objc_const` | `0x4a0` | `0x438` | **`-0x68`** |
| `__AUTH.__objc_data` | `0x48` | `0x98` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x8` | `0x54` | **`+0x4c`** |
| `__TEXT.__oslogstring` | `0x7f` | `0x3d` | **`-0x42`** |
| `__TEXT.__swift5_capture` | `0x340` | `0x310` | **`-0x30`** |
| `__TEXT.__swift_as_ret` | `0x4` | `0x34` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0x4` | `0x24` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x3c` | `0x28` | **`-0x14`** |
| `__DATA_CONST.__const` | `0x60` | `0x50` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x180` | `0x190` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1d2` | `0x1c2` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `—` | `0xc` | **`+0xc`** |
| `__TEXT.__swift5_protos` | `0x4` | `0x10` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x28` | `0x30` | **`+0x8`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

-  Functions: 360
-  Symbols:   278
-  CStrings:  11
+  Functions: 431
+  Symbols:   293
+  CStrings:  14
Symbols:
+ ___swift_allocate_boxed_opaque_existential_1
+ ___swift_memcpy56_8
+ ___swift_memcpy64_8
+ ___swift_mutable_project_boxed_opaque_existential_1
+ _get_enum_tag_for_layout_string 25UserDomainConceptsSupport18ListConceptManagerC12CommitAction33_068A1837F8ED68C018A2C8D9742CDD66LLO
+ _get_type_metadata 15Synchronization5MutexVy25UserDomainConceptsSupport18ListConceptManagerC5State33_068A1837F8ED68C018A2C8D9742CDD66LLVG noncopyable
+ _objc_retain_x25
+ _objc_retain_x27
+ _swift_allocBox
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_cvw_initWithTake
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_makeBoxUnique
+ _swift_release_x28
+ _swift_retain_n
+ _swift_retain_x25
+ _swift_retain_x28
+ _swift_storeEnumTagSinglePayloadGeneric
+ _swift_task_create
+ _swift_unknownObjectRetain_n
+ _symbolic $s25UserDomainConceptsSupport0aB22ConceptChangeObservingP
+ _symbolic $s25UserDomainConceptsSupport17ConceptPersistingP
+ _symbolic $s25UserDomainConceptsSupport24DarwinNotificationSourceP
+ _symbolic Say_____2id_y_____Ybc7handlertG 10Foundation4UUIDV 25UserDomainConceptsSupport23ListConceptManagerStateV
+ _symbolic ScA_pSg
+ _symbolic ScCySb_____G s5NeverO
+ _symbolic ScTyyt_____GSg s5NeverO
+ _symbolic So19HKUserDomainConceptC
+ _symbolic So19HKUserDomainConceptC7concept______9installedt 25UserDomainConceptsSupport23ListConceptManagerStateV
+ _symbolic _____ 25UserDomainConceptsSupport18ListConceptManagerC12CommitAction33_068A1837F8ED68C018A2C8D9742CDD66LLO
+ _symbolic _____ 25UserDomainConceptsSupport18ListConceptManagerC5State33_068A1837F8ED68C018A2C8D9742CDD66LLV
+ _symbolic _____ 25UserDomainConceptsSupport34ProductionDarwinNotificationSource33_068A1837F8ED68C018A2C8D9742CDD66LLV
+ _symbolic _____ 25UserDomainConceptsSupport8TaskSlot33_068A1837F8ED68C018A2C8D9742CDD66LLV
+ _symbolic _____ s6UInt64V
+ _symbolic _____Sg 10Foundation4UUIDV
+ _symbolic ______p 25UserDomainConceptsSupport17ConceptPersistingP
+ _symbolic ______p 25UserDomainConceptsSupport24DarwinNotificationSourceP
+ _symbolic _____y_____SgG 15Synchronization5MutexVAARi_zrlE 25UserDomainConceptsSupport39ListConceptManagerStateObservationTokenC
+ _symbolic _____ytIeghnr_ 25UserDomainConceptsSupport23ListConceptManagerStateV
+ _symbolic yXlSg
+ _symbolic ytIeAgHr_
+ _type_layout_string 25UserDomainConceptsSupport18ListConceptManagerC12CommitAction33_068A1837F8ED68C018A2C8D9742CDD66LLO
- _OBJC_CLASS_$_OS_dispatch_queue
- ___swift_memcpy40_8
- ___swift_memcpy4_4
- ___swift_memcpy57_8
- ___swift_noop_void_return
- _get_enum_tag_for_layout_string Iegh_Sg
- _get_type_metadata 15Synchronization5MutexVy25UserDomainConceptsSupport18ListConceptManagerC12MutableState33_068A1837F8ED68C018A2C8D9742CDD66LLVG noncopyable
- _swift_bridgeObjectRetain_n
- _symbolic Iegh_
- _symbolic SDy_____y_____YbcG 10Foundation4UUIDV 25UserDomainConceptsSupport23ListConceptManagerStateV
- _symbolic SaySo19HKUserDomainConceptCGSaySo010HKListUserbC0CGIeggg_
- _symbolic So23HKListUserDomainConceptC
- _symbolic _____ 25UserDomainConceptsSupport18ListConceptManagerC12MutableState33_068A1837F8ED68C018A2C8D9742CDD66LLV
- _symbolic _____ So16os_unfair_lock_sV
- _symbolic _____ s6UInt32V
- _symbolic _____Sg 7Combine14AnyCancellableC
- _symbolic _____Sg 9HealthKit31DarwinNotificationObserverTokenC
- _symbolic _____Sgz_Xx 7Combine14AnyCancellableC
- _symbolic _____XMT 25UserDomainConceptsSupport18ListConceptManagerC
- _symbolic _____ySb_____G 7Combine19CurrentValueSubjectC s5NeverO
- _symbolic _____y_____SgG 15Synchronization5MutexVAARi_zrlE 25UserDomainConceptsSupport18ListConceptManagerC
- _symbolic _____y_____SgG_Xx 15Synchronization5MutexVAARi_zrlE 25UserDomainConceptsSupport18ListConceptManagerC
- _symbolic _____y__________G 7Combine19CurrentValueSubjectC 25UserDomainConceptsSupport23ListConceptManagerStateV s5NeverO
- _symbolic ytIeghr_
- _symbolic yyYbcSg
- _type_layout_string 25UserDomainConceptsSupport18ListConceptManagerC12MutableState33_068A1837F8ED68C018A2C8D9742CDD66LLV
- _type_layout_string So16os_unfair_lock_sV
CStrings:
+ "Unable to cast merged result to HKListUserDomainConcept"
+ "[%{public}@] mergeDuplicates: persist of merged list failed; reload will retry."
+ "id handler "
+ "persistConcept(_:)"
- "%{public}s error persisting merged list %{public}s: %{public}s"
```
