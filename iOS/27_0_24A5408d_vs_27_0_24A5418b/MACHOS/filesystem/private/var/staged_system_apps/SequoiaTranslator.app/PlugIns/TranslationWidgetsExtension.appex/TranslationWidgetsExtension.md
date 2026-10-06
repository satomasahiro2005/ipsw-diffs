## TranslationWidgetsExtension

> `/private/var/staged_system_apps/SequoiaTranslator.app/PlugIns/TranslationWidgetsExtension.appex/TranslationWidgetsExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe264` | `0xd818` | **`-0xa4c`** |
| `__TEXT.__eh_frame` | `0x5e8` | `0x4f0` | **`-0xf8`** |
| `__TEXT.__auth_stubs` | `0x1040` | `0x1000` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x4f0` | `0x4b8` | **`-0x38`** |
| `__DATA_CONST.__auth_got` | `0x828` | `0x808` | **`-0x20`** |
| `__TEXT.__cstring` | `0x981` | `0x961` | **`-0x20`** |
| `__TEXT.__oslogstring` | `0x5ec` | `0x5cc` | **`-0x20`** |
| `__DATA.__common` | `0xd0` | `0xb8` | **`-0x18`** |
| `__DATA.__data` | `0x790` | `0x780` | **`-0x10`** |
| `__TEXT.__const` | `0x1644` | `0x1634` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x30` | `0x24` | **`-0xc`** |
| `__TEXT.__swift5_typeref` | `0xac6` | `0xabc` | **`-0xa`** |
| `__DATA_CONST.__const` | `0x7e8` | `0x7e0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1a0` | `0x198` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x1c` | `0x14` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x28` | `0x24` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-388.0.0.0.0
+389.1.0.0.0

-  - /System/Library/PrivateFrameworks/CloudSubscriptionFeatures.framework/CloudSubscriptionFeatures

-  - /usr/lib/swift/libswiftCompression.dylib

-  Functions: 392
-  Symbols:   137
-  CStrings:  109
+  Functions: 384
+  Symbols:   136
+  CStrings:  107
Symbols:
- __swift_FORCE_LOAD_$_swiftCompression
CStrings:
+ "appleIntelligenceAvailable %{bool}d didGetAirPodsConnected %{bool}d."
- "Command received in launcher"
- "PersonalTranslator"
- "appleIntelligenceOptedIn %{bool}d didGetAirPodsConnected %{bool}d."
```
