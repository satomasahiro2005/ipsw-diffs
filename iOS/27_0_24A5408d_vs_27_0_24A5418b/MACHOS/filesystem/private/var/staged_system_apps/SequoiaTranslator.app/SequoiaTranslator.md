## SequoiaTranslator

> `/private/var/staged_system_apps/SequoiaTranslator.app/SequoiaTranslator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x302ac0` | `0x3040c4` | **`+0x1604`** |
| `__TEXT.__oslogstring` | `0xdc8b` | `0xdceb` | **`+0x60`** |
| `__DATA.__data` | `0x15b00` | `0x15b30` | **`+0x30`** |
| `__DATA.__objc_const` | `0xdb28` | `0xdb48` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x8110` | `0x80f0` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0xf218` | `0xf238` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x11481` | `0x114a1` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xb3c2` | `0xb3e2` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x4090` | `0x4080` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x83d4` | `0x83e0` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0x2a6f0` | `0x2a6fc` | **`+0xc`** |
| `__TEXT.__eh_frame` | `0x851c` | `0x8524` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-388.0.0.0.0
+389.1.0.0.0

-  - /System/Library/PrivateFrameworks/CloudSubscriptionFeatures.framework/CloudSubscriptionFeatures

-  Functions: 13157
-  Symbols:   3846
-  CStrings:  4533
+  Functions: 13158
+  Symbols:   3844
+  CStrings:  4535
Symbols:
+ _MobileGestalt_get_deviceSupportsInstructionFollowingPruningModels
- _$s25CloudSubscriptionFeatures7GMOptInC07isOptedE0SbvgTj
- _$s25CloudSubscriptionFeatures7GMOptInC6sharedACvgZ
- _$s25CloudSubscriptionFeatures7GMOptInCMa
CStrings:
+ "2026-08-14 20:20:39"
+ "Neither source nor target locale are supported, resetting them to default values"
+ "appleIntelligenceAvailable %{bool}d didGetAirPodsConnected %{bool}d."
+ "hasValidatedLocales"
- "2026-08-04 13:35:14"
- "appleIntelligenceOptedIn %{bool}d didGetAirPodsConnected %{bool}d."
```
