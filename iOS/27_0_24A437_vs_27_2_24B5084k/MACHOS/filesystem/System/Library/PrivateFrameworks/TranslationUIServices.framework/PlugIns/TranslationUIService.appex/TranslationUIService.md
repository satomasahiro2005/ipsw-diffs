## TranslationUIService

> `/System/Library/PrivateFrameworks/TranslationUIServices.framework/PlugIns/TranslationUIService.appex/TranslationUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x530fc` | `0x53140` | **`+0x44`** |
| `__TEXT.__objc_stubs` | `0x1020` | `0x1060` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x558` | `0x568` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x2540` | `0x2530` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x12a8` | `0x12a0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x7f8` | `0x800` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-389.1.0.0.0
+393.1.0.0.0

-  CStrings:  452
+  CStrings:  454
Symbols:
+ _OBJC_CLASS_$__LTLanguageDetectionConfiguration
- _swift_retain_x9
Functions:
~ sub_1000199b8 : 220 -> 224
~ sub_10003ccf4 -> sub_10003ccf8 : 416 -> 440
~ sub_10003cf84 -> sub_10003cfa0 : 3912 -> 3944
~ sub_10003e008 -> sub_10003e044 : 276 -> 284
CStrings:
+ "initWithTaskHint:"
+ "languagesForText:configuration:completion:"
+ "setModel:"
- "languagesForText:usingModel:strategy:taskHint:useDedicatedTextMachPort:completion:"
```
