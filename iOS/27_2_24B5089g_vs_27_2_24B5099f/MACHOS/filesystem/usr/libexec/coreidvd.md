## coreidvd

> `/usr/libexec/coreidvd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6fddc0` | `0x7002a0` | **`+0x24e0`** |
| `__TEXT.__eh_frame` | `0x480a8` | `0x48210` | **`+0x168`** |
| `__TEXT.__oslogstring` | `0x2ef69` | `0x2f009` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x25560` | `0x255c0` | **`+0x60`** |
| `__TEXT.__const` | `0x32d70` | `0x32dc0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x16b10` | `0x16b48` | **`+0x38`** |
| `__TEXT.__objc_methname` | `0xdc76` | `0xdca6` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0xc1cd` | `0xc1fd` | **`+0x30`** |
| `__DATA.__data` | `0x18540` | `0x18560` | **`+0x20`** |
| `__DATA.__objc_const` | `0x11888` | `0x118a8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x29b6a` | `0x29b8a` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0xc225` | `0xc243` | **`+0x1e`** |
| `__TEXT.__constg_swiftt` | `0xdba8` | `0xdbc0` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0xd450` | `0xd460` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x64cc` | `0x64dc` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x1c50` | `0x1c60` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xe6c0` | `0xe6cc` | **`+0xc`** |
| `__TEXT.__swift_as_cont` | `0x3830` | `0x383c` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x1324` | `0x1330` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x6a38` | `0x6a40` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x4320` | `0x4318` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-9.104.0.0.0
+9.107.1.0.0

-  Functions: 18960
-  Symbols:   6001
-  CStrings:  8512
+  Functions: 18976
+  Symbols:   6003
+  CStrings:  8519
Symbols:
+ _$s11Distributed0A23TargetInvocationDecoderP18decodeNextArgumentqd__yKlFTj
+ _$s7CoreIDV21MobileDocumentElementV6weightACvgZ
+ _$sScTss5NeverORszABRs_rlE17checkCancellationyyKFZ
+ _ODIServiceProviderIdIDVMigrate
- _$s7Network30NWActorSystemInvocationDecoderV18decodeNextArgumentxyKSeRzSERzlF
- _swift_conformsToProtocol2
CStrings:
+ "%s finished ODI"
+ "%s kicking off ODI"
+ "%s reusing ODI assessment"
+ "%s skipping ODI assessment"
+ "Non fatal - failed to fetch ODI assessment with error: %@"
+ "Parsed KRL document type mismatch."
+ "ProducedAssetManager warmup ODI for %s - %s or %s - isDeviceMigration: %{bool}d"
+ "application/identifierlist+cwt"
+ "fetchODIAssessment()"
+ "isDeviceMigration"
+ "odiAssessmentTask"
- "Finished ODI"
- "Kicking off ODI"
- "ProducedAssetManager warmup ODI for %s - %s or %s"
- "documentWarmup(configuration:documents:region:proofingSessionID:)"
```
