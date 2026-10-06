## AirDropUI

> `/Applications/AirDropUI.app/AirDropUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13ef48` | `0x13df0c` | **`-0x103c`** |
| `__TEXT.__eh_frame` | `0x4d80` | `0x4c60` | **`-0x120`** |
| `__DATA_CONST.__const` | `0x6ad8` | `0x6a38` | **`-0xa0`** |
| `__TEXT.__auth_stubs` | `0x44f0` | `0x44a0` | **`-0x50`** |
| `__TEXT.__const` | `0xd014` | `0xcfc4` | **`-0x50`** |
| `__TEXT.__swift5_capture` | `0x1628` | `0x15d8` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x31e0` | `0x31a0` | **`-0x40`** |
| `__TEXT.__oslogstring` | `0x5e37` | `0x5e07` | **`-0x30`** |
| `__DATA_CONST.__auth_got` | `0x2280` | `0x2258` | **`-0x28`** |
| `__TEXT.__cstring` | `0x16e6` | `0x16c6` | **`-0x20`** |
| `__DATA.__data` | `0x8050` | `0x8040` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x12a0` | `0x1290` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x1450` | `0x1448` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x25774` | `0x2576c` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x3a0` | `0x398` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x1e0` | `0x1dc` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x190` | `0x18c` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-2131.20.65.2.1
+2131.20.71.0.0

-  Functions: 4532
-  Symbols:   2083
-  CStrings:  1762
+  Functions: 4521
+  Symbols:   2075
+  CStrings:  1760
Symbols:
- _$s11ActivityKit0A0C6update_18alertConfigurationyAA0A7ContentVy0F5StateQzG_AA05AlertE0VSgtYaFTjTu
- _$s11ActivityKit18AlertConfigurationV0C5SoundV6silentAEvgZ
- _$s11ActivityKit18AlertConfigurationV0C5SoundVMa
- _$s11ActivityKit18AlertConfigurationV22AutomaticDismissOptionO10nextUpdateyA2EmFWC
- _$s11ActivityKit18AlertConfigurationV22AutomaticDismissOptionOMa
- _$s11ActivityKit18AlertConfigurationV5title4body5sound22automaticDismissOption18breaksThroughFocusAC10Foundation23LocalizedStringResourceV_AkC0C5SoundVAC09AutomaticiJ0OSbtcfC
- _$s11ActivityKit18AlertConfigurationVMa
- _$s11ActivityKit18AlertConfigurationVMn
CStrings:
- "AirDrop changed state"
- "Updating AirDrop banner to %s for activity %s"
```
