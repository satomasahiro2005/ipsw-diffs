## OxygenSaturationSettings

> `/System/Library/NanoPreferenceBundles/Applications/OxygenSaturationSettings.bundle/OxygenSaturationSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x431c` | `0x39f0` | **`-0x92c`** |
| `__DATA.__bss` | `0x300` | `—` | **`-0x300`** |
| `__TEXT.__const` | `0x264` | `0x84` | **`-0x1e0`** |
| `__TEXT.__auth_stubs` | `0x750` | `0x680` | **`-0xd0`** |
| `__DATA_CONST.__auth_ptr` | `0xb8` | `0x8` | **`-0xb0`** |
| `__DATA_CONST.__auth_got` | `0x3b0` | `0x348` | **`-0x68`** |
| `__TEXT.__swift5_typeref` | `0xc8` | `0x76` | **`-0x52`** |
| `__DATA.__data` | `0x348` | `0x308` | **`-0x40`** |
| `__TEXT.__constg_swiftt` | `0x168` | `0x130` | **`-0x38`** |
| `__TEXT.__swift5_assocty` | `0x30` | `—` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0x52` | `0x22` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x148` | `0x118` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x108` | `0xe0` | **`-0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x64` | `0x48` | **`-0x1c`** |
| `__TEXT.__swift5_proto` | `0x18` | `—` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `—` | **`-0x14`** |
| `__DATA_CONST.__got` | `0x160` | `0x150` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0x981` | `0x971` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0x10` | `0xc` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7
+  - /System/Library/Frameworks/CoreServices.framework/CoreServices

+  - /System/Library/PrivateFrameworks/HealthAppServices.framework/HealthAppServices

-  Functions: 77
-  Symbols:   127
+  Functions: 56
+  Symbols:   124
Symbols:
+ _OBJC_CLASS_$_LSApplicationWorkspace
- _OBJC_CLASS_$_UIApplication
- __swiftEmptyDictionarySingleton
- _objc_retain
- _swift_getForeignTypeMetadata
CStrings:
+ "defaultWorkspace"
+ "hk_asyncOpenURL:"
- "openURL:options:completionHandler:"
- "sharedApplication"
```
