## Shortcuts

> `/private/var/staged_system_apps/Shortcuts.app/Shortcuts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbcb58` | `0xbc958` | **`-0x200`** |
| `__TEXT.__swift5_reflstr` | `0x14c2` | `0x1552` | **`+0x90`** |
| `__TEXT.__objc_methname` | `0x9fa4` | `0xa024` | **`+0x80`** |
| `__TEXT.__objc_stubs` | `0x5ce0` | `0x5c80` | **`-0x60`** |
| `__DATA.__objc_data` | `0x2780` | `0x27d0` | **`+0x50`** |
| `__DATA.__objc_const` | `0x34d8` | `0x3518` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x2c60` | `0x2ca0` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x241c` | `0x23dc` | **`-0x40`** |
| `__TEXT.__auth_stubs` | `0x4c70` | `0x4c40` | **`-0x30`** |
| `__DATA.__objc_selrefs` | `0x23e0` | `0x23c8` | **`-0x18`** |
| `__DATA_CONST.__auth_got` | `0x2648` | `0x2630` | **`-0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x13cc` | `0x13e4` | **`+0x18`** |
| `__DATA.__data` | `0x4620` | `0x4630` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xf14` | `0xf04` | **`-0x10`** |
| `__DATA.__common` | `0x440` | `0x438` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x2d30` | `0x2d28` | **`-0x8`** |

### Same-size Content Changes

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
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-5110.0.8.0.0
+5111.0.2.0.0

-  Functions: 4783
-  Symbols:   2432
-  CStrings:  2108
+  Functions: 4785
+  Symbols:   2429
+  CStrings:  2107
Symbols:
+ _$s14ShortcutsAgent017DescribeAShortcutB0V13configuration10workflowID18groundTruthEntries13initialExportAcA0B13ConfigurationV_SSSgSDySSSo28WFParameterStateCatalogEntryCGSgSo21WFPythonWorkflowProxyCSgtKcfC
+ _WFWhatsNewLastPresentedMessageVersionKey
- _$s14ShortcutsAgent017DescribeAShortcutB0V13configuration10workflowID18groundTruthEntries14initialCatalogAcA0B13ConfigurationV_SSSgSDySSSo016WFParameterStateL5EntryCGSgSo0noL0CtKcfC
- _$s14ShortcutsAgent017DescribeAShortcutB0V13configuration10workflowID18groundTruthEntries14initialCatalogAcA0B13ConfigurationV_SSSgSDySSSo016WFParameterStateL5EntryCGSgSo0noL0CtKcfcfA2_
- _$sSS11utf8CStrings15ContiguousArrayVys4Int8VGvg
- _OBJC_CLASS_$_NSProcessInfo
- __swift_stdlib_strtod_clocale
CStrings:
+ "$__lazy_storage_$_automationListViewModel"
+ "$__lazy_storage_$_columnAutomationsViewController"
+ "$__lazy_storage_$_compactAutomationsViewController"
+ "isAppleIntelligenceEnabled"
- "automationListViewModel"
- "isAppleIntelligenceAvailable"
- "operatingSystemVersion"
- "processInfo"
- "setDouble:forKey:"
```
