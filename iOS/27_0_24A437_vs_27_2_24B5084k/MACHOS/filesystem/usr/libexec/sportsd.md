## sportsd

> `/usr/libexec/sportsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa8980` | `0xa851c` | **`-0x464`** |
| `__TEXT.__auth_stubs` | `0x3760` | `0x3720` | **`-0x40`** |
| `__DATA_CONST.__auth_got` | `0x1bb8` | `0x1b98` | **`-0x20`** |
| `__TEXT.__const` | `0x5f98` | `0x5f88` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x2a38` | `0x2a28` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x9f8` | `0x9f0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x990` | `0x988` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x39e4` | `0x39dc` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-237.0.0.0.0
+238.0.0.0.0

-  Symbols:   1399
+  Symbols:   1393
Symbols:
+ _$s18AppIntentsServices0bC0O15localDispatcher11clientLabel6source11environment7optionsAA0A17IntentDispatching_pSS_So24LNTranscriptActionSourceVAA0aK11Environment_pAC14OptionsBuilderVy_AC0eQ0VGdtFZ
- _$s18AppIntentsServices0bC0O14InterfaceIdiomO23defaultForCurrentDeviceAESgvgZ
- _$s18AppIntentsServices0bC0O14InterfaceIdiomOMn
- _$s18AppIntentsServices0bC0O14PayloadPrivacyO7defaultyA2EmFWC
- _$s18AppIntentsServices0bC0O14PayloadPrivacyOMa
- _$s18AppIntentsServices0bC0O15localDispatcher11clientLabel6source11environment7optionsAA0A17IntentDispatching_pSS_So24LNTranscriptActionSourceVAA0aK11Environment_pAC0E7OptionsVtFZ
- _$s18AppIntentsServices0bC0O17DispatcherOptionsV14interfaceIdiom14payloadPrivacyAeC09InterfaceG0OSg_AC07PayloadI0OtcfC
- _$s18AppIntentsServices0bC0O17DispatcherOptionsVMa
```
