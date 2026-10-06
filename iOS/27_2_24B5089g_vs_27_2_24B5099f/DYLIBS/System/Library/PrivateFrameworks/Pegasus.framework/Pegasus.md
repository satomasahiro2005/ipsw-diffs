## Pegasus

> `/System/Library/PrivateFrameworks/Pegasus.framework/Pegasus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x44284` | `0x445a4` | **`+0x320`** |
| `__AUTH.__data` | `—` | `0x98` | **`+0x98`** |
| `__AUTH_CONST.__objc_const` | `0xadd0` | `0xae60` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `—` | `0x50` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x530` | `0x568` | **`+0x38`** |
| `__TEXT.__const` | `0x232` | `0x264` | **`+0x32`** |
| `__TEXT.__unwind_info` | `0x1478` | `0x1498` | **`+0x20`** |
| `__DATA.__bss` | `0xd8` | `0xf0` | **`+0x18`** |
| `__DATA.__common` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `—` | `0x10` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1b8` | `0x1c0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2d48` | `0x2d50` | **`+0x8`** |
| `__TEXT.__cstring` | `0x47de` | `0x47d8` | **`-0x6`** |
| `__TEXT.__swift5_typeref` | `0x26` | `0x2c` | **`+0x6`** |
| `__TEXT.__swift5_types` | `—` | `0x4` | **`+0x4`** |

### Other Changes

```diff

-310.100.0.0.0
+311.1.1.0.0

+  - /System/Library/Frameworks/DeveloperToolsSupport.framework/DeveloperToolsSupport

-  Functions: 1768
-  Symbols:   3174
+  Functions: 1776
+  Symbols:   3187
Symbols:
+ _OBJC_CLASS_$__TtCs12_SwiftObject
+ _OBJC_METACLASS_$__TtCs12_SwiftObject
+ __DATA__TtC7PegasusP33_507C1C536306FAF93DEACF1CE0F445C919ResourceBundleClass
+ __METACLASS_DATA__TtC7PegasusP33_507C1C536306FAF93DEACF1CE0F445C919ResourceBundleClass
+ ___swift_allocate_value_buffer
+ ___swift_project_value_buffer
+ _objc_opt_self
+ _swift_deallocClassInstance
+ _swift_deletedMethodError
+ _swift_getObjCClassFromMetadata
+ _swift_once
+ _swift_slowAlloc
+ _symbolic _____ 7Pegasus19ResourceBundleClass33_507C1C536306FAF93DEACF1CE0F445C9LLC
CStrings:
+ "PGToggleProminenceGlyph"
- "platter.filled.top.and.arrow.up.iphone"
```
