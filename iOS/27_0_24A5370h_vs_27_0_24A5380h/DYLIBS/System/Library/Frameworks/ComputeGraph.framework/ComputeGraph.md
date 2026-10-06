## ComputeGraph

> `/System/Library/Frameworks/ComputeGraph.framework/ComputeGraph`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1484cc` | `0x1482ac` | **`-0x220`** |
| `__TEXT.__eh_frame` | `0x95cc` | `0x9584` | **`-0x48`** |
| `__TEXT.__cstring` | `0x685c` | `0x682c` | **`-0x30`** |
| `__TEXT.__const` | `0x1eb74` | `0x1eb54` | **`-0x20`** |
| `__DATA.__data` | `0x2aa8` | `0x2a90` | **`-0x18`** |
| `__TEXT.__swift5_typeref` | `0x45ae` | `0x4596` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1120` | `0x1128` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x51a0` | `0x5198` | **`-0x8`** |

### Other Changes

```diff

-25.0.0.0.0
+27.0.0.0.0

-  Functions: 7556
-  Symbols:   20777
-  CStrings:  873
+  Functions: 7551
+  Symbols:   20767
+  CStrings:  872
Symbols:
+ _$s12ComputeGraph0a4NodeB0V0C0V4KindOSgWOe
+ _$s12ComputeGraph0a4NodeB0V22removeUnreachableNodesyyFSbAC4PortO7AddressV3key_SayAHG5valuet_tXEfU0_
+ _$ss10_NativeSetV11subtractingyAByxGqd__7ElementQyd__RszSTRd__lF12ComputeGraph0F7ContextV_ShyAIGTg5
+ _$ss10_NativeSetV11subtractingyAByxGqd__7ElementQyd__RszSTRd__lFSi_SD4KeysVySi12ComputeGraph0G16EmissionPipelineV_GTg5Tm
+ _swift_release_x12
- _$s15Synchronization5MutexVy12ComputeGraph7LibraryVGMR
- _$s15Synchronization5MutexVy12ComputeGraph7LibraryVGMd
- _$s15Synchronization5MutexVySDy12ComputeGraph0D7ContextVAD15StageDefinition_pXpGGMR
- _$s15Synchronization5MutexVySDy12ComputeGraph0D7ContextVAD15StageDefinition_pXpGGMd
- _$sSh11subtractingyShyxGABF12ComputeGraph0C7ContextV_Tg5
- _$sSh11subtractingyShyxGqd__7ElementQyd__RszSTRd__lFSi_SD4KeysVySi12ComputeGraph0E16EmissionPipelineV_GTg5Tm
- _$ss17_NativeDictionaryV6filteryAByxq_GSbx3key_q_5valuet_tqd__YKXEqd__YKs5ErrorRd__lF12ComputeGraph0g4NodeH0V4PortO7AddressV_SayANGs5NeverOTg5
- _$ss6ResultOys17_NativeDictionaryVy12ComputeGraph0E10DefinitionV9InputPortVSayAG06OutputH0VGGs5NeverOGWOe
- _$ss6ResultOys17_NativeDictionaryVy12ComputeGraph0E10DefinitionV9InputPortVSayAG06OutputH0VGGs5NeverOGWOy
- _$ss6ResultOys17_NativeDictionaryVy12ComputeGraph0d4NodeE0V4PortO7AddressVSayAKGGs5NeverOGWOe
- _get_type_metadata 12ComputeGraph0B9MigrationV noncopyable
- _get_type_metadata 12ComputeGraph17NodeConfigurationRzlAA5InoutVyAA0acB0V0C0VG noncopyable
- _get_type_metadata 15Synchronization5MutexVy12ComputeGraph7LibraryVG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDy12ComputeGraph0D7ContextVAD15StageDefinition_pXpGG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "Group port mismatch: output "
+ "Type mismatch between output "
+ "mismatched ports: output "
- "ComputeGraph/Library+NodeDefinition.swift"
- "Group port mismatch: input "
- "Type mismatch between input "
- "mismatched ports: input "
```
