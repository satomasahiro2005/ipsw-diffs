## CompanionSetup

> `/Applications/CompanionSetup.app/CompanionSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf5efc` | `0xf937c` | **`+0x3480`** |
| `__TEXT.__eh_frame` | `0x7830` | `0x7968` | **`+0x138`** |
| `__TEXT.__const` | `0x4854` | `0x48c4` | **`+0x70`** |
| `__TEXT.__cstring` | `0x44fa` | `0x455a` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x18f4` | `0x1954` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x30c8` | `0x3128` | **`+0x60`** |
| `__DATA.__data` | `0x2720` | `0x2770` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x1ca3` | `0x1cf3` | **`+0x50`** |
| `__DATA.__objc_const` | `0x2038` | `0x2078` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x4e97` | `0x4ed7` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x1af0` | `0x1b28` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x15c8` | `0x15f8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xc588` | `0xc560` | **`-0x28`** |
| `__TEXT.__swift_as_cont` | `0x89c` | `0x8c0` | **`+0x24`** |
| `__DATA_CONST.__got` | `0x1250` | `0x1270` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x1ccb` | `0x1cdb` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x2f0` | `0x2fc` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x308` | `0x314` | **`+0xc`** |
| `__TEXT.__swift5_capture` | `0x5274` | `0x5278` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-524.11.6.0.0
+524.11.10.0.0

-  Functions: 3540
-  Symbols:   1566
-  CStrings:  1533
+  Functions: 3558
+  Symbols:   1570
+  CStrings:  1539
Symbols:
+ _$s17CompanionSetupKit11CSKStepMiscC5EventO18personalContentAskyA2EmFWC
+ _$s17CompanionSetupKit16CSKAddUserClientC5EventO18personalContentAskyA2EmFWC
+ _$s17CompanionSetupKit16CSKAddUserClientC7CommandO23personalContentAnsweredyAESb_tcAEmFWC
+ _$sSo16UIViewControllerC17CompanionSetupKitE010CSKConfirmD9Dismissal7message13cancelHandler07dismissJ0ySS_yycSgAHtF
+ _$sSo28PRXCardContentViewControllerC17CompanionSetupKitE013CSKAddDismissF22WithConfirmationButton7message14dismissHandlerySS_yyctF
+ _OBJC_CLASS_$_UINavigationController
- _$sSo16UIViewControllerC17CompanionSetupKitE010CSKConfirmD9Dismissal13cancelHandler07dismissI0yyycSg_AGtF
- _$sSo28PRXCardContentViewControllerC17CompanionSetupKitE013CSKAddDismissF22WithConfirmationButton14dismissHandleryyyc_tF
CStrings:
+ "PERSONAL_CONTENT_DETAIL_HOME_ACCESSORY"
+ "PERSONAL_CONTENT_FOOTNOTE_HOME_ACCESSORY"
+ "Personal Content finished. Enabled: %{bool}d"
+ "Personal Content go back."
+ "app.grid.2x2.and.person.fill"
+ "footnoteLabel"
+ "resolvedFootnote"
- "person.badge.waveform.fill"
```
