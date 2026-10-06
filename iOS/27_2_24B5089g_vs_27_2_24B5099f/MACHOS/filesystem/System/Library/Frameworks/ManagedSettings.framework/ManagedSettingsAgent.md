## ManagedSettingsAgent

> `/System/Library/Frameworks/ManagedSettings.framework/ManagedSettingsAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72d50` | `0x73da0` | **`+0x1050`** |
| `__TEXT.__auth_stubs` | `0x1f80` | `0x2090` | **`+0x110`** |
| `__DATA_CONST.__auth_got` | `0xfc8` | `0x1050` | **`+0x88`** |
| `__TEXT.__cstring` | `0x7d5` | `0x825` | **`+0x50`** |
| `__TEXT.__const` | `0x1c7c` | `0x1c8c` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x1d38` | `0x1d28` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x2fb2` | `0x2fc2` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x490` | `0x498` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-318.0.0.0.0
+319.40.1.0.0

-  Functions: 1113
-  Symbols:   752
-  CStrings:  554
+  Functions: 1114
+  Symbols:   770
+  CStrings:  557
Symbols:
+ _$s15ManagedSettings15enableTelemetrys12StaticStringVvg
+ _$s2os12OSSignpostIDV3logACSo03OS_a1_D0C_tcfC
+ _$s2os12OSSignpostIDV8rawValues6UInt64Vvg
+ _$s2os12OSSignpostIDVMa
+ _$s2os12OSSignposterV15ManagedSettingsE5agentACvgZ
+ _$s2os12OSSignposterV9logHandleSo03OS_a1_C0Cvg
+ _$s2os12OSSignposterVMa
+ _$s2os15OSSignpostErrorO9doubleEndyA2CmFWC
+ _$s2os15OSSignpostErrorOMa
+ _$s2os23OSSignpostIntervalStateC10signpostIDAA0bF0Vvg
+ _$s2os23OSSignpostIntervalStateC2id6isOpenAcA0B2IDV_Sbtcfc
+ _$s2os23OSSignpostIntervalStateCMa
+ _$s2os28checkForErrorAndConsumeState5stateAA010OSSignpostD0OAA0i8IntervalG0C_tF
+ _$sSo18os_signpost_type_ta0A0E3endABvgZ
+ _$sSo18os_signpost_type_ta0A0E5beginABvgZ
+ _$sSo9OS_os_logC0B0E16signpostsEnabledSbvg
+ _$ss12StaticStringV11descriptionSSvg
+ __os_signpost_emit_with_name_impl
CStrings:
+ "%{public}s"
+ "[Error] Interval already ended"
+ "managedsettings-agent-updateStore"
```
