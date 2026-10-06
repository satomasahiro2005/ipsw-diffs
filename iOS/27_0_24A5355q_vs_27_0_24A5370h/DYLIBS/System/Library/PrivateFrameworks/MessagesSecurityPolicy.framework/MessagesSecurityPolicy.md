## MessagesSecurityPolicy

> `/System/Library/PrivateFrameworks/MessagesSecurityPolicy.framework/MessagesSecurityPolicy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a230` | `0x1aa78` | **`+0x848`** |
| `__TEXT.__swift5_capture` | `0x284` | `0x8b4` | **`+0x630`** |
| `__TEXT.__const` | `0x135e` | `0x159e` | **`+0x240`** |
| `__AUTH_CONST.__objc_const` | `0xc20` | `0xdc8` | **`+0x1a8`** |
| `__TEXT.__constg_swiftt` | `0xb04` | `0xc84` | **`+0x180`** |
| `__AUTH.__data` | `0x5b8` | `0x708` | **`+0x150`** |
| `__TEXT.__swift5_reflstr` | `0x610` | `0x760` | **`+0x150`** |
| `__TEXT.__swift5_typeref` | `0xa68` | `0xba4` | **`+0x13c`** |
| `__AUTH_CONST.__const` | `0x1378` | `0x1458` | **`+0xe0`** |
| `__TEXT.__swift5_fieldmd` | `0x798` | `0x858` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0xf8a` | `0xfda` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c8` | `0x2a8` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x598` | `0x5b8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x700` | `0x718` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0xd8` | `0xec` | **`+0x14`** |
| `__TEXT.__swift5_protos` | `0x60` | `0x74` | **`+0x14`** |
| `__DATA.__data` | `0x4a8` | `0x498` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x1d8` | `0x1c8` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x344` | `0x354` | **`+0x10`** |
| `__DATA.__common` | `—` | `0x8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x38` | `0x40` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xa4` | `0xa8` | **`+0x4`** |

### Other Changes

```diff

-1481.100.29.2.9
+1483.100.10.2.4

-  Functions: 539
-  Symbols:   474
-  CStrings:  117
+  Functions: 554
+  Symbols:   487
+  CStrings:  118
Symbols:
+ __DATA__TtC22MessagesSecurityPolicy25BlastDoorInterfaceFactory
+ __IVARS__TtC22MessagesSecurityPolicy21PolicyEngineBlastDoor
+ __METACLASS_DATA__TtC22MessagesSecurityPolicy25BlastDoorInterfaceFactory
+ ___swift_mutable_project_boxed_opaque_existential_1
+ _swift_conformsToProtocol2
+ _swift_makeBoxUnique
+ _symbolic $s22MessagesSecurityPolicy0A26BlastDoorInterfaceProtocolP
+ _symbolic $s22MessagesSecurityPolicy12FeatureFlagsP
+ _symbolic $s22MessagesSecurityPolicy17ServerBagProtocolP
+ _symbolic $s22MessagesSecurityPolicy20BlastDoorTextMessageP
+ _symbolic $s22MessagesSecurityPolicy33BlastDoorInterfaceFactoryProtocolP
+ _symbolic SiSg
+ _symbolic _____ 22MessagesSecurityPolicy25BlastDoorInterfaceFactoryC
+ _symbolic ______p 22MessagesSecurityPolicy0C23EngineBlastDoorProtocolP
+ _symbolic ______p 22MessagesSecurityPolicy12FeatureFlagsP
+ _symbolic ______p 22MessagesSecurityPolicy17ServerBagProtocolP
+ _symbolic ______p 22MessagesSecurityPolicy33BlastDoorInterfaceFactoryProtocolP
+ _symbolic ______pSg 22MessagesSecurityPolicy0A26BlastDoorInterfaceProtocolP
+ _type_layout_string 22MessagesSecurityPolicy18ParseMessageActionV
- _OBJC_CLASS_$_BlastDoorValidatorContext
- _OBJC_CLASS_$_IMMessagesBlastDoorInterface
- _objc_retain_x27
- _swift_dynamicCastClass
- _swift_release_x22
- _swift_retain_x26
CStrings:
+ "%s is not allowed in strict mode, choosing SkipPreviewAction."
+ "Sender with handle %s is in a known chat, sender is considered known"
- "%s is allowed in strict mode, choosing GeneratePreviewAction."
```
