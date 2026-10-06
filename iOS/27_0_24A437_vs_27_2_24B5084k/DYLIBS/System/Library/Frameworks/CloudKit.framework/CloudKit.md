## CloudKit

> `/System/Library/Frameworks/CloudKit.framework/CloudKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x369a80` | `0x369db4` | **`+0x334`** |
| `__TEXT.__oslogstring` | `0x17326` | `0x17405` | **`+0xdf`** |
| `__TEXT.__cstring` | `0x211da` | `0x2116a` | **`-0x70`** |
| `__DATA.__data` | `0x6378` | `0x6398` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2197c` | `0x21994` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x39bb0` | `0x39bc0` | **`+0x10`** |
| `__DATA.__bss` | `0xe968` | `0xe978` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xbff0` | `0xc000` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2538` | `0x2540` | **`+0x8`** |
| `__DATA.__common` | `0x820` | `0x828` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0xba8` | `0xbb0` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `0xd9` | `0xd1` | **`-0x8`** |

### Other Changes

```diff

-2710.120.0.0.0
+2720.14.0.0.0

-  Functions: 24371
-  Symbols:   6519
-  CStrings:  6277
+  Functions: 24375
+  Symbols:   6522
+  CStrings:  6281
Symbols:
+ _$s8CloudKit15CKLogReportJunk2os6LoggerVvg
+ _ck_log_facility_report_junk
+ _os_eligibility_get_domain_answer
CStrings:
+ "Removing public link from standard options due to ineligibility"
+ "Removing public link when resolving allowed options for share due to ineligibility"
+ "ReportJunk"
+ "os_eligibility_get_domain_answer failed with errno %d; treating as eligible"
```
