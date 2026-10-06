## diagnosticspushd

> `/usr/libexec/diagnosticspushd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15bc8` | `0x15dd0` | **`+0x208`** |
| `__TEXT.__auth_stubs` | `0xde0` | `0xe70` | **`+0x90`** |
| `__DATA_CONST.__auth_got` | `0x6f8` | `0x740` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x62d` | `0x66d` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x460` | `0x440` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x6c0` | `0x6b0` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x228` | `0x220` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-34.0.0.0.0
+35.0.0.0.0

-  Symbols:   346
+  Symbols:   355
Symbols:
+ _$s15EnhancedLogging13SessionStatusO16debugDescriptionSSvg
+ _$s15EnhancedLogging13SessionStatusO23stillNeedsEnrollConsentSbvg
+ _$s15EnhancedLogging14SessionManagerC07currentC0AA0C0CSgvg
+ _$s15EnhancedLogging14SessionManagerCACycfc
+ _$s15EnhancedLogging14SessionManagerCMa
+ _$s15EnhancedLogging7SessionC6cancel12remoteSourceySb_tF
+ _$s15EnhancedLogging7SessionC6statusAA0C6StatusOvg
+ _swift_release_n
+ _swift_retain_x21
Functions:
~ sub_100005a18 : 204 -> 216
~ sub_100005ae4 -> sub_100005af0 : 1584 -> 2020
~ sub_100006114 -> sub_1000062d4 : 276 -> 312
~ sub_100006228 -> sub_10000640c : 276 -> 312
CStrings:
+ "Ignoring TimberLorry teardown request; status is %{public}s"
- "cancelSession"
```
