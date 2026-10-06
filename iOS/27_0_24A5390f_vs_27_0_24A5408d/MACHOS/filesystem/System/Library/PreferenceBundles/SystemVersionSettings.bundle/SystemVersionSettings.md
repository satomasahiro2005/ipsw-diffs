## SystemVersionSettings

> `/System/Library/PreferenceBundles/SystemVersionSettings.bundle/SystemVersionSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x376dc` | `0x379b8` | **`+0x2dc`** |
| `__TEXT.__eh_frame` | `0x49c` | `0x6cc` | **`+0x230`** |
| `__TEXT.__swift5_typeref` | `0x1924` | `0x1b06` | **`+0x1e2`** |
| `__DATA_CONST.__const` | `0x1458` | `0x15e8` | **`+0x190`** |
| `__TEXT.__oslogstring` | `0x416` | `0x50e` | **`+0xf8`** |
| `__TEXT.__swift5_capture` | `0x69c` | `0x73c` | **`+0xa0`** |
| `__TEXT.__swift5_reflstr` | `0x3ea` | `0x36a` | **`-0x80`** |
| `__TEXT.__auth_stubs` | `0x1470` | `0x1430` | **`-0x40`** |
| `__TEXT.__const` | `0x17f4` | `0x1834` | **`+0x40`** |
| `__DATA.__data` | `0xab0` | `0xae8` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x30c` | `0x2dc` | **`-0x30`** |
| `__DATA.__objc_const` | `0x630` | `0x610` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0xa40` | `0xa20` | **`-0x20`** |
| `__TEXT.__cstring` | `0xba1` | `0xbc1` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0xbf8` | `0xbd8` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x8e0` | `0x900` | **`+0x20`** |
| `__DATA.__bss` | `0x12b8` | `0x12a8` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x20` | `0x30` | **`+0x10`** |
| `__DATA.__objc_data` | `0x1f8` | `0x1f0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x3a8` | `0x3b0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x14` | `0x1c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-772.0.10.0.0
+772.0.20.0.0

-  Functions: 1043
-  Symbols:   136
-  CStrings:  267
+  Functions: 1038
+  Symbols:   139
+  CStrings:  268
Symbols:
+ _SystemVersionSettingsVersionNumber
+ _SystemVersionSettingsVersionString
+ _swift_unknownObjectWeakDestroy
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
- _swift_getTupleTypeMetadata2
- _swift_release_x8
CStrings:
+ "Both Full OS and SPLAT documentations exists. Documentation seems to be SPLAT. Resetting the FullOS documentation."
+ "Copying the current software version \"%{public}s\" to clipboard: %{public}s"
+ "Dismissing edit menu for software: %{public}s"
+ "Failed to create regex pattern for SPLAT detection: %{public}@"
+ "Failed to fetch version information for %{public}s"
+ "Failed to load installation history: %{public}s"
+ "Install history loaded — no matching dates found for current builds."
+ "Installed OS: %{public}s"
+ "Installed Security Update: %{public}s"
+ "Presenting edit menu for software: %{public}s"
+ "Toggled build number visibility to: %{bool,public}d"
+ "Updated build number visibility on appear to match isInternalBuild: %{bool,public}d"
+ "Updated build number visibility to match isInternalBuild: %{bool,public}d"
+ "Updated install dates - OS: %{public}s, Security Update: %{public}s"
- "Both Full OS and SPLAT documentations exists. Documentation seems to be SPLAT. Resetting the FulOS documentation."
- "Copying the current software version \"%s\" to clipboard: %s"
- "Dismissing edit menu for software: %s"
- "Failed to create regex pattern for SPLAT detection: %@"
- "Failed to fetch version information for %s"
- "Failed to load installation history: %s"
- "Installed OS: %s"
- "Installed Security Update: %s"
- "Presenting edit menu for software: %s"
- "Toggled build number visibility to: %{bool}d"
- "Updated build number visibility on appear to match isInternalBuild: %{bool}d"
- "Updated build number visibility to match isInternalBuild: %{bool}d"
- "_installedSoftwaresTimes"
```
