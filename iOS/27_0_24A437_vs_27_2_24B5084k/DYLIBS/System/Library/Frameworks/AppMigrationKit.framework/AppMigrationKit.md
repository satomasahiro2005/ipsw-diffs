## AppMigrationKit

> `/System/Library/Frameworks/AppMigrationKit.framework/AppMigrationKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x76290` | `0x77134` | **`+0xea4`** |
| `__TEXT.__const` | `0x4f20` | `0x50a0` | **`+0x180`** |
| `__DATA.__bss` | `0x68b0` | `0x69b0` | **`+0x100`** |
| `__AUTH_CONST.__const` | `0x35f0` | `0x3670` | **`+0x80`** |
| `__TEXT.__eh_frame` | `0x6c10` | `0x6c60` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x24f0` | `0x2528` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x1130` | `0x1158` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x17e8` | `0x180c` | **`+0x24`** |
| `__AUTH_CONST.__auth_got` | `0x1038` | `0x1058` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0xf44` | `0xf64` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xb40` | `0xb50` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x13bf` | `0x13cd` | **`+0xe`** |
| `__DATA_CONST.__got` | `0x458` | `0x460` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x344` | `0x34c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x174` | `0x178` | **`+0x4`** |

### Other Changes

```diff

-138.0.0.0.0
+140.0.0.0.0

-  Functions: 2543
-  Symbols:   1058
-  CStrings:  177
+  Functions: 2563
+  Symbols:   1064
+  CStrings:  178
Symbols:
+ _NSUnderlyingErrorKey
+ ___swift_memcpy80_8
+ _associated conformance 15AppMigrationKit0A20ContentExportFailureV10Foundation13CustomNSErrorAAs5Error
+ _get_enum_tag_for_layout_string 15AppMigrationKit0A7ContentVSg
+ _symbolic _____ 15AppMigrationKit0A20ContentExportFailureV
+ _type_layout_string 15AppMigrationKit0A20ContentExportFailureV
CStrings:
+ "Returning partial stats for %s"
```
