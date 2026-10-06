## HealthHistoryDaemon

> `/System/Library/PrivateFrameworks/HealthHistoryDaemon.framework/HealthHistoryDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc7f44` | `0xca2c8` | **`+0x2384`** |
| `__TEXT.__eh_frame` | `0x73f4` | `0x76fc` | **`+0x308`** |
| `__TEXT.__oslogstring` | `0x18eb` | `0x19db` | **`+0xf0`** |
| `__DATA.__data` | `0xf50` | `0x1020` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x22f0` | `0x23b8` | **`+0xc8`** |
| `__AUTH.__objc_data` | `0x128` | `0x1e8` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0xae8` | `0xb98` | **`+0xb0`** |
| `__TEXT.__objc_methlist` | `0x410` | `0x478` | **`+0x68`** |
| `__AUTH_CONST.__const` | `0x2540` | `0x2590` | **`+0x50`** |
| `__TEXT.__const` | `0x1e34` | `0x1e74` | **`+0x40`** |
| `__TEXT.__cstring` | `0xd8e` | `0xdce` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1758` | `0x1790` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x4b8` | `0x4e8` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0xcfc` | `0xd28` | **`+0x2c`** |
| `__AUTH.__data` | `0x818` | `0x840` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0xa78` | `0xa9c` | **`+0x24`** |
| `__DATA_CONST.__objc_protolist` | `0x58` | `0x78` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0xa78` | `0xa94` | **`+0x1c`** |
| `__TEXT.__swift_as_cont` | `0x724` | `0x73c` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0xdb8` | `0xda6` | **`-0x12`** |
| `__DATA_CONST.__const` | `0xb8` | `0xc8` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x30` | `0x40` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x1118` | `0x1108` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0x1ec` | `0x1f8` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x38` | `0x40` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x1d4` | `0x1dc` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xcc` | `0xd0` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

+  - /System/Library/PrivateFrameworks/HealthRecordServices.framework/HealthRecordServices

+  - /usr/lib/swift/libswiftIntents.dylib
+  - /usr/lib/swift/libswiftMLCompute.dylib

-  Functions: 2343
-  Symbols:   671
-  CStrings:  156
+  Functions: 2379
+  Symbols:   693
+  CStrings:  159
Symbols:
+ _HKOntologyShardIdentifierMedicalHistory
+ _OBJC_CLASS_$__TtC19HealthHistoryDaemon38UniversalClassificationRuleInvalidator
+ _OBJC_METACLASS_$__TtC19HealthHistoryDaemon38UniversalClassificationRuleInvalidator
+ __DATA__TtC19HealthHistoryDaemon38UniversalClassificationRuleInvalidator
+ __INSTANCE_METHODS__TtC19HealthHistoryDaemon38UniversalClassificationRuleInvalidator
+ __IVARS__TtC19HealthHistoryDaemon38UniversalClassificationRuleInvalidator
+ __METACLASS_DATA__TtC19HealthHistoryDaemon38UniversalClassificationRuleInvalidator
+ __OBJC_$_PROP_LIST_HDOntologyDaemonComponentProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HDOntologyDaemonComponentProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HDOntologyShardImporterObserver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HDOntologyDaemonComponentProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HDOntologyShardImporterObserver
+ __OBJC_LABEL_PROTOCOL_$_HDOntologyDaemonComponentProviding
+ __OBJC_LABEL_PROTOCOL_$_HDOntologyShardImporterObserver
+ __OBJC_PROTOCOL_$_HDOntologyDaemonComponentProviding
+ __OBJC_PROTOCOL_$_HDOntologyShardImporterObserver
+ __PROTOCOLS__TtC19HealthHistoryDaemon38UniversalClassificationRuleInvalidator
+ __swift_FORCE_LOAD_$_swiftIntents
+ __swift_FORCE_LOAD_$_swiftIntents_$_HealthHistoryDaemon
+ __swift_FORCE_LOAD_$_swiftMLCompute
+ __swift_FORCE_LOAD_$_swiftMLCompute_$_HealthHistoryDaemon
+ _swift_dynamicCastObjCProtocolConditional
+ _symbolic _____ 19HealthHistoryDaemon38UniversalClassificationRuleInvalidatorC
- _symbolic SDy_____ScTyyt______pGG 17HealthOntologyKit0B17ConceptIdentifierV s5ErrorP
CStrings:
+ "HealthHistoryDaemon.UniversalClassificationRuleInvalidator"
+ "UniversalClassificationRuleInvalidator dropping cached rules after a medical history shard import"
+ "UniversalClassificationRuleInvalidator found no ontology shard importer; cached rules will not be dropped on import"
```
